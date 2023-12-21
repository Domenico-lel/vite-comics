<script>
export default {
    name: "appHeader"
}
</script>

<template>
    <header>
        <a href="/" class="brand">
            <img src=".../img/dc-logo.png" alt="">
        </a>

    </header>
</template>

<style lang="scss" scoped>
header {
    text-align: center;

    ul {
        list-style: none;
        margin: 2.5rem 1rem 4rem;
        @include center();

        li a {
            display: inline-block;
            padding: 1rem;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.3s;
        }

    }
}
</style>
