<template>
  <div id="app" class="bg-white flex flex-col h-screen justify-between">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- Two columns -->
    <div class="flex md:flex-row-reverse flex-wrap bg-blue-100">
      <div class="w-full md:w-3/4 p-4 text-center">
          <div class="w-full text-left">
            <p class="text-4xl">Carlo F. Gammarota</p>
            <p class="text-2xl">Full Stack Developer</p>
            <p class="text-xl">Front & Back</p>
          </div>
      </div>
      <div class="w-full md:w-1/4 p-4 text-center text-gray-700">
        <div class=" flex items-center justify-center">
          <img src="./assets/cg.png" class="w-32 border-4 border-white rounded-full " alt="">
        </div>
      </div>
    </div>
  <!-- <div class="flex mb-4 mx-10 mt-8">
    <div class="w-1/2">

      <div class="flex mb-4">

      <div class="flex mb-4">
        <div class="">
          <div class=" flex items-center justify-center mr-6">
          <img src="./assets/cg.png" class="h-48 rounded-full " alt="">
        </div>
        </div>
        <div class="w-1/2">
          <div class="w-full text-left">
            <p class="text-4xl">Carlo F. Gammarota</p>
            <p class="text-2xl">Full Stack Developer</p>
            <p class="text-xl">Front & Back</p>
          </div>
        </div>
      </div>
      </div>
    </div>
    <div class="w-2/2"></div>
    
  </div> -->
    <!-- Four columns -->
  <div class="flex-wrap flex mb-4 bg-blue-100 py-4">
    <div class="w-full md:w-1/4 sm:md:w-1/4 xl:w-1/4 text-sm font-bold items-center rounded-md border-black hover:bg-white">
      <img class="h-6 w-6 m-auto my-2" src="./assets/img/email.png" alt="">
      carlo.gammarota@gmail.com
    </div>
    <div class="w-full md:w-1/4 sm:md:w-1/4 xl:w-1/4 text-sm font-bold rounded-md border-black hover:bg-white">
      <img class="h-6 w-6 m-auto my-2" src="./assets/img/smartphone.png" alt="">
      3548 630543
    </div>
    <div class="w-full md:w-1/4 sm:md:w-1/4 xl:w-1/4 text-sm font-bold rounded-md border-black hover:bg-white">
      <img class="h-6 w-6 m-auto my-2" src="./assets/img/location.png" alt="">
      Villa Giardino, Córdoba
    </div>
    <a href="http://github.com/carlogammarota" class="w-full md:w-1/4 sm:md:w-1/4 xl:w-1/4 text-sm font-bold rounded-md border-black hover:bg-white cursor-pointer">
      <!-- <div class="w-full md:w-1/4 sm:md:w-1/4 xl:w-1/4 text-sm font-bold rounded-md border-black hover:bg-white cursor-pointer"> -->
      <div>
      <img class="h-6 w-6 m-auto my-2" src="./assets/img/github.png" alt="">
      github.com/carlogammarota
      </div>
    </a>
  </div>

  <!-- Two columns -->
  <div class="flex flex-wrap mb-4 mx-10 bg-blue-200 p-4 rounded-md">
    <div class="w-full sm:w-full md:w-1/2 text-left">
      <p class="text-xl font-bold uppercase mb-2">Online Works</p>
      <ul>
        <li>
          <a class="bg-green-100 hover:bg-green-200 rounded-md p-2" href="https://distracted-jepsen-8f606f.netlify.app/">https://distracted-jepsen-8f606f.netlify.app/ (AGIP BA)</a>
        </li>
        <li class="mt-4">
          <a class="bg-green-100 hover:bg-green-200 rounded-md p-2" href="https://lucid-colden-c5feed.netlify.app/">https://lucid-colden-c5feed.netlify.app/</a>
          <br>
          <p class="p-2"><span class="font-bold">user:</span> jorge2020@gmail.com <span class="font-bold">pw:</span> oNYRB</p>
        </li>
      </ul>

      <p class="text-xl font-bold uppercase my-2">Personal Works</p>
      <ul>
        <li>
          <a class="bg-green-100 hover:bg-green-200 rounded-md p-2" href="https://eloquent-cori-523797.netlify.app/">https://eloquent-cori-523797.netlify.app/ (Music Samples Maqueta)</a>
        </li>
        <li class="mt-4 mb-4">
          <a class="bg-green-100 hover:bg-green-200 rounded-md p-2  " href="https://lucid-ride-7a3acd.netlify.app/">https://lucid-ride-7a3acd.netlify.app/ (Esporahi Project)</a>
        </li>
        <li class="mt-4 mb-4">
          <a class="bg-green-100 hover:bg-green-200 rounded-md p-2  " href="https://jolly-payne-2c56a5.netlify.app/">https://jolly-payne-2c56a5.netlify.app/ (Maquetación)</a>
        </li>
      </ul>
    </div>
    <div class="w-full sm:w-full md:w-1/2 text-left mb-auto">
      <p class="text-xl font-bold uppercase">Skills Front-end</p>
      <div class="my-2 mb-4 flex flex-wrap">
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Vuex</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Vue.js</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Nuxt.js</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Axios</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">TailwindCss</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Vuetify</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Bulma</span>
        <span class="p-1 bg-pink-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Bootstrap</span>
      </div>
      <p class="text-xl font-bold uppercase ">Skills Back-end</p>
      <div class="my-2 mb-4 flex flex-wrap">
        <span class="p-1 bg-blue-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Node.js</span>
        <span class="p-1 bg-blue-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">npm & yarn</span>
        <span class="p-1 bg-blue-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Feathers.js</span>
        <span class="p-1 bg-blue-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Socket.io</span>
        <span class="p-1 bg-blue-100 hover:bg-blue-200 cursor-pointer rounded-md mr-1 mb-2">Express.js</span>
        
      </div>
      <p class="text-xl font-bold uppercase ">Others Skills</p>
        <div class="my-2 flex flex-wrap">
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Heroku</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Netlify</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Git</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">GitHub</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">GitLab</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Jquery</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Eslint</span>
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Prettier</span>   
          <span class="p-1 bg-yellow-100 cursor-pointer hover:bg-blue-200 rounded-md mr-1 mb-2">Slack</span>
        </div>
    </div>
  </div>
  <div class="w-full bottom-0 bg-blue-100 text-center flex-wrap">
    <p class="mr-10 py-2 ">© 2021 CV Carlo Gammarota</p>
  </div>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
