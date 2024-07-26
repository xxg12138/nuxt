<!--  -->
<template>
  <div class="container">头部{{ data.ceshi }}</div>
</template>

<script setup lang="ts">
const data = defineProps<{
  ceshi: number;
}>();
</script>

<style lang="scss" scoped></style>
