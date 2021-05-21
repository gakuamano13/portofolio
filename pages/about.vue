<template>
  <div>
    <div>
      <HeaderComponent></HeaderComponent>
    </div>
    <div>
      <AboutComponent></AboutComponent>
    </div>
    <div>
      <FooterComponent></FooterComponent>
    </div>
  </div>
</template>

<script>
import HeaderComponent from "../components/HeaderComponent.vue";
import AboutComponent from "../components/main/HelloWorld.vue";
import FooterComponent from "../components/FooterComponent.vue";

export default {
  components: {
    HeaderComponent,
    AboutComponent,
    FooterComponent,
  },
};
</script>

<style>
</style>
