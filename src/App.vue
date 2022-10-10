<script setup>
import { RouterLink, RouterView } from "vue-router";
import Nav from "./components/shared/nav.vue";
</script>

<template>
  <header>
    <Nav />
    <!-- <div class="h-96 w-full bg-gray-200 pt-16">
      <div class="flex justify-center">
        <form action="">
          <div class="flex">
            <input
              class="h-8 w-96 rounded-tl-md rounded-bl-md border-2 border-sky-500/70 bg-gray-100 p-5"
              type="text"
              name="search"
              id="search"
              placeholder="Que estas buscando?"
            />
            <button
              class="rounded-tr-md rounded-br-md bg-sky-500/70 px-5 tracking-widest text-white"
            >
              Buscar
            </button>
          </div>
        </form>
      </div>
    </div> -->
  </header>
  <RouterView />
</template>
