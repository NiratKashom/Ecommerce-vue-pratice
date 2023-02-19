<template>
  <v-app>
    <Navbar class="index" />
    <Dashboard />
    <Footer />
  </v-app>
</template>

<script>
import Dashboard from '@/components/Dashboard.vue';
import Footer from '@/components/Footer.vue';
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'Home',

  components: {
    Dashboard,
    Footer,
    Navbar
  },
}
</script>

<style scoped>
.index {
  z-index: 9999
}
</style>
