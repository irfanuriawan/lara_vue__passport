<template>
    <div class="container">
        <navbar-app></navbar-app>
        <content-app></content-app>
        <footer-app></footer-app>
    </div>
</template>

<script>
import navbarApp from '../components/navbar'
import contentApp from '../components/login'
import footerApp from '../components/footer'

export default {
    components: {
        navbarApp,
        contentApp,
        footerApp
    }  
}
</script>