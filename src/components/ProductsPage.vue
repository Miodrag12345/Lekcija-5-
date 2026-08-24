<template>
  <div>
    <div>Hello world</div>
    <ProductsDetails :productList="productList" />
  </div>
</template>

<script>
import ProductsDetails from "@/components/ProductDetails.vue";

export default {
  name: 'ProductsPage',
  components: {
    ProductsDetails
  },

}
</script>