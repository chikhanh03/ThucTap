<template>
    <div>
      <header class="shadow-sm bg-gradient-to-r from-violet-500 to-fuchsia-500">
        <nav class="container mx-auto p-5 flex justify-between">
          <NuxtLink to="/" class="font-bold">Trang chủ</NuxtLink>
          <ul class="flex gap-4">
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products" class="btn">Products</NuxtLink></li>
          </ul>
        </nav>
      </header>

      <div class="container mx-auto p-4">
        <slot />
      </div>

     
    </div>
  </template>

<style scoped>
    .router-link-exact-active{
        color: aqua;
    }
</style>