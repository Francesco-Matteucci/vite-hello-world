<script>
import AppTitle from './AppTitle.vue'
import AppHero from './AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <section>
    <AppTitle />
  </section>
  <section>
    <AppHero />
  </section>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}
</style>