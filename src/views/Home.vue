<template>
    <div>
        <TwoinOne :name="'MEME'" :imgsrc1="home" :imgsrc2="google" :imgsrc3="apple" :imgsrc4="googlephone" :imgsrc5="applephone" :visit="'/features'" :btnName="'Get Started'"/>
        <Body />
        <Footer />
    </div>
</template>

<script setup>
import TwoinOne from '../components/TwoinOne.vue';
import home from '../assets/images/group89.png'
import Body from '../components/Body.vue';
import google from '../assets/images/GooglePlay.png'
import googlephone from '../assets/images/google-play-badge-logo-svgrepo-c.png'
import applephone from '../assets/images/Download_on_the_App_Store_Badge_.png'
import apple from '../assets/images/AppStore.png'
import Footer from '../components/Footer.vue'
</script>

<style scoped>

</style>