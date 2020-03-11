<template>
  <div id="app">
    <MarkdownEditor id="myEditor" />
  </div>
</template>

<script>
import MarkdownEditor from "./components/MarkdownEditor.vue";
import "./assets/css/main.css";

export default {
  name: "app",
  components: {
    MarkdownEditor
  }
};
</script>

<style>
body {
  background-color: darkcyan;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0px;
}
#myEditor {
  background-color: white;
}
</style>