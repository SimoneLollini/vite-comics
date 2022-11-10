<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
import SiteFooter from "./components/SiteFooter.vue";




export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,

  }
}
</script>

<template>
  <SiteHeader />
  <!-- /end site-header -->

  <SiteMain />
  <!-- /end site-header -->

  <SiteFooter />
  <!-- /end site-header -->

</template>

<style scoped>

</style>
