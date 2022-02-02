<script setup lang="ts">
import sfv from '/assets/games/sfv.jpeg'
import gg from '/assets/games/gg.jpeg'
import mk11 from '/assets/games/mk11.jpeg'
import tekken from '/assets/games/tekken.jpeg'

</script>

<template>
  <div class="flex flex-wrap justify-center mt-10">
    <div class="card w-60 h-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="sfv" alt="street-fighter">
      </figure>
    </div>
    <div class="card w-60 h-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="gg" alt="street-fighter">
      </figure>
    </div>
    <div class="card w-60 h-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="mk11" alt="street-fighter">
      </figure>
    </div>
    <div class="card w-60 h-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="tekken" alt="street-fighter">
      </figure>
    </div>
  </div>
</template>
