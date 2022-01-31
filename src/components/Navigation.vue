<script setup lang="ts">
import { isDark, toggleDark } from '~/composables'
const { t } = useI18n()

</script>

<template>
  <nav class="text-xl mt-6">
    <router-link class="icon-btn mx-2" to="/" :title="t('button.home')">
      <carbon-home />
    </router-link>
    <router-link class="icon-btn mx-2" to="/team" :title="t('button.home')">
      <carbon-person />
    </router-link>
    <router-link class="icon-btn mx-2" to="/team" :title="t('button.home')">
      <carbon-shopping-cart />
    </router-link>

    <button class="icon-btn mx-2 !outline-none" :title="t('button.toggle_dark')" @click="toggleDark()">
      <carbon-moon v-if="isDark" />
      <carbon-sun v-else />
    </button>

    <a class="icon-btn mx-2" :title="t('button.toggle_langs')">
      <carbon-language />
    </a>
  </nav>
</template>
