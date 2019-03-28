<template>
    <v-toolbar class="indigo" dark>
        <v-toolbar-title class="mr-4" dark @click="navigateTo('home')">Playlist App</v-toolbar-title>

        <v-toolbar-items>
            <v-btn flat dark router to="/songs">My Songs</v-btn>
        </v-toolbar-items>

        <v-spacer></v-spacer>

        <v-toolbar-items>
            <v-btn flat dark router to="/login">Login</v-btn>
            <v-btn flat dark router to="/signup">Sign Up</v-btn>
        </v-toolbar-items>
    </v-toolbar>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>
