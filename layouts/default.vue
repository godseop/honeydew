<template>
  <h1>default layout</h1>
  <button @click="enableCustomLayout">custom layout</button>
  <Header/>
  <Navigator/>
  <slot/>
  <Footer/>
</template>

<script setup lang="ts">
function enableCustomLayout () {
  setPageLayout('custom')
}
// definePageMeta({
//   layout: false,
// });
</script>
