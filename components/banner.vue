<template>
  <section>
    <div class="banner">
      <div class="container">

        <div v-swiper:mySwiper="swiperOption">
       <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="item in banner" v-bind:key="item.key">
          <div class="banner-content">
            <div class="img">
              <img :src="item.src" alt="item.src" class="banner-img">
            </div>
            <div class="title">
              <span>#{{item.tag}}</span>
              <h2>{{item.title}}</h2>
              <p>{{item.descr}}</p>
              <button class="btn-lengkap">Selengkapnya</button>
            </div>
          </div>
        </div>
      </div>
      <div class="swiper-pagination"  slot="pagination"></div>
    </div>
      <div class="mt-5">
        <div class="banner-b">
          <img src="https://kiriminaja.com/assets/home-2/pesta-pora-new.png" alt="">
        </div>
      </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  data () {
    return {
      banner: [{
          src: 'https://kiriminaja.com/storage/Slider/April22/1650526232_NCS (Slider) (1) (1).png',
          title: 'Kini NCS sudah tersedia di KiriminAja',
          descr: 'Yeay! Nusantara Card Semesta sudah tersedia di KiriminAja, makin happy karena makin banyak ekspedisi nih. Yuk buruan cobain!',
          tag: '1 Info',
        }, {
          src: 'https://kiriminaja.com/storage/Slider/June22/1654855912_Small.png',
           title: 'Pengumuman Pemenang #aMEIzinghadiahnya',
          descr: 'Penasaran siapa aja SahabatKA yang beruntung ? bagi yang belum beruntung semoga berkesempatan menang di Pestapora #JuniMendadakHepi bulan ini yaa!',
          tag: '2 Info',
        }, {
          src: 'https://kiriminaja.com/storage/Slider/June22/1655115388_Untitled-1.png',
           title: 'Makin happy dengan #JuniMendadakHepi',
          descr: 'Eits siapa nih yang belum berkesempatan memenangkan lucky draw Pestapora KiriminAja? Yuk coba lagi dibulan Juni siapa tau kamu bisa mendadak hepi',
          tag: '3 Info',
        }, {
          src: 'https://kiriminaja.com/storage/Slider/April22/1651137429_Gosend Silder (4) (1).png',
           title: 'Kirim Paket Instan dengan GoSend sekarang juga',
          descr: 'Customer Sahabat KA ingin paket dikirim saat itu juga? Tenang, sekarang Sahabat KA kirim paket instan pakai GoSend',
          tag: '4 Info',
        }
      ],
      swiperOption: {
        slidesPerView: 1,
        spaceBetween: 8,
        breakpoints: {
          // when window width is <= 320px
          320: {
            slidesPerView: 1,
            spaceBetween: 8
          },
          // when window width is <= 480px
          480: {
            slidesPerView: 2,
            spaceBetween: 8
          },
          // when window width is <= 800px
          800: {
            slidesPerView: 3,
            spaceBetween: 8
          }
        },
        autoplay: {
          delay: 5000,
          disableOnInteraction: false
        },
        pagination: {
          el: '.swiper-pagination'
        }
      }
    }
  }
}
</script>

<style lang="scss" scoped>
.banner{
  margin: 40px 0 30px 0;
  .swiper-wrapper{
    .banner-content{
      position: relative;
      display: flex;
      flex-direction: row;
      align-items: center;
      .banner-img{
        width: 400px;
      }
      .title{
        padding-left: 40px;
        span{
          font-size: 16px;
          font-weight: 500px;
          color: rgb(250, 179, 0);
          background: rgba(243, 185, 92, 0.157);
          padding: 8px 16px;
          border-radius: 100px;
        }
        h2{
          font-size: 3em;
          font-weight: 700;
          width: 85%;
        }
        p{
          font-size: 18px;
          font-weight: 400;
          line-height: 25px;
          margin-top: 20px;
        }
        .btn-lengkap{
          font-size: 18px;
          font-weight: 600;
          cursor: pointer;
          background: none;
          color: #8C46CF;
          padding: 6px 20px;
          border: 2px solid #8C46CF;
          border-radius: 100px;
          &:hover{
        background:#8C46CF ;
        color: #fff;
      }
        }
      }
    }
  }
  .banner-b{
    cursor: pointer;
    img{
      width: 100%;
    }
  }
}

</style>