<script setup>
// import RenderFriends from './RenderFriends.vue'
import { ref, defineAsyncComponent } from 'vue';

let showFriends = ref(false)

const toggleFriends = () => (showFriends.value = !showFriends.value)
const RenderFriends = defineAsyncComponent(() => import('./RenderFriends.vue'))

;
</script>

<template>
  <div v-if="showFriends">
    <RenderFriends />
  </div>
  <button @click="toggleFriends">Toggle Friends List</button>
</template>
