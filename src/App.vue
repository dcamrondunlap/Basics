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
// import CustomValidator from "./components/CustomValidator.vue";
// import ComponentEvent from "./components/ComponentEvent.vue";
// import FromComponent from "./components/FromComponent.vue";
// import SlotComponent from "./components/SlotComponent.vue";
// import FallBackContent from "./components/FallBackContent.vue";
// import NameSlot from "./components/NameSlot.vue";
// import DefaultSlot from "./components/DefaultSlot.vue";
// import SchoolComponent from './components/SchoolComponent.vue';
// import PracticeComponent from './components/PracticeComponent.vue';
// import LifeCycleComponent from './components/LifeCycleComponent.vue';
// import BasicComponent from './components/BasicComponent.vue';
// import ReactiveObject from './components/ReactiveObject.vue';
// import MultipleSources from './components/MultipleSources.vue'
// import BasicRef from './components/BasicRef.vue'
// import FunctionRef from './components/FunctionRef.vue'
// import RefComponent from './components/RefComponent.vue'
// import ToggleFriends from './components/ToggleFriends.vue'
import CounterComponent from './components/CounterComponent.vue'
import YetAnotherComponent from './components/YetAnotherComponent.vue';

// import {provide} from 'vue';
// provide('studentName', 'Anthony');
// provide('studentAge', 26);
// provide('studentLocation', ['Earth', 'Canada']);

// Provide array
// provide('friends', ['Anthony', 'Gage', 'Jordan', 'Jacob']);

// Provide object
// provide('games', {
//   id: 1,
//   title: "Epic Adventure game",
//   genre: ['Action', 'Adventure', 'RPG'],
//   platform: ['PC', 'PlayStation', 'Xbox', 'Nintendo Switch'],
//   releaseDate: '03/15/2023',
//   developer: {
//     name: 'Awesome Game Studios',
//     location: 'San Francisco, CA',
//     teamSize: '50'
//   }
// });

// Provide Array of objects
// provide('moreGames', [
//   {
//     title: 'Space Explorer',
//     genre: 'Sci-Fi',
//     platform: 'PC',
//     releaseDate: '2023-05-20'
//   },
//   {
//     title: 'Fantasy Quest',
//     genre: 'Fantasy',
//     platform: 'PlayStation',
//     releaseDate: '2023-07-10'
//   },
//   {
//     title: 'Inception',
//     director: 'Christopher Nolan',
//     genre: 'Sci-Fi',
//     releaseDate: '2010-07-16'
//   },
//   {
//     title: 'The Shawshank Redemption',
//     director: 'Frank Darabont',
//     genre: 'Drama',
//     releaseDate: '1994-09-23'
//   }
// ]);


// import { ref } from "vue";

// let count = ref(0);

// const formHandler = (username, email, password) => {
//   console.log('username', username)
//   console.log('email', email)
//   console.log('password', password)
// };



// const firstName = ref('Camron');
// const lastName = ref('Dunlap');

// const myFavoriteNumber = ref(5);

// const showHide = ref(true);

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
  <!-- <CustomValidator name="Camron" :age="29" password="impossiblePassword"/> -->

  <!-- <h1>Count: {{ count }}</h1>
  <ComponentEvent @incrementCounter="count++" /> -->

  <!-- <FromComponent @userInfo="formHandler"/> -->

  <!-- <SlotComponent>
    <h1>Content 1</h1>
    <h2>Content 2</h2>
  </SlotComponent> -->

  <!-- <hr /> -->

  <!-- <FallBackContent></FallBackContent> -->
  <!-- <FallBackContent>

  </FallBackContent> -->

  <!-- <hr/> -->

  <!-- <NameSlot>
    v-slot:one
    <template v-slot:one>
      <h1>This content will go to slot "one"</h1>
    </template>
    #two
    <template #two>
      <h1>This content will go to slot "two"</h1>
    </template>
  </NameSlot>

  <hr>

  <DefaultSlot>
    <template #default>
      <h1>This is some random default content</h1>
    </template>
  </DefaultSlot> -->

  <!-- <SchoolComponent /> -->

  <!-- <PracticeComponent /> -->

  <!-- <LifeCycleComponent v-if="showHide" />
  <button @click="showHide = !showHide">Show / Hide</button> -->

  <!-- <BasicRef/> -->
  <CounterComponent/>
  <YetAnotherComponent />
</template>
