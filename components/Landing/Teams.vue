<template>
  <div>
    <div
      class="flex flex-col items-center justify-center max-w-md pb-3 mx-auto mb-5 text-center"
    >
      <h5 class="text-xl font-bold uppercase text-primary-600">TEAM MEMBERS</h5>
      <h1 class="mb-0 text-4xl font-extrabold">
        Professional Stuffs Ready to Help Your Business
      </h1>
      <div class="mx-auto mt-3 w-36 animated_underline"></div>
    </div>
    <div>
      <div class="grid grid-cols-3 gap-x-8">
        <Landing-TeamMember
          :member="{
            image: '/img/samuel.jpg',
            name: 'Samuel Noah',
            role: 'Co-Founder',
          }"
        />
        <Landing-TeamMember
          :member="{
            image: '/img/yonatan.jpg',
            name: 'Yonatan Tesfaye',
            role: 'Co-Founder',
          }"
        />
        <Landing-TeamMember
          :member="{
            image: '/img/zerubabel.jpg',
            name: 'Zerubabel Kassahun',
            role: 'Co-Founder',
          }"
        />
      </div>
    </div>
  </div>
</template>
