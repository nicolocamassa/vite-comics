<script>
export default {
  name: "AppJumbotron",
  data() {
    return {};
  },
};
</script>
<template lang="">
  <div class="jumbotron">
    <div class="current">CURRENT SERIES</div>
  </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
.jumbotron{
  height: 400px;
  width: 100%;
  background-image: url('../assets/jumbotron.jpg');
  background-size: cover;
  position: relative;

  .current{
    position: absolute;
    bottom: -30px;
    left: 250px;
    background-color: $main_color;
    padding: 20px 40px;
    font-weight: 800;
    color: white;
  }
}


</style>
