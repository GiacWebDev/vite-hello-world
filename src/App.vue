  <script>
import AppHeroVue from './components/AppHero.vue';

    import AppTitle from './components/AppTitle.vue';
    import AppHero from './components/AppHero.vue'; 


    export default {
    name: 'App',

    // aggiungo la proprietà components con i relativi componenti: 
    components: {
      AppTitle,
      AppHero,
    }
  
  }
  </script>


<template>
  
  <AppHero />
  <AppTitle />
  
</template>


<style>

</style>