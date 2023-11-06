<script setup>
onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});

const isScrolling = ref(false);
const handleScroll = () => {
  const header = document.querySelector("header");
  const scrollY = window.scrollY;
  if (scrollY > 40) {
    isScrolling.value = true;
  } else {
    isScrolling.value = false;
  }
};
</script>
<template>
  <header
    class="fixed left-0 z-50 flex items-center w-full px-20 transition-all duration-300 shadow"
    :class="
      isScrolling
        ? 'bg-white top-0 text-black py-2 h-24'
        : 'bg-transparent top-10 text-white h-28 py-0 border-b-[0.5px] border-gray-500'
    "
  >
    <div class="flex items-center justify-between w-full h-full">
      <div class="flex items-center gap-x-5">
        <nuxt-img src="/img/newLogo.png" width="80" />
        <h1
          class="text-[2.5rem] font-[900] leading-5"
          :class="!isScrolling ? 'text-white' : 'text-primary-600'"
        >
          AHAVA
        </h1>
      </div>
      <nav class="flex h-full text-lg font-semibold gap-x-5">
        <nuxt-link
          exact-active-class="relative text-primary-600 after:absolute after:w-full after:h-[2px] after:border-t-primary-600 after:border-t-[2px] after:bottom-0 after:left-0"
          class="relative flex items-center justify-center h-full hover:text-primary-600 hover:after:absolute hover:after:w-full hover:after:h-[2px] hover:after:border-t-primary-600 after:transition-all after:duration-500 hover:after:border-t-[2px] hover:after:bottom-0 after:left-0"
          to="/"
          >Home</nuxt-link
        >
        <nuxt-link
          exact-active-class="relative text-primary-600 after:absolute after:w-full after:h-[2px] after:border-t-primary-600 after:border-t-[2px] after:bottom-0 after:left-0"
          class="relative flex items-center justify-center h-full hover:text-primary-600 hover:after:absolute hover:after:w-full hover:after:h-[2px] hover:after:border-t-primary-600 after:transition-all after:duration-500 hover:after:border-t-[2px] hover:after:bottom-0 after:left-0"
          to="/about"
          >About</nuxt-link
        >
        <nuxt-link
          exact-active-class="relative text-primary-600 after:absolute after:w-full after:h-[2px] after:border-t-primary-600 after:border-t-[2px] after:bottom-0 after:left-0"
          class="relative flex items-center justify-center h-full hover:text-primary-600 hover:after:absolute hover:after:w-full hover:after:h-[2px] hover:after:border-t-primary-600 after:transition-all after:duration-500 hover:after:border-t-[2px] hover:after:bottom-0 after:left-0"
          to="/about"
          >Services</nuxt-link
        >
        <nuxt-link
          class="relative flex items-center justify-center h-full hover:text-primary-600 hover:after:absolute hover:after:w-full hover:after:h-[2px] hover:after:border-t-primary-600 after:transition-all after:duration-500 hover:after:border-t-[2px] hover:after:bottom-0 after:left-0"
          to="/about"
          >Contact</nuxt-link
        >
      </nav>
    </div>
  </header>
</template>
