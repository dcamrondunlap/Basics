<script setup>
// import GlobalStyle from './components/GlobalStyle.vue'
// import LocalStyle from './components/LocalStyle.vue'
// import CombinedStyle from './components/CombinedStyle.vue'
// import ModuleStyle from './components/ModuleStyle.vue'
// import MyEvents from './components/MyEvents.vue';
// import MyReactive from './components/MyReactive.vue';
// import MyRef from './components/MyRef.vue';
// import ComputedProperties from './components/ComputedProperties.vue';
// import ConditionalRendering from "./components/ConditionalRendering.vue";
// import IterationComponent from "./components/IterationComponent.vue";
// import StaticPropsComponents from "./components/StaticPropsComponents.vue";
// import DynamicPropsComponent from "./components/DynamicPropsComponent.vue";
// import ChangingPropsValue from "./components/ChangingPropsValue.vue";
// import PropValidation from "./components/PropValidation.vue"
// import ComplexProps from "./components/ComplexProps.vue"
import CustomValidator from "./components/CustomValidator.vue";

// import { ref } from "vue"




// const firstName = ref('Camron');
// const lastName = ref('Dunlap');

// const myFavoriteNumber = ref(5);

</script>

<template>
  <!-- <StaticPropsComponents name="Anthony" />
  <hr />
  <DynamicPropsComponent :firstName="firstName" :lastName="lastName"/>
  <hr />
  <ChangingPropsValue  :myFavoriteNumber="myFavoriteNumber"/>
  <hr />
  <PropValidation  fullName="Anthony" :age="26"/>
  <hr />
  <ComplexProps :friends="['Anthony', 'Gage', 'Jordan', 'Jalon']" :userInfo="{name: 'Anthony', age: 26, location: ['Earth', 'Canada']}"/>
  <hr /> -->
  <CustomValidator name="Camron" :age="29" password="impossiblePassword"/>
</template>
