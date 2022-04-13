<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
  <BeakerIcon />
</template>

<script>
import { BeakerIcon } from "@heroicons/vue/solid";

export default {
  components: { BeakerIcon },
  name: "HomeTest",
  props: {
    msg: String,
  },
};
</script>

<style scoped></style>
