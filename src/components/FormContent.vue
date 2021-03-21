<template>
    <form @submit.prevent="sendForm">
        <p><label for="title">Titre de la page</label></p>
        <p><input v-model="title" type="text" name="title"></p><br><br>
        <p><label for="meta-t">Meta Title</label></p>
        <p><input v-model="metat" type="text" name="meta-t"></p><br><br>
        <p><label for="meta-d">Meta Description</label></p>
        <p><input v-model="metad" type="text" name="meta-d"></p><br><br>
        <p><label for="body">Corps du post</label></p>
        <p><textarea v-model="body" name="body" id="" cols="30" rows="10"></textarea></p><br>
        <input type="button" value="Créer la page">
    </form>
</template>

<script>
export default {
    name: 'FormContent',
    data() {
        return {
            title: '',
            metat: '',
            metad: '',
            body: '',
        }
    },
    methods: {
        sendForm: function() {
            if (this.title && this.metat && this.metad && this.body) {
                return true;
            }

            this.errors = [];

            if (!this.title || !this.metat || !this.metad || !this.body) {
                this.errors.push('Tout les champs sont requis');
            }
        }
    }
}
</script>