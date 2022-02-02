<script setup lang="ts">
import bc from '/assets/sponsors/bc.png'
import pirru from '/assets/sponsors/pirru.jpg'
import satsui from '/assets/sponsors/satsui.png'

</script>

<template>
  <div class="flex flex-wrap justify-center mt-10 ">
    <div class="card w-72 h-100 card-bordered card-compact lg:card-normal mr-5 mt-5">
      <figure>
        <img class="game" :src="bc" alt="street-fighter">
      </figure>
    </div>
    <div class="card w-72 h-100 card-bordered card-compact lg:card-normal mr-5 mt-5">
      <figure>
        <img class="game" :src="pirru" alt="street-fighter">
      </figure>
    </div>
    <div class="card w-72 h-100 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="satsui" alt="street-fighter">
      </figure>
    </div>
  </div>
</template>
