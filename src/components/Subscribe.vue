<template>
  <div class="flex flex-col items-center">
    <form class="w-full max-w-md pt-5">
      <div class="md:flex md:items-center mb-6">
        <div class="md:w-1/3">
          <label
            class="block text-gray-500 font-bold md:text-right mb-1 md:mb-0 pr-4"
            for="inline-full-name"
          >Full Name</label>
        </div>
        <div class="md:w-2/3">
          <input
            class="bg-gray-200 appearance-none border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-gray-800"
            id="inline-full-name"
            type="text"
            value="Jane Doe"
          />
        </div>
      </div>
      <div class="md:flex md:items-center mb-6">
        <div class="md:w-1/3">
          <label
            class="block text-gray-500 font-bold md:text-right mb-1 md:mb-0 pr-4"
            for="inline-full-name"
          >E-Mail</label>
        </div>
        <div class="md:w-2/3">
          <input
            class="bg-gray-200 appearance-none border-2 border-gray-200 rounded w-full py-2 px-4 text-gray-700 leading-tight focus:outline-none focus:bg-white focus:border-gray-800"
            id="inline-full-name"
            type="text"
            value="jane@myemail.com"
          />
        </div>
      </div>
      <div class="md:flex md:items-center mb-6">
        <!-- <div class="md:w-1/3"></div> -->
        <label class="block text-gray-500 font-bold mx-auto">
          <input class="mr-2 leading-tight" type="checkbox" />
          <span class="text-sm">I agree to receive newsletters</span>
        </label>
      </div>
      <div class="md:flex md:items-center pb-5">
        <!-- <div class="md:w-1/3"></div> -->
        <div class="md:w-2/3 mx-auto">
          <button
            class="shadow bg-red-500 hover:bg-red-400 focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded"
            type="button"
          >Subscribe</button>
        </div>
      </div>
      <div class="md:flex md:items-center pb-5">
        <!-- <div class="md:w-1/3"></div> -->
        <div class="md:w-2/3 mx-auto">
          <router-link to="/" class="pt-4">
            <Button text="Back" />
          </router-link>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
import Button from "./Button.vue";
export default {
  components: {
    Button
  }
};
</script>

<style scoped>
</style>