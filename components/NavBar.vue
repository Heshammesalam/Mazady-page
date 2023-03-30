<template>
  <div class="bg-gradient-to-r from-pink-600 to-pink-900">
    <header class="px-10">
      <nav
        class="bg-gradient-to-r from-pink-600 to-pink-900 flex flex-wrap items-center justify-between w-full py-4 md:py-0 text-lg text-white"
      >
        <div class="flex items-center">
          <div
            class="dropdown inline-block bg-orange-500 h-8 rounded-full mx-5 sm:mx-1 my-2 sm:mt-3"
          >
            <button
              class="font-semibold py-3 px-4 rounded inline-flex items-center relative h-full focus:outline-none"
            >
              <svg
                class="fill-current h-4 w-4"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="#fff"
              >
                <path
                  d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                  fill="#fff"
                  class=""
                />
              </svg>
              <span class="mr-1 text-white mb-2">عربي</span>
            </button>
            <ul
              class="dropdown-menu absolute hidden text-white pt-1 bg-orange-500 rounded-md"
            >
              <li class="">
                <a
                  class="rounded-ttext-white hover:bg-pink-600 py-2 px-4 block whitespace-no-wrap"
                  href="#"
                  >عربي</a
                >
              </li>
              <li class="">
                <a
                  class="text-white hover:bg-pink-600 py-2 px-4 block whitespace-no-wrap"
                  href="#"
                  >Turky</a
                >
              </li>
              <li class="">
                <a
                  class="text-white hover:bg-pink-600 rounded-b py-2 px-4 block whitespace-no-wrap"
                  href="#"
                  >English</a
                >
              </li>
            </ul>
          </div>
          <ul
            class="pt-4 text-base text-gray-700 md:flex md:justify-between md:pt-0"
          >
            <li class="material-icons text-white mx-3 cursor-pointer">
             favorite
            </li>
            <li class="material-icons text-white mx-3 cursor-pointer">
              notifications
            </li>
            <li class="material-icons text-white mx-3 cursor-pointer">book</li>
          </ul>
        </div>

        <svg
          xmlns="http://www.w3.org/2000/svg"
          id="menu-button"
          class="h-6 w-6 cursor-pointer md:hidden block mt-2"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          @click="toggleBar()"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>

        <div class="hidden w-full md:flex md:items-center md:w-auto" id="menu">
          <ul
            class="pt-4 text-base text-gray-700 md:flex md:justify-between md:pt-0"
          >
            <li>
              <a
                class="md:p-4 py-2 text-white block hover:text-purple-400"
                href="#"
                >حسابي</a
              >
            </li>
            <li>
              <a
                class="md:p-4 py-2 text-white block hover:text-purple-400"
                href="#"
                >مشترياتي</a
              >
            </li>
            <li>
              <a
                class="md:p-4 py-2 text-white block hover:text-purple-400"
                href="#"
                >التصنيفات</a
              >
            </li>
            <li>
              <a
                class="md:p-4 py-2 text-white block hover:text-purple-400"
                href="#"
                >الرئسية</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>
  </div>
</template>

<script>
// const button = document.querySelector('#menu-button');

export default {
  methods: {
    toggleBar() {
      const menu = document.querySelector("#menu");
      menu.classList.toggle("hidden");
    },
  },
};
</script>

<style>
.dropdown:hover .dropdown-menu {
  display: block;
}
</style>
