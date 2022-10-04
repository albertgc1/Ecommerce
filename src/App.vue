<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>

    <div>
      <h2 class="text-indigo-400">Hello world!</h2>

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
