<script setup>
import { RouterLink, RouterView } from 'vue-router'
import ProfileItem from './components/ProfileItem.vue'
</script>

<template lang="pug">
  header
    ul
      li.right
        ProfileItem
  main
    RouterView
  footer about
</template>

<style scoped>
header {
  position: fixed;
  top: 0;
  width: 100%;
  position: sticky;
  height: 50px;
  box-shadow: 0 5px 5px lightgray;
}

footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  text-align: center;
  height: 50px;
  box-shadow: 0 -5px 5px lightgray;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  /* overflow: hidden; */
}

li {
  float: left;
}

.right {
  float: right !important;
}

li a {
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
</style>
