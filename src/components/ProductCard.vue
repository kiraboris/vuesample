<template>
  <div class="product-card">
    <h1>{{ title }}</h1>
    <p>{{ description }}</p>
    <button class="buy-now">Buy Now</button>
  </div>
</template>

<script>
export default {
  name: "ProductCard",
  props: {
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
/* Add styles for product cards here */
</style>
