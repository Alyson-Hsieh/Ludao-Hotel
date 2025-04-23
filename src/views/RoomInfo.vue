<script setup>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import r1 from "@/assets/images/r1.jpg";
import r2 from "@/assets/images/r2.jpg";
import r3 from "@/assets/images/r3.jpg";
import r4 from "@/assets/images/r4.jpg";


</script>

<template>
  <Navbar class="fixed z-50" />
  <section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-wrap justify-center -mx-4 -mb-10 text-center">
      <div class="sm:w-1/2 mb-10 px-4">
        <div class="rounded-lg h-64 overflow-hidden">
          <!-- <img alt="content" class="object-cover object-center h-full w-full" src="https://dummyimage.com/1201x501"> -->
          <img :src="r1" alt="r1" class="object-cover object-center h-full w-full" />
        </div>
        <h2 class="title-font text-2xl font-medium text-gray-900 mt-6 mb-3">行政套房(一大床)</h2>
        <p class="leading-relaxed text-base">定價$ 15800假日$ 5500平日$ 5000</p>
        <button class="flex cursor-pointer mx-auto mt-6 text-white bg-amber-500  border-0 py-2 px-5 focus:outline-none hover:bg-amber-600  rounded">瞭解更多</button>
      </div>
      <div class="sm:w-1/2 mb-10 px-4">
        <div class="rounded-lg h-64 overflow-hidden">
          <img :src="r2" alt="r2" class="object-cover object-center h-full w-full" />

        </div>
        <h2 class="title-font text-2xl font-medium text-gray-900 mt-6 mb-3">典雅客房(一大一小床)</h2>
        <p class="leading-relaxed text-base">定價$ 10800假日$ 3800平日$ 3300</p>
        <button class="flex cursor-pointer mx-auto mt-6 text-white bg-amber-500  border-0 py-2 px-5 focus:outline-none hover:bg-amber-600  rounded">瞭解更多</button>
      </div>
      <div class="sm:w-1/2 mb-10 px-4">
        <div class="rounded-lg h-64 overflow-hidden">
          <!-- <img alt="content" class="object-cover object-center h-full w-full" src="https://dummyimage.com/1201x501"> -->
          <img :src="r3" alt="r3" class="object-cover object-center h-full w-full" />
        </div>
        <h2 class="title-font text-2xl font-medium text-gray-900 mt-6 mb-3">精緻客房(兩小床)</h2>
        <p class="leading-relaxed text-base">定價$ 6600假日$ 3300平日$ 2700</p>
        <button class="flex cursor-pointer mx-auto mt-6 text-white bg-amber-500  border-0 py-2 px-5 focus:outline-none hover:bg-amber-600  rounded">瞭解更多</button>
      </div>
      <div class="sm:w-1/2 mb-10 px-4">
        <div class="rounded-lg h-64 overflow-hidden">
          <img :src="r4" alt="r4" class="object-cover object-center h-full w-full" />

        </div>
        <h2 class="title-font text-2xl font-medium text-gray-900 mt-6 mb-3">精英客房(一大床)</h2>
        <p class="leading-relaxed text-base">定價$ 7800假日$ 3300平日$ 2700</p>
        <button class="flex cursor-pointer mx-auto mt-6 text-white bg-amber-500  border-0 py-2 px-5 focus:outline-none hover:bg-amber-600  rounded">瞭解更多</button>
      </div>
    </div>
  </div>
</section>
<Footer class="fixed -z-50" />
</template>
