<template>
  <div class="flex flex-col sm:flex-row justify-center  sm:justify-between  px-4  sm:px-10 h-auto sm:h-14  ">
    <div class="logo w-full sm:w-72 h-16 sm:h-full">
      <img src="../static/logo-top.png" alt="" class="w-full h-full" />
    </div>
    <div class="flex w-full sm:w-3/5 mb-2">
      <button class="bg-gradient-to-l from-pink-600 to-pink-900 rounded-md rounded-r-none px-6 focus:outline-none" >
        <span class="material-icons text-3xl text-white">search</span>
      </button>
      <input type="text" name="" id="" class="bg-pink-300 w-2/3 sm:w-3/4 px-3 focus:outline-none" />
      
      <div class="dropdown relative bg-pink-300 rounded-md rounded-l-none text-white text-sm mx-1 flex justify-center items-center w-1/3 sm:w-1/4 h-14 sm:h-auto">
            
        <button
              class=" text-gray-700 font-semibold py-2 px-4 rounded inline-flex items-center focus:outline-none h-full sm:h-auto"
            >
            <svg
              class="fill-current h-4 w-4"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 20 20"
            >
              <path
                d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
              />
            </svg>
              <span class="mr-1 text-[10px] sm:text-sm"> مزاد مباشر متعدد</span>
            </button>
            
          </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
