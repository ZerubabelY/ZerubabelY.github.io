<template>
  <div
    class="z-50 flex items-center justify-between py-2.5 text-white bg-midnight-950 px-5"
  >
    <div class="flex items-center gap-x-5">
      <button>
        <Icon name="solar:phone-bold" />
        <span>+251939064200</span>
      </button>
      <button>
        <Icon name="ic:baseline-email" />
        <span>test@gmail.com</span>
      </button>
    </div>
    <div class="flex items-center gap-x-2">
      <nuxt-link
        class="flex items-center justify-center border border-white rounded-full w-7 h-7 hover:bg-white hover:text-black"
        href="/"
        ><Icon name="mdi:twitter" />
      </nuxt-link>
      <nuxt-link
        class="flex items-center justify-center border border-white rounded-full w-7 h-7 hover:bg-white hover:text-black"
        href="/"
      >
        <Icon name="ri:facebook-fill" /> </nuxt-link
      ><nuxt-link
        class="flex items-center justify-center border border-white rounded-full w-7 h-7 hover:bg-white hover:text-black"
        href="/"
      >
        <Icon name="ri:linkedin-fill" />
      </nuxt-link>
      <nuxt-link
        class="flex items-center justify-center border border-white rounded-full w-7 h-7 hover:bg-white hover:text-black"
        href="/"
        ><Icon name="ri:instagram-fill"
      /></nuxt-link>
    </div>
  </div>
</template>
