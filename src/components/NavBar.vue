<template>
  <div>
    <!-- Navbar container -->
    <div
      class="w-full h-[88px] relative flex items-center justify-between px-4 md:px-10 md:mb-12"
    >
      <!-- Logo -->
      <img
        class="w-[180.78px] h-[42px] md:w-[180px] md:h-[42px]"
        src="../assets/logo-light.png.png"
        alt="Logo"
      />

      <div class="hidden md:flex space-x-8">
        <div
          class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
        >
          About Us
        </div>
        <div class="relative">
          <div
            class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
          >
            Our Services
          </div>
          <div
            class="w-[11.31px] h-[11.31px] absolute top-[10px] right-0 origin-top-left -rotate-45 border-l border-b border-white"
          ></div>
        </div>
        <div
          class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
        >
          Work with Us
        </div>
        <div
          class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
        >
          Blog
        </div>
      </div>

      <div class="md:hidden">
        <button @click="toggleMenu" class="focus:outline-none">
          <svg
            class="w-6 h-6 text-white"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16m-7 6h7"
            ></path>
          </svg>
        </button>
      </div>

      <div
        class="hidden md:flex items-center justify-center pl-[27px] pr-[7.36px] py-px"
      >
        <div
          class="w-4 h-4 bg-gradient-to-br from-[#665dcd] via-[#5fa4e6] to-[#d2ab67] rounded-lg"
        ></div>
        <div
          class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide ml-2"
        >
          Get In Touch
        </div>
      </div>
    </div>

    <div v-if="isMenuOpen" class="md:hidden px-4 py-2 space-y-2 bg-gray-900">
      <div
        class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
      >
        About Us
      </div>
      <div
        class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
      >
        Our Services
      </div>
      <div
        class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
      >
        Work with Us
      </div>
      <div
        class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide"
      >
        Blog
      </div>
      <div class="flex items-center justify-center py-2">
        <div
          class="w-4 h-4 bg-gradient-to-br from-[#665dcd] via-[#5fa4e6] to-[#d2ab67] rounded-lg"
        ></div>
        <div
          class="text-white text-[15px] font-normal font-inter uppercase leading-normal tracking-wide ml-2"
        >
          Get In Touch
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      isMenuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    },
  },
};
</script>

<style></style>
