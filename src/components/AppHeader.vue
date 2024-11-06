<template>
  <header class="header">
    <div class="logo">
      <span>KANJIN</span>
      <span class="pro">@PRO</span>
    </div>
    <nav class="navigation">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/product">Product</router-link>
      <router-link to="/reviews">Reviews</router-link>
    </nav>
    <div class="auth-buttons">
      <button class="login-btn">Login</button>
      <button class="signup-btn">Sign Up</button>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
/* Add your styles from the header section here */
</style>
