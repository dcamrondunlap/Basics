<script setup>
import {reactive} from 'vue';

// let initialState = reactive({count: 0});
let initialState = reactive({val: {count: 0}, user:['Camron', 'Clara']});
</script>

<template>
  <!-- <h1>Count: {{initialState.count}}</h1>
  <button @:click="initialState.count++">+</button>
  <button @:click="initialState.count--">-</button> -->

  <h1>Current Count: {{ initialState.val.count }} </h1>
  <h2>Users: {{ initialState.val.user }} </h2>
</template>
