<script setup>
import { Icon } from '@iconify/vue';
defineProps(["imagem"]);
</script>
<template>
    <div class="card">
        <button>
            <Icon icon="material-symbols:heart-plus-outline-rounded" width="24" height="24" />
            <Icon icon="material-symbols:heart-plus-outline-rounded" width="24" height="24"  style="color: #fff" />
            <Icon icon="material-symbols:heart-check-rounded" width="24" height="24" />
            <Icon icon="material-symbols:heart-check-rounded" width="24" height="24"  style="color: #fff" />
        </button>
        <img :src="imagem"
            alt="Praia de São Conrado" />
    </div>
</template>
<style scoped lang="scss">
.card {
    width: 30vw;
    height: 50vh;
    position: relative;

    img {
        border-radius: 10px;
        width: 100%;
        height: 100%;
    }

    button {
        position: absolute;
        right: 10px;
        background-color: transparent;
        border: none;
    }
}
</style>