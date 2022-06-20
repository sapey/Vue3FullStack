<script setup>
import { RouterView } from "vue-router";

</script>


<template>

<div id="navbar">
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/signIn">signIn</a>
  <a href="/signUp">signUp</a>
  <a href="/todolists">Todo list</a>
</div>
  
  <RouterView />
</template>

<style></style>
