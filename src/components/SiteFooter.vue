<template>
  <div >
    <FooterTop />
    <FooterMain />
    <FooterBottom />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import FooterTop from '@/components/FooterTop.vue'
import FooterMain from '@/components/FooterMain.vue'
import FooterBottom from '@/components/FooterBottom.vue'

export default {
  name: 'FooterComponent',
  components: {
    FooterTop,
    FooterMain,
    FooterBottom
  }
}
</script>

<style lang="scss">

</style>