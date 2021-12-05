<template>
  <div>
    <Main />
  </div>
</template>

<script>
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Main,
  },
};
</script>

<style lang="scss">
* {
  ::-webkit-scrollbar-track {
    position: absolute;
    background-color: #00000099;
    border-radius: 3px;
  }
  ::-webkit-scrollbar {
    width: 6px;
  }
}
#app,
body {
  font-family: "Courier New", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #0f1f30;
  color: #dadada;
  margin-top: 40px;
}
</style>
