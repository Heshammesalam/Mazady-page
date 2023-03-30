<template>
  <div class="flex flex-col-reverse sm:flex-row gap-10 px-1 sm:px-12 w-full drop-shadow-xl mt-5">
    <div class="mx-0 sm:mx-4 overflow-hidden w-[100%] sm:w-1/3 ">
      <div class="bg-white rounded-md p-3 shadow-lg shadow-gray-500/50 w-full">
        <div
          class="bg-gray-200 text-gray-500 flex justify-between p-3 rounded-sm"
        >
          <div class="font-bold">5000</div>
          <div>القيمة الابتدائية</div>
        </div>
        <div
          class="bg-gray-200 text-gray-500 flex justify-between p-3 rounded-sm mt-3"
        >
          <div class="font-bold">5000</div>
          <div>القيمة التقريبيه</div>
        </div>
        <div
          class="bg-gray-200 text-gray-500 flex justify-between p-3 rounded-sm mt-3"
        >
          <div class="font-bold">5000</div>
          <div>العربون</div>
        </div>

        <div
          class="bg-gray-200 text-gray-500 flex justify-between p-3 rounded-sm mt-3"
        >
          <div class="font-bold">5000</div>
          <div>سعر الشراء الفوري</div>
        </div>

        <div
          class="bg-gray-200 text-gray-500 flex justify-between p-3 rounded-sm mt-3"
        >
          <div class="font-bold">5000</div>
          <div>قيمة ذياده المزاد</div>
        </div>
      </div>
      <div class="bg-white rounded-md p-3 mt-5 shadow-lg shadow-gray-500/50">
        <div class="text-right mb-2 text-xl font-semibold">
          <h6>المزادات المفضلة</h6>
          <div class="flex justify-end items-center" v-for="i in 3" :key="i">
            <div class="w-full">
              <span class="text-gray-600 text-sm">سيارة سريعة بي ام دبليو</span
              ><br />
              <span class="text-gray-600 text-sm"
                >تصنيع 2021 حلة جيدة السيارة</span
              ><br />
              <span class="text-gray-600 text-sm">سريعة بي ام دبلية 2021</span
              ><br />
              <span class="text-gray-600 text-sm">سريعة بي ام دبلية 2021</span
              ><br />
              <div
                class="flex justify-between items-center text-gray-400 text-sm"
              >
                <span>$500</span>
                <div class="flex items-center">
                  <span>اعلي سعر</span>
                  <span class="material-icons">monetization_on</span>
                </div>
              </div>
            </div>
            <div class="w-52 h-32 bg-gray-600 ml-3 rounded-md p-3">
              <div class="flex items-start justify-between">
                <div
                  class="relative bg-black/20 text-white px-4 py-2 text-sm text-right after:absolute after:content-[attr(data-label)] after:-bottom-[40%] after:left-[54px] after:h-6 after:w-[5rem] after:bg-yellow-500 after:text-white after:text-center"
                  data-label="مزاد مباشر"
                >
                  <span
                    class="material-icons text-green-800 absolute -top-1 -right-1 font-bold"
                    >adjust</span
                  ><br />
                  <span>live</span><br />
                  <span>now</span>
                </div>
                <div
                  class="w-8 h-8 bg-white flex justify-center items-center rounded-full"
                >
                  <span class="material-icons text-red-700">favorite</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="mx-0 sm:mx-4 w-full sm:w-2/3">
      <div class="bg-white text-right p-6 rounded-md">
        <h2 class="text-gray-800 font-bold text-2xl mb-2">
          ارسل رساله الي البائع
        </h2>
        <p class="text-gray-600 mb-2">
          يمكنك في وقت البث المباشر ارسال رسالة الي البائع للاستفسار
        </p>
        <div class="w-full flex justify-end items-center">
          <button
            class="bg-gradient-to-l from-pink-600 to-pink-900 mx-2 rounded-full w-10 h-10 flex items-center justify-center focus:outline-none"
          >
            <span class="material-icons text-lg text-white mx-1">send</span>
          </button>
          <input
            type="text"
            class="w-11/12 bg-gray-200 rounded-3xl mt-2 mb-2 text-right p-3 focus:outline-none"
            placeholder="اكتب سوالك"
          />
        </div>
      </div>
      <div class="bg-white text-right p-6 rounded-md mt-3">
        <h2 class="text-gray-800 font-bold text-2xl mb-4">تفاصيل المزاد</h2>
        <div class="flex justify-between">
          <div>
            <span> 200 قطعة</span><br />
            <span class="text-yellow-500 flex justify-center items-cente mt-2"
              ><span>صوت</span> <span class="material-icons">mic</span></span
            >
          </div>
          <div>
            <span
              class="flex justify-center items-center hover:text-violet-700 cursor-pointer"
              ><span>Mansoura, Egypt</span>
              <span class="material-icons ml-2">location_on</span></span
            ><br />
            <span
              class="flex justify-center items-center hover:text-violet-700 cursor-pointer"
              ><span>Mansoura, Egypt</span>
              <span class="material-icons ml-2">monetization_on</span></span
            ><br />
            <span
              class="flex justify-center items-center hover:text-violet-700 cursor-pointer"
              ><span>Mansoura, Egypt</span>
              <span class="material-icons ml-2">dashboard</span></span
            ><br />
          </div>
        </div>
        <hr />
        <div class="p-3">
          <h2 class="text-xl text-gray-700 font-bold">وصف</h2>
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
        <hr />
        <div class="p-3">
          <h2 class="text-xl text-gray-700 font-bold">
            سياسة الاستبدال والاسترجاع
          </h2>
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
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
