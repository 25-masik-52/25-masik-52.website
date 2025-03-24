<script setup>
import { ref } from 'vue'
const title = ref('Мой первый сайт на Vue!')
</script>

<template>
  <h1>{{ title }}</h1>
  <p>Скоро этот сайт будет на GitHub Pages!</p>
</template>

<style>
body {
  font-family: Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}
</style>