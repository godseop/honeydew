<template>
  <h1>Post Page</h1>
  <hr/>
  <ul>
    <li v-for="post in postList">
      <Post v-bind="post"/>
    </li>
  </ul>
</template>

<script setup lang="ts">
const postList = [
  {title:'title1', likes:10, author:'godseop', date:new Date(), contents:'내용1'},
  {title:'title2', likes:26, author:'misomi', date:new Date(), contents:'내용2'},
  {title:'title3', likes:1, author:'song', date:new Date(), contents:'내용3'},
  {title:'title4', likes:7, author:'haeng', date:new Date(), contents:'내용4'},
  {title:'title5', likes:7, author:'hongildong', date:new Date(), contents:'내용5'},
];


</script>
