<script setup>
import { RouterLink, RouterView } from "vue-router";
import Nav from "./components/shared/nav.vue";
</script>

<template>
  <header>
    <Nav />
    <div class="h-96 w-full bg-gray-200"></div>
  </header>
  <RouterView />
</template>
