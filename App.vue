<template>
  <div id="app">

    <VirtualHealth></VirtualHealth>
  </div>
</template>

<script>
import VirtualHealth from './components/virtual-health.vue';

export default {
  name: 'App',
  components: {
    VirtualHealth
  }
}

</script>

<style>
/* Global Styles and Resets */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f5f5f5;
  color: #333;
}

header {
  background-color:white;
  color: #fff;
  padding: 20px;
  text-align: center;
}

h1 {
  font-size: 24px;
  margin-bottom: 20px;
}

</style>
