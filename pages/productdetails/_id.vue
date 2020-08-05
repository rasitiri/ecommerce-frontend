<template>
  <div>
    <div class="product">
      <div class="productimage">
        <zoom-on-hover
          class="pimage"
          img-normal="https://www.bestjquery.com/tutorial/product-grid/demo5/images/img-1.jpg"
        ></zoom-on-hover>
      </div>

      <div class="prodinfos mx-auto ">
        <div class="nex">
          <span class="productname mx-auto">Kadın Kazağı</span>
          <hr />
        </div>
        <div class="infoflex mx-auto card-deck">
          <div class="productinfo mx-auto ">
            <div class="pbp mx-auto">
              <h4 class="productprice pr m-auto">50 TL</h4>
              <nuxt-link class="productbrand pr m-auto" to="#">Gucci</nuxt-link>
            </div>
            <div class="productselects">
              <select class="custom-select pr productsize">
                <option disabled selected>Beden Seçin</option>
                <option value="Xs">XS</option>
                <option value="s">S</option>
                <option value="m">M</option>
                <option value="l">L</option>
                <option value="xl">XL</option>
                <option value="xl">XXL</option>
              </select>

              <select class="custom-select pr productsize">
                <option disabled selected>Renk Seçin</option>
                <option value="Xs">Siyah</option>
                <option value="s">Kırmızı</option>
                <option value="m">Sarı</option>
                <option value="l">Beyaz</option>
              </select>
            </div>
            <div class="text-center">
              <div class="quantity">Adet</div>
              <number-input v-model="value" :min="1" inline controls></number-input>
            </div>
          </div>

          <div class="productinfo2 mx-auto ">
            <a href="#" class="productcomme">
              <b-form-rating
                class="rating"
                icon-empty="heart"
                icon-half="heart-half"
                icon-full="heart-fill"
                id="rating-readonly"
                value="3.6"
                readonly
                show-value
                precision="1"
                variant="danger"
              ></b-form-rating>
              <span class="productcom badge badge-danger my-3">
                Ürün Yorumları
                <span class="badge badge-light">4</span>
              </span>
               <span class="productcom2 btn btn-danger my-3">
               Yorum Yap <i class="far fa-comment"></i>
              </span>
            </a>

            <span
              class="productdet pr mx-auto"
            >lorem Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita magnam rem a nisi enim voluptas ullam dolorem alias iure sint numquam sit non atque cum, ut, aspernatur voluptatum animi vitae!</span>
          </div>
        </div>

        <div class="productbuy">
          <button class="btn btn-primary m-5">
            <i class="fas fa-shopping-cart"></i> Sepete Ekle
          </button>
          <button class="btn btn-outline-primary m-5">
            <i class="fas fa-credit-card"></i> Hemen Al
          </button>
        </div>
      </div>
    </div>

    <div class="recommended">
      <div class="rectitle text-center">Benzer Ürünler</div>

      <div class="recdeck card-deck mx-auto">
        <nuxt-link to="#" class="mx-auto recproduct">
          <div class="rpimage-box mx-auto">
            <img
              src="https://sky-static.mavi.com/sys-master/maviTrImages/h29/h9f/9282399371294/167245-25705_image_1.jpg_Default-ZoomProductImage"
             
            />
          </div>

          <div class="mx-auto" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm m-1">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm m-1 text-1">
              <i class="fas fa-external-link-square-alt"></i> Ürünü İncele
            </button>
          </div>
        </nuxt-link>

 <nuxt-link to="#" class="mx-auto recproduct">
          <div class="rpimage-box mx-auto">
            <img
              src="https://sky-static.mavi.com/sys-master/maviTrImages/h29/h9f/9282399371294/167245-25705_image_1.jpg_Default-ZoomProductImage"
             
            />
          </div>

          <div class="mx-auto" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm m-1">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm m-1 text-1">
              <i class="fas fa-external-link-square-alt"></i> Ürünü İncele
            </button>
          </div>
        </nuxt-link>


         <nuxt-link to="#" class="mx-auto recproduct">
          <div class="rpimage-box mx-auto">
            <img
              src="https://sky-static.mavi.com/sys-master/maviTrImages/h29/h9f/9282399371294/167245-25705_image_1.jpg_Default-ZoomProductImage"
             
            />
          </div>

          <div class="mx-auto" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm m-1">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm m-1 text-1">
              <i class="fas fa-external-link-square-alt"></i> Ürünü İncele
            </button>
          </div>
        </nuxt-link>


         <nuxt-link to="#" class="mx-auto recproduct">
          <div class="rpimage-box mx-auto">
            <img
              src="https://sky-static.mavi.com/sys-master/maviTrImages/h29/h9f/9282399371294/167245-25705_image_1.jpg_Default-ZoomProductImage"
             
            />
          </div>

          <div class="mx-auto" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm m-1">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm m-1 text-1">
              <i class="fas fa-external-link-square-alt"></i> Ürünü İncele
            </button>
          </div>
        </nuxt-link>




      </div>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'

Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)
export default {
  data() {
    return {
      value: 1,
    }
  },
}
</script>

