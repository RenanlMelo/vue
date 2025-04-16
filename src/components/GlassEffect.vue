<template>
  <div class="dark-glass" />
  <div class="glass">
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.glass {
  background: rgba(0, 0, 0, 0.05);
  backdrop-filter: blur(25px);
  margin: auto;
  padding: 3rem 2rem;
  border-radius: 10px;
  border: 2px solid #ffffff50;
  box-sizing: border-box;
}

.dark-glass {
  background: rgba(0, 0, 0, 0.5);
  width: 100vw;
  height: 100vh;
  position: absolute;
  top: 0;
}
</style>
