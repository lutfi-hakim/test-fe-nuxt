<template>
  <div>
    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="#"><img src="https://kiriminaja.com/assets/atrust/svg-logo-primary.svg" alt="logo" class="logo"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="/">Beranda <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Blog</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/about">Kabar</a>
            </li>
            <div class="collapse navbar-collapse" id="navbarNavDarkDropdown">
              <ul class="navbar-nav">
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Layanan
                </a>
                <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="navbarDarkDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
            </ul>
          </div>
           <li class="nav-item">
              <a class="nav-link" href="#">Cek Ongkir</a>
            </li>
             <li class="nav-item">
              <a class="nav-link" href="#">Lacak</a>
            </li>
             <li class="nav-item">
              <a class="nav-link daftar" href="#">Daftar</a>
            </li>
             <li class="nav-item">
              <a class="nav-link masuk" href="#">Masuk</a>
            </li>
          </ul>
        </div>
      </div>
    
    </nav>
  </div>
</template>

<script>
export default {
  methods : {
    goBack () {
      this.$store.commit('setArticle', {})
      this.$router.replace({ 'path' : '/' })
    }
  }
}
</script>

<style lang="scss" scoped>
.navbar{
  padding: 16px 0;
}
.navbar-brand {
  span {
    font-size: 32px;
  }
}
.navbar-nav{
  li a{
    color: #8C46CF;
    margin: 0 10px;
    font-weight: 600;

    &:hover{
      font-weight: 600;
      color: #175ABA;
    }
  }
    .masuk, .daftar{
      border: 1px solid #175ABA;
      border-radius: 100px;
      padding: 8px 24px;
      &:hover{
        background:#8C46CF ;
        color: #fff;
      }
    }
}
.logo{
  width: 145px;
}
</style>