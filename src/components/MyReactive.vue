<!-- <script setup>
import {reactive} from 'vue';

let initialState = reactive({count: 0});
let initialState = reactive({val: {count: 0}, user:['Camron', 'Clara']});

const changeUser = () => {
  initialState.user[0] = 'Jordan';
  initialState.user[1] = 'Chelsea'
};
</script>


<template>
  <h1>Count: {{initialState.count}}</h1>
  <button @:click="initialState.count++">+</button>
  <button @:click="initialState.count--">-</button>

  <h1>Current Count: {{ initialState.val.count }} </h1>
  <h2>Users: {{ initialState.user }} </h2>

  <button @click="initialState.val.count+=10">Add 10</button>
  <button @click="changeUser">Change User</button>
  <button @click="initialState.user.push('John Doe') ">Add one more user</button>
</template> -->
