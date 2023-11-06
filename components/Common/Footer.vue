<template>
  <footer>
    <div
      class="px-20 mt-5 container-fluid bg-midnight-950 text-primary-50 wow fadeInUp"
      data-wow-delay="0.1s"
    >
      <div class="container">
        <div class="grid grid-cols-4 gap-x-10">
          <div class="col-span-1 footer-about">
            <div
              class="flex flex-col items-center justify-center h-full p-4 text-center bg-primary-600"
            >
              <nuxt-link href="index.html" class="navbar-brand">
                <nuxt-img
                  src="img/newLogo.png"
                  width="80"
                  class="p-2"
                  height="80"
                  alt=""
                />
                <h1 class="m-0 text-white">AHAVA</h1>
              </nuxt-link>
              <p class="mt-3 mb-4">
                Our mission is to develop cutting-edge software solutions that
                streamline and optimize business processes for organizations
                across various industries.
              </p>
              <form action="">
                <div class="flex items-center h-full">
                  <input
                    type="text"
                    class="p-3 border-white"
                    placeholder="Your Email"
                  />
                  <button class="box-border h-full px-3 bg-midnight-950">
                    Sign Up
                  </button>
                </div>
              </form>
            </div>
          </div>
          <div class="col-span-3">
            <div class="grid grid-cols-3 gap-x-10">
              <div class="pt-5 mb-5 col-md-12">
                <div class="relative pb-3 mb-4 section-title section-title-sm">
                  <h3
                    class="mb-0 text-primary-50 text-[28px] font-[700] h-14 animated_underline"
                  >
                    Get In Touch
                  </h3>
                </div>
                <!-- <div class="flex items-center mb-2 gap-x-2">
                  <i class="bi bi-geo-alt text-primary-600 me-2"></i>
                  <p class="mb-0">123 Street, New York, USA</p>
                </div> -->
                <div class="flex items-center mb-2 gap-x-2">
                  <Icon name="ic:baseline-email" class="text-primary-600" />
                  <p class="mb-0">AHAVA@gmail.com</p>
                </div>
                <div class="flex items-center mb-2 gap-x-2">
                  <Icon name="solar:phone-bold" class="me-0 text-primary-600" />
                  <p class="mb-0">+012 345 67890</p>
                </div>
                <div class="flex gap-x-3">
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
              <div class="pt-5 mb-5 col-md-12">
                <div class="relative pb-3 mb-4 section-title section-title-sm">
                  <h3
                    class="mb-0 text-primary-50 text-[28px] font-[700] h-14 animated_underline"
                  >
                    Quick Links
                  </h3>
                </div>
                <div class="flex flex-col justify-start">
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >Home</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >About Us</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Our
                    Services</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Meet
                    The Team</nuxt-link
                  >
                  <!-- <nuxt-link class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4" href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Latest
                    Blog</nuxt-link
                  > -->
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >Contact Us</nuxt-link
                  >
                </div>
              </div>
              <div class="pt-5 mb-5 col-md-12">
                <div class="relative pb-3 mb-4 section-title section-title-sm">
                  <h3
                    class="mb-0 text-primary-50 text-[28px] font-[700] h-14 animated_underline"
                  >
                    Popular Links
                  </h3>
                </div>
                <div class="flex flex-col justify-start link-animated">
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >Home</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >About Us</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Our
                    Services</nuxt-link
                  >
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Meet
                    The Team</nuxt-link
                  >
                  <!-- <nuxt-link class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4" href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i>Latest
                    Blog</nuxt-link
                  > -->
                  <nuxt-link
                    class="w-full mb-2 transition-all duration-500 ease-linear text-primary-50 hover:translate-x-4"
                    href="#"
                    ><i class="bi bi-arrow-right text-primary-600 me-2"></i
                    >Contact Us</nuxt-link
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-white container-fluid" style="background: #061429">
      <div class="container text-center">
        <div class="flex justify-center">
          <div class="col-lg-8 col-md-6">
            <div class="flex items-center justify-center" style="height: 75px">
              <p class="mb-0">
                &copy;
                <nuxt-link class="text-white border-b" href="#"
                  >AHAVA Technologies</nuxt-link
                >. All Rights Reserved.

                <!--/*** This template is free as long as you keep the footer author’s credit link/attribution link/backlink. If you'd like to use the template without the footer author’s credit link/attribution link/backlink, you can purchase the Credit Removal License from "https://htmlcodex.com/credit-removal". Thank you for your support. ***/-->
                Designed by
                <nuxt-link
                  class="text-white border-b"
                  href="https://htmlcodex.com"
                  >AHAVA</nuxt-link
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
