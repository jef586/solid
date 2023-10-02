<script setup lang="ts">
import Presentation from './components/Presentation.vue';
import UserDetails from './components/UserDeteils.vue';
import UserSummary from './components/UserSumary.vue';

</script>

<template>
   
   <div id="app">
    <Presentation />
    <UserDetails />
    <UserSummary />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
