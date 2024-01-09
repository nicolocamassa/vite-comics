<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppBanner from './components/AppBanner.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppBanner
  }
}
</script>
<template lang="">
  <div>
    <AppHeader />
    <AppMain />
    <AppBanner />
    <AppFooter />

  </div>
</template>
<style lang="scss">
  @use './styles/generals.scss' as *;
  

  /* TODO: add scoped, remove padding from lists */
</style>