<template>
  <nav class="fixed bg-sky-800 z-50 w-full h-20">
    <UContainer>
      <div class="grid grid-cols-1 md:grid-cols-4 justify-between items-center">
        <!-- logo -->
        <div class="hidden md:block cursor-pointer">
          <span><img src="/img/enter-logo.png" alt="" class="md:h-14 lg:h-16"></span>
        </div>
        <!-- Navbar -->
        <div class="py-5 md:col-span-3 ml-2">
          <UInput
            icon="i-heroicons-magnifying-glass-20-solid"
            size="xl"
            class="w-full"
            color="white"
            variant="outline"
            :trailing="true"
            placeholder="Search..."
          />
        </div>
      </div>
    </UContainer>
  </nav>
</template>
