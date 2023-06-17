<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <DemoInput>
  <!-- <HelloWorld msg="Hello Vue 3 in CodeSandbox!" /> -->
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
import DemoInputVue from "./components/DemoInput.vue";

export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
    DemoInput: DemoInputVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
