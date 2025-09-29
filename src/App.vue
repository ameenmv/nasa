<template>
  <div class="smooth-wrapper">
    <!-- Intro component - shows on all pages -->
    <Intro />

    <div class="smooth-content">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",

  data() {
    return {};
  },
  methods: {},
};
</script>

<style lang="scss" scoped></style>
