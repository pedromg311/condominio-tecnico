<template>
  <div id="app">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item">
          <img src="./assets/logo_v2.png" alt="Condomínio Técnico" class="page-logo">
        </a>
        <p class="navbar-title navbar-item title is-4"> Condomínio Técnico</p>
      </div>
    </nav>
    <FullPageSection :section-title="'Contactos'" mainColor="#DADADA">
      <div>
        <p><strong>Francisco Gomes:</strong> 913 931 027</p>
      </div>
    </FullPageSection>
    <FullPageSection :section-title="'Página em Construção'" mainColor="#03ADFF">
      <img src="./assets/ducky.png" alt="Site is a work in progress">
    </FullPageSection>
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
   }

  .navbar-item .page-logo {
    max-height: 4rem;
    height: auto;
    width: 4rem;
  }

  .navbar-title {
    flex: 1;
  }
</style>
