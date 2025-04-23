<script setup>
const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth",
  });
};
</script>
<template>
  <header class="w-full sticky top-0 z-50">
    <nav class="max-w-8xl mx-auto flex justify-end items-center px-4 py-6">
      <button
        @click="scrollToTop"
        type="button"
        class="mt-4 text-md cursor-pointer hover:text-amber-700 transition font-serif tracking-wide border-b"
      >
        Back to top
      </button>
    </nav>
  </header>
</template>
