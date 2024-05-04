<script setup>
import { ref } from 'vue';

//When using a scrip setup its private by default
//a parent referencing a child wont be able to access anything


//first we have to expose all the properties and methods
//then we'd be able to use them in parent component
// use (defineExpose) to expose our data for the parent to use


const count = ref(10)
const increment = () => count.value++
const decrement = () => count.value--

defineExpose({count, increment, decrement})

;
</script>

<template>
  <h1>Count: {{ count }}</h1>
  <button @click="increment">+</button>
  <button @click="decrement">-</button>
</template>
