<script setup>
import { Icon } from "@iconify/vue";
import { ref } from "vue";
defineProps(["imagem"]);
const like = ref(false);
</script>

<template>
    <div class="card">
        <button @click="like = !like">
            <Icon v-if="like"
            icon="material-symbols:heart-check-rounded" width="30" height="30" style="color: red" />

            <Icon v-else
            icon="material-symbols:heart-plus-outline-rounded" 
            width="30" height="30" style="color: #fff"/>
        </button>
        <img :src="imagem" alt="Praia de São Conrado" />
    </div>
</template>

<style scoped lang="scss">
.card {
    width: 29rem;
    height: 50rem;
    position: relative;

    img {
        border-radius: 10px;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    button {
        display: flex;
        position: absolute;
        right: 0.7rem;
        top: 0.5rem;
        background-color: #101e7a;
        border: none;
        border-radius: 50%;
        padding: 0.7rem;
        transition: ease 0.3s;
        
        &:hover {
            transform: scale(1.1);
        }

        &:active {
            transform: scale(0.9);
        }
    }
}
</style>