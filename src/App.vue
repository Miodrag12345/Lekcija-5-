<template>

  <products-page :products-list="productList" />

</template>

<script>

import ProductsPage from "@/components/ProductsPage.vue";

export default {
  name: 'App',
  components: {ProductsPage},
  data: () => ({
    productList: [
      {
        name: "HTML Course",
        price: 150,
        length: "3 months"
      },
      {
        name: "CSS Course",
        price: 120,
        length: "2 months"
      },
      {
        name: "JavaScript Course",
        price: 200,
        length: "4 months"
      },
      {
        name: "React Course",
        price: 250,
        length: "5 months"
      },
      {
        name: "Node.js Course",
        price: 220,
        length: "4 months"
      }
    ]
  })
}
</script>

