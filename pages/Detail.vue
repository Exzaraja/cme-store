<template>
  <NuxtLayout>
    <!-- DETAIL PRODUK -->
    <section>
      <UContainer class="pt-24 ">
        <div class="flex w-full my-8 flex-col lg:flex-row bg-sky-800 rounded-xl text-white">
          <div class="lg:w-2/5 m-0 overflow-hidden text-white shrink-0 rounded-xl bg-clip-border">
            <img
              src="/img/TITAN.png"
              alt="image"
              class="object-cover rounded-lg w-full lg:w-[420px] lg:h-[520px] mx-auto lg:my-8 bg-black"
            >
          </div>
          <div class="p-6 text-justify ">
            <h1
              class="block mb-2 font-sans text-2xl antialiased font-semibold leading-snug tracking-normal text-blue-gray-900"
            >
              Pentingnya Daur Ulang Kembali, Memberikan Kehidupan Baru untuk Sumpit Sekali Pakai
            </h1>
            <div class="mt-4">
              <UBadge color="primary" size="lg" variant="solid" class="mx-auto">
                Ready
              </UBadge>
              <UBadge color="violet" size="lg" variant="solid" class="ml-2">
                Best Seller!!!
              </UBadge>
            </div>
            <div class="font-semibold text-5xl text-green-500 my-4">
              <h2>Rp2.350.000</h2>
            </div>
            <div class="font-normal text-lg my-6">
              <h3>Product by NAMA BRAND</h3>
              <h4 class="mt-4">
                Seri Produk :
              </h4>
              <h4>Kategori Produk :</h4>
              <h4>Tipe Produk :</h4>
              <h4>Kategori Brand :</h4>
              <h4>Tag Produk :</h4>
            </div>
            <div class="grid gap-4 justify-end ">
              <UButton
                to="/"
                color="primary"
                size="xl"
                variant="solid"
                icon="i-mdi-whatsapp"
                class="font-semibold px-24"
              >
                Beli Sekarang
              </UButton>
              <p class="font-normal opacity-60">
                Dapat dibeli di marketplace :
              </p>
              <div class=" flex justify-start gap-8">
                <a href="#" class="text-white hover:text-green-500">
                  <UIcon to="" name="i-arcticons-tokopedia" class="text-7xl" />
                </a>
                <a href="#" class="text-white hover:text-orange-500">
                  <UIcon name="i-arcticons-shopee" class="text-7xl" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </UContainer>
    </section>
    <!-- Rekomendasi -->
    <section>
      <UContainer class="md:max-w-full lg:mx-28 mt-16">
        <div class="bg-sky-800 mt-5 shadow-sm rounded-lg overflow-hidden">
          <div class="text-white">
            <div class="text-center">
              <h1 class="rounded bg-rose-600 py-4 px-6 text-white font-semibold text-xl">
                Rekomendasi Produk
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
  </NuxtLayout>
</template>
