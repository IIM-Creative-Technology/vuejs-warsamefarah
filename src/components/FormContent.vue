<template>
    <form>
        <label for="title">Titre de la page</label> <br>
        <input type="text" name="title"><br><br>
        <label for="meta-t">Meta Title</label><br>
        <input type="text" name="meta-t"><br><br>
        <label for="meta-d">Meta Description</label><br>
        <input type="text" name="meta-d"><br><br>
        <label for="body">Corps du post</label><br>
        <textarea name="body" id="" cols="30" rows="10"></textarea><br>
        <button type="submit">Créer la page</button>
    </form>
</template>

<script>
export default {
    name: 'FormContent'
}
</script>