<template>
  <div class="container mx-auto p-4 flex flex-col items-center">
    <h1 class="text-3xl font-bold mb-6 py-4 text-black">About Me</h1>
    <div class="flex flex-col md:flex-row items-center md:items-center">
      <div class="w-full md:w-1/3 mb-4 md:mb-0 flex justify-center md:justify-start">
        <img src="@/assets/images/rovs.png" alt="Profile Image" class="w-48 h-48 md:w-full md:h-auto rounded-full object-cover shadow-md">
      </div>
      <div class="w-full md:w-2/3 md:ml-8 flex justify-center md:justify-start text-center md:text-left">
        <p class="text-lg mb-4 text-black">
          My name is Rovie Lyn Ycong. I pursued a Bachelor of Science in Information Technology at Cordova Public College. I aspire to become a proficient web developer in the future, and I am committed to studying diligently to achieve this goal. My motivation stems from my desire to support my parents financially, driving me to work even harder towards a successful future.
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
