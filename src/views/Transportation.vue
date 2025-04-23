<script setup>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <div class="flex flex-col text-center w-full my-20">
    <h1 class="text-3xl font-medium title-font mb-4 text-gray-900 tracking-widest font-serif">
      交通指引
    </h1>
  </div>
  <section class="bg-white p-6 md:p-10 rounded-lg shadow-md text-gray-800 max-w-4xl mx-auto my-10">
    <div class="mb-8">
      <h2 class="text-2xl font-semibold mb-4">地理位置</h2>
      <p class="leading-relaxed text-lg text-gray-700">
        酒店地理位置便利，位於金門大街上，周邊即有超市可供購物，距離金城鎮中心僅約 1 公里，
        前往水頭碼頭亦僅需 15 分鐘車程。無論您是來金門觀光旅遊，或是經常往返廈金的商務人士，
        <span class="font-medium">金門陸島觀光酒店</span> 都是您理想的住宿選擇。
      </p>
    </div>

    <h2 class="text-2xl font-semibold mb-4">航空資訊</h2>

    <p class="mb-4">空運：台北、台中、台南、高雄每天均有班機直飛來回金門。</p>

    <div class="mb-4">
      <h3 class="font-semibold">機場資訊</h3>
      <p>機場名稱：交通部民用航空局－金門航空站</p>
      <p>地址：金門縣金湖鎮尚義機場2號</p>
      <p>服務電話：</p>
      <ul class="list-disc ml-6">
        <li>人工：886-82-322381、886-82-313694</li>
        <li>語音：886-82-322383、886-82-313666</li>
      </ul>
    </div>

    <div class="mb-4">
      <h3 class="font-semibold">航空公司資訊</h3>
      <ul class="space-y-2 mt-2">
        <li>
          <span class="font-medium">🛫 立榮航空：</span>金門縣金湖鎮尚義機場2號｜886-82-324501
        </li>
        <li>
          <span class="font-medium">🛫 華信航空：</span>金門縣金湖鎮尚義機場2號｜886-82-328000
        </li>
        <li>
          <span class="font-medium">🛫 遠東航空：</span>金門縣金湖鎮尚義機場2號｜886-82-372688
        </li>
      </ul>
    </div>

    <p class="text-sm text-gray-500 mt-6">※ 以上交通資訊僅供參考，如有任何問題請來電洽詢。</p>
  </section>
  <!-- Google Map 嵌入 -->
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
          聯絡資訊
        </h2>
        <p class="font-serif text-gray-900 mb-2">電話：082-320048</p>
        <p class="font-serif text-gray-900 mb-2">傳真：082-375936</p>
        <p class="font-serif text-gray-900 mb-2">手機：0911-665-175</p>
        <p class="font-serif text-gray-900 mb-2">地址：金門縣金寧鄉下埔下90號</p>
      </div>
    </div>
  </section>
  <Footer />
</template>
