<script setup>
import { RouterLink, RouterView } from 'vue-router';

</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/"> Categorias</RouterLink>
        <RouterLink to="/Livros"> Livros </RouterLink>
        <RouterLink to="/Editoras"> Editoras </RouterLink>
        <RouterLink to="/Autores"> Autores </RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>


<style>
@import '@/assets/style.css';
</style>
