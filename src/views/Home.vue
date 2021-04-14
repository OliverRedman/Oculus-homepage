<template>
  <div class="home flex justify-center">
    <div class="flex justify-center pt-28 relative color-cont">
      <div
        class="absolute ball ball-y z-50 rounded-full top-20 right-36 filter blur-sm transform rotate-25"
      ></div>
      <div
        class="absolute ball ball-p rounded-full filter blur-sm transform -rotate-45 left-72 z-10"
      ></div>
      <div
        class="absolute ball ball-p2 rounded-full filter blur-sm bottom-36 left-48 z-50"
      ></div>
      <div
        class="absolute ball ball-b rounded-full filter blur-sm bottom-10 right-64 z-10"
      ></div>
      <img src="../../public/quest2.png" alt="quest2" class="occ" />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {};
</script>
<style>
.color-cont {
  min-width: 1280px;
  max-width: 1280px;
}
.ball-b {
  transform: rotate(111.22deg);

  background: linear-gradient(
    180deg,
    rgba(149, 225, 249, 0.8) 0%,
    rgba(206, 252, 255, 0.3) 100%
  );
}
.ball-p2 {
  transform: rotate(-168deg);

  background: linear-gradient(
    180deg,
    rgba(149, 153, 249, 0.8) 0%,
    rgba(210, 206, 255, 0.3) 100%
  );
}
.ball-p {
  background: linear-gradient(
    180deg,
    rgba(223, 149, 249, 0.8) 0%,
    rgba(242, 206, 255, 0.3) 100%
  );
}
.dm {
  font-family: "DM Mono", monospace;
}
.occ {
  z-index: 20;
  width: 800px;
}
.ball {
  width: 170px;
  height: 170px;
}
.ball-y {
  background: linear-gradient(
    180deg,
    rgba(249, 227, 149, 0.8) 0%,
    rgba(255, 250, 206, 0.3) 100%
  );
}
</style>
