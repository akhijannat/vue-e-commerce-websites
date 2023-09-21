<script setup></script>
<template>
  <section
    class="bg-green-100 bg-cover border bg-no-repeat bg-center h-screen"
    style="
      background-image: url('../assets/bg.jpg');
      border-bottom-right-radius: 40%;
    "
  >
    <div
      class="container mx-auto text-center flex flex-col justify-center items-center py-20 px-10"
    >
      <p>Best Quality Plants</p>
      <h1 class="text-7xl font-bold my-10">
        Amazing Variety Of <br />
        Plants Starting Just $6
      </h1>
      <button
        class="bg-lime-600 font-semibold text-white py-3 px-5 rounded ease-in-out duration-300 hover:scale-105 border hover:bg-transparent hover:border-lime-600 hover:text-lime-600 uppercase"
      >
        Shop Now
      </button>
    </div>
  </section>

  <section class="text-center">
    <div class="grid grid-cols-1 md:grid-cols-5 items-center gap-5 mt-5">
      <div></div>
      <div
        class="bg-gradient-to-tr from-green-200 to-white py-5 rounded-xl shadow-xl"
      >
        <h1 class="text-5xl">100 %</h1>
        <p>Plants Collection</p>
      </div>
      <div
        class="bg-gradient-to-tr from-green-200 to-white py-5 rounded-xl shadow-xl"
      >
        <h1 class="text-5xl">100 +</h1>
        <p>Free Shipping</p>
      </div>
      <div
        class="bg-gradient-to-tr from-green-200 to-white py-5 rounded-xl shadow-xl"
      >
        <h1 class="text-5xl">100%</h1>
        <p>Money Back</p>
      </div>
      <div></div>
    </div>
  </section>
</template>
