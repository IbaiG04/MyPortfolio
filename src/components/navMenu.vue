<template>
  <header class="flex">
    <nav class="text-white p-10 flex justify-between items-center w-full">
        <div>
            <router-link to="/" :class="{ 'active-link': $route.path === '/' }"
                class="text-white mx-2 p-3 rounded-full  bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35">Home</router-link>
            <router-link to="/about" :class="{ 'active-link': $route.path === '/about' }"
                class="text-white mx-2 p-3 rounded-full bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35">About</router-link>
            <router-link to="/projects" :class="{ 'active-link': $route.path === '/projects' }"
                class="text-white mx-2 p-3 rounded-full bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35">Projects</router-link>
        </div>
        <div class="flex items-center">
            <a href="https://github.com/Ibaigz" target="_blank"
                class="text-white mx-2 p-3 rounded-full bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35"><img class="w-8" src="/img/github.png" alt="Github">
            </a>
            <a href="https://www.linkedin.com/in/ibai-gonzalez-7b1b3b1b9/" target="_blank"
                class="text-white mx-2 p-3 rounded-full bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35"><img class="w-8" src="/img/linkedin.png"
                    alt="Linkedin">
            </a>

            <a href="https://discord.com/users/842762466428452925" target="_blank"
                class="text-white mx-2 p-3 rounded-full bg-transparent bg-opacity-35 hover:bg-purple-400 hover:bg-opacity-35"><img class="w-8"
                    src="/img/discord.png" alt="Discord"></a>
        </div>
    </nav>
</header>

</template>