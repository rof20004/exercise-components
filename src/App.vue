<template>
    <div class="container">
        <header-component></header-component>
        <hr>
        <server-component></server-component>
        <hr>
        <footer-component></footer-component>
    </div>
</template>

<script>
    import Header from './Header.vue'
    import Server from './Server.vue'
    import Footer from './Footer.vue'

    export default {
        components: {
            'header-component': Header,
            'server-component': Server,
            'footer-component': Footer
        }
    }
</script>

<style>

</style>
