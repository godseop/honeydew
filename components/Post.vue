<template>
  <div>
    <p>{{ post.title }}</p>
    <p>{{ post.likes }}</p>
    <p>{{ post.author }}</p>
    <p>{{ post.date }}</p>
    <span>{{ post.contents }}</span>
  </div>
</template>

<script setup lang="ts">
const post = defineProps<{
  title?: String,
  likes?: Number,
  author?: String,
  date?: Date,
  contents?: String,
}>()

</script>
