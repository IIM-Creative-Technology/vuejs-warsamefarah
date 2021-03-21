<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <blog/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Blog from '../views/Blog.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Blog
  }
}
</script>
