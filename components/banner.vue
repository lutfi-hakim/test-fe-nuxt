<template>
  <div>
    <div v-swiper:mySwiper="swiperOption">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="item in banner" v-bind:key="item.key">
          <img :src="item.src" alt="item.src">
        </div>
      </div>
      <div class="swiper-pagination"  slot="pagination"></div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      banner: [{
          src: 'https://kiriminaja.com/storage/Slider/April22/1650526232_NCS (Slider) (1) (1).png'
        }, {
          src: 'https://kiriminaja.com/storage/Slider/June22/1654855912_Small.png'
        }, {
          src: 'https://kiriminaja.com/storage/Slider/June22/1655115388_Untitled-1.png'
        }, {
          src: 'https://kiriminaja.com/storage/Slider/April22/1651137429_Gosend Silder (4) (1).png'
        }, {
          src: 'https://kiriminaja.com/storage/Slider/April22/1650526232_NCS (Slider) (1) (1).png'
        },
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