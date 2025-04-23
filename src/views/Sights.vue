<script setup>
import Footer from "@/components/Footer.vue";
import s6 from "@/assets/images/八二三.jpg";
import s7 from "@/assets/images/民俗文化村.jpg";
import s3 from "@/assets/images/金酒.jpg";
import s8 from "@/assets/images/得月樓.jpg";
import s2 from "@/assets/images/莒光樓.jpg";
import s5 from "@/assets/images/陽宅老街.jpg";
import s1 from "@/assets/images/翟山坑道.jpg";
import s4 from "@/assets/images/慈湖.jpg";
</script>

<template>
  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-20">
        <h1 class="text-3xl font-medium title-font mb-4 text-gray-900 tracking-widest">周邊景點</h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-2xl">
          探索金門，漫遊閩南建築群的歲月記憶
        </p>
      </div>
      <div class="flex flex-wrap -m-4">
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s1"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">翟山坑道</p>
              <p class="mb-4">
                戰時開鑿的地下水道，結合自然潮汐與人工建設，昔日運兵重要據點，如今成為金門必訪的軍事景點。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s2"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">莒光樓</p>
              <p class="mb-4">
                融合傳統與現代的建築風格，象徵忠勇精神，登高遠望可俯瞰金門港灣與市區景致，是金門代表性地標。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s3"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">
                金門酒廠（高粱文化館）
              </p>
              <p class="mb-4">
                金門高粱酒發源地，館內展示釀酒技術與歷史故事，還能試飲高粱，深刻體驗金門的酒文化與風土。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s4"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">慈湖三角堡</p>
              <p class="mb-4">
                位於慈湖旁的觀景堡壘，曾為軍事瞭望哨，現成熱門打卡地，可欣賞海景與夕陽，是文青系旅人最愛。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s5"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">陽翟老街</p>
              <p class="mb-4">
                懷舊街道保留 60
                年代風貌，曾為電影《軍中樂園》拍攝地，街道氛圍獨特，是網美與影迷熱愛之地。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s6"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">八二三戰史館</p>
              <p class="mb-4">
                紀念金門歷史上關鍵的 823
                砲戰，館內展出豐富戰役資料、武器與影像，是感受戰地歷史的重要據點。
              </p>
            </div>
          </div>
        </div>
        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s7"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">金門民俗文化村</p>
              <p class="mb-4">
                保存完整的古厝建築群，展示傳統婚禮、生活器物與民俗文化，是了解金門人文歷史的絕佳場域。
              </p>
            </div>
          </div>
        </div>

        <div class="p-4 lg:w-1/2">
          <div
            class="h-full flex sm:flex-row flex-col items-center sm:justify-start justify-center text-center sm:text-left"
          >
            <img
              alt="team"
              class="flex-shrink-0 rounded-lg w-48 h-48 object-cover object-center sm:mb-0 mb-4"
              :src="s8"
            />
            <div class="flex-grow sm:pl-8">
              <p class="title-font font-medium text-lg text-gray-900 mb-4">水頭聚落（得月樓）</p>
              <p class="mb-4">
                昔日僑民回鄉興建的洋樓群，保留閩南與西洋融合建築，漫步其中彷彿走進時光隧道。
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <Footer />
</template>
