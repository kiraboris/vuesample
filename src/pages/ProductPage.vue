<template>
  <div class="product-page">
    <AppHeader />
    <main class="main-content">
      <!-- Reuse the ProductCard component -->
      <ProductCard
        title="Botanical Mix Passion Fruit with Milk Thistle Exact"
        description="Campuran Botani Buah Markisa dengan ekstrack ‘Milk Thistle’"
      />
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
  name: "ProductPage",
  components: {
    AppHeader,
    ProductCard,
  },
};
</script>


<style src="../styles/main.css"></style>
