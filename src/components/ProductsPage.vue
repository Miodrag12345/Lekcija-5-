<template>
  <div>
    <DiscountedProducts />
    <ProductsDetails />
  </div>
</template>

<script>
import ProductsDetails from "@/components/ProductDetails.vue";
import DiscountedProducts from "@/components/DiscountedProducts.vue";

export default {
  name: 'ProductsPage',
  components: {
    DiscountedProducts,
    ProductsDetails
  },

}
</script>