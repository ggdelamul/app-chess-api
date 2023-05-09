<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
</script>

<template>
  <div class="container">
    <TheHeader />
    <RouterView />
    <TheFooter />
  </div>
</template>

<style scoped></style>
