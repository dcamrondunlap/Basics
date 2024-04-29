<template>
  <!-- <h1 :class="$style['m-class']">Using module CSS with $ syntax (kabob-case)</h1> -->
  <h1 :class="myClasses.anotherClass">Using Module CSS with $ syntax (camelCase)</h1>
</template>

<style module="myClasses">
  /*Kabab-case*/
  .m-class {
    background: firebrick;
    color: white;
  }

  .anotherClass {
    background: seagreen;
    color: white;
  }
</style>
