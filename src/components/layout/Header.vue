<template>
    <header class="header">
        <h1>TodoList</h1>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </header>
</template>

<script>
export default {
    name:"Header"
}
</script>

<style scoped>
    .header{
        background: #d1f5d3;
        color: #FFF;
        text-align: center;
        padding: 10px
    }

    .header a{
        color: #fff;
        padding-right: 5px;
        text-decoration: none;
    }

</style>