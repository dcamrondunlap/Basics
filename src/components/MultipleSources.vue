<script setup>
import { reactive, ref, watch } from 'vue';

const username = ref('Gage')
const counter = ref(0)

watch([username, counter], (newValue, oldValue) => {
  console.log('New Value:', newValue)
  console.log('Old Value:', oldValue)
})

;
</script>

<template>
  <h1>{{ username }}</h1>
  <h1>Count: {{ counter }}</h1>

  <button @click="username = 'Anthony'">Change Name</button>
  <button @click="counter++">Increment Counter</button>
</template>
