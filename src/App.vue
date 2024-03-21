<template>
  
  <div class="relative overflow-hidden">
    <img class="fixed inset-0 z-0 object-cover w-full h-full pointer-events-none" src="/img/fondo.png" alt="">
    <div class="relative z-10">
      <header class="flex items-center justify-center">
        <nav class="text-white">
         
          <router-link to="/" class="text-white">Home</router-link>
          <router-link to="/about" class="text-white">About</router-link>
          <router-link to="/projects" class="text-white">Projects</router-link>
          <router-link to="/contact" class="text-white">Contact</router-link>
        </nav>
      </header>
      <body>
        
        
        
        <RouterView class="relative z-10"/>
        <cardInfoVue/> 
      </body>
    </div>
  </div>
</template>

<script>
import { RouterView } from 'vue-router'
import cardInfoVue from './components/cardInfo.vue'

export default {
 name: 'App',
 components: {
  RouterView,
  cardInfoVue,
 }
}
</script>
