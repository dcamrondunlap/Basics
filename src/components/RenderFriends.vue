<script setup>
import { ref } from 'vue';
const friends = ref(['Anthony', 'Gage', 'Jordan', 'Jacob'])


;
</script>

<template>
  <h3 v-for="(friend, i) in friends" :key="i">
    {{ friend }}
  </h3>
</template>
