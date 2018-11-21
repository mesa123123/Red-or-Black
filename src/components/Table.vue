<template>
  <div id="table">
    <div class="table-side">
      <div class="cardSlot">
        <img class="card" src='../assets/cardBackImg.svg' height="100%" alt="card"/>
      </div>
      <div class="cardSlot">
        <img class="card" src='../assets/cardBackImg.svg' height="100%" alt="card"/>
      </div>
    </div>
    <chipSelect/>
    <div class='table-side'>
      <div class="cardSlot">
        <img class="card" src='../assets/cardBackImg.svg' height="100%" alt="card"/>
      </div>
      <div class="cardSlot">
        <img class="card" src='../assets/cardBackImg.svg' height="100%" alt="card"/>
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
  display: flex;
  flex-direction: row;
  height: 80vh;
  width: 100vw;
}

.table-side {
  display: flex;
  flex-direction: row;
  width: 40vw;
}

.cardSlot {
  width: 18vw;
  height: 80vh;
  justify-content: center;
  margin: 1vw;
}

.card {
  width: 18vw;
  height: 80vh;
}
</style>
