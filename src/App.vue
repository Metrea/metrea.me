<template>
  <div>
    <router-link to="/">Home</router-link>
    <router-link to="/blog">Blog</router-link>
    <router-link to="/project">Projects</router-link>
    <router-link to="/about">About Me</router-link>
    <router-link to="/contact">Contact</router-link>
  </div>

  <!-- Render active components -->
  <router-view />
</template>

<script>
// import HomeTest from "./components/HomeTest.vue";

export default {
  name: "App",
  components: {
    // HomeTest,
  },
};
</script>

<style></style>
