<template>
  <NewComponent />
  <button @click="helloWorld">Button</button>
</template>

<script setup>
import NewComponent from './components/NewComponent.vue'

function helloWorld() {
  console.log("Hello World")
}
</script>

<style scoped>
button {
  margin-top: 20px;
  padding: 5px 10px;
  border: 2px solid black;
}
</style>
