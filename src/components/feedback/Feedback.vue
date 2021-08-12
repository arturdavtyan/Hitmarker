<template>
  <div class="relative flex flex-col lg:flex-row items-start">
    <div class="relative flex-grow flex-shrink-0 max-w-4xs">
      <div class="absolute right-7 w-22 h-22 bg-primary flex justify-center items-center">
        <img :src="require('@/assets/images/apostroph.png')" alt="Apos">
      </div>
      <div class="absolute top-12 left-0 bottom-0 right-0 -z-1 bg-dark"></div>
      <img class="" :src="require('@/assets/images/image 49.png')" alt="Feedback">
    </div>
    <div class="flex flex-auto justify-between pt-37 pl-11 pb-6 relative">
      <div class="text-3xl text-blue-900 font-medium">
        <span>What pepole say</span>
      </div>
      <div class="flex">
        <div class="flex justify-center items-center bg-primary-100 rounded-full w-12 h-12 mr-6 cursor-pointer">
          <img :src="require('@/assets/images/Left.png')" alt="Left">
        </div>
        <div class="flex justify-center items-center w-12 h-12 bg-primary rounded-full cursor-pointer">
          <img :src="require('@/assets/images/Right.png')" alt="Right">
        </div>
      </div>

      <div class="box absolute top-full -left-6 right-0 border border-gray-200 bg-white">
        <div class="flex justify-between items-center relative">
          <div class="py-6 px-9 mb-7">
            <div class="mb-2 text-2xl text-blue-900 font-medium">
              <span>Darrell Steward</span>
            </div>
            <div class="text-xl text-blue-900 mb-7">
              <span>CEO, ESport.</span>
            </div>
            <div class="text-sm text-gray-300 pr-6">
              <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .box {
    box-shadow: 4px 20px 100px rgba(8, 21, 38, 0.06);

    & > div::after {
      content: '';
      position: absolute;
      top: -1px;
      bottom: -1px;
      left: -1px;
      width: 12px;
      background-color: #FF6810;
    }
  }
</style>
