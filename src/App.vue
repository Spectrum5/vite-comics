<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue"
import AppFooter from "./components/AppFooter.vue"

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    
  },

  data() {
    return {
    }
  }
}
</script>

<template>
  <!-- creazione template html -->

  <AppHeader />
  <AppMain />
  <AppFooter />

</template>

<style>
  /* aggiunta stile css */


</style>