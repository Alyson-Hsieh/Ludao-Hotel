<script setup>
import Footer from "@/components/Footer.vue";
</script>

<template>
    <div class="flex flex-col text-center w-full mt-20 mb-8">
    <h1 class="text-3xl font-medium title-font  text-gray-900 tracking-widest font-serif">
      聯絡我們
    </h1>
  </div>
  <section class="text-gray-600 body-font relative">
    <div class="container px-5 pb-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-12">
        <!-- <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900">聯絡我們</h1> -->
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
          請留下您的寶貴意見，您的回饋是我們前進的動力。
        </p>
      </div>
      <div class="lg:w-1/2 md:w-2/3 mx-auto">
        <div class="flex flex-wrap -m-2">
          <div class="p-2 w-1/2">
            <div class="relative">
              <label for="name" class="leading-7 text-sm text-gray-600">姓名</label>
              <input
                type="text"
                id="name"
                name="name"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
          </div>
          <div class="p-2 w-1/2">
            <div class="relative">
              <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
              <input
                type="email"
                id="email"
                name="email"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
              />
            </div>
          </div>
          <div class="p-2 w-full">
            <div class="relative">
              <label for="message" class="leading-7 text-sm text-gray-600">意見描述</label>
              <textarea
                id="message"
                name="message"
                class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
              ></textarea>
            </div>
          </div>
          <div class="p-2 w-full">
            <button
              class="flex mx-auto text-white bg-amber-600 border-0 py-2 px-8 focus:outline-none hover:bg-amber-500 rounded text-lg cursor-pointer"
            >
              送出
            </button>
          </div>
          <div class="p-2 w-full pt-8 mt-8 border-t border-gray-200 text-center">
            <a class="text-amber-600">金門陸島觀光飯店</a>
            <p class="leading-normal my-5">感謝您的回饋，祝您有美好的一天！</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <Footer />
</template>
