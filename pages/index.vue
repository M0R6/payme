<template>
  <v-app class="h-screen pa-5 background-photo align-center">
    <div class="mx-auto my-auto justify-center align-center">
      <img class="responsive-img" src="/assets/MorganQRIS.svg">
      <h1 class="text-center barriecito-regular text-4xl mt-5">
        Morgan's QRIS
      </h1>
    </div>
   </v-app>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Barriecito&display=swap');

.barriecito-regular {
  font-family: "Barriecito", system-ui;
  font-weight: 400;
  font-style: normal;
}
</style>

<style scoped>

.responsive-img {
  max-width: 100%;
  height: auto;
}

.background-photo {
  background-image: url('/assets/unsplashBG.jpg') !important;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>

