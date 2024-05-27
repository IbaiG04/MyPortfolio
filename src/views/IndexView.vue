<template>
  <div class="text-white  flex-col">
    <div class=" flex-row  text-center pt-32 pb-32">
      <div class="wavy text-5xl font-bold bg-clip-text bg-gradient-to-r from-fuchsia-500 via-fuchsia-700 to-violet-700">
        <span style="--i:1" class="text-transparent">I</span>
        <span style="--i:2" class="text-transparent">B</span>
        <span style="--i:3" class="text-transparent">A</span>
        <span style="--i:4" class="text-transparent">I</span>
        <span style="--i:5" class="text-transparent">G</span>
        <span style="--i:6" class="text-transparent">Z</span>
      </div>
      <h1 class="pt-4 pb-4  text-3xl">
        <span class=" font-semibold">PORTFOLIO</span>
      </h1>
      <span class="text-purple-500 text font-semibold">Frontend Developer</span>
    </div>
    </div>
  <cardInfoVue />
</template>

<style>
.wavy {
  position: relative;
  -webkit-box-reflect: below -12px linear-gradient(transparent, rgba(0, 0, 0, 0.2));
}

.wavy span {
  position: relative;
  display: inline-block;
  color: #fff;
  font-size: 2em;
  text-transform: uppercase;
  animation: animate 2s ease-in-out infinite;
  animation-delay: calc(0.1s * var(--i))
}

@keyframes animate {
  0% {
    transform: translateY(0px);
    
  }

  20% {
    transform: translateY(-30px);
    color: rgb(168 85 247 / var(--tw-text-opacity));
  }

  40%,
  100% {
    transform: translateY(0px);
  }
}



@media (max-width: 320px) {
  .wavy span {
    font-size: 110%;
  }
}

@media (max-width: 224px) {
  .wavy span {
    font-size: 80%;
  }
}

@media (max-width: 205px) {
  .wavy span {
    font-size: 70%;
  }
}

@media (max-width: 185px) {
  .wavy span {
    font-size: 50%;
  }
}
</style>

<script>
import cardInfoVue from '../components/cardInfo.vue'

export default {
  name: 'App',
  components: {
    cardInfoVue,

  },
  mounted() {
    document.title = 'Portafolio';
  }
}


</script>