<template>
  <div
    class="fixed justify-center top-0 left-0 w-full h-16 flex items-center px-4 mt-[15px] z-50"
  >
    <img
      class="align-middle"
      src="https://cdn.prod.website-files.com/650057f73744d6f9a46e25b5/650057f73744d6f9a46e25c1_logo_sm.svg"
      alt=""
    />
    <div class="flex justify-center items-center gap-3 absolute right-[150px]">
      <p class="font-medium">About</p>
      <p class="">services</p>
      <p class="">Team</p>
      <p class="">Contact</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
p {
  opacity: 0.8;
  color: #ccc;
  letter-spacing: 0.2px;
  text-transform: uppercase;
  cursor: pointer;
  mix-blend-mode: luminosity;
  padding: 4px 4px 2px;

  font-size: 14px;
  font-weight: 500;
  line-height: 130%;
  text-decoration: none;
  transition: opacity 0.25s, color 0.25s;
}
</style>
