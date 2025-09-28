<template>
  <div
    class="w-screen h-screen overflow-hidden flex justify-center items-center relative"
  >
    <video
      src="../assets/landing.mp4"
      autoplay
      muted
      loop
      playsinline
      class="w-full h-full object-cover z-0"
    ></video>
    <p class="p">
      Partnering with the next <br />
      generation of creatives <br />
      in entertainment
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.p {
  position: absolute;
  color: white;
  font-size: 70px;
  color: #eee;
  font-weight: 600;
  line-height: 130%;
  text-align: center;
  z-index: 10;
}
</style>
