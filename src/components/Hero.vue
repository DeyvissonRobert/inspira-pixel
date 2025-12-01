<script setup>

</script>

<template>
    <section class="hero">
        <aside>
            <h2>Onde a paisagem vira <span>inspiração</span>.</h2>
            <p>Explore paisagens, cores e luzes que inspiram novas histórias através da fotografia.</p>
        </aside>

        <img src="../assets/fotografo.png" alt="Imagem ilustrativa">
    </section>

</template>

<style scoped lang="scss">
.hero {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 2rem;
}

aside {
    width: 40rem;
}

h2 {
    font-size: 3.75rem;
    font-weight: 800;
    color: #262626;
}

span {
    font-size: 5rem;
    color: #E1306C;
}

p {
    font-size: 1.25rem;
    font-weight: 500;
    color: #262626;
}

img {
    width: 40vw;
}


</style>