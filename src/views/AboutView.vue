<template>
  <div>
    <!-- About Me -->
    <div>
      <AboutMe />
    </div>

    <!-- About counter -->
    <AboutCounter />
  </div>
</template>

<script>
import AboutMe from "@/components/AboutMe.vue";
import AboutCounter from "@/components/AboutCounter.vue";

export default {
  name: "AboutView",
  components: {
    AboutMe,
    AboutCounter,
  },
};
</script>

<style scoped></style>
