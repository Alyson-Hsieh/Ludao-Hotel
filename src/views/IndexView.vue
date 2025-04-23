<script setup>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import logo from "@/assets/images/Ludao_logo.png";
import b1 from "@/assets/images/b1.jpg";
import c1 from "@/assets/images/c1.jpg";
import i5 from "@/assets/images/i5.jpg";
import i7 from "@/assets/images/i7.jpg";
import r5 from "@/assets/images/r5.jpg";
</script>

<template>
  <Navbar class="fixed z-50" />
  <div class="px-4">
    <section class="mb-5">
      <div class="flex justify-center py-30">
        <img :src="logo" alt="logo" class="w-[50%]" />
      </div>
      <div class="w-full flex justify-end">
        <div class="flex w-[70%]">
          <img :src="b1" alt="b1" class="w-[50%]" />
          <img :src="i5" alt="i5" class="w-[50%]" />
        </div>
      </div>
    </section>
    <section class="p-20 lg:p-30 bg-stone-200 my-5 flex justify-between gap-8 flex-col lg:flex-row">
      <div class="lg:w-[50%] flex flex-col justify-center items-center lg:items-start">
        <p class="text-3xl mb-4 font-serif">金門陸島觀光飯店</p>
        <p>
          金門唯一的觀光飯店，座落于福建清新之鄉─金寧鄉，與廈門隔海相望，可遠眺都市繁華，又能享受鄉間小鎮的寧靜，是您遠離塵囂來到金門旅遊的最佳度假住宿選擇。
        </p>
      </div>
      <div class="lg:w-[50%]">
        <img :src="i7" alt="i7" />
      </div>
    </section>
    <section class="my-10 relative">
      <div class="flex space-x-12 mb-24">
        <div class="p-4 sm:m-auto sm:text-center">
          <p class="text-3xl pb-2 font-serif">Service</p>
          <hr class="mb-4 text-gray-400" />
          <span class="text-gray-800 sm:text-xl">免費私人停車場 | 附設餐廳 | 全館免費 WiFi</span>
        </div>
      </div>
      <div class="flex space-x-12 mb-24">
        <div class="p-4 sm:w-[50%]">
          <p class="text-3xl pb-2 font-serif">About</p>
          <hr class="mb-4 text-gray-400" />
          <span class="text-gray-800"
            >金門陸島酒店 Ludao Hotel
            以福建土樓為原型打造出充滿在地特色的外觀，內部裝潢則是中式傳統加上南洋風情混搭出令人放鬆自在的氛圍，讓每個到來的旅人都能夠擺脫煩憂。</span
          >
        </div>
        <img :src="c1" alt="c1" class="h-[30vh] rounded shadow hidden sm:block" />
      </div>
      <div class="flex space-x-12 justify-end">
        <img :src="r5" alt="r5" class="h-[30vh] rounded shadow-xl hidden sm:block" />
        <div class="p-4 sm:w-[50%]">
          <p class="text-3xl pb-2 font-serif">Welcome</p>
          <hr class="mb-4 text-gray-400" />
          <span class="text-gray-800"
            >Ludao Hotel
            提供二至三人房型，房間分有VIP包廂房、單床式雙人房，更有貼心專為年長者設計的長青房，裡頭空間寬敞，衛浴設備增加許多扶手設施，讓您全家大小都可安心地在此入住，旅店內每間房型所使用的家具為專門訂製的「藤家私」家具，藤製家具散發著慵懶清爽的氣息，讓旅人能以最舒服愜意的姿態在金門渡過美好難忘的假期時光。</span
          >
        </div>
      </div>
    </section>
    <section class="text-gray-600 body-font relative">
      <div class="absolute inset-0 bg-gray-300">
        <iframe
          width="100%"
          height="100%"
          frameborder="0"
          marginheight="0"
          marginwidth="0"
          title="map"
          scrolling="no"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3632.3024225970435!2d118.31003311006172!3d24.44029076185251!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3414a26573d02933%3A0x2e111cc95a422d19!2z6YeR6ZaA6Zm45bO26YWS5bqX!5e0!3m2!1szh-TW!2stw!4v1745170948387!5m2!1szh-TW!2stw"
          style="filter: contrast(1.2) opacity(0.5)"
        ></iframe>
      </div>
      <div class="container px-5 py-24 mx-auto flex">
        <div
          class="lg:w-1/3 md:w-1/2 bg-white rounded-lg p-8 flex flex-col md:ml-auto w-full mt-10 md:mt-0 relative z-10 shadow-xl"
        >
          <h2 class="font-serif text-black text-2xl mb-8 font-medium title-font text-center">
            飯店聯絡資訊
          </h2>
          <p class="font-serif text-gray-900 mb-2">電話：082-320048</p>
          <p class="font-serif text-gray-900 mb-2">傳真：082-375936</p>
          <p class="font-serif text-gray-900 mb-2">手機：0911-665-175</p>
          <p class="font-serif text-gray-900 mb-2">地址：金門縣金寧鄉下埔下90號</p>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>
