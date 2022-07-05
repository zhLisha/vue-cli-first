<template>
  <div id="app">
    <Title msg="La mia prima app con Vue CLI"/>
    <Hero />
  </div>
</template>

<script>
import Title from './components/MyTitle.vue'
import Hero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
