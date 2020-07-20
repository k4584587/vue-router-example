<template>
    <div class="Header">
        <ul>
            <li>
                <router-link to="/" exact>Home</router-link>
            </li>
            <li>
                <router-link to="/login" exact>Login</router-link>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "RwvHeader"
    }
</script>

<style scoped>

</style>
