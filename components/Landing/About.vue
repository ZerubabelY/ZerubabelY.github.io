<template>
  <section class="grid min-h-[80vh] grid-cols-7 items-center">
    <div class="col-span-4">
      <div class="pb-3 mb-5 animated_underline">
        <h5 class="text-xl font-bold uppercase text-primary-600">About Us</h5>
        <h1 class="mt-3 mb-0 text-4xl font-extrabold text-midnight-950">
          The Best IT Solution For Your <br />
          Business
        </h1>
      </div>
      <p class="mb-4 text-secondary-600">
        Our mission is to develop cutting-edge software solutions that
        streamline and optimize business processes for organizations across
        various industries.. We believe that by leveraging cutting-edge
        technology, embracing creativity, and fostering collaboration, we can
        bring positive change to software industry and make a meaningful impact
        on the world.
      </p>
      <div class="grid grid-cols-2 mb-3">
        <div class="col-sm-6 wow zoomIn">
          <h5 class="mb-3 text-lg font-[500] gap-x-3">
            <Icon
              name="ic:round-check"
              class="text-2xl font-extrabold text-primary-600"
            />
            Reliable Service
          </h5>
          <h5 class="mb-3 text-lg font-[500] gap-x-3">
            <Icon
              name="ic:round-check"
              class="text-2xl font-extrabold text-primary-600"
            />
            Professional Staff
          </h5>
        </div>
        <div class="col-sm-6 wow zoomIn" data-wow-delay="0.4s">
          <h5 class="mb-3 text-lg font-[500] gap-x-3">
            <Icon
              name="ic:round-check"
              class="text-2xl font-extrabold text-primary-600"
            />
            24/7 Support
          </h5>
          <h5 class="mb-3 text-lg font-[500] gap-x-3">
            <Icon
              name="ic:round-check"
              class="text-2xl font-extrabold text-primary-600"
            />
            Fair Prices
          </h5>
        </div>
      </div>
      <div class="flex mb-4 align-center wow fadeIn" data-wow-delay="0.6s">
        <div
          class="flex items-center justify-center w-16 h-16 rounded bg-primary-600"
        >
          <Icon name="ic:round-phone" class="text-2xl text-white" />
        </div>
        <div class="ps-4">
          <h5 class="mb-2 text-xl">Call to ask any question</h5>
          <h4 class="mb-0 text-primary-600 font-[700] text-2xl">
            +251 939 064 200
          </h4>
        </div>
      </div>
      <div class="mt-10">
        <nuxt-link
          href="quote.html"
          class="px-5 py-3 text-white rounded bg-primary-600 zoomIn"
          >Request A Quote</nuxt-link
        >
      </div>
    </div>
    <div class="col-span-3">
      <nuxt-img
        src="/img/about us.jpg"
        class="object-contain w-full h-full :animate-zoomIn"
      />
    </div>
  </section>
</template>
