<template>
  <div class="home-page">
    <AppHeader />
    <main class="main-content">
      <div class="product-info">
        <ProductCard
          title="Botanical Mix Passion Fruit with Milk Thistle Exact"
          description="Campuran Botani Buah Markisa dengan ekstrack ‘Milk Thistle’"
        />
      </div>
      <div class="product-image">
        <div class="image-placeholder"></div>
      </div>
    </main>
  </div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";
import ProductCard from "../components/ProductCard.vue";

export default {
  name: "HomePage",
  components: {
    AppHeader,
    ProductCard,
  },
};
</script>

<style src="../styles/main.css"></style>
<style scoped>
/* Add your home page styles here */
</style>
