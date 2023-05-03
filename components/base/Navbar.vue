<template>
  <nav id="navbar" class="relative z-10 w-full text-neutral-800">
    <div class="flex flex-col max-w-screen-xl px-8 mx-auto lg:items-center lg:justify-center lg:flex-row py-4">
      <div class="flex flex-col lg:flex-row items-center space-x-4 xl:space-x-8">
        <div class="w-full flex flex-row items-center justify-center py-6">
          <div>
            <img :src="require('~/assets/img/logo/ajr.png')" class="w-24 xl:w-28" alt="AJR Logo" />
          </div>
        </div>
      </div>
       <!--  <div class="flex flex-col lg:flex-row items-center space-x-4 xl:space-x-8">
        <ul :class="[open ? 'flex' : 'hidden lg:flex']"
          class="w-full h-auto flex flex-col flex-grow lg:items-center pb-4 lg:pb-0 lg:justify-end lg:flex-row origin-top duration-300 xl:space-x-2 space-y-3 lg:space-y-0">
          <NuxtLink class="mr-4" to="/products">Products</NuxtLink>
          <NuxtLink to="/products">About Us</NuxtLink>
        </ul>
      </div>-->
    </div>
  </nav>
</template>
<script>
export default {
  name: 'BaseNavbar',
  data() {
    return {
      open: false,
      dropdownNavbar: false,
    }
  }
}
</script>
