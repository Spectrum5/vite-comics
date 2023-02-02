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
  <div class="container">
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<style>
  /* aggiunta stile css */
.container {
  width: 65%;
  margin: 0 auto;
}

</style>