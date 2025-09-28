<template>
  <div>
    <Navbar />
    <Landing />
  </div>
</template>

<script>
import Landing from "../components/Landing.vue";
import Navbar from "../components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Landing,
    Navbar,
  },
};
</script>

<style lang="scss" scoped></style>
