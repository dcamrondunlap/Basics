<script setup>
import { ref, watch} from 'vue';
const message = ref('Hello, Vue');
const inputText = ref('apple');

//Watch for changes in input text and update message accordingly
watch(inputText, (newValue, oldValue) => {
  //You can perform some logic here when inputText changes
  // eslint-disable-next-line no-unused-vars
  console.log(newValue);
  // eslint-disable-next-line no-unused-vars
  console.log(oldValue);
  message.value = `You typed: ${newValue}`;
});
</script>

<template>
  <h1>{{ message }}</h1>
  <!-- eslint-disable-next-line vue/valid-v-model -->
  <input v-model="inputText" placeholder="Type Something...">
</template>
