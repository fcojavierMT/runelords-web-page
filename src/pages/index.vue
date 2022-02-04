<script setup lang="ts">
import { ref } from 'vue'

import sfv from '/assets/games/sfv.jpeg'
import gg from '/assets/games/gg.jpeg'
import mk11 from '/assets/games/mk11.jpeg'
import tekken from '/assets/games/tekken.jpeg'

const games = ref([
  {
    alt: 'street-figter',
    img: sfv,
  },
  {
    alt: 'guilty-gear',
    img: gg,
  },
  {
    alt: 'mortal-kombat',
    img: mk11,
  },
  {
    alt: 'tekken',
    img: tekken,
  }],
)

</script>

<template>
  <div class="flex flex-wrap justify-center mt-10">
    <div v-for="(game, index) in games" :key="index" class="card w-60 h-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="game.img" :alt="game.alt">
      </figure>
    </div>
  </div>
</template>

<style scoped>
.card {
  margin: 1rem;
}
</style>
