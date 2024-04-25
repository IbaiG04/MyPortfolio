<template>
  
  <div class="relative overflow-hidden bg-black">
    <img class="fixed inset-0 z-0 object-cover w-full h-full pointer-events-none" src="/img/fondo.png" alt="">
    <div class="relative z-10">
      <navMenu/> 
      <body>
        
        
        <RouterView class="relative z-10"/>
       
      </body>
    </div>
  </div>
</template>

<script>
import { RouterView } from 'vue-router'
import navMenu from './components/navMenu.vue'

export default {
 name: 'App',
 components: {
  RouterView,
  navMenu,
 }
}
</script>