<style>
.pr {
  margin: 15px;
}

.productbuy {
  display: flex;
  justify-content: center;
}

.pbs {
  font-size: 12px !important;
}

.nex {
  margin: 25px;
  justify-content: center;
  align-items: center;
  text-align: center;
  max-width: 800px;
  overflow: hidden;
}

.pbp {
  display: flex;
  margin-bottom: 25px;
}

.product {
  border-radius: 10px;
  border: rgb(235, 235, 235) 2px solid;
  margin: 25px;
  display: flex;
}

.productimage {
  border-radius: 10px;
  align-items: center;
  overflow: hidden;
  width: 400px;
  height: 500px;
  margin: 25px;

  justify-content: center;
}

.pimage {
  border-radius: 10px;
}

.productinfo {
  margin: 25px;
}

.productinfo2 {
  margin: 25px;
}

.productname {
  color: rgb(44, 44, 44);
  font-size: 2rem;
}

.productbrand {
  color: gray !important;
  font-size: 20px !important;
  font-weight: 400 !important;
}

.productbrand:hover {
  color: black !important;
}

.productprice {
  font-weight: 400;
  font-size: 20px;
}

.productprice2 {
  font-weight: 400;
  font-size: 16px;
}

.productdet {
  display: flex;
  max-width: 400px;

  padding: 15px;
  color: gray;
}

.productsize {
  margin-top: 50px;
}

.productcomme {
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.rating {
  border: 1px solid rgb(223, 223, 223) !important;
}

.rating:focus {
  box-shadow: none !important;
}

.rating:hover {
  background-color: rgb(243, 243, 243);
}

.productcom {
  font-size: 12px;
  color: white !important;
  font-weight: 400 !important;
  
}

.productcom2 {
  font-size: 10px !important;
  padding: 2px !important;
  color: gray !important ;
background-color: white !important;
  font-weight: 400 !important;
}

.productcom2:hover {background-color: #DC3545 !important;}

.productselects {
  display: flex;
}

.quantity {
  position: relative;
  z-index: 20;
  bottom: -33px;
  left: 50%;
  color: gray;

  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -o-user-select: none;
  user-select: none;
  width: 60px;
}
.recdeck {
  border-radius: 10px;
  border: rgb(235, 235, 235) 2px solid;
  margin: 25px;

}

.recproduct {
  margin: 25px;
  width: 280px;

  border-radius: 10px;
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 25px;
}

.recproduct:hover {
  background-color: rgb(250, 250, 250);
}



.rpimage-box {
    display: flex;
    position: relative;
justify-content: center;
align-items: center;
text-align: center;
    overflow: hidden;
   height: 240px;
  width: 200px;
  border-radius: 10px;
   transition: transform 0.5s ease;
}
.rpimage-box img {
    border-radius: 10px;
max-width: 100%;
    transition: all 0.3s;
    display: block;
    width: 100%;
    height: 100% ;
    transform: scale(1);
     transition: transform 0.5s ease;
  
}

.rpimage-box:hover img {
    transform: scale(1.3);
}

@media only screen and (max-width: 760px) {
  .productimage{
    display: none;
  }
}

</style>