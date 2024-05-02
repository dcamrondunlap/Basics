<script setup>
import { reactive, watch } from 'vue';

const state = reactive({username: 'Anthony'});

// Here we can't provide specific property of the object
// we have to provide the entire object, otherwise it's gonna give us error in the console

watch(() => state.username, (newValue, oldValue) => {
  // if we're using "object" both the new and old values will be the same
  console.log('new value:', newValue)
  console.log('oldValue:', oldValue)
});
</script>

<template>
  <h1>{{ state.username }}</h1>
  <button @click="state.username = 'Gage'">Change Name</button>
</template>
