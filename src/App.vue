<template>
  <Blog :fontSize="fontSize" />
  <Blog :fontSize="fontSize" />
</template>

<script setup lang="ts">
import { ref } from 'vue';
import Blog from './Blog.vue';

const fontSize = ref(2);
</script>

<style scoped lang="scss"></style>
