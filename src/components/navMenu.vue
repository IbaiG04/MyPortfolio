<template>
<header class="flex items-center justify-center">
    <nav class="text-white p-10 ">
     
      <router-link to="/" :class="{ 'active-link': $route.path === '/' }" class="text-white mx-2 p-3 rounded-md bg-purple-400 bg-opacity-35">Home</router-link>
    <router-link to="/about" :class="{ 'active-link': $route.path === '/about' }" class="text-white mx-2 p-3 rounded-md bg-purple-400 bg-opacity-35">About</router-link>
    <router-link to="/projects" :class="{ 'active-link': $route.path === '/projects' }" class="text-white mx-2 p-3 rounded-md bg-purple-400 bg-opacity-35">Projects</router-link>
    <!-- <router-link to="/contact" :class="{ 'active-link': $route.path === '/contact' }" class="text-white mx-2 p-3 rounded-md bg-purple-400 bg-opacity-35">Contact</router-link> -->
    </nav>
  </header>
</template>