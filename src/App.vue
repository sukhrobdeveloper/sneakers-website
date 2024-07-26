<script setup>
import MyHello from './components/MyHello.vue'
</script>

<template>
  <div class="mb-40">
    <MyHello title="Nike" :price="1000" :isAdded="true" />
  </div>
  <div class="mb-40">
    <MyHello title="Nike" :price="1000" :isAdded="true" />
  </div>
</template>
