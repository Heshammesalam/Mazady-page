<template>
  <div
    class="flex flex-col-reverse sm:flex-row gap-10 px-1 sm:px-12 mt-4 sm:mt-16 w-full drop-shadow-xl"
  >
    <div class="mx-0 sm:mx-4 overflow-hidden w-[100%] sm:w-1/3">
      <div class="bg-white rounded-md p-3 shadow-lg shadow-gray-500/50">
        <div class="bg-gray-600 text-white flex justify-between p-3 rounded-sm">
          <div>22-4-2022</div>
          <div>تاريخ البث</div>
        </div>
        <div class="flex justify-between gap-1 mt-2">
          <div class="p-2 bg-gray-300 w-1/2 text-center h-24 rounded-sm">
            <h5 class="text-2xle text-violet-900 mb-2">
              القيمة الحالية بعد الضريبة
            </h5>
            <span class="text-2xle text-violet-900 mb-5"
              >$ <span class="text-3xl">5050</span></span
            >
          </div>
          <div class="p-2 bg-violet-900 w-1/2 text-center h-24 rounded-sm">
            <h5 class="text-2xle text-white mb-2">
              القيمة الحالية بعد الضريبة
            </h5>
            <span class="text-2xle text-white mb-5"
              >$ <span class="text-3xl">5050</span></span
            >
          </div>
        </div>
      </div>
      <div
        class="bg-white rounded-md py-10 px-3 mt-5 shadow-lg shadow-gray-500/50"
      >
        <div class="text-right mb-4 text-xl font-semibold">
          <h6>المتنافسون</h6>
        </div>
        <div
          class="flex justify-between items-center gap-1 mt-2"
          v-for="i in 5"
          :key="i"
        >
          <div
            class="p-2 bg-yellow-100 text-yellow-400 text-center h-8 w-16 flex justify-center items-center font-bold rounded-sm"
          >
            <span>$20</span>
          </div>
          <div class="flex justify-end p-2 w-1/2 rounded-sm">
            <div class="text-right">
              <span>اسم المزايد</span><br />
              <span class="text-gray-400 text-sm"> 23:52:0</span>
            </div>
            <div class="w-12 h-12">
              <img src="../static/profile.png" alt="" class="w-full mx-2" />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div
      class="mx-0 sm:mx-4 w-[100%] sm:w-2/3 mb-0 sm:mb-2 flex flex-col sm:flex-row sm:h-auto"
    >
      <div
        class="w-[100%] sm:w-[85%] bg-white border border-gray-200 rounded-lg mb-2"
      >
        <div class="relative">
          <img class="rounded-t-lg" :src="current_img" alt="" />

          <div
            class="inline-flex rounded-md shadow-sm absolute top-24 sm:top-6 right-6 sm:right-6  "
            role="group"
          >
            <button
              type="button"
              class="flex items-center justify-center px-4 py-2 text-sm font-medium text-white bg-black/30 border border-gray-200 rounded-l-lg hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 dark:bg-gray-700 dark:border-gray-600"
            >
              2322 <span class="material-icons">visibility</span>
            </button>
            <button
              type="button"
              class="px-4 py-2 text-sm font-medium text-white bg-black/30 border-t border-b border-gray-200 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700"
            >
              254554
            </button>
            <button
              type="button"
              class="flex items-center justify-center px-4 py-2 text-sm font-medium text-white bg-black/30 border border-gray-200 rounded-r-md hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700"
            >
              media
            </button>
          </div>

          <div class="inline-flex rounded-md shadow-sm absolute top-6 left-6" role="group">
            <button
              type="button"
              class="flex justify-center items-center r px-4 py-2 text-sm font-medium  text-white bg-black/30 w-14 h-14 rounded-full"
            >
             <span class="material-icons ">share</span>
             
            </button>
            <button
              type="button"
              class="flex justify-center mx-2 items-center px-4 py-2 text-sm font-medium   text-white bg-black/30 w-14 h-14 rounded-full  "
            >
             <span class="material-icons text-white ">favorite</span>
             
            </button>
            <button
              type="button"
              class="flex justify-center  items-center px-4 py-2 text-sm font-medium text-white bg-black/30 w-14 h-14 rounded-full  "
            >
             <span class="material-icons ">flag</span>
             
            </button>
          
          </div>
        </div>
        <div class="pb-3 shadow-lg shadow-slate-600">
          <div class="flex justify-end items-center">
            <div class="flex justify-center items-center font-bold rounded-sm">
              <span class="material-icons relative text-yellow-400 text-2xl"
                >star
              </span>
              <span class="material-icons relative text-yellow-400 text-2xl"
                >star
              </span>
              <span class="material-icons relative text-yellow-400 text-2xl"
                >star
              </span>
              <span class="material-icons relative text-yellow-400 text-2xl"
                >star
              </span>
            </div>
            <div class="flex justify-end p-2 rounded-sm">
              <div class="text-right">
                <span>احمد محمد السيد علي</span><br />
                <span class="text-gray-400 text-sm"> السعودية :الرياض</span>
              </div>
              <div class="relative">
                <img
                  src="../static/profile.png"
                  alt=""
                  class="w-12 h-12 mx-2"
                />
                <div
                  class="bg-white w-6 h-6 absolute -bottom-2 left-2 rounded-full flex items-center justify-center"
                >
                  <span class="material-icons text-red-800 text-lg">
                    favorite</span
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="text-end w-full p-3">
            <h2 class="font-bold text-gray-800">
              شراء مجموعة من اسيارات من موديل 1992
            </h2>
            <span>code 2525</span>
          </div>
          <div class="flex flex-col-reverse sm:flex-row justify-between p-2">
            <div class="flex justify-between mb-2 sm:mb-0">
              <button
                class="p-2 bg-gradient-to-l from-pink-600 to-pink-900 rounded-md px-8 focus:outline-none"
              >
                تاكيد
              </button>
              <input
                type="search"
                name=""
                id=""
                class="mx-2 rounded-md text-end"
                placeholder="اكتب المبلغ"
              />
            </div>
            <div class="flex justify-between mb-2 sm:mb-0">
              <button
                class="bg-pink-500/30 py-1 px-2 rounded-sm text-pink-900 font-bold mx-1"
              >
                $1000
              </button>
              <button
                class="bg-pink-500/30 py-1 px-2 rounded-sm text-pink-900 font-bold mx-1"
              >
                $1010
              </button>
              <button
                class="bg-pink-500/30 py-1 px-2 rounded-sm text-pink-900 font-bold mx-1"
              >
                $1020
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="w-[100%] sm:w-[15%] flex sm:flex-col">
        <div class="w-full p-1 mx-1" v-for="(img, i) in imgs" :key="i">
          <img
            :src="img"
            alt=""
            class="w-full rounded-md h-32"
            @click="changePic(img)"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      imgs: [
        require("../static/car-st.jpg"),
        require("../static/manheim_20.webp"),
        require("../static/BuyingService_AuctionTypes.jpg"),
        require("../static/maxresdefault.jpg"),
      ],
      current_img: null,
    };
  },
  methods: {
    changePic(img) {
      this.current_img = img;
    },
  },
  created() {
    this.current_img = this.imgs[0];
  },
};
</script>

<style scoped></style>
