<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'
const { t } = useI18n()

</script>

<template>
  <nav class="flex items-center justify-between text-xl mt-6">
    <div class="flex flex-row links">
      <router-link class="flex icon-btn mx-2 items-center" to="/" :title="t('button.home')">
        <carbon-home class="mr-2" /> Inicio
      </router-link>
      <router-link class="flex icon-btn mx-2" to="/team" :title="t('button.home')">
        <carbon-events class="mr-2" /> Team
      </router-link>
      <router-link class="flex icon-btn mx-2" to="/team" :title="t('button.home')">
        <carbon-shopping-cart class="mr-2" /> Tienda
      </router-link>
    </div>

    <div class="">
      <button class="icon-btn mx-2 !outline-none" :title="t('button.toggle_dark')" @click="toggleDark()">
        <carbon-moon v-if="isDark" />
        <carbon-sun v-else />
      </button>

      <a class="icon-btn mx-2" :title="t('button.toggle_langs')">
        <carbon-language />
      </a>
    </div>
  </nav>
</template>
