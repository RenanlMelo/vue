<template>
  <main>
    <GlassEffect />
  </main>
</template>

<script>
import GlassEffect from "./components/GlassEffect.vue";

export default {
  name: "App",
  components: {
    GlassEffect,
  },
};
</script>

<style>
body {
  background: url(/public/bg.webp);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ccc;
  margin-top: 60px;
}

main {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 85vh;
}
</style>
