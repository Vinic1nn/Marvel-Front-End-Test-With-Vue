<template>
  <div id="app">
    <app-header />
    <app-selectionBar @hero-selected="updateSelectedHero" />
    <app-main :selected-hero="selectedHero" />
  </div>
</template>

<script>
import header from "./components/header.vue";
import selectionBar from "./components/selectionBar.vue";
import menu from "./components/menu.vue";

export default {
  components: {
    "app-header": header,
    "app-selectionBar": selectionBar,
    "app-main": menu,
  },
  data() {
    return {
      selectedHero: "hulk",
    };
  },
  methods: {
    updateSelectedHero(hero) {
      this.selectedHero = hero;
    },
  },
};
</script>
<style >
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@500&family=Roboto&display=swap");
html {
  background-color: #101010;
  color: #fff;
  background-color: black;
  font-family: "Oswald", "Roboto";
}
</style>