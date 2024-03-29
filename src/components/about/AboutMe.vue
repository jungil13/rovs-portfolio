<template>
  <div class="container mx-auto p-4 flex flex-col items-center">
    <h1 class="text-3xl font-bold mb-6 py-4">About Me</h1>
    <div class="flex flex-col md:flex-row items-center md:items-start">
      <div class="w-full md:w-1/3 mb-4 md:mb-0">
        <img src="@/assets/images/rovs.png" alt="Profile Image" class="w-48 h-48 md:w-full md:h-auto rounded-full object-cover shadow-md">
      </div>
      <div class="w-full md:w-2/3 md:ml-8">
        <p class="text-lg mb-4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer rutrum, orci vel eleifend congue, mi mi
          molestie magna, vitae feugiat lorem nulla et odio.
        </p>
        <p class="text-lg">
          Sed tempus justo eget justo pharetra posuere. Vestibulum ac mi sit amet diam bibendum consectetur. Sed nec
          condimentum nunc.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>

<style lang="css" scoped>
/* Add custom styles here if needed */
</style>
