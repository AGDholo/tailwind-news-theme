<template>
  <div class="flex justify-between my-4 items-center">
    <div class="text-2xl uppercase font-black">
      Hero<span class="text-gray-400">News</span>
    </div>

    <div class="flex divide-x">
      <HSearch />

      <div v-for="item in DButtons" class="ml-2">
        <HButton :item="item" />
      </div>

      <div class="relative text-blue-700">
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
            d="M15 13l-3 3m0 0l-3-3m3 3V8m0 13a9 9 0 110-18 9 9 0 010 18z"
          ></path>
        </svg>

        <HButton :item="{ text: 'Free download' }" class="pl-7" />
      </div>
    </div>
  </div>
</template>

<script>
import HButton from "../../base/HButton/HButton.vue";
import HSearch from "../../base/HSearch/HSearch.vue";
import { DButtons, DCategories } from "./data";
export default {
  components: { HSearch, HButton },
  setup() {
    return {
      DButtons,
      DCategories,
    };
  },
};
</script>
