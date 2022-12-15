<template>
    <div class="container">
        <h2>This is a New Component</h2>
        <p>{{ data }}</p>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const data = ref("Hi! this is data from my javascript");

</script>

<style>
.container {
    border: 2px solid black;
    border-radius: 10px;
    padding: 10px 30px;
    box-shadow:0px 3px 3px rgba(0, 0, 0, 0.272);
}
</style>