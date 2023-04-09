<script setup>
import NavBarGlobal from './NavBarGlobal.vue';
defineProps({
  headOne: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <header class="bg-dark d-flex justify-content-between p-3 pb-2">
    <h1 class="text-white">{{ headOne }}</h1>
    <NavBarGlobal />
  </header>
</template>

<style scoped></style>
