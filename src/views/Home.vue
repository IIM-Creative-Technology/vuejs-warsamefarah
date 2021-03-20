<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <blog-body/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import BlogBody from '../components/BlogBody.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    BlogBody
  }
}
</script>
