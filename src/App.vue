<template>
  
  <div class="relative overflow-hidden">
    <img class="fixed inset-0 z-0 object-cover w-full h-full pointer-events-none" src="/img/fondo.png" alt="">
    <div class="relative z-10">
      <header class="flex items-center justify-center">
        <nav class="text-white">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/info">CardInfo</RouterLink>

        </nav>
      </header>
      <body>
        
        <RouterView class="relative z-10"/>
      </body>
    </div>
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>
