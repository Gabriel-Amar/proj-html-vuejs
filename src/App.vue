<template>
  <div id="app">
    <app-header/>
    <app-jumbo/>
    <app-main/>
    <app-footer/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppJumbo from './components/AppJumbo.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppJumbo,
    AppMain,
    AppFooter
  }
}
</script>

<style lang="scss">
@import "./assets/style/general.scss";
@import "./assets/style/vars.scss";



</style>
