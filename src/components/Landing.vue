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
      class="w-[100vw] h-full object-cover z-0"
    ></video>
    <p class="p">
      Partnering with the next <br />
      generation of creatives <br />
      in entertainment
    </p>
    <p
      class="absolute bottom-[80px] font-medium text-[14px] flex flex-col justify-center items-center gap-3 z-5"
    >
      DIVE DEEPER
      <img
        class="w-[24px] h-[20px] img"
        src="https://cdn.prod.website-files.com/650057f73744d6f9a46e25b5/650057f73744d6f9a46e25c7_arrow%201.svg"
        alt=""
      />
    </p>
    <img
      class="absolute bottom-[40px] right-[100px] opacity-[.8] z-5"
      src="https://cdn.prod.website-files.com/650057f73744d6f9a46e25b5/650057f73744d6f9a46e25c0_circle.svg"
      alt=""
    />
    <img
      class="absolute bottom-[40px] left-[100px] opacity-[.8] z-5"
      src="https://cdn.prod.website-files.com/650057f73744d6f9a46e25b5/650057f73744d6f9a46e25c0_circle.svg"
      alt=""
    />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.p {
  position: absolute;
  font-size: 70px;
  color: #eee;
  font-weight: 600;
  line-height: 130%;
  text-align: center;
  z-index: 10;
}
.img {
  animation: up-down 2.5s ease-in-out infinite;
}
@keyframes up-down {
  0%,
  100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(15px);
  }
}
</style>
