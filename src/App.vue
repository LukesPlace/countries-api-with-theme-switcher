<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HeaderComp from './components/Header.vue';
</script>

<template>
  <header-comp></header-comp>
  <RouterView />
</template>

<style>

html {
  background-color: hsl(207, 26%, 17%);
}
</style>
