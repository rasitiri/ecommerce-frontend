<template>
  <div>
    <div class="cartempty mx-auto">
      <i class="fa fa-shopping-cart fa-10x" aria-hidden="true"></i>

      <div class="cartemptyw">Sepetinizde Ürün Bulunmuyor.</div>
    </div>
    <i class="far fa-frown cesad"></i>
    <span class="badge badge-danger cebadge">0</span>

    <featured-products></featured-products>
  </div>
</template>

<script>
import FeaturedProducts from '../components/FeaturedProducts/FeaturedProducts'

export default {
  components: {
    FeaturedProducts,
  },
}
</script>

<style>
.cartempty {
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: rgb(223, 223, 223);
  border: 2px solid rgb(223, 223, 223) !important;
  padding: 25px;
  margin: 25px;
  border-radius: 10px;
  max-width: 800px;
}

.cartemptyw {
  margin: 10px;
  color: #dc3545;
  font-weight: bold;
}

.cesad {
  z-index: 5;
  position: relative;
  color: white;
  font-size: 50px;

  left: 49.5%;
  bottom: 220px;
}

.cebadge {
  z-index: 5;
  position: relative;
  color: red;
  font-size: 20px !important;
  background-color: white;
  left: 51%;
  bottom: 260px;
  padding: 10px !important;
  width: 40px !important;
  height: 40px !important;
  border-radius: 50% !important;
}

@media only screen and (max-width: 315px) {
  .cesad {
    bottom: 245px;
  }

  .cebadge {
    bottom: 285px;
  }
}
</style>
