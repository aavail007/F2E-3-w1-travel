<template>
  <div class="home">
    <div class="banner bg-cover bg-no-repeat w-full">
      <div class="relative w-full flex flex-col justify-center items-center md:p-20 lg:p-32 xl:p-44">
        <h4 class="text-5xl text-white font-bold text-shadow-md">想去哪裡玩?</h4>
        <p class="text-white font-bold my-3 text-shadow">這裡共有上千個活動及美食等著你去一同體驗</p>
        <div class="relative md:w-4/5 lg:w-3/5 mt-10">
          <input class="rounded-full w-full py-3 px-4 bg-white border-6 border-gray4" placeholder="搜尋關鍵字..." />
          <span class="absolute right-3 transform top-2/4 -translate-y-1/2 btn-primary text-white">
            <i class="fas fa-search"></i>
            搜尋
          </span>
        </div>
      </div>
    </div>
    <!-- 縣市快選 -->
    <section class="relative">
      <!-- 圖案 -->
      <div class="absolute hidden lg:block w-10/12 h-80 xl:h-96 bg-gray6 rounded-br-8xl"></div>
      <div class="absolute hidden lg:block w-72 h-72 -inset-x-48 -bottom-56 rounded-full bg-c-primary"></div>
      <img class="absolute hidden lg:block h-24 xl:h-40 -bottom-14 left-10 xl:-bottom-28 xl:left-18" src="@/assets/img/travel-people.png">
      <!--  -->
      <div class="container relative px-10 mx-auto grid grid-cols-2 lg:grid-cols-6 xl:grid-cols-7 gap-6 lg:gap-10 xl:gap-12 pt-20">
        <div class="col-span-2 lg:col-span-1 xl:col-span-2 flex items-center justify-center">
          <div>
            <h3 class="text-2xl xl:text-3xl text-black font-bold">縣市快選</h3>
            <div class="text-gray5 mt-3 text-sm">Choose Cities</div>
          </div>
        </div>
        <div class="bg-white rounded-2xl p-8 filter drop-shadow-2xl flex-row text-center">
          <div class="bg-c-primary rounded-full w-24 h-24 lg:w-16 lg:h-16 xl:w-20 xl:h-20 text-center flex items-center m-auto">
            <img class="w-2/3 m-auto" src="@/assets/img/place/city-icon1.png" />
          </div>
          <div class="mt-4 font-bold text-black">北部</div>
        </div>
        <div class="bg-white rounded-2xl p-8 filter drop-shadow-2xl flex-row text-center">
          <div class="bg-c-primary rounded-full w-24 h-24 lg:w-16 lg:h-16 xl:w-20 xl:h-20 text-center flex items-center m-auto">
            <img class="w-2/3 m-auto" src="@/assets/img/place/city-icon2.png" />
          </div>
          <div class="mt-4 font-bold text-black">中部</div>
        </div>
        <div class="bg-white rounded-2xl p-8 filter drop-shadow-2xl flex-row text-center">
          <div class="bg-c-primary rounded-full w-24 h-24 lg:w-16 lg:h-16 xl:w-20 xl:h-20 text-center flex items-center m-auto">
            <img class="w-2/3 m-auto" src="@/assets/img/place/city-icon3.png" />
          </div>
          <div class="mt-4 font-bold text-black">南部</div>
        </div>
        <div class="bg-white rounded-2xl p-8 filter drop-shadow-2xl flex-row text-center">
          <div class="bg-c-primary rounded-full w-24 h-24 lg:w-16 lg:h-16 xl:w-20 xl:h-20 text-center flex items-center m-auto">
            <img class="w-2/3 m-auto" src="@/assets/img/place/city-icon4.png" />
          </div>
          <div class="mt-4 font-bold text-black">東部</div>
        </div>
        <div class="bg-white rounded-2xl p-8 filter drop-shadow-2xl flex-row text-center">
          <div class="bg-c-primary rounded-full w-24 h-24 lg:w-16 lg:h-16 xl:w-20 xl:h-20 text-center flex items-center m-auto">
            <img class="w-2/3 m-auto" src="@/assets/img/place/city-icon5.png" />
          </div>
          <div class="mt-4 font-bold text-black">離島</div>
        </div>
      </div>
      
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home'
};
</script>

<style lang="scss" scoped>
.banner {
  background-image: url('../assets/img/banner.png');
}
</style>
