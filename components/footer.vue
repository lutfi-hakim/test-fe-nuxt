<template>
<section>

  <div>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-3 footer-column">
            <ul class="nav flex-column">
              <li class="nav-item">
                <span class="footer-title">Tautan Cepat</span>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Cek Tarif Aja</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Kabar Buatmu</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Manajemen Order</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Integrasi API</a>
          </li>
        </ul>
      </div>
      <div class="col-md-3 footer-column">
        <ul class="nav flex-column">
          <li class="nav-item">
            <span class="footer-title">KiriminAja</span>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Tentang Kami</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Syarat & Ketentuan</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Kebijakan Privasi</a>
          </li>
           <li class="nav-item">
            <a class="nav-link" href="#">Fakta & Pertanyaan</a>
          </li>
        </ul>
      </div>
      <div class="col-md-3 footer-column">
        <ul class="nav flex-column">
          <li class="nav-item">
            <span class="footer-title">Contact & Support</span>
          </li>
          <li class="nav-item">
            <span class="nav-link"><i class="fas fa-phone"></i>0274 8000 123</span>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="fas fa-comments"></i>Live chat</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="fas fa-envelope"></i>support@kiriminaja.com</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="fas fa-star"></i>Jl. Palagan Tentara Pelajar No. 30 KM 08, Mudal, Kelurahan Sariharjo, Kecamatan Ngaglik, Kabupaten Sleman, Provinsi Daerah Istimewa Yogyakarta</a>
          </li>
        </ul>
      </div>
      <div class="col-md-3 footer-column">
         <p class="text-white">Terdaftar di</p>
      <img src="https://kiriminaja.com/assets/home-2/logo-kominfo.svg" alt="">
      </div>
    </div>

  
    <div class="row text-center">
      <div class="col-md-4 box">
        <span class="copyright quick-links">Copyright &copy; 2022
        </span>
      </div>
      <div class="col-md-4 box">
        <ul class="list-inline social-buttons">
          <li class="list-inline-item">
            <a href="#">
            <i class="fab fa-twitter"></i>
          </a>
          </li>
          <li class="list-inline-item">
            <a href="#">
              <i class="fab fa-facebook-f"></i>
          </a>
          </li>
          <li class="list-inline-item">
            <a href="#">
              <i class="fab fa-linkedin-in"></i>
          </a>
          </li>
        </ul>
      </div>
      <div class="col-md-4 box">
        <ul class="list-inline quick-links">
          <li class="list-inline-item">
            <a href="#">Privacy Policy</a>
          </li>
          <li class="list-inline-item">
            <a href="#">Terms of Use</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</footer>
    </div>

            </section>
</template>


<style>
a {
  color: #fff;
}

a:hover {
  color: #fec503;
  text-decoration: none;
}

::selection {
  background: #fec503;
  text-shadow: none;
}

footer {
  padding: 2rem 0;
  background: #8c46cfa1;
}

.footer-column:not(:first-child) {
  padding-top: 2rem;
}
@media (min-width: 768px) {
  .footer-column:not(:first-child) {
    padding-top: 0rem;
  }
}

.footer-column {
  text-align: left;
  margin-bottom: 40px;
}
.footer-column .nav-item .nav-link {
  padding: 0.4rem 0;
}
.footer-column .nav-item span.nav-link {
  color: #fff;
}
.footer-column .nav-item span.footer-title {
  font-size: 16px;
  font-weight: 700;
  color: rgb(231, 227, 227);
}
.footer-column .nav-item .fas {
  margin-right: 0.5rem;
}
.footer-column ul {
  display: inline-block;
}
@media (min-width: 768px) {
  .footer-column ul {
    text-align: left;
  }
}

ul.social-buttons {
  margin-bottom: 0;
}

ul.social-buttons li a:active,
ul.social-buttons li a:focus,
ul.social-buttons li a:hover {
  background: #fec503;
}

ul.social-buttons li a {
  font-size: 14px;
  line-height: 40px;
  display: block;
  width: 40px;
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  transition: all 0.3s;
  color: #fff;
  border-radius: 100%;
  outline: 0;
  background: #1a1d20;
}

footer .quick-links {
  font-size: 14px;
  line-height: 40px;
  margin-bottom: 0;
  text-transform: none;
  /* font-family: Montserrat, "Helvetica Neue", Helvetica, Arial, sans-serif; */
}

.copyright {
  color: #fff;
}

.fa-ellipsis-h {
  color: #fff;
  padding: 2rem 0;
}

</style>