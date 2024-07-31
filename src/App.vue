<template>
  <div class="container">
    <nav-bar/>
    <hero-section/>
  </div>
</template>

<script>
import HeroSection from './components/layout/HeroSection.vue';
import NavBar from './components/layout/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection
  }
  
};
</script>

