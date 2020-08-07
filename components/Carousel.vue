<template>
  <div class="cr">
    <b-carousel
      id="carousel-fade"
      v-model="slide"
      :interval="2000"
      fade
      controls
      background="white"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
      class="b-carousel mx-auto items-center"
    >
      <b-carousel-slide
        img-src="https://images.pexels.com/photos/35537/child-children-girl-happy.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://images.pexels.com/photos/428340/pexels-photo-428340.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://images.pexels.com/photos/235469/pexels-photo-235469.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    }
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true
    },
    onSlideEnd(slide) {
      this.sliding = false
    },
  },
}
</script>
