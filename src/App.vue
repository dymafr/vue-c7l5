<template>
  <Product :product="product" />
</template>

<script setup lang="ts">
import { reactive } from 'vue';
import Product from './Product.vue';
import ProductI from './interfaces/product.interface.ts';

const product: ProductI = reactive({
  available: true,
  price: 1500,
  name: 'Moto',
});
</script>

<style scoped lang="scss"></style>
