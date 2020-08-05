<template>
  <div>
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.14.0/css/all.css"
      integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
      crossorigin="anonymous"
    />
    <script
      src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
      integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"
      integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
      crossorigin="anonymous"
    ></script>

    <div id="navbar1" class="ns flex">
      <span class="my-auto nsler m-3 ns1">200 TL VE ÜZERİ ÇANTA HEDİYE</span>
      <span class="mx-auto my-auto nsler ns2">90 GÜN DEĞİŞİM VE İADE</span>
      <span class="my-auto nsler m-3 ns3">TÜM ALIŞVERİŞLERDE KARGO ÜCRETSİZ</span>
    </div>

    <div class="aranav m-auto">
      <nuxt-link to="./productdetails/3" class="mincat mt-1">Yardım</nuxt-link>
      <span class="my-auto text-muted">|</span>
      <nuxt-link to="#" class="mincat mt-1">Siparişlerim</nuxt-link>
      <span class="my-auto text-muted">|</span>
      <nuxt-link to="#" class="mincat mt-1">Kampanyalar</nuxt-link>
      <span class="my-auto text-muted">|</span>
      <nuxt-link to="#" class="mincat mt-1">Kupon</nuxt-link>
      <span class="my-auto text-muted">|</span>
      <nuxt-link to="#" class="mincat mt-1">Language</nuxt-link>
    </div>

    <div id="navbar2" class="navbar2 sticky-top">
      <nuxt-link class="logo" to="/">
        STORE
        <div>
          <i class="fas fa-store"></i>
        </div>
      </nuxt-link>

      <form class="form-inline m-auto">
        <input class="searchbar" type="search" placeholder="Ne arıyordunuz?" aria-label="Search" />
        <button class="searchbutton" type="submit">
          Ara
          <i class="fa fa-search" aria-hidden="true"></i>
        </button>
      </form>

      <div class="m-auto text-center border rounded p-1 category">
        <i class="fa fa-shopping-cart" aria-hidden="true"></i>
        <span class="badge badge-danger ml-1">0</span>
        <div>Sepetim</div>
      </div>

      <div class="my-auto categories2">
        <!-- Button trigger modal -->
        <div class="category border-0" data-toggle="modal" data-target="#login">Giriş Yap</div>

        <div class="category border-0" data-toggle="modal" data-target="#signup">Kayıt Ol</div>
      </div>
      <!-- Modal -->
      <div
        class="modal"
        id="login"
        tabindex="-1"
        role="dialog"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">Giriş Yap</h5>
              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
            <div class="modal-body">
              <form>
                <div class="form-group">
                  <label for="email">E-mail Adresi</label>
                  <input placeholder="email@örnek.com" class="form-control" id="email" />
                </div>
                <div class="form-group">
                  <label for="password">Şifre</label>
                  <input type="password" class="form-control" id="password" />
                </div>
                <div class="form-group form-check">
                  <input type="checkbox" class="form-check-input" id="exampleCheck1" />
                  <label class="form-check-label" for="exampleCheck1">Beni Hatırla</label>
                </div>
              </form>
            </div>
            <div class="modal-footer">
              <button type="submit" class="giris">Giriş Yap</button>
              <button type="submit" class="giris2">
                <i class="fab fa-facebook"></i> Facebook ile Giriş Yap
              </button>
              <button type="submit" class="giris3">
                <i class="fab fa-google-plus"></i> Google ile Giriş Yap
              </button>
            </div>
          </div>
        </div>
      </div>

      <div
        class="modal"
        id="signup"
        tabindex="-1"
        role="dialog"
        aria-labelledby="exampleModalLabel2"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">Kayıt Ol</h5>
              <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
            </div>
            <div class="modal-body">
              <form>
                <div class="form-group namesurname">
                  <div class="mr-1">
                    <label for="name">Adınız</label>
                    <input class="form-control" id="name" />
                  </div>
                  <div>
                    <label for="surname">Soyadınız</label>
                    <input class="form-control" id="surname" />
                  </div>
                </div>

                <div class="form-group">
                  <label for="email">E-mail Adresi</label>
                  <input placeholder="email@örnek.com" class="form-control" id="email" />
                </div>
                <div class="form-group">
                  <label for="password">Şifre</label>
                  <input type="password" class="form-control" id="password" />
                </div>
                <div class="form-group">
                  <label for="password">Tekrar Şifre</label>
                  <input type="password" class="form-control" id="password" />
                </div>
              </form>
            </div>
            <div class="modal-footer">
              <button type="submit" class="giris">Kayıt Ol</button>
              <button type="submit" class="giris2">
                <i class="fab fa-facebook"></i> Facebook ile Kayıt Ol
              </button>
              <button type="submit" class="giris3">
                <i class="fab fa-google-plus"></i> Google ile Kayıt Ol
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="categories1 m-auto">
      <div class="subnav">
        <nuxt-link to="news" class="category subnavbtn">Yeniler</nuxt-link>
        <div class="subnav-content">
          <span>Company</span>
          <span>fm</span>
          <span>Careers</span>
        </div>
      </div>
      <div class="subnav">
        <div class="category subnavbtn">Kadın</div>
        <div class="subnav-content">
          <span href="#team">Elbise</span>
          <span href="#company">T-shirt</span>

          <span>Careers</span>
        </div>
      </div>
      <div class="subnav">
        <div class="category subnavbtn">Erkek</div>
        <div class="subnav-content">
          <div class="subimage m-auto flex text-center" alt="model-photo" src>
            <span class="m-auto imagetext">Tümünü Gör</span>
          </div>
          <div class="block m-auto block1">
            <ul class="text-center">
              <span class="lititle">Öne Çıkanlar</span>
              <li class="litop">Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
            </ul>
          </div>

          <div class="block m-auto block2">
            <ul class="text-center">
              <span class="lititle">Öne Çıkanlar</span>
              <li class="litop">Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
            </ul>
            <ul class="text-center">
              <span class="lititle">Öne Çıkanlar</span>
              <li class="litop">Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
            </ul>
          </div>

          <div class="block m-auto block3">
            <ul class="text-center">
              <span class="lititle">Öne Çıkanlar</span>
              <li class="litop">Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
            </ul>
            <ul class="text-center">
              <span class="lititle">Öne Çıkanlar</span>
              <li class="litop">Company</li>
              <li>Company</li>
              <li>Company</li>
              <li>Company</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="subnav">
        <div class="category subnavbtn">Çocuk</div>
        <div class="subnav-content">
          <span>Comprany</span>
          <span>sdam</span>
          <span>Careers</span>
        </div>
      </div>

      <div class="subnav">
        <div class="category subnavbtn">Aksesuar</div>
        <div class="subnav-content">
          <span>Company</span>
          <span>dfam</span>
          <span>Casadfsreers</span>
        </div>
      </div>
    </div>

    <div class="navbar3 sticky-top">
      <form class="form-inline mx-auto my-2">
        <input class="searchbar2" type="search" placeholder="Ne arıyordunuz?" aria-label="Search" />
        <button class="searchbutton2" type="submit">
          Ara
          <i class="fa fa-search" aria-hidden="true"></i>
        </button>
      </form>
    </div>

    <nuxt></nuxt>
    <div>
      <a v-scroll="handleScroll" class="tothetop" href="#navbar1">
     
        <i class="fas fa-chevron-up "></i>
      </a>
    </div>
    <footerpart></footerpart>
  </div>
