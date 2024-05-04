<script setup>
import { ref, onMounted } from 'vue'
import MySecondComponent from './MySecondComponent.vue'

const myRef = ref(null)

onMounted(() => {
  console.log(myRef.value)
})

;
</script>

<template>
  <MySecondComponent ref="myRef" />
</template>
