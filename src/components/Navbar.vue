<script setup>
import logo from "@/assets/images/Ludao_logo.png";
import { ref } from "vue";

const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};

const closeMenu = () => {
  isMenuOpen.value = false;
};
</script>

<template>
  <!-- nav bar -->
  <header class="w-full sticky top-0 z-80 body-font">
    <nav class="max-w-7xl mx-auto flex justify-between items-center px-4 py-6">
      <!-- logo -->
      <RouterLink to="/" class="flex title-font font-medium items-end md:mb-0">
        <h1 class="text-2xl font-serif tracking-wide cursor-pointer">Ludao Hotel</h1>
      </RouterLink>

      <!-- Menu / Close 按鈕 -->
      <button
        @click="toggleMenu"
        class="text-2xl font-serif border-b-2 focus:outline-none cursor-pointer"
      >
        {{ isMenuOpen ? "Close" : "Menu" }}
      </button>
    </nav>

    <!-- 展開選單 -->
    <transition name="fade-slide">
      <div
        v-if="isMenuOpen"
        class="w-[100vw] h-auto sm:rounded-full bg-radial from-amber-300 from-10% to-gray-200 sm:w-[60vw] absolute sm:right-5 z-40 p-12 text-center sm:h-[60vw] flex items-center justify-center md:"
      >
        <!-- <RouterLink to="/" @click="closeMenu">
          <img :src="logo" alt="logo" class="mr-4 w-[40%] lg:w-[50%] hidden sm:block" />
        </RouterLink> -->
        <img :src="logo" alt="logo" class="mr-4 w-[40%] lg:w-[50%] hidden sm:block" />
        <ul class="space-y-8 text-lg font-serif text-stone-600">
          <li>
            <RouterLink
              to="/room"
              @click="closeMenu"
              class="hover:text-black text-xl hover:text-2xl sm:text-3xl sm:hover:text-4xl lg:text-4xl lg:hover:text-5xl hover:border-b-2"
              >客房介紹</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/sights"
              @click="closeMenu"
              class="hover:text-black text-xl hover:text-2xl sm:text-3xl sm:hover:text-4xl lg:text-4xl lg:hover:text-5xl hover:border-b-2"
              >周邊景點</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/transportation"
              @click="closeMenu"
              class="hover:text-black text-xl hover:text-2xl sm:text-3xl sm:hover:text-4xl lg:text-4xl lg:hover:text-5xl hover:border-b-2"
              >交通指引</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/contact"
              @click="closeMenu"
              class="hover:text-black text-xl hover:text-2xl sm:text-3xl sm:hover:text-4xl lg:text-4xl lg:hover:text-5xl hover:border-b-2"
              >聯絡我們</RouterLink
            >
          </li>
        </ul>
      </div>
    </transition>
    <!-- 遮罩 -->
    <transition name="fade">
      <div
        v-if="isMenuOpen"
        class="fixed inset-0 bg-black opacity-80 z-30"
        @click="closeMenu"
      ></div>
    </transition>
  </header>
</template>

<style scoped>
/* 淡入 + 滑動 + 放大動畫 */
.fade-slide-enter-active,
.fade-slide-leave-active {
  transition: all 1s ease;
}

.fade-slide-enter-from {
  opacity: 0;
  transform: translateY(-20px) scale(0.9);
}
.fade-slide-enter-to {
  opacity: 1;
  transform: translateY(0) scale(1);
}

.fade-slide-leave-from {
  opacity: 1;
  transform: translateY(0) scale(1);
}
.fade-slide-leave-to {
  opacity: 0;
  transform: translateY(-20px) scale(0.9);
}
</style>
