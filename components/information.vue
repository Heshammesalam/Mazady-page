<template>
  <div class="flex flex-col sm:flex-row gap-10 px-1 sm:px-12 w-full drop-shadow-xl mb-4">
    <div class="mx-0 sm:mx-4 overflow-hidden w-full sm:w-1/3 ">
      <div class="bg-white rounded-md p-3 mt-7 shadow-lg shadow-gray-500/50 mb-3 ">
        <div class="text-right mb-2 text-xl font-semibold">
          <h6>البائعين المفضلين</h6>
        </div>
        <div class="flex justify-end items-center gap-1 mt-2" v-for="i in 3" :key="i">
          <div class="flex justify-end p-2 rounded-sm">
            <div class="text-right">
              <span>احمد محمد السيد علي</span><br />
              <span class="text-gray-400 text-sm"> السعودية :الرياض</span>
            </div>
            <div class="relative">
              <img src="../static/profile.png" alt="" class="w-16 h-16 mx-2" />
              <div
                class="bg-white w-8 h-8 absolute -bottom-2 left-2 rounded-full flex items-center justify-center"
              >
                <span class="material-icons text-red-800 text-lg">
                  favorite</span
                >
              </div>
            </div>
          </div>
        </div>
        
      </div>
    </div>

    <div class="bg-white text-end mx-0 sm:mx-4 w-full sm:w-2/3 p-6 mt-5">
      <h2 class="mb-5 font-bold text-2xl">تفاصيل المنتج</h2>

      <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
        <table
          class="w-full text-sm text-end text-gray-500 dark:text-gray-400"
        >
         
          <tbody>
            <tr class="bg-yellow-500/20 border-b">
            
                <td class="px-6 py-4 font-bold text-gray-900">1500</td>
                <td class="px-6 py-4 text-yellow-400 font-bold">العدد</td>
              
            </tr>
            <tr
            
            >
              
            <td class="px-6 py-4 font-bold text-gray-900"> 5885488</td>
            <td class="px-6 py-4 text-yellow-400 font-bold">رقم الهيكل</td>
              
            </tr>
            <tr class="bg-yellow-500/20 border-b">
              
                <td class="px-6 py-4 font-bold text-gray-900">الصين</td>
                <td class="px-6 py-4 text-yellow-400 font-bold">المنشا</td>
              
            </tr>
            <tr
             
            >
              
            <td class="px-6 py-4 font-bold text-gray-900">للايجار</td>
            <td class="px-6 py-4 text-yellow-400 font-bold">الحالة</td>
              
            </tr>
            <tr class="bg-yellow-500/20 border-b">
             
                <td class="px-6 py-4 font-bold text-gray-900">تسلا</td>
                <td class="px-6 py-4 text-yellow-400 font-bold">الماركة</td>
            
            </tr>
            <tr>
             
                <td class="px-6 py-4 font-bold text-gray-900">تسلا برو</td>
                <td class="px-6 py-4 text-yellow-400 font-bold">الموديل</td>
            
            </tr>
            <tr class="bg-yellow-500/20">
             
                <td class="px-6 py-4 font-bold text-gray-900">2021</td>
                <td class="px-6 py-4 text-yellow-400 font-bold">سنة المصنع</td>
            
            </tr>
          </tbody>
        </table>
      </div>
      <div class="p-3">
          <h2 class="text-xl text-yellow-400 font-bold mb-2">وصف</h2>
          <p class="text-gray-500">
            هذا النص هو مثال لنص يمكن أن يستبدل في نفس المساحة، لقد تم توليد هذا
            النص من مولد النص العربى، حيث يمكنك أن تولد مثل هذا النص أو العديد
            من النصوص الأخرى إضافة إلى زيادة عدد الحروف التى يولدها التطبيق. إذا
            كنت تحتاج إلى عدد أكبر من الفقرات يتيح لك مولد النص العربى زيادة عدد
            الفقرات كما تريد، النص لن يبدو مقسما ولا يحوي أخطاء لغوية، مولد النص
            العربى مفيد لمصممي المواقع على وجه الخصوص، حيث يحتاج العميل فى كثير
            من الأحيان أن يطلع على صورة حقيقية لتصميم الموقع.
          </p>
        </div>

        
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
