<script setup lang="ts">
import TestTs from './components/TestTs.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" src="./assets/logo.svg" width="32" height="32" />
  </header>

  <main>
    <test-ts />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 2px;
}
/*
@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
  */
</style>
