<script setup>
import { Icon } from '@iconify/vue';

</script>

<template>
    <footer>
    <div class="redes">
        <a href=""><Icon icon="ic:baseline-facebook" width="24" height="24"  style="color: #fff" /></a>
        <a href=""><Icon icon="ri:linkedin-fill" width="24" height="24"  style="color: #fff" /></a>
        <a href=""><Icon icon="mdi:instagram" width="24" height="24"  style="color: #fff" /></a>
        <a href=""><Icon icon="mdi:twitter" width="24" height="24"  style="color: #fff" /></a>
    
    </div>

    <div>
        <h2>Contato</h2>
        <a href="">contato@inspiralens.com</a>
        <a href="">Central de ajuda</a>
        <a href="">Rio de Janeiro – Brasil</a>
    </div>
    <div>
        <h2>Sobre</h2>
        <a href="">Politicas</a>
        <a href="">Politicas de privacidade</a>
        <a href="">Blog</a>
    </div>

    <div>
        <h2>Assine nossa newsletter</h2>
        <input type="email" placeholder="Seu email">
        <button type="submit">Inscrever-se</button>
    </div>

</footer>
</template>

<style scoped lang="scss">

</style>