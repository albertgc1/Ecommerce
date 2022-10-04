<template>
  <nav class="flex h-16 w-full flex-row justify-between bg-sky-500/100">
    <div class="flex items-center pl-5 text-zinc-300">Logo</div>
    <div class="flex items-center text-zinc-300">
      <RouterLink class="mr-3 tracking-widest hover:text-gray-100" to="/"
        >Home</RouterLink
      >
      <RouterLink class="mr-3 tracking-widest hover:text-gray-100" to="/about"
        >About</RouterLink
      >
      <RouterLink class="mr-3 tracking-widest hover:text-gray-100" to="/about"
        >Explore</RouterLink
      >
      <RouterLink class="mr-3 tracking-widest hover:text-gray-100" to="/about"
        >Contact</RouterLink
      >
    </div>
    <div class="flex items-center pr-5 text-zinc-300">User Name</div>
  </nav>
</template>
