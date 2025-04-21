<script setup>
import { computed, ref, onMounted } from "vue";
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
import logo from "@/assets/images/Ludao_logo.png";
import b1 from "@/assets/images/b1.jpg";
import b2 from "@/assets/images/b2.jpg";
import i1 from "@/assets/images/i1.jpg";
import i2 from "@/assets/images/i2.jpg";
import c1 from "@/assets/images/c1.jpg";
import c2 from "@/assets/images/c2.jpg";
</script>

<template>
  <div class="px-4">
    <Navbar />
    <section class="mb-5">
      <div class="flex justify-center py-30">
        <img :src="logo" alt="logo" class="w-[50%]" />
      </div>
      <div class="w-full flex justify-end">
        <div class="flex w-[70%]">
          <img :src="b1" alt="b1" class="w-[50%]" />
          <img :src="b2" alt="b2" class="w-[50%]" />
        </div>
      </div>
    </section>
    <section class="py-30 bg-gray-200 my-5">
      <div class="w-[90%] flex justify-center m-auto">
        <div class="w-1/2 pr-10 flex flex-col justify-center">
          <p class="text-3xl mb-4 font-serif">金門陸島觀光飯店</p>
          <p>
            金門唯一的觀光飯店，座落于福建清新之鄉─金寧鄉，與廈門隔海相望，可遠眺都市繁華，又能享受鄉間小鎮的寧靜，是您遠離塵囂來到金門旅遊的最佳度假住宿選擇。
          </p>
        </div>
        <div class="w-1/2 flex flex-row">
          <div class="w-[50%] pr-4">
            <img :src="i1" alt="i1" />
          </div>
          <div class="w-[50%]">
            <img :src="i2" alt="i2" />
          </div>
        </div>
      </div>
    </section>
    <section class="my-10 h-[90vh] relative">
      <div class="">
        <div class="flex flex-col items-center p-2 m-30">
          <p class="text-3xl pb-2 font-serif">Service</p>
          <hr />
          <span class="text-xl text-gray-700">免費私人停車場 | 附設餐廳 | 全館免費 WiFi</span>
        </div>
        <div class="flex space-x-12 mb-8">
          <div class="w-[50%]">
            <p class="text-3xl pb-2 font-serif">About</p>
            <hr class="mb-4 text-gray-400"/>
            <span class="text-gray-800"
              >金門陸島酒店 Ludao Hotel
              以福建土樓為原型打造出充滿在地特色的外觀，內部裝潢則是中式傳統加上南洋風情混搭出令人放鬆自在的氛圍，讓每個到來的旅人都能夠擺脫煩憂。</span
            >
          </div>
          <img :src="c1" alt="c1" class="w-[20%] rounded shadow" />
        </div>
        <div class="flex space-x-12 justify-end">
          <img :src="c2" alt="c2" class="w-[25%] rounded shadow-xl" />
          <div class="w-[50%]">
            <p class="text-3xl pb-2 font-serif">Welcome</p>
            <hr class="mb-4 text-gray-400"/>
            <span class="text-gray-800"
              >Ludao Hotel
              提供二至三人房型，房間分有VIP包廂房、單床式雙人房，更有貼心專為年長者設計的長青房，裡頭空間寬敞，衛浴設備增加許多扶手設施，讓您全家大小都可安心地在此入住，旅店內每間房型所使用的家具為專門訂製的「藤家私」家具，藤製家具散發著慵懶清爽的氣息，讓旅人能以最舒服愜意的姿態在金門渡過美好難忘的假期時光。</span
            >
          </div>
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
          style="filter: grayscale(1) contrast(1.2) opacity(0.5)"
        ></iframe>
      </div>
      <div class="container px-5 py-24 mx-auto flex">
        <div
          class="lg:w-1/3 md:w-1/2 bg-white rounded-lg p-8 flex flex-col md:ml-auto w-full mt-10 md:mt-0 relative z-10 shadow-md"
        >
          <h2 class="text-gray-900 text-lg mb-1 font-medium title-font">聯絡我們</h2>
          <p class="leading-relaxed mb-5 text-gray-600">留下您的寶貴意見</p>
          <div class="relative mb-4">
            <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
            <input
              type="email"
              id="email"
              name="email"
              class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
            />
          </div>
          <div class="relative mb-4">
            <label for="message" class="leading-7 text-sm text-gray-600">意見說明/message</label>
            <textarea
              id="message"
              name="message"
              class="w-full bg-white rounded border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"
            ></textarea>
          </div>
          <button
            class="text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg"
          >
            提交
          </button>
          <p class="text-xs text-gray-500 mt-3">
            Chicharrones blog helvetica normcore iceland tousled brook viral artisan.
          </p>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>
