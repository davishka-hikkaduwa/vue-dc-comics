<template>
  <div id="app">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import { comics } from '@/assets/data/dc-comics.json';
console.log(comics);

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  },
  data() {
    return { comics }
  }
}
</script>

<style lang="scss">
@import './styles/generic';
@import './styles/variables';

.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>
