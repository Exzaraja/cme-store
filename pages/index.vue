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
    <!-- SHOP BY CATEGORY  -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-800 shadow-sm rounded-lg overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Shop by Categories
              </h1>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-4 pb-4 items-center justify-center">
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/Lampu.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Lampu
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/StopKontak.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Kabel dan Stop Kontak
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/Senter.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Senter
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/Kipas.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Kipas Angin
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/Speaker.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Speaker
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/server.svg" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Blender
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class="text-primary-500">
                  <img src="/img/Rice.png" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Rice Cooker
                  </h1>
                </div>
              </div>
              <div class="rounded-lg bg-sky-800 p-8 md:p-16 lg:p-16">
                <div class=" text-primary-500">
                  <img src="/img/server.svg" alt="" class="rounded-full bg-neutral-100">
                  <h1 class="font-medium text-center text-3xl mt-4">
                    Produk Lainnya
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- END SHOP BY CATEGORY  -->
    <!-- BARANG PILIHAN -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-800 mt-5 shadow-sm rounded-lg overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Barang Pilihan
              </h1>
            </div>
            <div class="p-8 items-center grid lg:grid-cols-5 gap-10 lg:gap-10 px-4 lg:px-20">
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink to="/Detail" class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">

                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">

                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">

                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">

                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">

                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">

                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- END BARANG PILIHAN -->
    <!-- OFFICIAL BRAND -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
          <div class="bg-neutral-200 rounded-lg mt-5 overflow-hidden">
            <div class="text-white">
              <div class="flex">
                <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                  Official Brands
                </h1>
              </div>
              <div class="grid grid-cols-2 lg:grid-cols-3 pb-4 items-center justify-center">
                <div class="p-8 mx-auto">
                  <div class=" text-primary-500">
                    <img src="/img/logo-philips.png" alt="">
                  </div>
                </div>
                <div class="p-8 mx-auto">
                  <div class=" text-primary-500">
                    <img src="/img/logo-luby.png" alt="">
                  </div>
                </div>
                <div class="p-8  mx-auto">
                  <div class=" text-primary-500">
                    <img src="/img/logo-miyako.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- MARKET PLACE -->
          <div class="bg-sky-900 rounded-lg mt-5 overflow-hidden">
            <div class="text-white">
              <div class="flex">
                <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                  Marketplace
                </h1>
              </div>
              <div class="grid grid-cols-1 lg:grid-cols-2 pb-4 items-center justify-center">
                <div class=" bg-white rounded-3xl mt-8 mx-auto w-80">
                  <div class=" text-primary-500">
                    <img src="/img/logo-tokopedia.png" alt="">
                  </div>
                </div>
                <div class="mt-8 mx-auto">
                  <div class=" text-primary-500">
                    <img src="/img/logo-shopee.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- END OFFICIAL BRAND & MARKETPLACE -->
    <!-- BARANG TERBARU -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-sky-800 mt-5 shadow-sm rounded-lg overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Barang Terbaru
              </h1>
            </div>
            <div class="p-8 items-center grid lg:grid-cols-5 gap-10 lg:gap-10 px-4 lg:px-20">
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Facebook</span>
                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Instagram</span>
                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">
                    <span class="sr-only">Twitter</span>
                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Facebook</span>
                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Instagram</span>
                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">
                    <span class="sr-only">Twitter</span>
                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Facebook</span>
                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Instagram</span>
                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">
                    <span class="sr-only">Twitter</span>
                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Facebook</span>
                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Instagram</span>
                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">
                    <span class="sr-only">Twitter</span>
                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
              <div class="max-w-sm rounded-xl bg-white overflow-hidden shadow-lg pb-8">
                <img class="w-full bg-slate-400 rounded-b-lg" src="/img/TITAN.png" alt="">
                <div class="px-6 py-2">
                  <ULink class="text-gray-700 text-justify text-sm hover:text-green-300">
                    Contoh barang yang dijual - 404 - warna RGB - 404WATT
                  </ULink>
                  <div class="mx-auto mt-2">
                    <UBadge color="primary" variant="solid">
                      Ready
                    </UBadge>
                    <UBadge class="mx-2" color="indigo" variant="solid">
                      Best Seller!!!
                    </UBadge>
                    <h2 class="text-primary font-semibold text-3xl mt-4 ">
                      Rp2.350.000
                    </h2>
                  </div>
                </div>
                <div class="flex justify-center mt-4 space-x-4">
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Facebook</span>
                    <UIcon name="i-uil-whatsapp" class="text-7xl" />
                  </a>
                  <a href="#" class="text-green-400 hover:text-green-300">
                    <span class="sr-only">Instagram</span>
                    <UIcon name="i-arcticons-tokopedia" class="text-7xl" />
                  </a>
                  <a href="#" class="text-orange-400 hover:text-orange-300">
                    <span class="sr-only">Twitter</span>
                    <UIcon name="i-simple-icons-shopee" class="text-6xl" />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- END BARANG TERBARU -->
    <!-- SHOP BY BRANDS -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28">
        <div class="bg-neutral-200 rounded-lg mt-5 overflow-hidden">
          <div class="text-white">
            <div class="flex">
              <h1 class=" rounded-br-full bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Shop by Brands
              </h1>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-8 pb-4 items-center justify-center">
              <div class="p-8 mx-auto">
                <div class=" text-primary-500">
                  <img src="/img/logo-philips.png" alt="">
                </div>
              </div>
              <div class="p-8 mx-auto">
                <div class=" text-primary-500">
                  <img src="/img/logo-luby.png" alt="">
                </div>
              </div>
              <div class="p-8  mx-auto">
                <div class=" text-primary-500">
                  <img src="/img/logo-miyako.png" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- END SHOP BY BRANDS -->
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
