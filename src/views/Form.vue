<template>
    <router-link to="/create"><form-content/></router-link>
</template>

<script>
import FormContent from '../components/FormContent.vue'

export default {
    name: 'Form',
    components: {
        FormContent
    }
}
</script>