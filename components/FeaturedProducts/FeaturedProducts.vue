<template>
  <div>
    <div class="rectitle text-center">Öne Çıkan Ürünler</div>

    <div class="recdeck card-deck">
      <product v-for="p in 4" :key="p"></product>
    </div>
  </div>
</template>

<script>
import Product from './Product'

export default {
  components: {
    Product,
  },
}
</script>
