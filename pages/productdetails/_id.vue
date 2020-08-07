<template>
  <div>
    <div class="product">
      <div class="productimage">
        <zoom-on-hover
          class="pimage"
          img-normal="https://www.bestjquery.com/tutorial/product-grid/demo5/images/img-1.jpg"
        ></zoom-on-hover>
      </div>

      <div class="prodinfos mx-auto">
        <div class="nex">
          <span class="productname mx-auto">Kadın Kazağı</span>
          <hr />
        </div>
 <div class="productimage2 mx-auto">
        <zoom-on-hover
          class="pimage2"
          img-normal="https://www.bestjquery.com/tutorial/product-grid/demo5/images/img-1.jpg"
        ></zoom-on-hover>
      </div>


        <div class="infoflex mx-auto card-deck">
          <div class="productinfo mx-auto">
            <div class="pbp mx-auto">
              <h4 class="productprice pr m-auto">50 TL</h4>
              <nuxt-link class="productbrand pr m-auto" to="#">Gucci</nuxt-link>
            </div>
            <div class="productselects">
           <div class=" idblock  m-2 ">
     <label for="color" class="quantity">Beden Seçin</label>
     <div>
              <select id="color" class="custom-select   productsize">
                <option disabled selected>Beden Seçin</option>
                <option value="XS">XS</option>
                <option value="S">S</option>
                <option value="M">M</option>
                <option value="L">L</option>
                 <option value="XL">XL</option>
              </select> </div>
  </div>
  <div class=" idblock m-2  ">
     <label for="color" class="quantity">Renk Seçin</label>
     <div>
              <select id="color" class="custom-select   productsize">
                <option disabled selected>Renk Seçin</option>
                <option value="black">Siyah</option>
                <option value="red">Kırmızı</option>
                <option value="yellow">Sarı</option>
                <option value="white">Beyaz</option>
              </select> </div>
  </div>
            </div>
            <div class=" idblock  ">
              <div>
              <label for="number-input" class="quantity">Adet</label>
              </div>   <number-input id="number-input" v-model="value" :min="1" inline center controls></number-input>
            </div>
            <div class="productbuy">
              <button class="btn btn-danger text-light productbuys">
                <i class="fas fa-shopping-cart"></i> Sepete Ekle
              </button>
              <button class="btn btn-outline-danger productbuys">
                <i class="fas fa-credit-card"></i> Hemen Al
              </button>
            </div>
          </div>

          <div class="productinfo2 mx-auto">
            <a href="#pills-pcomments-tab" class="productcomme">
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
                Yorum Yap
                <i class="far fa-comment"></i>
              </span>
            </a>

            <span
              class="productdet pr mx-auto"
            >lorem Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita magnam rem a nisi enim voluptas ullam dolorem alias iure sint numquam sit non atque cum, ut, aspernatur voluptatum animi vitae!</span>
          </div>
        </div>
      </div>
    </div>

 
      <div class="rectitle text-center">Benzer Ürünler</div>

      <div class="recdeck card-deck">
        <nuxt-link to="#" class="mx-auto recproduct">
          <div class="rpimage-box mx-auto">
            <img
              src="https://sky-static.mavi.com/sys-master/maviTrImages/h29/h9f/9282399371294/167245-25705_image_1.jpg_Default-ZoomProductImage"
            />
          </div>

          <div class="mx-auto rptitle" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm text-1">
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

          <div class="mx-auto rptitle" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm">
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

          <div class="mx-auto rptitle" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm text-1">
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

          <div class="mx-auto rptitle" to="#">Kadın T-Shirt</div>
          <h4 class="productprice2 mt-1 mx-auto">50 TL</h4>
          <div class="productbuy">
            <button class="btn btn-danger pbs btn-sm">
              <i class="fas fa-shopping-cart"></i> Sepete Ekle
            </button>
            <button class="btn btn-outline-danger pbs btn-sm text-1">
              <i class="fas fa-external-link-square-alt"></i> Ürünü İncele
            </button>
          </div>
        </nuxt-link>
      </div>

      <div class="pdtitle text-center">Ürün Detayları</div>

      <div class="productdetailtab">
        <ul class="nav nav-pills mb-3 npd" id="pills-tab" role="tablist">
          <li class="nav-item mx-auto" role="presentation">
            <a
              class="nav-link active"
              id="pills-pcomments-tab"
              data-toggle="pill"
              href="#pcomments"
              role="tab"
              aria-controls="pills-pcomments"
              aria-selected="true"
            >
              <i class="far fa-comment"></i> Ürün Yorumları
            </a>
          </li>
          <li class="nav-item mx-auto" role="presentation">
            <a
              class="nav-link"
              id="pills-profile-tab"
              data-toggle="pill"
              href="#profile"
              role="tab"
              aria-controls="pills-profile"
              aria-selected="false"
            >
              <i class="fas fa-info-circle"></i> Ürün Özellikleri
            </a>
          </li>
          <li class="nav-item mx-auto" role="presentation">
            <a
              class="nav-link"
              id="pills-contact-tab"
              data-toggle="pill"
              href="#pills-contact"
              role="tab"
              aria-controls="pills-contact"
              aria-selected="false"
            >
              <i class="fas fa-exchange-alt"></i> İade ve Değişim
            </a>
          </li>
        </ul>
        <div class="tab-content" id="myTabContent">
          <div
            class="tab-pane fade show active"
            id="pcomments"
            role="tabpanel"
            aria-labelledby="pcomments-tab"
          >
            <div class="pcommentfirstdiv row">
              <div class="col mx-auto">
                <img
                  class="productimagecomment"
                  src="https://www.bestjquery.com/tutorial/product-grid/demo5/images/img-1.jpg"
                />
              </div>
              <div class="m-auto col-lg-8 col-md-auto p-rating">
                <b-form-rating
                  class="rating2 mx-auto"
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
                <div class="pvotes m-auto">
                  <div class="pvote1">
                    5
                    <b-icon icon="heart-fill" class="m-2" variant="danger"></b-icon>
                    <div class="pvote mx-auto">(2 Oy Verildi)</div>
                  </div>
                  <div class="pvote1">
                    4
                    <b-icon icon="heart-fill" class="m-2" variant="danger"></b-icon>
                    <div class="pvote">(1 Oy Verildi)</div>
                  </div>
                  <div class="pvote1">
                    3
                    <b-icon icon="heart-fill" class="m-2" variant="danger"></b-icon>
                    <div class="pvote">(0 Oy Verildi)</div>
                  </div>
                  <div class="pvote1">
                    2
                    <b-icon icon="heart-fill" class="m-2" variant="danger"></b-icon>
                    <div class="pvote">(2 Oy Verildi)</div>
                  </div>
                  <div class="pvote1">
                    1
                    <b-icon icon="heart-fill" class="m-2" variant="danger"></b-icon>
                    <div class="pvote">(0 Oy Verildi)</div>
                  </div>
                </div>
              </div>
            </div>

            <div class="pcommentseconddiv">
              <div class="comments mx-auto row">
                <div class="col m-auto comav">
                  <div class="commentavatar m-auto">EÖ</div>
                  <span class="commentname mx-auto">Emre Özer</span>
                </div>
                <div class="comment mx-auto col-lg-8 col-md-auto">
                  <b-form-rating
                    class="com-0"
                    inline
                    value="5"
                    icon-empty="heart"
                    icon-half="heart-half"
                    icon-full="heart-fill"
                    readonly
                    variant="danger"
                  ></b-form-rating>
                  <br />
                  <span class="com-title mx-auto">Yorum Başlığı</span>
                  <span
                    class="com-1 mx-auto"
                  >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ab iusto similique corrupti exercitationem voluptate unde. Veritatis ipsum, officia, eveniet, eius repellat non maiores facere dicta sunt soluta dignissimos consectetur suscipit!</span>
                </div>
              </div>

              <div class="comments mx-auto row">
                <div class="col m-auto comav">
                  <div class="commentavatar m-auto">EÖ</div>
                  <span class="commentname mx-auto">Emre Özer</span>
                </div>
                <div class="comment mx-auto col-lg-8 col-md-auto">
                  <b-form-rating
                    class="com-0"
                    inline
                    value="5"
                    icon-empty="heart"
                    icon-half="heart-half"
                    icon-full="heart-fill"
                    readonly
                    variant="danger"
                  ></b-form-rating>
                  <br />
                  <span class="com-title mx-auto">Yorum Başlığı</span>
                  <span
                    class="com-1 mx-auto"
                  >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ab iusto similique corrupti exercitationem voluptate unde. Veritatis ipsum, officia, eveniet, eius repellat non maiores facere dicta sunt soluta dignissimos consectetur suscipit!</span>
                </div>
              </div>

              <div class="comments mx-auto row">
                <div class="col m-auto comav">
                  <div class="commentavatar m-auto">Rİ</div>
                  <span class="commentname mx-auto">Raşit İri</span>
                </div>
                <div class="comment mx-auto col-lg-8 col-md-auto">
                  <b-form-rating
                    class="com-0"
                    inline
                    value="4"
                    icon-empty="heart"
                    icon-half="heart-half"
                    icon-full="heart-fill"
                    readonly
                    variant="danger"
                  ></b-form-rating>
                  <br />
                  <span class="com-title mx-auto">Yorum Başlığı</span>
                  <span
                    class="com-1 mx-auto"
                  >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ab iusto similique corrupti exercitationem voluptate unde. Veritatis ipsum, officia, eveniet, eius repellat non maiores facere dicta sunt soluta dignissimos consectetur suscipit!</span>
                </div>
              </div>
            </div>


             <div class="nav nav-pills mt-3 npd" id="pills-tab" role="tablist">
                   <a
              class="nav-link mx-auto"
              
              href="#"
             
              
            >
              <i class="far fa-comments"></i> Tüm Yorumları Gör
            </a>
             </div>
          </div>




          <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">...</div>
          <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">...</div>
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

