import type { LandingTeamMember } from '#build/components';
<script setup>
defineProps({
  member: {
    type: Object,
    required: true,
  },
});
</script>
<template>
  <div class="w-full h-full overflow-hidden rounded bg-primary-50">
    <div class="relative w-full overflow-hidden h-[85%]">
      <div
        class="relative w-full h-full max-h-[450px] overflow-hidden hover:bg-primary-950 bg-opacity-60"
      >
        <img
          class="object-cover w-full h-full transition-all duration-300 hover:scale-110"
          :src="member.image"
          :alt="`${member.name} image`"
        />
        <div class="absolute flex flex-col top-2 right-2 gap-y-3">
          <nuxt-link
            class="flex items-center justify-center w-10 h-10 transition-all duration-300 rounded cursor-pointer bg-primary-600 hover:scale-110"
            href=""
            ><Icon class="text-2xl text-white" name="mdi:twitter"
          /></nuxt-link>
          <nuxt-link
            class="flex items-center justify-center w-10 h-10 transition-all duration-300 rounded cursor-pointer bg-primary-600 hover:scale-110"
            href=""
            ><Icon class="text-2xl text-white" name="ri:facebook-fill"
          /></nuxt-link>
          <nuxt-link
            class="flex items-center justify-center w-10 h-10 transition-all duration-300 rounded cursor-pointer bg-primary-600 hover:scale-110"
            href=""
            ><Icon class="text-2xl text-white" name="ri:instagram-fill"
          /></nuxt-link>
          <nuxt-link
            class="flex items-center justify-center w-10 h-10 transition-all duration-300 rounded cursor-pointer bg-primary-600 hover:scale-110"
            href=""
            ><Icon class="text-2xl text-white" name="ri:linkedin-fill"
          /></nuxt-link>
        </div>
      </div>
    </div>
    <div class="py-4 text-center">
      <h4 class="text-2xl text-primary text-primary-600 font-[700]">
        {{ member.name }}
      </h4>
      <p class="m-0 text-base uppercase text-secondary-600">
        {{ member.role }}
      </p>
    </div>
  </div>
</template>
