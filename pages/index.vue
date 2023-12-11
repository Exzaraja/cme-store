<template>
  <NuxtLayout>
    <section>
      <Swiper
        :modules="[SwiperAutoplay]"
        :slides-per-view="1"
        :loop="true"
        :effect="'creative'"
        :autoplay="{
          delay: 4000,
          disableOnInteraction: true,
        }"
      >
        <SwiperSlide v-for="(item, idx) in swiperData" :key="idx">
          <div>
            <img :src="item.img" class="h-full min-w-full py-20 rounded-3xl object-cover" alt="">
          </div>
        </SwiperSlide>
      </Swiper>
    </section>
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-800 shadow-sm rounded-lg overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Shop by Categories
              </h1>
            </div>
            <p class="p-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. In libero sint, maxime nihil maiores sed, totam
              voluptates vitae vero consequatur beatae sapiente dolores molestiae? Vel? lorem130
            </p>
          </div>
        </div>
      </UContainer>
    </section>
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-800 rounded-lg mt-5 overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Official Brands
              </h1>
            </div>
            <p class="p-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. In libero sint, maxime nihil maiores sed, totam
              voluptates vitae vero consequatur beatae sapiente dolores molestiae? Vel? lorem130
            </p>
          </div>
        </div>
      </UContainer>
    </section>
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-900 rounded-lg mt-5 overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Marketplace
              </h1>
            </div>
            <p class="p-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. In libero sint, maxime nihil maiores sed, totam
              voluptates vitae vero consequatur beatae sapiente dolores molestiae? Vel? lorem130
            </p>
          </div>
        </div>
      </UContainer>
    </section>
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-900 rounded-lg mt-5 overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Shop by Brands
              </h1>
            </div>
            <p class="p-4">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. In libero sint, maxime nihil maiores sed, totam
              voluptates vitae vero consequatur beatae sapiente dolores molestiae? Vel? lorem130
            </p>
          </div>
        </div>
      </UContainer>
    </section>
  </NuxtLayout>
</template>

<script setup lang="ts">
const swiperData = [
  {

    img: '/img/Banner-Slider-Home_1.jpg'
  },
  {

    img: '/img/Banner-Slider-Home_2.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_3.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_4.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_5.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_6.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_7.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_8.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_9.jpg'

  },
  {

    img: '/img/Banner-Slider-Home_10.jpg'

  }
]
</script>
