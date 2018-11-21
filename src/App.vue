<template>
  <div id="app">
    <headerCell/>
    <tableTop/>
  </div>
</template>

<script>
import headerCell from "./components/Header";
import tableTop from "./components/Table";

export default {
  name: "app",
  components: {
    headerCell,
    tableTop
  }
};
</script>

<style lang="scss">
@import "./assets/styles.css";
</style>
