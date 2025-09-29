<template>
  <div class="w-full overflow-hidden">
    <div class="fwd"></div>
    <Navbar />
    <Landing />
    <About />
  </div>
</template>

<script>
import About from "../components/About.vue";
import Landing from "../components/Landing.vue";
import Navbar from "../components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Landing,
    Navbar,
    About,
  },
};
</script>

<style lang="scss" scoped>
.fwd {
  z-index: 40;
  display: block;
  position: fixed;
  inset: 0%;
  pointer-events: none;
}
.fwd::before {
  background-image: url(../assets/noise.png);
  content: "";
  height: 300%;
  left: -50%;

  position: fixed;
  top: -110%;
  width: 300%;
}

</style>
