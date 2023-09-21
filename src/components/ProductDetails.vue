<script setup>
import { ref, onMounted } from "vue";
import { useRoute } from "vue-router";
import axios from "axios";

const productId = useRoute().params.id;
const product = ref(null);

onMounted(() => {
  axios.get(`https://dummyjson.com/products/${productId}`).then((response) => {
    product.value = response.data;
  });
});
</script>
<template>
  <div>
    <h1 class="text-3xl font-semibold mb-4">Product Details</h1>
    <div class="bg-white p-6 rounded shadow">
      <img
        :src="product.image"
        :alt="product.title"
        class="w-full h-64 object-cover mb-4"
      />
      <h2 class="text-xl font-semibold">{{ product.title }}</h2>
      <p class="text-gray-600 mb-4">{{ product.price }}</p>
      <p>{{ product.description }}</p>
    </div>
  </div>
</template>
