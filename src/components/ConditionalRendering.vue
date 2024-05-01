<script setup>
  import { ref } from "vue";

  // const isTrue = true;
  // const isFalse = false;

  // let isUserLoggedin = ref(true);
  // let username = 'Camron';
  // let showDetails = ref(isUserLoggedin);

  // const isActive = ref(true);

  let password = ref('mypersonal password');
</script>

<template>
  <!-- <div>
    <p v-if="isTrue">This is will show if isTrue is true</p>
    <p v-else-if="isFalse">This is will show if isTrue is true</p>
    <p v-else>This will show is neither isTrue nor isFalse is true</p>
  </div> -->

  <!-- <p v-show="isVisible">This paragraph will be shown or hidden based on the value of isVisible</p>
  <button @click="isVisible = !isVisible">Toggle visibility</button> -->

  <!-- <div>
    <h1 v-if="isUserLoggedin">Welcome, {{ username }}</h1>
    <p v-else>Please log in to access this content</p>

    <div v-show="showDetails">
      <h4>You're now able to modify your dashboard'</h4>
    </div>
  </div> -->

  <!-- <div v-if="isActive">
    <h1>Blog Post</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla, accusantium vel eum animi magnam, id reprehenderit, autem nam consequuntur ex at soluta vero ab unde consequatur maiores molestiae doloremque eius.</p>
  </div> -->

  <!-- <button @click="isActive = !isActive">Toggle Post</button> -->

  <h1 v-if="password.length > 8">Strong Password</h1>
  <h1 v-else-if="password.length < 8">Weak Password</h1>
  <h1 v-else>Please enter your password</h1>

</template>
