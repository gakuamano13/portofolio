<template>
  <div>
    <div class="container">
      <HeaderComponent></HeaderComponent>
    </div>
    <div>
      <HelloWorld></HelloWorld>
      <AboutComponent></AboutComponent>
      <WorkComponent></WorkComponent>
      <SkillComponent></SkillComponent>
    </div>
    <div>
      <FooterComponent></FooterComponent>
    </div>
  </div>
</template>

<script>
import HeaderComponent from "../components/HeaderComponent.vue";
import HelloWorld from "../components/main/HelloWorld.vue";
import AboutComponent from "../components/main/AboutComponent.vue";
import WorkComponent from "../components/main/WorkComponent.vue";
import SkillComponent from "../components/main/SkillComponent.vue";
import FooterComponent from "../components/FooterComponent.vue";

// FontAwesome //



export default {
  components: {
    HeaderComponent,
    HelloWorld,
    AboutComponent,
    WorkComponent,
    SkillComponent,
    FooterComponent,
  },
};
</script>

<style>
</style>
