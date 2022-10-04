<script setup>
import { RouterLink, RouterView } from "vue-router";
import Nav from "./components/shared/nav.vue";
</script>

<template>
  <header>
    <Nav />
  </header>
  <RouterView />
</template>
