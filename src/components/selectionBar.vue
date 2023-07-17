<template>
  <div>
    <div class="selectionBar">
      <div
        id="hulkSpan"
        :class="{ active: redNow === 'hulkSpan' }"
        @click="
          turnRed('hulkSpan');
          eventHero('hulk');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Hulk</span>
      </div>
      <div
        id="spiderSpan"
        :class="{ active: redNow === 'spiderSpan' }"
        @click="
          turnRed('spiderSpan');
          eventHero('spider');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Spider-man</span>
      </div>
      <div
        id="ironmanSpan"
        :class="{ active: redNow === 'ironmanSpan' }"
        @click="
          turnRed('ironmanSpan');
          eventHero('ironman');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Iron Man</span>
      </div>
      <div
        id="thorSpan"
        :class="{ active: redNow === 'thorSpan' }"
        @click="
          turnRed('thorSpan');
          eventHero('thor');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Thor</span>
      </div>
      <div
        id="hawkeyeSpan"
        :class="{ active: redNow === 'hawkeyeSpan' }"
        @click="
          turnRed('hawkeyeSpan');
          eventHero('hawkeye');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Hawkeye</span>
      </div>
      <div
        id="blackwidowSpan"
        :class="{ active: redNow === 'blackwidowSpan' }"
        @click="
          turnRed('blackwidowSpan');
          eventHero('widow');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Black Widow</span>
      </div>
      <div
        id="captainSpan"
        :class="{ active: redNow === 'captainSpan' }"
        @click="
          turnRed('captainSpan');
          eventHero('captain');
        "
        @mouseover="onHover"
        @mouseleave="notHover"
      >
        <span class="heroText">Captain America</span>
      </div>
    </div>
  </div>
</template>
    
    <script>
export default {
  data() {
    return {
      redNow: null,
      anotherVisible: false,
      visibleNow: null,
    };
  },
  methods: {
    turnRed(heroSpan) {
      this.redNow = heroSpan;
    },
    onHover(heroSpan) {
      heroSpan.target.style.transform = "scale(1.1)";
    },
    notHover(heroSpan) {
      heroSpan.target.style.transform = "scale(1)";
    },
    eventHero(hero) {
      this.$emit("hero-selected", hero);
    },
  },
}
</script>
    
    <style>
.selectionBar {
  display: flex;
  margin-top: 25px;
  justify-content: space-around;
}
.selectionBar div {
  clip-path: polygon(
    20% 0%,
    80% 0%,
    100% 0,
    100% 70%,
    80% 100%,
    20% 100%,
    0 100%,
    0% 30%
  );
  padding: 10px 35px 10px 35px;
  font-size: 17px;
  cursor: pointer;
}
.active {
  background-color: #e62429;
}
.heroText {
  transition: transform 0.3s;
}
.selectionBar div:hover .heroText {
  transform: scale(1.15);
}
</style>
    