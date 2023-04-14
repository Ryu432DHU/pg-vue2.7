<template>
  <div>
    <h1>This is about page.</h1>
    <p>This is a counter: {{  counter }}</p>
    <button @click="countUp">Count up</button>
  </div>
</template>

<script setup>
import { ref } from 'vue';


const counter = ref(0)

const countUp = () => {
  counter.value++
}
</script>