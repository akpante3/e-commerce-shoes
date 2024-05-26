<template>
  <div id="page-wrap">
    <ProductsGrid :products="products" />
    <!-- <h1>this is product page</h1> -->
  </div>
</template>

<script>
import { products } from '../fake-data';
import ProductsGrid from '../components/ProductsGrid.vue';

export default {
    name: 'ProductsPage',
    components: {
      ProductsGrid,
    },
    data() {
      return {
        products,
      };
    }
};
</script>

