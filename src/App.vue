<template>
  <div id="app">
    <HeaderWithNav />
    <ContentPage />
    <ShopNav />
    <OtherLinks />
    <FooterWithNav />
  </div>
</template>

<script>
import HeaderWithNav from './components/HeaderWithNav.vue';
import ContentPage from './components/ContentPage.vue';
import ShopNav from './components/ShopNav.vue';
import OtherLinks from './components/OtherLinks.vue';
import FooterWithNav from './components/FooterWithNav.vue';

export default {
  name: 'App',
  components: {
    HeaderWithNav,
    ContentPage,
    ShopNav,
    OtherLinks,
    FooterWithNav
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
