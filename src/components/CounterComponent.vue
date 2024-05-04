<script setup>
import { useCounter } from '@/Shared/useCounter';
const counter = useCounter()
;
</script>

<template>
  <h1>Count: {{counter.count.value}}</h1>
  <button @click="counter.increment">+</button>
  <button @click="counter.decrement">-</button>
</template>
