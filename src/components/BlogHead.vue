<template>
    <ul>
        <div class="menu">
            <li><router-link to="/admin">Gérer le Blog</router-link></li>
            <li><router-link to="/blog">Blog</router-link></li>
            <li>Login</li>
        </div>
        <div class="btn">
            <li class="cta"><router-link to="/create">Créer une page</router-link></li>
        </div>
    </ul>
</template>

<script>
export default {
    name: 'BlogHead'
}
</script>

<style scoped>
    ul {
        display: flex;
        justify-content: space-around;
    }

    li {
        list-style: none;
    }

    li a {
        text-decoration: none;
    }

    .menu {
        display: flex;
        justify-content: space-between;
    }

    .menu li {
        width: 150px;
    }

    .cta {
        border: 1px solid #000;
        padding: 1rem 1.5rem;
    }
</style>