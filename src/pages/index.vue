<script setup lang="ts">
import imgUrl from '/assets/runelords.svg'
import sfv from '/assets/games/sfv.jpeg'
import gg from '/assets/games/gg.jpeg'
import mk11 from '/assets/games/mk11.jpeg'
import tekken from '/assets/games/tekken.jpeg'

</script>

<template>
  <div class="flex place-content-center">
    <img id="logo" :src="imgUrl" class="image" alt="team-logo">
  </div>
  <div class="flex flex-col place-content-center who-text prose-xl mt-10">
    <h2>¿Quiénes somos?</h2>
    <p>Somos Runelords, un equipo amateur dedicado 100% al ambito de los Juegos de Lucha.</p>
    <p>¿A que juegas competimos?</p>
  </div>

  <div class="flex flex-wrap items-center mt-10">
    <div class="box mt-5">
      <div class="text-center space-y-2">
        <img class="game" :src="sfv" alt="street-fighter">
      </div>
    </div>
    <div class="box mt-5">
      <div class="text-center space-y-2">
        <img class="game" :src="gg" alt="guilty-gear">
      </div>
    </div>
    <div class="box mt-5">
      <div class="text-center space-y-2">
        <img class="game" :src="mk11" alt="mortal-kombat">
      </div>
    </div>
    <div class="box mt-5">
      <div class="text-center space-y-2">
        <img class="game" :src="tekken" alt="mortal-kombat">
      </div>
    </div>
  </div>
</template>

<style scoped>
  .image {
    width: 35%;
  }

  .game {
    width: 200px;
    height: 300px;
    object-fit: scale-down;
  }

</style>
