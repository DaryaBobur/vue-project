<template>
  <img alt="Vue logo" src="./assets/logo.png">
 <Btn></Btn>
 <TitleFirst></TitleFirst>
</template>

<script>
import Btn from "./components/Button"
import TitleFirst from "./components/Title-first.vue";


export default {
  name: 'App',
  components: {
Btn,
TitleFirst
  }
}
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
