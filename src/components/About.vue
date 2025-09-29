<template>
  <div class="relative">
    <div class="hero">
      <div class="hero-top"></div>
      <div class="hero-bottom"></div>
    </div>
    <video
      src="../assets/first-about.mp4"
      autoplay
      muted
      loop
      playsinline
      class="w-[100vw] h-[400px] object-cover z-0"
    ></video>
    <div class="fwd-transition-space fwd-lightest">
      <div class="fwd-gradient fwd-lightest-blue-top"></div>
      <div class="fwd-gradient fwd-lightest-blue-bottom"></div>
    </div>
  </div>
  <section class="bbgg h-[100vh]">
    <div class="containerr flex items-center h-full">
      <p class="p">
        Tricky Knot is an entertainment <br />
        financing and development <br />
        company backing rising voices <br />
        in Hollywood.
      </p>
    </div>
  </section>
  <section class="bbgg h-[50vh]"></section>
  <section class="bbgg h-[100vh]">
    <div class="containerr flex items-center h-full">
      <p class="p !text-[40px]">We empower artistic freedom</p>
    </div>
  </section>

  <section class="bbgg h-[100vh]">
    <div class="containerr flex items-center justify-center h-full">
      <p class="p !text-[40px]">We provide long-term business support</p>
    </div>
  </section>
  <section class="bbgg h-[100vh]">
    <div class="containerr flex items-center justify-center h-full">
      <p class="p !text-[40px] absolute right-[150px]">
        We foster a sense of collaboration
      </p>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.hero {
  z-index: 1;
  background-color: #062741;
  align-self: center;
  width: 100%;
  height: 5vh;
  position: relative;
  .hero-top {
    background-image: linear-gradient(#06274103 4%, #062741 96%, #062741);
    height: 400%;
    position: relative;
    top: -400%;
  }
  .hero-bottom {
    background-image: linear-gradient(#06274103, #062741 0%, #06274100);
    height: 500%;
    position: relative;
    top: -300%;
  }
}

.fwd-transition-space {
  align-self: center;
  width: 100%;
  height: 5vh;
  position: relative;
  background-color: #254bab;
  .fwd-lightest-blue-top {
    background-image: linear-gradient(#06274100 35%, #00000003 35%, #254bab);
    height: 500%;
    position: relative;
    top: -500%;
    z-index: 10;
  }
  .fwd-lightest-blue-bottom {
    background-image: linear-gradient(#254bab, #00000003 90%, #06274100 90%);
    height: 400%;
    position: relative;
    top: -400%;
    z-index: 10;
  }
}

.p {
  font-size: 60px;
  color: #eee;
  font-weight: 600;
  line-height: 130%;

  z-index: 10;
}
</style>
