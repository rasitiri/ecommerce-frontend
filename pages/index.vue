<template>
  <div>
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
        <!-- Text slides with image -->
        <b-carousel-slide img-src="https://images.pexels.com/photos/35537/child-children-girl-happy.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"></b-carousel-slide>

        <!-- Slides with custom text -->
        <b-carousel-slide img-src="https://images.pexels.com/photos/428340/pexels-photo-428340.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260"></b-carousel-slide>

        <!-- Slides with image only -->
        <b-carousel-slide img-src="https://images.pexels.com/photos/235469/pexels-photo-235469.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"></b-carousel-slide>

        <!-- Slides with img slot -->
        <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
        <b-carousel-slide>
          <template v-slot:img>
            <img
              class="d-block img-fluid w-100"
              src="https://images.pexels.com/photos/3722151/pexels-photo-3722151.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
              alt="image slot"
            />
          </template>
        </b-carousel-slide>

        <!-- Slide with blank fluid image to maintain slide aspect ratio -->
      </b-carousel>
    </div>

    <!-- <div class="cmp">
      <span class="campaignestitle mt-4 mx-auto">Kampanyalar</span>
      <div class="marqq mx-auto mb-4">
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
        <nuxt-link to="#" class="img1 campaignes"></nuxt-link>
      </div>
    </div> -->

<div class="bok">sdfsadf</div>
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

<style >
@import url('https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&display=swap');
.bok {margin-top: 2000px;}
.carousel-control-prev-icon,
.carousel-control-next-icon {
  border-radius: 50%;

  height: 40px !important;
  width: 40px !important;
  transition: 1s;
}

.cr {
  z-index: 0;
}
.carousel-item {
  display: flex;

  justify-content: center;


margin: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;
 
}

.img-fluid {
  justify-content: center;
  margin: auto; 
    height: 400px !important;
}

.campaignestitle {
  display: block;
  font-weight: bold;
  font-variant: small-caps;
  font-style: italic;
  font-size: 75px;
  cursor: pointer;
  font-family: 'Amatic SC', cursive;
  text-shadow: 2px 2px rgb(255, 68, 68);
  width: 85%;
  height: 100px;
  justify-content: center;
  text-align: center;
  -webkit-box-shadow: 0px -10px 22px 8px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: 0px -10px 22px 8px rgba(0, 0, 0, 0.1);
  box-shadow: 0px -10px 22px 8px rgba(0, 0, 0, 0.1);
  border-radius: 10px 10px 0px 0px;
  -moz-border-radius: 10px 10px 0px 0px;
  -webkit-border-radius: 10px 10px 0px 0px;
  border: 0px solid #000000;
  z-index: 0;
}


.marqq {
  z-index: 10;
  display: flex;
  width: 95%;
  border-radius: 25px;
  -webkit-box-shadow: 0px 0px 35px 6px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: 0px 0px 35px 6px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 0px 35px 6px rgba(0, 0, 0, 0.1);
  overflow: auto;
  height: 400px;
  justify-content: center;
  align-items: center;
  padding-left:500px;


}


</style>