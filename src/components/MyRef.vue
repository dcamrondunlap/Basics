<!-- <script setup>
import { reactive, ref } from 'vue';
let count = ref(0);
let userName = ref('');
let userList = ref(['Camron, Clara, Chelsea, Jordan']);
let userInfo = ref({name: 'Camron', age: 29, location: ['OH', 'Fremont'], isMarried: false});
let friends = reactive([ref('Camron'), ref('Jordan'), ref('Gage')]);

</script>

<template>
    <h1>Count:{{ count }} </h1>
  <button @click="count++">+</button>
  <button @click="count--">-</button>

   <h1>Username: {{userName}}</h1>
  <button @click="userName = 'Clara'">Add user</button>

 <h1>Users List: {{ userList }} </h1>
  <button @click="userList.push('Doe')">Add User</button>

   <h1>Name: {{ userInfo.name }} </h1>
  <h1>Age: {{ userInfo.age }} </h1>
  <h1>Location: {{ userInfo.location }} </h1>
  <h1>isMarried: {{ userInfo.isMarried }} </h1>

  <button @click="userInfo.name = 'Jordan'">Change Name</button>
  <button @click="userInfo.age = '29'">Change Age</button>
  <button @click="userInfo.location = ['Oh', 'Holland']">Change Location</button>
  <button @click="userInfo.isMarried = 'true'">Change Married Status</button>

  <h1>1. {{ friends[0] }}</h1>
  <h1>1. {{ friends[1] }}</h1>
  <h1>1. {{ friends[2] }}</h1>

  <button @click="friends[0] = 'John'">Change</button>
  <button @click="friends[1] = 'Jacob'">Change</button>
  <button @click="friends[2] = 'Jingle-Heimer-Schmidt'">Change</button>

</template> -->
