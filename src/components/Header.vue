<script setup>
import { Icon } from '@iconify/vue';
</script>

<template>
    <header>
        <img src="../assets/logo.svg" alt="">

        <nav>
            <ul>
                <li><a href="">
                        <Icon icon="material-symbols:search-rounded" width="24" height="24" />
                    </a></li>

                <li><a href="">
                        Início
                        <Icon icon="material-symbols:home-outline-rounded" width="24" height="24" />
                    </a></li>

                <li><a href="">
                        Galeria
                        <Icon icon="material-symbols:home-storage-outline-sharp" width="24" height="24" />
                    </a></li>

                <li><a href="">
                        Favoritos
                        <Icon icon="material-symbols:favorite-outline" width="24" height="24" />
                    </a></li>
                    
                <li><a href="">
                        <Icon icon="material-symbols:person-outline" width="24" height="24" />
                    </a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped lang="scss"></style>