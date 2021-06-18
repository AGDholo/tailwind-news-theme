<template>
  <div>
    <div class="bg-gray-300" style="height: 1px"></div>

    <div class="flex justify-between items-center">
      <div class="flex my-2">
        <a
          v-for="item in DCategories"
          class="mr-2 hover:underline cursor-pointer"
          >{{ item.text }}</a
        >
      </div>

      <div class="relative">
        <svg
          class="w-6 h-6 absolute top-2"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"
          ></path>
        </svg>
        <HButton class="pl-7" :item="{ text: 'Newspaper · 06/18' }" />
      </div>
    </div>

    <div class="bg-gray-300" style="height: 1px"></div>
  </div>
</template>

<script>
import { DCategories } from "./data";

import HButton from "../../base/HButton/HButton.vue";
export default {
  components: { HButton },
  setup() {
    return {
      DCategories,
    };
  },
};
</script>
