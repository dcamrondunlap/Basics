<script setup>
const myRefFunc = (el) => {
  console.log(el.textContent) //Reading text content
  el.textContent = 'Text Changed'
  el.style.color = 'crimson'
}


;
</script>

<template>
  <h1 :ref="myRefFunc">This is initial value</h1>
</template>
