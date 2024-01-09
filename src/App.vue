<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppBanner from './components/AppBanner.vue';
import AppJumbotron from './components/AppJumbotron.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppBanner,
    AppJumbotron
  }
}
</script>
<template lang="">
  <div>
    <AppHeader />
    <AppJumbotron />
    <AppMain />
    <AppBanner />
    <AppFooter />

  </div>
</template>
<style lang="scss">
  @use './styles/generals.scss' as *;
  

  /* TODO: add scoped, remove padding from lists */
</style>