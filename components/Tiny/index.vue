<template>
  <div>
    <editor
      v-model="editorData"
      api-key="46auy8pyr9e6dp5fpimr0lkujgjuccumkby3w9n3hs1x0yco"
    ></editor>
  </div>
</template> 

<script>
import Editor from "@tinymce/tinymce-vue";

export default {
  name: "App",
  components: {
    editor: Editor,
  },

  data() {
    return {
      editorData: "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
      init: {
        toolbar_mode: "sliding",

        toolbar:
          "undo redo | blocks fontfamily fontsize | bold italic underline strikethrough | link image media table mergetags | align lineheight | tinycomments | checklist numlist bullist indent outdent | emoticons charmap | removeformat",
      },
    };
  },

  methods: {
    switchToEmptyString() {
      this.editorData = "";
    },

    switchToRealString() {
      this.editorData =
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit.";
    },

    switchToNullValue() {
      this.editorData = null;
    },
  },
};
</script>

<style>
/* #app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

div {
  width: 100%;
  display: flex;
  flex-direction: columns;
  flex-wrap: wrap;
}

.toggle__button {
  border: none;
  flex: 1 1 100%;
  padding: 10px;
  margin-bottom: 10px;
  text-align: center;
  background: #99d8d0;
} */
</style>
