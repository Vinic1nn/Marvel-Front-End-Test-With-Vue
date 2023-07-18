<template>
  <div id="footer">
    {{ getted }}
  </div>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      getted: null,
    };
  },
  mounted() {
    axios
      .get(`https://api.adviceslip.com/advice `)
      .then((response) => (this.getted = response.data.slip.advice));
    console.log(this.getted);
  },
};
</script>

<style>
#footer {
  display: flex;
  flex-direction: row;
  background: #101010;
  align-items: center;
  width: 100%;
  height: 5%;
  position: fixed;
  bottom: 0%;
  border-top: 1px solid black;
  font-family: "Roboto";
  color: #fff;
}
</style>