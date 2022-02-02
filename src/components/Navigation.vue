<script setup lang="ts">
import imgUrl from '/assets/sponsors/rune.png'
const { t } = useI18n()

</script>

<template>
  <div class="navbar mb-2 shadow-lg bg-neutral text-neutral-content rounded-box">
    <div class="flex-none px-2 mx-2">
      <img id="logo" :src="imgUrl" class="image" alt="team-logo">
    </div>
    <div class="flex-1 px-2 mx-2">
      <div class="items-stretch hidden lg:flex">
        <router-link class="btn btn-sm rounded-btn mr-4" to="/" :title="t('button.home')">
          <carbon-home class="mr-2" /> Inicio
        </router-link>
        <router-link class="btn btn-sm rounded-btn mr-4" to="/team" :title="t('button.home')">
          <carbon-events class="mr-2" /> Team
        </router-link>
        <router-link class="btn btn-sm rounded-btn mr-4" to="/shop" :title="t('button.home')">
          <carbon-shopping-cart class="mr-2" /> Tienda
        </router-link>
        <router-link class="btn btn-sm rounded-btn mr-4" to="/sponsors" :title="t('button.home')">
          <carbon-badge class="mr-2" /> Sponsors
        </router-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.navigation {
  overflow: hidden;
  position: fixed;
  top: 0;
  width: 95%;
}
.image {
  width: 3.125rem;
}
</style>
