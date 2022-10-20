<script setup>
import CategoriasComp from "../components/CategoriasComp.vue";
</script>

<template>
  <div class="container">
    <div class="recomendados">
      <h2>Recomendados</h2>
      <div class="filmes"></div>
    </div>
    <CategoriasComp />
  </div>
</template>

<style scoped>
.container {
  display: grid;
  color: rgb(226, 35, 35);
  height: 100vh;
  grid-template-areas: "recomendados categorias";
  text-align: left;
  display: flex;
}

.recomendados {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
}

.filmes {
  background-color: rgb(255, 66, 66);
  border-radius: 10px;
  width: 80%;
  height: 400px;
}
</style>
