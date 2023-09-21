<!-- <script setup>
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
</template> -->

<script setup></script>
<template>
  <div class="container mx-auto md:p-10 p-5">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
      <div>
        <img src="../assets/cactus6-free-img.jpg" class="" alt="" />

        <div class="hidden md:grid md:grid-cols-4 items-center mt-4">
          <img
            src="../assets/cactus6-free-img.jpg"
            class="h-32 mx-auto"
            alt=""
          />
          <img
            src="../assets/cactus2-free-img.jpg"
            class="h-32 mx-auto"
            alt=""
          />
          <img
            src="../assets/cactus6-free-img.jpg"
            class="h-32 mx-auto"
            alt=""
          />
          <img
            src="../assets/cactus2-free-img.jpg"
            class="h-32 mx-auto"
            alt=""
          />
        </div>
      </div>
      <div class="md:flex-1 px-4">
        <h2
          class="mb-2 leading-tight tracking-tight font-bold text-gray-800 text-2xl md:text-3xl"
        >
          Lorem ipsum dolor, sit amet consectetur, adipisicing elit.
        </h2>
        <p class="text-gray-500 text-sm">
          By
          <a href="#" class="text-lime-600 hover:underline">ABC Company</a>
        </p>

        <div class="flex items-center space-x-4 my-4">
          <div>
            <div class="rounded-lg bg-gray-100 flex py-2 px-3">
              <span class="text-lime-400 mr-1 mt-1">$</span>
              <span class="font-bold text-lime-600 text-3xl">25</span>
            </div>
          </div>
          <div class="flex-1">
            <p class="text-green-500 text-xl font-semibold">Save 12%</p>
            <p class="text-gray-400 text-sm">Inclusive of all Taxes.</p>
          </div>
        </div>

        <p class="text-gray-500">
          Lorem ipsum, dolor sit, amet consectetur adipisicing elit. Vitae
          exercitationem porro saepe ea harum corrupti vero id laudantium enim,
          libero blanditiis expedita cupiditate a est.
        </p>

        <div class="flex py-4 space-x-4">
          <div class="flex items-center border border-lime-600 rounded">
            <span class="pl-2">Qty:</span>
            <select name="" id="" class="px-3 focus:outline-none">
              <option value="1">1</option>
              <option value="2">2</option>
              <option value="3">3</option>
              <option value="4">4</option>
            </select>
          </div>

          <button
            type="button"
            class="px-6 py-2 font-semibold rounded-xl bg-lime-600 hover:bg-green-500 text-white"
          >
            Add to Cart
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
