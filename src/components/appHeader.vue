<template>
  <div id="app-header">
    <div class="header">
      <img class="header-img" src="../assets/img/MARVEL.png" alt="Marvel" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header {
  position: relative;
  text-align: center;
  height: 60px;
  border-bottom: 1px solid #333232;
}
.header .header-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 90%;
  object-fit: contain;
}
</style>