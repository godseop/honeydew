<template>
  <header>
    <h1>Hello {{ app.title }}</h1>
  </header>
</template>

<script setup lang="ts">
const app = useAppConfig();

</script>
