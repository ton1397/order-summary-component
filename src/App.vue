<template>
    <div id="app">
        <order-summary/>
    </div>
</template>

<script>
import orderSummary from "./components/order-summary.vue";
export default {
  name: 'App',
  components: {
    orderSummary
  }
}
</script>

<style>
body, html{
    padding: 0;
    margin: 0;
    background-color: #e2e9fd;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
