<template>
  <div>
    <div class="bottombars">
      <span>
        <i class="fas fa-fire-alt"></i> Yeniler
      </span>
      <span>
        <i class="fas fa-male"></i> Erkek
      </span>
      <span>
        <i class="fas fa-female"></i> Kadın
      </span>
      <span>
        <i class="fas fa-child"></i> Çocuk
      </span>

      <span>
        <i class="far fa-gem"></i> Aksesuar
      </span>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.bottombars {
  bottom: 0;
  display: none;
  background-color: white;
  position: -webkit-sticky;
  position: sticky;
}
@media only screen and (max-width: 760px) {
  .bottombars {
    border-top: rgb(212, 212, 212) 1px solid;
    height: 75px;
    display: flex;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    justify-content: center;
    color: white;
    text-align: center;
    color: black;
    z-index: 999;
    cursor: pointer;
    display: flex;
    padding-top: 25px;
  }

  .bottombars span {
    display: block;
    margin-left: 1.5%;
    margin-right: 1.5%;
  }

  .bottombars span:focus {
    color: rgb(255, 68, 68);
  }
}

.bottombars span:active {
  color: rgb(255, 68, 68);
}

.bottombars span:hover {
  color: rgb(255, 68, 68);
}

.bottombars span:focus {
  color: rgb(255, 68, 68);
}
</style>
