<template>
  <div id="app">
    <!-- <registration-home/> -->
    <home-banner/>
  </div>
</template>

<script>
// import RegistrationHome from './components/RegistrationForm.vue'
import HomeBanner from './components/HomeBanner.vue'

export default {
  name: 'App',
  components: {
    // RegistrationHome,
    HomeBanner,
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
