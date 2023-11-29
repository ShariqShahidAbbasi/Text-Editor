<template>
  <div id="app">
    <!-- <vue-editor v-model="content" :editorToolbar="customToolbar"></vue-editor> -->
    <vue-editor v-model="content"></vue-editor>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";
import { VueEditor } from "vue2-quill-editor";

export default {
  name: "App",
  components: {
    // HelloWorld,
    VueEditor,
  },
  data() {
    return {
      content: "<h1>Html For Editor</h1>",
      customToolbar: [
        ["bold", "italic", "underline"],
        [{ list: "ordered" }, { list: "bullet" }],
        [{ align: [] }],
        ["link"],
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
