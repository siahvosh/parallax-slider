<template>
    <div class="main">
      <div class="card-1">
        <v-img class="sld1-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld1-bg.jpeg" alt=""></v-img>
        <v-img class="sld2-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld3-bg.webp" alt=""></v-img>
        <v-img class="sld2-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld4-bg.webp" alt=""></v-img>
        <v-img class="sld1-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld2-bg.webp" alt=""></v-img>
      </div>
<!--      <div class="card-2">-->
<!--        <v-img class="car-cloud" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/carcloud.webp" alt=""></v-img>-->
<!--        <v-img class="land" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/land.webp" alt=""></v-img>-->

<!--      </div>-->
    </div>

</template>

<script setup>
  //
</script>


<style>

.main{
  width: 100%;
  background: black !important;
  position: relative;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  flex-direction: column;
  overflow: hidden;


}

.card-1 {
  position: relative !important;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column ;
  justify-content: initial;


}

.sld1-bg, .sld2-bg{
  object-fit: fill;
  width: 100%;
  display: flex;
  justify-self: center;
  /*border: 2px solid red;*/

}
.car-cloud{
  position: absolute !important;
  width: 30%;
  height: 30%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);


}

.land{
  position: absolute !important;
  width: 100%;
  bottom: 0;
}
</style>
