<template>
    <router-link to="/blog"><blog-body/></router-link>
</template>

<script>
import BlogBody from '../components/BlogBody.vue'

export default {
    name: 'Form',
    components: {
        BlogBody
    }
}
</script>