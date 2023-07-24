<template>
  <h1>custom layout</h1>
  <button @click="enableDefaultLayout">custom layout</button>
  <slot/>
</template>

<script setup lang="ts">
function enableDefaultLayout () {
  setPageLayout('default')
}
// definePageMeta({
//   layout: false,
// });
</script>