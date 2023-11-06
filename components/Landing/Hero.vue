<script setup>
import { Carousel, Slide, Navigation } from "vue3-carousel";
import "vue3-carousel/dist/carousel.css";
</script>
<template>
  <div class="w-full h-max animate-slide">
    <carousel :items-to-show="1" class="w-full h-full">
      <slide v-for="slide in 2" :key="slide" class="w-full h-full">
        <div class="relative w-full h-full">
          <span
            class="absolute top-0 left-0 z-0 w-full h-full bg-midnight-950 bg-opacity-80"
          >
            <div class="flex items-center justify-center w-full h-full">
              <div>
                <div class="text-white">
                  <h3 class="text-xl font-semibold animate-slideInDown">
                    CREATIVE & INNOVATIVE
                  </h3>
                  <h1 class="text-[80px] font-extrabold animate-zoomIn">
                    Creative & Innovative <br />
                    Digital Solution
                  </h1>
                </div>
                <div class="mt-5 font-semibold text-white">
                  <nuxt-link
                    class="px-8 py-3 rounded-sm bg-primary-600 hover:bg-primary-800"
                    to="/"
                    >Free Quote</nuxt-link
                  >
                  <nuxt-link
                    class="px-8 py-3 ml-5 border border-white rounded-sm hover:bg-white hover:text-black"
                    to="/"
                    >Contact Us</nuxt-link
                  >
                </div>
              </div>
            </div>
          </span>
          <img
            :src="`/img/carousel-${slide}.jpg`"
            class="z-0 object-cover w-full"
            alt=""
          />
        </div>
      </slide>

      <template #addons>
        <navigation />
      </template>
    </carousel>
  </div>
</template>

<style>
.carousel__prev,
.carousel__next,
.carousel__prev--active,
.carousel__next--active {
  @apply text-white border border-white rounded-full w-12 bg-midnight-950 bg-opacity-50 h-12 hover:text-white hover:bg-opacity-80;
}
.carousel__icon {
  @apply w-32;
}
.carousel__prev--disabled,
.carousel__next--disabled {
  display: none;
}
</style>
