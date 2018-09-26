<template>
  <div id="table">
    <div id="table-side" >
      <div class="cardSlot">
        <img src='../assets/cardBackImg.svg' alt="card" height="45%" width="30%"/>
      </div>
      <div class="cardSlot">
        <img src='../assets/cardBackImg.svg' alt="card" height="45%" width="30%"/>
      </div>
    </div>
    <div id='table-side'>
      <div id="SelectByChip">
        <chipSelect/>
      </div>
      <div class="cardSlot">
        <img src='../assets/cardBackImg.svg' alt="card" height="45%" width="30%"/>
      </div>
      <div class="cardSlot">
        <img src='../assets/cardBackImg.svg' alt="card" height="45%" width="30%"/>
      </div>
    </div>
  </div>
</template>

<script>
import chipSelect from "./chipSelect";
export default {
  name: "tableTop",
  components: {
    chipSelect
  }
};
</script>

<style scoped>
@import "../assets/styles.css";

#table {
  display: inline;
}

.cardSlot {
  position: relative;
  display: inline;
  margin: 2%;
}

#SelectByChip {
  display: inline;
}
</style>
