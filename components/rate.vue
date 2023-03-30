<template>
  <div class="flex flex-col sm:flex-row  gap-0 sm:gap-10 px-2 sm:px-12 w-full mt-6 drop-shadow-xl PY-6">
    <div class="w-full sm:w-1/3 mx-0 sm:mx-4"></div>
    <div class="w-full sm:w-2/3 bg-white MX-0 SM:mx-4 overflow-hidden">
      <div class="mx-4 mt-3 flex justify-between items-center p-1">
        <button class="text-pink-700 font-bold text-2xl">اضافة تقييم +</button>
        <h2 class="font-bold text-2xl">التقيمات</h2>
      </div>
      <div class="bg-white rounded-md p-4 mt-5 shadow-lg shadow-gray-500/50">
        <div class="border-b-2 pb-3" v-for="i in 5" :key="i">
          <div class="flex justify-between items-center gap-1 mt-2">
            <div
              class="p-2 text-center h-8 w-16 flex justify-center items-center font-bold rounded-sm"
            >
              <span class="material-icons relative text-yellow-400 text-4xl"
                >star
              </span>
            </div>
            <div class="flex justify-end p-2 w-1/2 rounded-sm">
              <div class="text-right">
                <span> Ahmed Reda</span><br />
                <span class="text-gray-500 text-sm">
                  السيارة مطابقة للمواصفات والسعر الفوري مناسب لها</span
                >
              </div>
              <div class="w-12 h-12">
                <img src="../static/profile.png" alt="" class="w-full mx-2" />
              </div>
            </div>
          </div>
          <div class="flex justify-between items-center mr-12 ml-4">
            <span>22-4-2021 8:22:30</span>
            <button class="text-pink-700">
              ابلاغ <span class="material-icons">flag</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
