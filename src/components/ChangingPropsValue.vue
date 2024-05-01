<script setup>
  const myFavoriteNumberProp = defineProps(['myFavoriteNumber']);

  // Props are "immutable" which means the value can't be changed and they're just readonly'
  // myFavoriteNumberProp.myFavoriteNumber = 10;
</script>

<template>
  <h1>{{myFavoriteNumberProp.myFavoriteNumber}}</h1>
</template>
