<template>
  <div id='headerCell'>
      <h1 id='titleWriting'>Red or Black?</h1>
  </div>
</template>

<script>
export default {
  name: "headerCell"
};
</script>

<style scoped>
@import "../assets/styles.css";

#headerCell {
  color: #dbc38a;
  font-size: 3vw;
  font-family: "Quicksand", sans-serif;
  text-align: center;
  background-color: black;
  border: 1vw solid #dbc38a;
  border-radius: 1%;
  min-height: 15%;
  min-width: 15%;
  max-width: 60%;
  max-height: 25%;
  margin: auto;
  -webkit-box-shadow: -3px 10px 5px -7px #000;
  -moz-box-shadow: -3px 10px 5px -7px #000;
  box-shadow: -3px 10px 5px -7px #000;
}

#titleWriting {
  margin: auto;
  margin-bottom: 0.5vw;
  max-width: 90%;
  box-shadow: #dbc38a;
}
</style>
