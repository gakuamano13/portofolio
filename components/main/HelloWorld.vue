<template>
  <div class="container d-flex justify-content-center hello-world">
    <div class="text-center">
      <img class="top-image" src="~assets/image/the-sky-is-the-limit.png" alt="トップ画面">
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>

.hello-world {
  margin-bottom: 50px;
  width:100%;
  height:600px;
}

.top-image{
  width:100%;
  height: 100%;
}

@media screen and (max-width: 768px) {
  .hello-world {
  margin-bottom: 20px;
  width:100%;
  height:350px;
}
}

@media screen and (max-width: 560px) {
  .hello-world {
  margin:0 auto 0;
  width:100%;
  height:250px;
}
}

</style>
