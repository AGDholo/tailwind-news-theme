<template>
  <appbar />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Appbar from "./components/shared/HAppbar/HAppbar.vue";

export default defineComponent({
  name: "App",
  components: {
    Appbar,
  },
});
</script>
