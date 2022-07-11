
<script>
import { ref } from "vue";
export default {
  name: 'HomeView',
  setup() {
    const count = ref(0);
    return {
      count
    }
  }
}
</script>

<template>
  <h1>{{ count }}</h1>
  <button @click="count++">increment</button>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
