<template>
  <div class="mainWrapper w-100 vh-100 bg-dark">
    <header class="container">
      <AppTitle/>
      <AppHero/>
    </header>

  </div>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from './components/AppHero.vue'
export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<style lang="scss">
@import '../node_modules/bootstrap/scss/bootstrap.scss'
</style>