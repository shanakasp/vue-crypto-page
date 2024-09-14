<template lang="">
  <div>
    <div
      class="w-full md:w-[1056px] h-auto md:h-[889.39px] relative mx-auto px-5 md:px-0 md:top-20"
    >
      <!-- Title -->
      <div
        class="absolute top-12 md:top-16 left-0 md:left-[168.55px] text-center text-white text-2xl md:text-[57px] font-medium font-['Inter'] leading-tight md:leading-[78px] mb-4 md:mb-8"
      >
        We are in a good company
      </div>

      <!-- Subtitle -->
      <div
        class="absolute w-full md:w-[603.75px] top-28 md:top-36 left-0 md:left-[226.22px] text-center text-white text-base md:text-xl font-normal font-['Inter'] leading-relaxed md:leading-7 px-4 md:px-0 mb-6"
      >
        Our partnerships have delivered great value to our projects and we’re
        happy to share some of their feedback below
      </div>

      <!-- Main Section -->
      <div
        class="absolute w-full md:w-[1056px] top-[180px] md:top-[240px] left-0"
      >
        <!-- Navigation Arrows (Placeholder for Functionality) -->
        <div class="w-full flex justify-center items-center h-[58px] mb-4">
          <div
            class="w-[58px] h-[58px] flex items-center justify-center cursor-pointer"
          >
            <div class="w-[57.02px] h-[57.02px]"></div>
          </div>
          <div
            class="w-[58px] h-[58px] flex items-center justify-center cursor-pointer rotate-180"
          >
            <div class="w-[57.02px] h-[57.02px]"></div>
          </div>
        </div>

        <!-- Feedback Section -->
        <div
          class="bg-[#141619] w-full h-auto p-6 md:p-12 md:w-[1056px] md:h-[455px] rounded-lg"
        >
          <div class="mx-auto max-w-[682px]">
            <div
              class="text-center text-white text-base md:text-[26px] font-normal leading-relaxed md:leading-[44px] mb-6"
            >
              Since 2019, Gravity team has been an astounding market maker for
              Bitkub. They have proven themselves to be one of the most
              consistent, committed, and driven market makers on our exchange.
              Gravity Team has contributed high-quality volume and has proven to
              be a very reliable and trustworthy partner. We strongly advocate
              Gravity Team as they have been an indispensable part of our
              market-making team.
            </div>
            <div class="mt-4 text-center text-white text-lg font-bold mb-2">
              Atthakrit Chimplapibul
            </div>
            <div class="mt-2 text-center text-white text-sm font-light mb-4">
              Co-founder & CEO of Bitkub
            </div>
            <div class="flex justify-center items-center">
              <div class="border-l border-gray-600 h-8 mb-2"></div>
              <img
                class="ml-4"
                src="../assets/logoBibucket.png"
                alt="Bitkub Logo"
              />
            </div>
          </div>
        </div>

        <!-- Dots Navigation -->
        <div class="flex justify-center items-center mt-6 mb-6">
          <div
            class="w-2 h-2 bg-gradient-to-br from-[#665dcd] via-[#5fa4e6] to-[#d2ab67] rounded-full mx-1"
          ></div>
          <div class="w-2 h-2 bg-[#333333] rounded-full mx-1"></div>
          <div class="w-2 h-2 bg-[#333333] rounded-full mx-1"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutCompanySite",
};
</script>

<style>
/* Responsive Styles */
@media (max-width: 768px) {
  .absolute {
    position: static;
  }
  .text-center {
    text-align: center;
  }
  .mb-4 {
    margin-bottom: 1rem;
  }
  .mb-6 {
    margin-bottom: 1.5rem;
  }
  .mt-6 {
    margin-top: 1.5rem;
  }
  .p-6 {
    padding: 1.5rem;
  }
  .p-12 {
    padding: 3rem;
  }
  .w-full {
    width: 100%;
  }
  .h-auto {
    height: auto;
  }
}
</style>
