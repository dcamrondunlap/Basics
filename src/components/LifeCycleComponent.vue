<!-- <script setup>
import {
  ref,
  onBeforeMount,
  onMounted,
  onBeforeUpdate,
  onUpdated,
  onBeforeUnmount,
  onUnmounted
  } from "vue"

  const message = ref('Hello, Vue');

  //LifeCycle Hooks
  onBeforeMount(() => {
    console.log('Component is about to be mounted')
  });

  onMounted(() => {
    console.log('Component has been mounted')
  });

  onBeforeUpdate(() => {
    console.log('Component is about to update')
  });

  onUpdated(() => {
    console.log('Component has been updated')
  })

  onBeforeUnmount(() => {
    console.log('Component is about to be unmounted')
  });

  onUnmounted(() => {
    console.log('Component has been unmounted')
  })

  const updateMessage = () => {
    message.value = 'Updated Message!'
  };



</script>

<template>
  <p>{{ message }}</p>
  <button @click="updateMessage">Update Method</button>
</template> -->
