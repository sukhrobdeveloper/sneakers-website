<script setup>
defineProps({
  title: String,
  price: double,
  isAdded: Boolean
})
</script>

<template>
  <div class="product">
    <h2>Tovar: {{ title }}</h2>
    <h3>Narxi: {{ price }}</h3>
    <h3>isAdded: {{ isAdded }}</h3>
  </div>
</template>

<style scoped>
.product {
  border: 1px solid blue;
  padding: 10px;
  margin-bottom: 10px;
}
</style>
