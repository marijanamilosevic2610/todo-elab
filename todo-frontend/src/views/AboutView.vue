<template>
  <div>
    <Navbar />
    <About />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import About from "@/components/About.vue";
export default {
  // 2. registrujemo komponentu
  components: {
    Navbar,
    About
  }
};
</script>

<style scoped>
</style>