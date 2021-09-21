<template>
  <div>
    <h1>Home page</h1>
    <div class="d-img">
      <img
        class="b-img"
        src="../assets/home_herbal_about1.jpg"
        alt="about main img-2"
      />
    </div>
    <Services />
    <About />
  </div>
</template>

<script>
import Services from "./Services.vue";
import About from "./About.vue";
export default {
  components: {
    Services,
    About,
  },
};
</script>

<style></style>
