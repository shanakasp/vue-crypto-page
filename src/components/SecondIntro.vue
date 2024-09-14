<template>
  <div
    class="flex flex-col md:flex-row items-center justify-between w-full h-auto md:h-[400px] mt-24 py-2 md:py-0"
  >
    <!-- Left Side (Image) -->
    <div class="flex justify-center w-full md:w-1/2">
      <img
        class="w-full max-w-xs sm:max-w-sm md:max-w-md lg:max-w-lg xl:max-w-2xl object-contain mx-auto"
        src="../assets/div2.png"
        alt="Left Side Image"
      />
    </div>

    <!-- Right Side (Text) -->
    <div
      class="flex flex-col justify-center w-full md:w-1/2 px-6 md:px-8 lg:px-12 mt-12 md:mt-0 text-center md:text-left"
    >
      <h2
        class="text-3xl md:text-4xl lg:text-5xl font-extrabold text-white mb-8"
      >
        Empowering Your Business with Digital Solutions
      </h2>
      <p class="mb-6 text-lg md:text-xl text-white leading-relaxed">
        We provide innovative market-making solutions for crypto projects,
        helping them enhance liquidity and drive sustainable growth in the
        evolving digital asset space. Partner with us to stay ahead in the
        competitive landscape.
      </p>
      <button
        class="mt-8 bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600 transition-all duration-300"
      >
        Learn More
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "SecondIntro",
};
</script>

<style scoped>
/* Custom margin adjustments for more spacing on larger screens */
@media (min-width: 768px) {
  .flex-col {
    margin-top: 8%; /* Extra top margin for larger screens */
  }
}
</style>
