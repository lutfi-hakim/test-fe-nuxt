<template>
<section>

    <div class="container">
        <div class="playstore">
            <div class="playstore-left">
                <img src="https://kiriminaja.com/assets/home-2/call-to-action.png" alt="image" class="hp">
            </div>
            <div class="playstore-right">
                <h2>Gratis daftar dalam hitungan detik</h2>
                <p>Semua bisa mulai kirim paket tanpa ribet. Jadikan pengalaman pengiriman paket lebih mudah dengan KiriminAja.</p>
                <span>
                    <img src="https://kiriminaja.com/assets/service/v2/appstore-compressed.png" alt="">
                    <img src="https://kiriminaja.com/assets/service/v2/googleplay-compressed.png" alt="">
                </span>
            </div>
        </div>
    </div>
                    </section>
</template>

<style lang="scss" scoped>

    .hp{
        width: 450px;
    }
    .playstore{
        position: relative;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        margin: 80px 0;
        .playstore-right{
            span{
                img{
                    cursor: pointer;
                    width: 120px;
                }
            }
        }

    }
</style>