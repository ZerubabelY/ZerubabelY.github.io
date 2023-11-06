<template>
  <div class="py-5 container-fluid wow fadeInUp" data-wow-delay="0.1s">
    <div class="container py-5">
      <div
        class="flex flex-col items-center justify-center max-w-md pb-3 mx-auto mb-5 text-center"
      >
        <h5 class="text-xl font-bold uppercase text-primary-600">
          Why Choose Us
        </h5>
        <h1 class="mb-0 text-4xl font-extrabold">
          We Are Here to Grow Your Business Exponentially
        </h1>
        <div class="mx-auto mt-3 w-36 animated_underline"></div>
      </div>
      <div class="grid grid-cols-3 gap-x-10">
        <div class="">
          <div class="grid grid-rows-2 gap-y-5">
            <div class="zoomIn">
              <div
                class="flex items-center justify-center mb-3 rounded bg-primary-600"
                style="width: 60px; height: 60px"
              >
                <Icon name="fa6-solid:cubes" class="text-2xl text-white"></Icon>
              </div>
              <h4 class="text-2xl font-[700]">Reliable Service</h4>
              <p class="mb-0 text-secondary-600">
                Our top priority is delivering reliable software solutions that
                meet your needs and expectations.
              </p>
            </div>
            <div class="zoomIn">
              <div
                class="flex items-center justify-center mb-3 rounded bg-primary-600"
                style="width: 60px; height: 60px"
              >
                <Icon
                  name="icomoon-free:price-tags"
                  class="text-2xl text-white"
                ></Icon>
              </div>
              <h4 class="text-2xl font-[700]">Fair Price</h4>
              <p class="mb-0 text-secondary-600">
                We believe that quality software solutions should be accessible
                and affordable. Our pricing is designed to be fair and
                competitive, providing excellent value for your investment.
              </p>
            </div>
          </div>
        </div>
        <div class="zoomIn" style="min-height: 350px">
          <div class="relative h-full">
            <nuxt-img
              class="absolute w-full h-full rounded zoomIn"
              src="img/teamwork2.png"
              style="object-fit: cover"
              alt=""
            />
          </div>
        </div>
        <div>
          <div class="grid grid-rows-2 gap-y-5">
            <div class="zoomIn" data-wow-delay="0.4s">
              <div
                class="flex items-center justify-center mb-3 rounded bg-primary-600"
                style="width: 60px; height: 60px"
              >
                <Icon
                  name="fa-solid:users-cog"
                  class="text-2xl text-white"
                ></Icon>
              </div>
              <h4 class="text-2xl font-[700]">Professional Staff</h4>
              <p class="mb-0 text-secondary-600">
                Our team consists of dedicated professionals who are passionate
                about software development.
              </p>
            </div>
            <div class="zoomIn" data-wow-delay="0.8s">
              <div
                class="flex items-center justify-center mb-3 rounded bg-primary-600"
                style="width: 60px; height: 60px"
              >
                <Icon
                  name="solar:phone-bold"
                  class="text-2xl text-white"
                ></Icon>
              </div>
              <h4 class="text-2xl font-[700]">24/7 Support</h4>
              <p class="mb-0 text-secondary-600">
                We understand that software issues can arise at any time,
                affecting your business operations. That's why we offer 24/7
                support to address your concerns promptly.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
