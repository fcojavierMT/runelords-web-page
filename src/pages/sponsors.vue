<script setup lang="ts">
import bc from '/assets/sponsors/bc.png'
import pirru from '/assets/sponsors/pirru.jpg'
import satsui from '/assets/sponsors/satsui.png'

</script>

<template>
  <div class="flex flex-wrap justify-center mt-10">
    <div class="card w-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="satsui" alt="street-fighter">
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white">
          ¡Nuestro primer sponsor oficial!
        </h2>
        <p class="text-white mt-5">
          We r custom builders! ❤️ 🔥 🕹️
        </p>
        <p class="text-white mt-5">
          Fabricantes artesanales de arcades de todo tipo. Hitbox, sticks... with love!
        </p>
        <p class="text-white">
          <a class="link" href="https://twitter.com/satsuisticks" target="_blank">
            @satsuisticks
            <carbon-logo-twitter />
          </a>
        </p>
      </div>
    </div>
    <div class="card w-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="pirru" alt="street-fighter">
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white">
          La pirruteca!
        </h2>
        <p class="text-white mt-5">
          🎬 Cine / series
        </p>
        <p class="text-white mt-5">
          📦 Unboxings
        </p>
        <p class="text-white mt-5">
          Pilotados por:
        </p>
        <p class="text-white">
          <a class="link" href="https://twitter.com/pirrulove" target="_blank">
            @pirrulove
            <carbon-logo-twitter />
          </a>
        </p>
        <p class="text-white">
          <a class="link" href="https://twitter.com/fridamadridfrik" target="_blank">
            @fridamadridfrik
            <carbon-logo-twitter />
          </a>
        </p>
      </div>
    </div>
    <div class="card w-80 card-bordered card-compact lg:card-normal mt-5">
      <figure>
        <img class="game" :src="bc" alt="street-fighter">
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white">
          ¡BC WEARS!
        </h2>
        <p class="text-white mt-5">
          🌎  Envíos Internacionales
        </p>
        <p class="text-white mt-5">
          🎨 Diseño de equipaciones
        </p>
        <p class="text-white mt-5">
          👕 Ropa Deportiva y merchandising
        </p>
        <p class="text-white">
          <a class="link" href="https://twitter.com/BcWears" target="_blank">
            @BcWears
            <carbon-logo-twitter />
          </a>
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  margin: 1rem;
}
</style>
