<template>
    <div class="main">
      <div class="card-1">
      <v-img class="sld1-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld1-bg.jpeg" alt=""></v-img>
      <v-img class="car-cloud" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/carcloud.webp" alt=""></v-img>
      </div>
    </div>

</template>

<script setup>
  //
</script>


<style>

.main{
  width: 100%;
  height: 100%;
  background: black !important;
  position: relative;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  flex-direction: column;
}

.card-1{
  position: relative;
  width: 100%;
  height: 100%;
}

.sld1-bg{
  object-fit: fill;
  position: absolute !important;

  width: 100%;
  height: 100%;
}
.car-cloud{
  position: absolute !important;
  width: 30%;
  height: 30%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

}
</style>
