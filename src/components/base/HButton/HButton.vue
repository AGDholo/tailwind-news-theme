<template>
  <button
    class="p-2 hover:bg-gray-100 rounded capitalize"
    :class="item.classes"
  >
    {{ item.text }}
  </button>
</template>

<script lang="ts">
import { PropType } from "vue";
import { IButton } from "./IButton";

export default {
  props: {
    item: {
      type: Array as PropType<IButton[]>,
      required: true,
    },
  },
};
</script>
