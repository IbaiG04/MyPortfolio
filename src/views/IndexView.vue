<template>
  <div class="text-white flex items-center justify-center h-screen flex-col">
    <div class=" flex-row text-center mt-80 mb-72">
      <h1
        class="bg-clip-text text-transparent bg-gradient-to-r from-fuchsia-500 via-fuchsia-700 to-violet-700 font-bold text-6xl">
        <span class="text-white font-semibold">Welcome to </span>Ibai Gonzalez<span class="text-white font-semibold">
          portfolio</span>
      </h1>
      <span class="text-purple-500 text font-semibold">Full-Stack Web Developer</span>
      


    </div>
    <div id="zio" class=" mb-20 flex items-center justify-center flex-col animate-bouncing">
      <img class="w-16 mx-auto block" src="../../public/img/down-arrow.png" alt="">
    
  </div>
  </div>
  
  

  <!-- <div class="w-1/2 flex items-center justify-center">
          <img class="w-1/2 h-1/2" src="../../public/img/main-img.svg" alt="">
        </div> -->



</template>

<script>
export default {
  mounted() {
    document.title = 'Portafolio';
  }
}
</script>