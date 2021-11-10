<template>
  <div class="home bg-contain bg-no-repeat h-screen flex flex-col justify-center items-center">
    <h4 class="text-5xl text-white font-bold text-shadow-md">想去哪裡玩?</h4>
    <p class="text-white font-bold my-3 text-shadow">這裡共有上千個活動及美食等著你去一同體驗</p>
    <div class="relative w-2/5 mt-10">
      <input class="rounded-full w-full py-3 px-4 bg-white border-6 border-gray4" placeholder="搜尋關鍵字..." />
      <span class="absolute right-3 transform top-2/4 -translate-y-1/2 btn-primary text-white">
        <i class="fas fa-search"></i>
        搜尋
      </span>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home'
};
</script>

<style lang="scss" scoped>
.home {
  background-image: url('../assets/img/banner.png');
}
</style>
