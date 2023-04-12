<template>
  <div class="mainWrapper w-100 vh-100 bg-dark">
    <header class="container">
      <AppTitle/>
      
    </header>

  </div>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
export default {
  name: 'App',
  components: {
    AppTitle,
  }
}
</script>

<style lang="scss">
@import '../node_modules/bootstrap/scss/bootstrap.scss'
</style>