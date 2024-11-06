<template>
  <div>
    <AppHeader />
    <h1>About Us</h1>
    <p>This is the about page.</p>
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";

export default {
  name: "AboutPage",
  components: {
    AppHeader,
  },
};
</script>

<style src="../styles/main.css"></style>
<style scoped>
/* Add AboutPage styles */
</style>
