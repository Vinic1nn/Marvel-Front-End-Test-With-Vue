<template>
  <div id="app">
    <app-header />
    <app-selectionBar @hero-selected="updateSelectedHero" />
    <app-menu :selected-hero="selectedHero" />
    <app-footer/>
  </div>
</template>

<script>
import header from "./components/appHeader.vue";
import selectionBar from "./components/selectionBar.vue";
import menu from "./components/appMenu.vue";
import footer from "./components/appFooter.vue"

export default {
  components: {
    "app-header": header,
    "app-selectionBar": selectionBar,
    "app-menu": menu,
    "app-footer": footer 
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
  font-family: "Oswald", "Roboto";
}
</style>