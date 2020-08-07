<template>
  <div>
    <carousel></carousel>
    <div class="bok">sdfsadf</div>
  </div>
</template>

<script>
import Carousel from '../components/Carousel'

export default {
  components: {
    Carousel,
  },
}
</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&display=swap');
.bok {
  margin-top: 2000px;
}
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
  padding-left: 500px;
}
</style>
