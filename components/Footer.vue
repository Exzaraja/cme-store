<template>
  <section>
    <UContainer>
      <div class="max-w-screen-xl px-4 py-12 mx-auto space-y-8 overflow-hidden sm:px-6 lg:px-8">
        <nav class="flex flex-wrap justify-center -mx-5 -my-2">
          <div class="px-5 py-2 font-semibold">
            <ULink
              to=""
              active-class="text-rose-500"
              inactive-class="text-neutral-950 e hover:text-blue-500"
            >
              About
            </ULink>
          </div>
          <div class="px-5 py-2  font-semibold">
            <ULink
              to=""
              active-class="text-rose-500"
              inactive-class="text-neutral-950  hover:text-blue-500"
            >
              Blog
            </ULink>
          </div>
          <div class="px-5 py-2  font-semibold">
            <ULink
              to=""
              active-class="text-rose-500"
              inactive-class="text-neutral-950  hover:text-blue-500"
            >
              Team
            </ULink>
          </div>
          <div class="px-5 py-2  font-semibold">
            <ULink
              to=""
              active-class=" text-rose-500"
              inactive-class="text-neutral-950  hover:text-blue-500"
            >
              Pricing
            </ULink>
          </div>
          <div class="px-5 py-2  font-semibold">
            <ULink
              to=""
              active-class=" text-rose-500"
              inactive-class="text-neutral-950  hover:text-blue-500"
            >
              Contact
            </ULink>
          </div>
          <div class="px-5 py-2  font-semibold">
            <ULink
              to=""
              active-class=" text-rose-500"
              inactive-class="text-neutral-950 hover:text-blue-500"
            >
              Terms
            </ULink>
          </div>
        </nav>
        <div class="flex justify-center mt-8 space-x-6">
          <a href="#" class="text-neutral-950  hover:text-gray-300">
            <span class="sr-only">Facebook</span>
            <UIcon name="i-uil-facebook" class="text-4xl" />
          </a>
          <a href="#" class="text-neutral-950 hover:text-gray-300">
            <span class="sr-only">Instagram</span>
            <UIcon name="i-uil-instagram" class="text-4xl" />
          </a>
          <a href="#" class="text-neutral-950  hover:text-gray-300">
            <span class="sr-only">Twitter</span>
            <UIcon name="i-uil-twitter" class="text-4xl" />
          </a>
          <a href="#" class="text-neutral-950  hover:text-gray-300">
            <span class="sr-only">GitHub</span>
            <UIcon name="i-uil-github" class="text-4xl" />

          </a>
        </div>
        <p class="mt-8  font-semibold leading-6 text-center text-neutral-950 ">
          © 2021 SomeCompany, Inc. All rights reserved.
        </p>
      </div>
    </UContainer>
  </section>
</template>
