<template>
  <div>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
      crossorigin="anonymous"
    />
    <header-component></header-component>
    <navbar-top></navbar-top>
    <navbar-main></navbar-main>
    <navbar-modal></navbar-modal>
    <search></search>

    <nuxt></nuxt>

    <div>
      <a v-scroll="handleScroll" class="tothetop" href="#navbar1">
        <i class="fas fa-chevron-up"></i>
      </a>
    </div>
    <footerpart></footerpart>
  </div>
</template>

<script>
import footerpart from '../components/footerpart'
import HeaderComponent from '../components/Navbar/HeaderComponent'
import NavbarTop from '../components/Navbar/NavbarTop'
import NavbarMain from '../components/Navbar/NavbarMain'
import Search from '../components/Navbar/Search'
import NavbarModal from '../components/Navbar/NavbarModal'

export default {
  components: {
    footerpart,
    HeaderComponent,
    NavbarTop,
    NavbarMain,
    Search,
    NavbarModal,
  },

  methods: {
    handleScroll: function (evt, el) {
      if (window.scrollY > 700) {
        el.setAttribute('style', 'display:block; ')
      }

      if (window.scrollY < 200) {
        el.setAttribute('style', 'display:none;')
      }
    },
  },
}
</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100;300;400;500;700;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

* {
  font-family: 'Noto Sans JP', sans-serif;
}

button {
  box-shadow: none !important;
}
select {
  box-shadow: none !important;
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
  border: 2px solid #bebebe;
  border-right: 0px;
  padding: 6px;
  outline: none;
  width: 500px;
  margin-left: 30px;
}

.searchbar:focus {
  border: 2px solid rgb(255, 87, 87);
}

.searchbutton {
  border-radius: 0px 10px 10px 0px;
  -moz-border-radius: 0px 10px 10px 0px;
  -webkit-border-radius: 0px 10px 10px 0px;
  border: 2px solid #bebebe;
  border-left: 0px !important;
  color: gray;
  background-color: white;
  padding: 6px;
  outline: none !important;
}

.searchbutton:focus {
  border: 2px solid rgb(255, 87, 87) !important;
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
  border: 2px solid #bebebe;
  border-right: 0px;
  padding: 6px;
  outline: none;
  width: 500px;
}

.searchbar2:focus {
  border: 2px solid rgb(255, 87, 87);
}

.searchbutton2 {
  border-radius: 0px 10px 10px 0px;
  -moz-border-radius: 0px 10px 10px 0px;
  -webkit-border-radius: 0px 10px 10px 0px;
  border: 2px solid #bebebe;
  border-left: 0px !important;
  color: gray;
  background-color: white;
  padding: 6px;
  outline: none !important;
}

.searchbutton2:focus {
  border: 2px solid rgb(255, 87, 87) !important;
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

.catsignn {
  padding: 10px;
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
  padding: 10px 15px;
  color: rgb(235, 235, 235) !important;
  box-shadow: 1px 1px 1px rgb(165, 165, 165), 2px 2px 2px rgb(170, 170, 170);
  transition: 1.5s all cubic-bezier(0.39, 0.575, 0.565, 1);
  display: none;
  transform: translate3d(0, -10px, 0);
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
