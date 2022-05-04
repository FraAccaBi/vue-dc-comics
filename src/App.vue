<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain />
    <SiteFooter/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from '@/components/SiteMain.vue'
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
