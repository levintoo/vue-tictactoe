
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
  <h1 class="text-3xl font-bold underline bg-blue">
    Hello world!
  </h1>
  <h1>{{ count }}</h1>
  <button @click="count++" class="inline-flex items-center px-4 py-2 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none">increment</button>
  
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
</style>
