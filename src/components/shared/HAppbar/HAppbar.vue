<template>
  <div class="container mx-auto">
    <HAppbarHeader />

    <HToolbar />

    <HAppbarAD />
  </div>
</template>

<script lang="ts">
import HToolbar from "./HToolbar.vue";
import HAppbarHeader from "./HAppbarHeader.vue";
import HAppbarAD from "./HAppbarAD.vue";

export default {
  components: { HAppbarAD, HAppbarHeader, HToolbar },
};
</script>
