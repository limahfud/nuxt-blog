<template>
    <div>
        <h1>This is all views</h1>
        <nuxt-link to="/users/1">Going to user 1</nuxt-link>
        <nuxt-link to="/users/2">Going to user 2</nuxt-link>
        <nuxt-link to="/users/3">Going to user 3</nuxt-link>
        <nuxt-link to="/users/4">Going to user 4</nuxt-link>

        <br>
        <nuxt-link to="/users/setting">Setting</nuxt-link>

        <button @click="loadRandomUser()">Click me!</button>

        <nuxt-child />
    </div>
</template>

<script>
export default {
    data() {
        return { 
            userId: ''
        }
    },
    methods: {
        loadRandomUser() {
            const rand = Math.floor(Math.random() * 4) + 1;
            this.$router.push('/users/' + rand);
        }
    },
    layout: 'users'
}
</script>

