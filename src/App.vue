<template>
  <div>
    <Hero />
    <Feature />
    <WorkFeature />
    <Footer />
  </div>
</template>

<script>
import Hero from './components/Hero.vue';
import Feature from './components/Feature.vue';
import WorkFeature from './components/WorkFeature.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Hero,
    Feature,
    WorkFeature,
    Footer
    
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
