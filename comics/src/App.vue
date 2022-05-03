<template>
  <div id="app">
    <!-- header -->
    <SiteHeader />
    <!-- main -->
    <SiteMain />
    <!-- footer -->
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'
import SiteFooter from './components/SiteFooter.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter
  }
}
</script>

<style lang="scss">
@import './assets/sass/style.scss'
</style>
