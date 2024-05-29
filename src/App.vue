<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <NavBar />
  <div class="page-wrap">
    <router-view></router-view>
  </div>
  
</template>

<script>
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar, 
    // https://github.com/LinkedInLearning/vuejs-creating-and-hosting-a-full-stack-site-4359014/tree/01_06_e/front-end/src/assets
  }
}
</script>

