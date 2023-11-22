<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div id="nav">
      <RouterLink to="/">Inicio</RouterLink> | 
      <RouterLink   to="/about">Acerca De</RouterLink> |
      <RouterLink to="/brazil">Brasil</RouterLink>
    </div>
    <div class="container">
      <RouterView />
    </div>
</template>

<style scoped>

</style>
