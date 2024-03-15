<template>
  <HeaderSection />
  <HeroSection />
  <MainSection />
  <FooterSection />
</template>

<script>
import HeaderSection from "./components/HeaderSection.vue";
import HeroSection from "./components/HeroSection.vue";
import MainSection from "./components/MainSection.vue";
import FooterSection from "./components/FooterSection.vue";

export default {
  name: "App",
  components: {
    HeaderSection,
    HeroSection,
    MainSection,
    FooterSection,
  },
};
</script>

<style>
#app {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  font-family: "Inter";
}
</style>
