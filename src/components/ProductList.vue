<script setup>
import Hero from "../components/Hero.vue";

const detailsBtn =
  "text-right border border-lime-600 font-semibold transition duration-200 rounded-sm py-1 px-3 text-lime-600 hover:shadow-xl";
</script>
<template>
  <Hero />
  <section class="container mx-auto py-20 px-10">
    <h1 class="text-2xl md:text-6xl font-semibold pb-2 text-center">
      Featured Plants
    </h1>
    <p class="text-center">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    </p>

    <div class="h-1 bg-lime-600 w-52 mx-auto my-3"></div>

    <div class="grid grid-cols-1 md:grid-cols-4 gap-5 mt-5 md:mt-10">
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/plant1-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>

      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/plant3-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/plant4-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/plant5-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/plant6-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/cactus2-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/cactus4-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
      <div class="border hover:shadow-lg cursor-pointer">
        <img
          src="../assets/cactus6-free-img.jpg"
          class="h-[300px] w-auto"
          alt=""
        />
        <div class="p-5">
          <span class="text-gray-500 italic text-sm">Plant</span>
          <h4>Boncellensis Secullant</h4>
          <p>$34.00</p>
          <div class="flex justify-between items-center">
            <div class="flex items-center mt-2">
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
              <img src="../assets/star.svg" class="h-4" alt="" />
            </div>
            <button :class="detailsBtn" type="submit">View Details</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
