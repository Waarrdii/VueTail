<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  
  <RouterView />
</template>


<style>
@config '../tailwind.config.cjs'
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
