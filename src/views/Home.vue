<template>
    <div>
        <TwoinOne :name="'memeworld'" :imgsrc="home" :visit="'/about'" :btnName="'Get Started'"/>
    </div>
</template>

<script setup>
import TwoinOne from '../components/TwoinOne.vue';
import home from '../assets/images/group89.png'
</script>

<style scoped>

</style>