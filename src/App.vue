<script setup>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import Inspire from './components/Inspire.vue';
import Footer from './components/Footer.vue';

</script>

<template>
  <Header />
  <Hero />
  <Inspire />
  <Footer />

</template>

<style scoped lang="scss">
/* Modo light */
 $text: #040820;
$background: #f2f3fd;
$primary: #101e7a;
$secondary: #ee77af;
$accent: #b61619;

/* Dark Mode */
$text: #dfe3fb;
$background: #02030d;
$primary: #8593ef;
$secondary: #881149;
$accent: #e9494c;

/* Modo light */
$text: #0b0014;
$background: #f8f0ff;
$primary: #920bf9;
$secondary: #fc7e82;
$accent: #fba050;

/* Dark Mode */
$text: #f6ebff;
$background: #08000f;
$primary: #8d06f4;
$secondary: #810308;
$accent: #af5404;
</style>