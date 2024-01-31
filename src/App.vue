<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  name: 'MyApp',
  data: () => ({
    name: 'Primo Esercizio'
  }),
  components: {
    AppTitle,
    AppHero
  }

}
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style></style>
