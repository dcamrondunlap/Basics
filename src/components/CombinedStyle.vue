<template>
  <h2 class="g-1">Another Global style</h2>
  <h2 class="l-1">Another Local Styling</h2>
</template>

Global Styling
<style>
  .g-1{
    background: fuchsia;
    color: white;
  }
</style>

Local Styling
<style scoped>
  .l-1{
    background: black;
    color: white;
  }
</style>
