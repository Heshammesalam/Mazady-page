<template>
  <div class="flex gao-0 sm:gap-10 px-0 sm:px-12 w-full mt-6 drop-shadow-xl PY-6">
    <div class="w-full sm:w-1/3 mx-0 sm:mx-4"></div>
    <div class="w-full sm:w-2/3 bg-white mx-0 sm:mx-4">
      <div class="text-end mx-4 sm:mx-10 mt-3">
        <h2 class="font-bold text-2xl">الشحن والمتابعة</h2>
      </div>
      <div class="relative">
        <div
          class="slides-container-2 flex snap-x snap-mandatory overflow-hidden space-x-2 rounded scroll-smooth before:w-[45vw] before:shrink-0 after:w-[45vw] after:shrink-0 md:before:w-0 md:after:w-0 mx-0 sm:mx-10 my-10"
        >
          <div
            class="slide aspect-square h-full flex-shrink-0 snap-center rounded"
            v-for="i in 5"
            :key="i"
          >
            <div class="max-w-xs h-full bg-white">
              <div class="w-full">
                <img
                  class="rounded-t-lg w-full hover:opacity-80"
                  src="../static/card-img.png"
                  alt=""
                />
              </div>
              <div class="p-2 text-end">
                <h3 class="font-bold">سيارة سريعة بي ام دبليو</h3>
                <p class="font-bold">تصنيع 2021 حالة جيده</p>
                <div class="flex justify-between items-center">
                  <span class="text-pink-700 text-2xl font-bold">$ 500</span
                  ><span class="text-gray-400">بدايه المزاد</span>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="absolute top-[50%] sm:top-0 left-0 h-full items-center  md:flex">
          <button
            role="button"
            class="prev px-2 py-2 rounded-full bg-neutral-100 text-neutral-900 group"
            aria-label="prev"
            @click="prev2()"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-5 h-5 group-active:-translate-x-2 transition-all duration-200 ease-linear"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15.75 19.5L8.25 12l7.5-7.5"
              />
            </svg>
          </button>
        </div>
        <div class="absolute top-[50%] sm:top-0 right-0 h-full items-center  md:flex">
          <button
            role="button"
            class="next px-2 py-2 rounded-full bg-neutral-100 text-neutral-900 group"
            aria-label="next"
            @click="next2()"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-5 h-5 group-active:translate-x-2 transition-all duration-200 ease-linear"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M8.25 4.5l7.5 7.5-7.5 7.5"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    next2() {
      const slidesContainer = document.querySelector(".slides-container-2");
      const slideWidth = slidesContainer.querySelector(".slide").clientWidth;

      slidesContainer.scrollLeft += slideWidth;
    },
    prev2() {
      const slidesContainer = document.querySelector(".slides-container-2");
      const slideWidth = slidesContainer.querySelector(".slide").clientWidth;
      slidesContainer.scrollLeft -= slideWidth;
    },
  },
};
</script>

<style></style>
