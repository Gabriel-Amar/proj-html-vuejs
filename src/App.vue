<template>
  <div id="app">
    <app-header/>
    <app-jumbo/>
    <app-intro/>
    <app-courses/>
    <app-main/>
    <app-footer/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppJumbo from './components/AppJumbo.vue'
import AppIntro from './components/AppIntro.vue'
import AppCourses from './components/AppCourses.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppJumbo,
    AppIntro,
    AppCourses,
    AppMain,
    AppFooter,
  }
}
</script>

<style lang="scss">
@import "./assets/style/general.scss";
@import "./assets/style/vars.scss";



</style>
