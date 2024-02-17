<template>
    <div class="main">
      <div class="card-1">
        <v-img class="sld1-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld1-bg.jpeg" alt=""></v-img>
        <v-img class="sld2-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld3-bg.webp" alt=""></v-img>
        <v-img class="sld2-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld4-bg.webp" alt=""></v-img>
        <v-img class="sld2-bg" src="file:///C:/Users/PC/Desktop/vue%20project/parallax-slider/vuetify-project/src/assets/sld2-bg.webp" alt=""></v-img>
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
  background: black !important;
  width: 100%;


  /*overflow: hidden;*/

}
.main:hover .sld2-bg{
  transform: translate(0, 0);
  animation: fade;
  /*opacity: 1;*/
}

@keyframes fade {
  0%{
    opacity: 0;
  }
  20%{
    opacity: 0;
  }
  60%{
    opacity: 1;
  }
  100% {
    opacity: 1;
  }

}
.main:hover .sld1-bg{
  transform: translate(0, -100%);
  opacity: .3;


}

.card-1 {
  position: relative !important;
  width: 100%;
  height: 100%;
  display: flex;

  flex-direction: column;
  /*overflow: hidden;*/



}

.sld1-bg{
  object-fit: fill;
  width: 100%;
  margin-top: 80px;
  transform: translate(0, 0);
  transition: all 1.5s ease .1s;
  opacity: 1;
  z-index: 0 !important;

  /*border: 2px solid red;*/

}
.sld2-bg{
  opacity: 0;
  object-fit: fill;
  width: 100%;
  position: absolute !important;
  transform: translate(0, 100%);
  transition: all 1.5s ease;

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