</template>

<script>
import footerpart from '../components/footerpart'

export default {
  components: {
    footerpart,
  },

  methods: {
    handleScroll: function (evt, el) {
      if (window.scrollY > 700) {
        el.setAttribute(
          'style',
          'display:block; '
        )
      }

       if (window.scrollY < 200) {
        el.setAttribute(
          'style',
          'display:none;'
        )
      }

    
    },
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100;300;400;500;700;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

* {
  font-family: 'Noto Sans JP', sans-serif;
}

.giris {
  justify-content: center;
  width: 100%;
  border-radius: 5px;
  border: 2px solid rgb(199, 199, 199);
  background-color: white;
  color: rgb(87, 87, 87);
  font-weight: bold;
  padding: 5px;
}

.giris:hover {
  background-color: rgb(236, 236, 236);
}

.giris2 {
  justify-content: center;
  width: 100%;
  border-radius: 5px;
  border: 2px solid #156bdb;
  background-color: #1877f2;
  color: white;
  font-weight: bold;
  padding: 5px;
}

.giris2:hover {
  background-color: #156bdb;
}

.giris3 {
  justify-content: center;
  width: 100%;
  border-radius: 5px;
  border: 2px solid rgb(195, 57, 47);
  background-color: rgb(223, 78, 67);
  color: white;
  font-weight: bold;
  padding: 5px;
}

.giris3:hover {
  background-color: rgb(195, 57, 47);
}

.namesurname {
  display: inline-flex;
}
.searchbar {
  border-radius: 10px 0px 0px 10px;
  -moz-border-radius: 10px 0px 0px 10px;
  -webkit-border-radius: 10px 0px 0px 10px;
  border: 1px solid #000000;
  border-right: 0px;
  padding: 6px;
  outline: none;
  width: 500px;
}

.searchbar:focus {
  border: 2px solid rgb(255, 68, 68);
  border-right: 0px !important;
}

.searchbutton {
  border-radius: 0px 10px 10px 0px;
  -moz-border-radius: 0px 10px 10px 0px;
  -webkit-border-radius: 0px 10px 10px 0px;
  border-right: 1px solid #000000 !important;
  border-bottom: 1px solid #000000 !important;
  border-top: 1px solid #000000 !important;
  border-left: 0px !important;
  color: gray;
  background-color: white;
  padding: 6px;
  outline: none !important;
}

.searchbutton:focus {
  border: 2px solid rgb(255, 68, 68) !important;
}

.searchbutton:hover {
  background-color: rgb(236, 236, 236);
}

.navbar3 {
  border-bottom: rgb(212, 212, 212) 1px solid;
  position: -webkit-sticky !important;
  position: sticky !important;
  display: none;
  width: 100%;

  background-color: white;
}

.searchbar2 {
  border-radius: 10px 0px 0px 10px;
  -moz-border-radius: 10px 0px 0px 10px;
  -webkit-border-radius: 10px 0px 0px 10px;
  border: 1px solid #000000;
  border-right: 0px;
  padding: 6px;
  outline: none;
  width: 500px;
}

.searchbar2:focus {
  border: 2px solid rgb(255, 68, 68);
}

.searchbutton2 {
  border-radius: 0px 10px 10px 0px;
  -moz-border-radius: 0px 10px 10px 0px;
  -webkit-border-radius: 0px 10px 10px 0px;
  border-right: 1px solid #000000 !important;
  border-bottom: 1px solid #000000 !important;
  border-top: 1px solid #000000 !important;
  border-left: 0px !important;
  color: gray;
  background-color: white;
  padding: 6px;
  outline: none !important;
}

.searchbutton2:focus {
  border: 2px solid rgb(255, 68, 68) !important;
}

.searchbutton2:hover {
  background-color: rgb(236, 236, 236);
}

.categories1 {
  display: flex;
  justify-content: center;
  padding: 15px;

  z-index: 999;
  border-bottom: rgb(212, 212, 212) 1px solid;
}

.category {
  padding: 25px;
  padding-bottom: 15px;
  padding-top: 15px;
  display: inline;
  cursor: pointer;
}

.category:hover {
  border-bottom: 1px solid rgb(255, 68, 68);
  color: rgb(255, 68, 68) !important;
}

a {
  color: black !important;
  text-decoration: none !important;
}

.logo {
  padding: 10px;
  margin: auto;
  font-size: 30px;
  font-weight: bold;
  letter-spacing: 8px;
  cursor: pointer;
  display: inline-flex;
}

.navbar2 {
  position: -webkit-sticky !important;
  position: sticky !important;
  display: flex;
  background-color: white;
  z-index: 1;
  /* box-shadow: 1px 1px rgb(212, 212, 212); */
}
.modal-dialog {
  z-index: 999;
  -webkit-box-shadow: 500px 500px 500px 500px rgba(0, 0, 0, 0.1);
  box-shadow: 10px 500px 500px 500px rgba(0, 0, 0, 0.5);
}

.navbar3 {
  z-index: 999 !important;
}

.modal {
  z-index: 1020 !important;
}

.modal-backdrop {
  position: unset !important;
}

.tothetop {
  position: fixed;
  z-index: 1020;
  bottom: 25px;
  right: 25px;
  border-radius: 25px;
  background-color: rgb(105, 105, 105);
  padding: 10px 15px ;
  color: rgb(235, 235, 235) !important;
  box-shadow: 1px 1px 1px rgb(165, 165, 165), 2px 2px 2px rgb(170, 170, 170);
  transition: 1.5s all cubic-bezier(0.39, 0.575, 0.565, 1);
  display:none;
  transform: translate3d(0, -10px, 0)
}

.ns {
  height: 30px;
  background-color: black;
  display: flex;
  color: white;
  font-size: 10px;
}

.aranav {
  font-size: 12px;
  display: flex;
  justify-content: center;
}

.mincat {
  color: gray !important;
  margin-right: 15px;
  margin-left: 15px;
}

.mincat:hover {
  color: black !important;
}

.nsler {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif !important;
}

@media only screen and (max-width: 1080px) {
  .category {
    padding-left: 15px;
    padding-right: 15px;
  }
}

@media only screen and (max-width: 1080px) {
  .category {
    padding-left: 12px;
    padding-right: 12px;
    font-size: 14px;
  }

  .subimage {
    height: 250px !important;
  }
}

@media only screen and (max-width: 1010px) {
  .searchbar {
    width: 400px;
  }

  .lititle {
    font-size: 12px !important;

    padding: 2px 10px !important;
  }

  .subimage {
    height: 230px !important;
  }

  .subnav-content li {
    font-size: 10px;
    padding: 2px !important;
    border-radius: 10px;
  }
}

@media only screen and (max-width: 910px) {
  .searchbar {
    width: 300px;
  }
}

@media only screen and (max-width: 800px) {
  .searchbar {
    width: 200px;
  }
}

@media only screen and (max-width: 760px) {
  .categories1 {
    display: none;
  }

  .category:hover {
    border: none;
  }

  .categories2 {
    margin-left: auto;
  }

  .searchbar {
    display: none;
  }

  .searchbutton {
    display: none;
  }

  .navbar2 {
    border: none;
  }

  .navbar3 {
    display: flex;
    position: -webkit-sticky;
    position: sticky;
  }

  .tothetop {
    bottom: 80px;
    right: 15px;
    padding: 6px 10px;
    font-size: 14px;
    
  }

  .navbar2 {
    position: relative !important;
    display: flex;
    background-color: white;
    z-index: 0;
    /* box-shadow: 1px 1px rgb(212, 212, 212); */
  }
}

@media only screen and (max-width: 560px) {
  .ns1 {
    display: none;
  }
  .ns2 {
    display: none;
  }
  .ns3 {
    margin: auto;
    justify-content: center;
    display: flex;
    width: 100%;
  }
  .mincat {
    font-size: 8px;
    margin-right: 10px;
    margin-left: 10px;
  }

  .category {
    font-size: 10px;
    padding: 7px;
  }

  .searchbar2 {
    width: 300px;
  }
}

@media only screen and (max-width: 370px) {
  .logo {
    font-size: 15px;
  }
  .category {
    font-size: 10px;
    padding: 7px;
  }
  .bottombars {
    font-size: 13px;
  }

  .searchbar2 {
    width: 220px;
  }
}

.subnav {
  float: left;
  z-index: 10;
}

.subnav-content {
  display: none;
  position: absolute;
  left: 0;
  min-height: 400px;
  margin-top: 16px;
  background: white;
  max-width: 80%;
  left: 10%;

  -webkit-box-shadow: 0px 500px 0px 500px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 500px 0px 500px rgba(0, 0, 0, 0.1);
  justify-content: center;
  width: 100%;
  z-index: 1;
  border-radius: 0px 0px 40px 40px;
}

.subnav-content ul {
  justify-content: center;
  margin-top: 25px;
  color: rgb(66, 66, 66);
  text-decoration: none;
  list-style-type: none;
  display: block;
}

.subimage {
  height: 300px;
  width: 25%;
  margin-left: 50px !important ;
  border-radius: 25px;
  cursor: pointer;
  transition: 2s;
  background-image: url('https://www.oxxo.com.tr/ContentImages/CatalogBanners/Menu/giyim2.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
}

.imagetext {
  display: none;
  font-size: 25px;
  font-weight: bold;
  color: white;

  letter-spacing: 5px;
  text-shadow: 2px 2px black;
  transition: 2s;
}

.subimage:hover {
  -webkit-box-shadow: inset 200px 200px 42px 200px rgba(255, 255, 255, 0.3);
  -moz-box-shadow: inset 200px 200px 42px 200px rgba(255, 255, 255, 0.3);
  box-shadow: inset 200px 200px 42px 200px rgba(255, 255, 255, 0.3);
}

.subimage:hover .imagetext {
  transition: 2s;
  display: block;
}

.subnav-content li {
  border: 1px solid white;
  color: rgb(66, 66, 66);
  text-decoration: none;
  cursor: pointer;
  padding: 5px;
  border-radius: 10px;
  font-family: 'Ubuntu', sans-serif;
}

.subnav-content li:hover {
  color: rgb(255, 68, 68);
  border: 1px solid rgb(255, 68, 68);
}

.subnav:hover .subnav-content {
  display: flex;
}

.lititle {
  font-size: 15px;
  font-weight: bold;
  border-right: 1px solid white;
  border-top: 1px solid white;
  border-left: 1px solid white;
  border-bottom: gray 1px solid;
  padding: 5px 15px;
  cursor: pointer;
}

.lititle:hover {
  color: rgb(255, 68, 68);
  border: 1px solid rgb(255, 68, 68);
  border-radius: 10px;
}

.litop {
  margin-top: 10px;
}

.subnav:hover .category {
  border-bottom: 1px solid rgb(255, 68, 68) !important;
  color: rgb(255, 68, 68) !important;
}



</style>