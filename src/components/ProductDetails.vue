<template>
  <ul>
    <li v-for="product in productList" :key ="product.id">
      {{product.name}}-${{product.price}}
    </li>
  </ul>
</template>


<script>

export default {
  name:"ProductsDetails",
  inject:["productList"],

}
</script>