<!-- <script setup>
import {ref} from 'vue'
let count = ref(0);

const incrementCounter = () => count.value++;
const decrementCounter = () => count.value--;

const submitHandler = (e) => {
  e.preventDefault();
  alert('Valid Credentials');
};

const showMessage = (message) => alert(message);
</script>

<template>
   <h1>Count: {{ count }} </h1>
  <button v-on:click="">Increment</button>
   These are two different ways to do the buttons
  <button @:click="">Increment</button>

  <button v-on:click="incrementCounter">Increment</button>
  Another a destructured way to do this
  <button @:click="decrementCounter">Decrement</button>

  <form @:submit="submitHandler">
    <input type="text" placeholder="Please enter your name">
    <input type="email" placeholder="Please enter your email">
    <button type="submit">Submit</button>
  </form>

  <button @:click="showMessage('This is my message')">Show Message</button> 
 </template> -->
