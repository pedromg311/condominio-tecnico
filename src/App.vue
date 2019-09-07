<template>
  <div id="app">
    <FullPageSection :section-title="'Telhados'"></FullPageSection>
  </div>
</template>

<script>
import FullPageSection from './components/FullPageSection.vue'

export default {
  name: 'app',
  components: {
    FullPageSection
  }
}
</script>

<style lang="scss">
  @import './styles/styles.scss';

  #app {
     font-family: 'Avenir', Helvetica, Arial, sans-serif;
     -webkit-font-smoothing: antialiased;
     -moz-osx-font-smoothing: grayscale;
     text-align: center;
     color: #2c3e50;
     margin-top: 60px;
   }
</style>
