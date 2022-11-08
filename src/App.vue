<script>
  import  AppTitle from './components/AppTitle.vue';
  import  AppHero from './components/AppHero.vue';

export default {
  
  
  
  data() {
    return {
      greeting: "Ciao mondo!"
    }
  },
  components: {
    AppTitle,
    AppHero
  },
}

</script>

<template>
  <h1>{{ greeting }}</h1>
  <section>
    <AppTitle />
    <AppHero />
  </section>
</template>

<style scoped>

</style>
