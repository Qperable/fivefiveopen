<template>
  <div id="app">
    <Header />
    <Activity />
  </div>
</template>

<script>
import Activity from "./components/Activity.vue";
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
    Activity,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 24px;
}

p {
  display: block;
  margin-block-start: 0;
  margin-block-end: 0;
  margin-inline-start: 0px;
  margin-inline-end: 0px;
}
</style>
