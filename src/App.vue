<template>
  <HomePage />
  <BackGround />
</template>

<script>
import HomePage from "./components/Home.vue";
import BackGround from "./components/Background.vue";

export default {
  name: "App",
  components: {
    HomePage,
    BackGround,
  },
};
</script>

<style>
body {
  scroll-behavior: smooth;
  margin: 0px;
  height: 100%;
  background-color: #000000;
  color: #fff;

  --navigation-height: 70px;
}
h1 {
  font-size: 55px;
}
</style>
