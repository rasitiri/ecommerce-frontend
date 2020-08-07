<template>
  <div>
<div class="cartempty mx-auto">
 
  <i class="fa fa-shopping-cart fa-10x" aria-hidden="true"></i>
 
<div class="cartemptyw">
Sepetinizde Ürün Bulunmuyor.</div>
  </div>
    <i class="far fa-frown cesad"></i>
 <span class="badge badge-danger cebadge">0</span>


      <div class="rectitle text-center">Öne Çıkan Ürünler</div>

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




   </div>
</template>

<script>
export default {

}
</script>

<style>
.cartempty 
{display: block;
justify-content: center;
align-items: center;
text-align: center;
background-color:rgb(223, 223, 223); 
  border: 2px solid rgb(223, 223, 223) !important;
padding: 25px;
margin: 25px;
border-radius: 10px;
max-width: 800px;
}

.cartemptyw {

margin: 10px;
color:#DC3545;
font-weight: bold;
}

.cesad {
    z-index: 5;
    position: relative;
    color:white;
    font-size: 50px;
 
   left: 49.5%;
   bottom:220px   }

   .cebadge {
    z-index: 5;
    position: relative;
    color:red;
    font-size: 20px !important;
background-color:white; 
   left: 51%;
   bottom:260px  ;
   padding:10px !important;
   width: 40px !important;
   height:40px !important;
   border-radius: 50% !important;
    }


    @media only screen and (max-width: 315px) {
.cesad {
    bottom:245px;
}

.cebadge { bottom: 285px;}
    }
</style>