<style lang="scss">
.pr {
  margin: 15px;
}

.productbuy {
  display: flex;
  justify-content: center;
}

.productbuys {
  margin: 25px !important;
}

.pbs {
  margin: 2px;
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
  height: 480px;
  margin: 25px;

  justify-content: center;
}

.productimage2 {
  border-radius: 10px;
  align-items: center;
  overflow: hidden;
  width: 200px;
  height: 240px;
text-align: center;
display:none;
  justify-content: center;
}

.pimage {
  border-radius: 10px;
}

.pimage2 {
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
  font-weight: 500;
  font-size: 24px;
  color: #343432;
  letter-spacing: 1px;
}

.productprice2 {
  font-weight: 400;
  font-size: 16px;
  letter-spacing: 1px;
 
}

.rptitle {
  font-weight: bold;
  color:rgb(44, 44, 44)
}

.productdet {
  display: flex;
  max-width: 400px;

  padding: 15px;
  color: gray;
}



.productcomme {
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.rating {
  border: 1px solid rgb(223, 223, 223) !important;
  display: flex;
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

.productcom2:hover {
  background-color: #dc3545 !important;
  color: white !important;
}

.productselects {
  display: flex;
  justify-content: center;
  margin: 5px;
}

.idblock {
  display:block;
 text-align: center;
}

.quantity {

  color: gray;

 
}
.recdeck {
  border-radius: 10px;
  border: rgb(235, 235, 235) 2px solid;
  margin: 25px !important;
}

.recproduct {
  max-width: 280px;

  border-radius: 10px;
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 25px;
}

.recproduct:hover {
-webkit-box-shadow: 0px 0px 38px -4px rgba(0,0,0,0.24);
-moz-box-shadow: 0px 0px 38px -4px rgba(0,0,0,0.24);
box-shadow: 0px 0px 38px -4px rgba(0,0,0,0.24);
 transition: 0.7s;
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
  height: 100%;
  transform: scale(1);
  transition: transform 0.5s ease;
}

.rpimage-box:hover img {
  transform: scale(1.2);
}

.productdetailtab {
  min-height: 500px;
  margin: 25px;
  border-radius: 10px;
  border: rgb(235, 235, 235) 2px solid;
}
.npd {
  background-color: white !important;
  border-radius: 10px;
  -webkit-box-shadow: 4px 10px 37px -8px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: 4px 10px 37px -8px rgba(0, 0, 0, 0.3);
  box-shadow: 4px 10px 37px -8px rgba(0, 0, 0, 0.3);
}

.nav-link {
  color: #c82333 !important;
  font-size: 15px;
}

.nav-pills .nav-link.active,
.nav-pills .show > .nav-link {
  border-radius: 5px !important;
  background-color: #c82333 !important;
  color: white !important;
}

.pcommentfirstdiv {
  padding: 10px 20px;
  justify-content: center;
  text-align: center;
  align-items: center;
}

.productimagecomment {
  border-radius: 10px;

  width: 250px;
  height: 300px;

  margin: 2%;
}

.pvotes {
  display: grid;
  border: 1px solid rgb(223, 223, 223) !important;
  border-radius: 5px;

  justify-content: center;
  text-align: center;
  align-items: center;
}

.pvote1 {
  display: flex;

  padding: 5%;
  justify-content: center;
  text-align: center;
  align-items: center;
}

.p-rating {
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 2%;
}

.pvote {
  color: gray;
  font-size: 10px;
  display:inline-flex !important;
}

.rating2 {
  border: 1px solid rgb(223, 223, 223) !important;

  margin: 2%;
}

.rating2:focus {
  box-shadow: none !important;
}

.rating2:hover {
  background-color: rgb(243, 243, 243);
}
.comments {
  display: flex;
  border-top: 1px solid rgb(223, 223, 223) !important;
}
.comment {
  margin: 25px;
  display: block !important;
}

.com-0 {
  display: flex;
  margin-left: 15px !important;
  border: none !important;
  padding: 0 !important;
}

.com-title {
  display: flex;
  padding-left: 15px;
  padding-right: 15px;
  color: rgb(32, 32, 32);
  font-size: medium;
  font-weight: bold;
  margin: 5px;
}

.com-1 {
  display: flex;
  padding-left: 15px;
  padding-right: 15px;
  color: gray;
  font-size: smaller;
}

.comav {
  display: grid;
  justify-content: center;
  padding: 15px;
}

.commentavatar {
display: flex;
  border-radius: 50%;
  background-color: #575757;
  text-align: center;
  color: white;
  font-size: 20px;
width: 60px;
height: 60px;
justify-content: center;
align-items: center;
}

.commentname {
  font-size: 14px;
  
  margin: 10px !important;
  color: gray;
}

@media only screen and (max-width: 760px) {
  .productimage {
    display: none;
  }
  .productimage2 {
    display: flex;
  }


  .pcommentfirstdiv {
    display: block !important;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .productimagecomment {
    width: 200px;
    height: 240px;
  }
}

@media only screen and (max-width: 560px) {
  .productbuys {
    margin: 1% !important;
    font-size: 14px !important;
  }

  .pbs {
    font-size: 10px !important;
  }
}
</style>