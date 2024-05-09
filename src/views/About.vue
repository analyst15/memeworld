<template>
    <div>
        <TwoinOne :name="'Welcome to About Page'" :imgsrc1="home" :visit="'/services'" :btnName="'Get Started'"/>
    </div>
</template>

<script setup>
import TwoinOne from '../components/TwoinOne.vue';
import home from '../assets/images/group89.png'
</script>

<style scoped>

</style>