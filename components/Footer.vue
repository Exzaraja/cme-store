<template>
  <footer id="footer" class=" bg-sky-800 py-6 rounded-t-xl mt-4">
    <UContainer>
      <div class="divide-y divide-white divide-opacity-50">
        <div class="hidden py-4 lg:grid lg:grid-cols-12">
          <div class="pb-6 col-span-full md:pb-0 md:col-span-6">
            <a href="#" class="flex justify-center md:justify-start mb-2">
              <span><img src=""></span>
            </a>
            <p class="text-justify text-white max-w-sm">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Neque obcaecati, sunt fuga aliquam ad ipsum deserunt eaque provident officiis quaerat qwertyasd?
            </p>
          </div>
          <div class="flex text-left text-xl font-normal my-auto md:text-left md:col-span-3">
            <ul>
              <li>
                <ULink
                  to="/about"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  Our Story
                </ULink>
              </li>
              <li>
                <ULink
                  to="/features"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  Features
                </ULink>
              </li>
              <li>
                <ULink
                  to="/contact"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  Our Solution
                </ULink>
              </li>
              <li>
                <ULink
                  to="/movement"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  Movement
                </ULink>
              </li>
            </ul>
          </div>
          <div class="flex ml-28 text-right text-xl font-normal my-auto md:text-right md:col-span-3 lg:ml-0">
            <ul>
              <li>
                <ULink
                  to="/contact"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  Contact Us
                </ULink>
              </li>
              <li>
                <ULink
                  to="/"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  0812 3456 7890
                </ULink>
              </li>
              <li>
                <ULink
                  to="/"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  sampahberkah@gmail.com
                </ULink>
              </li>
              <li>
                <ULink
                  to="/"
                  active-class="text-yellow-500"
                  inactive-class="text-white hover:text-color-secondary"
                >
                  JL. Sorogenen No.17 Kalasan Sleman, Yogyakarta
                </ULink>
              </li>
            </ul>
          </div>
        </div>
        <div class="grid lg:flex lg:justify-between pt-4">
          <div class="flex flex-col self-center text-sm text-center text-white md:block lg:col-start-1 md:space-x-6">
            <span>©2023 Saber</span>
            <a rel="noopener noreferrer" href="#">
              <span>Blog</span>
            </a>
            <a rel="noopener noreferrer" href="#">
              <span>FAQ</span>
            </a>
            <a rel="noopener noreferrer" href="#">
              <span>Privacy Police</span>
            </a>
            <a rel="noopener noreferrer" href="#">
              <span>Terms of service</span>
            </a>
          </div>
          <div class="flex-col items-center text-white text-center md:block lg:col-start-1 md:space-x-2">
            <UIcon name="i-uil-facebook" class="text-4xl m-2" />
            <UIcon name="i-uil-instagram" class="text-4xl m-2" />
            <UIcon name="i-uil-twitter" class="text-4xl m-2" />
          </div>
        </div>
      </div>
    </UContainer>
  </footer>
</template>
