<template>
    <div class="list">
        <section v-for="(title) in form" v-bind:key="title.id">
            <form-content>
                <h2>{{form.title}}</h2>
            </form-content>
        </section>
    </div>
</template>

<script>

export default {
    name: 'BlogBody',
}
</script>

<style scoped>
    section {
        margin: auto;
        width: 80%;
        height: 200px;
        border: 1px solid #000;
    }
</style>