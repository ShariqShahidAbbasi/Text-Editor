<template>
  <div>
    <!-- <editor
      v-model="editorData"
      api-key="46auy8pyr9e6dp5fpimr0lkujgjuccumkby3w9n3hs1x0yco"
    ></editor> -->
  </div>
</template> 

<script>
// import Editor from "@tinymce/tinymce-vue";

export default {
  name: "Tiny",
  // components: {
  //   editor: Editor,
  // },
  props: ["one"],

  data() {
    // return {
    //   editorData: "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
    //   init: {
    //     toolbar_mode: "sliding",
    //     toolbar:
    //       "undo redo | blocks fontfamily fontsize | bold italic underline strikethrough | link image media table mergetags | align lineheight | tinycomments | checklist numlist bullist indent outdent | emoticons charmap | removeformat",
    //   },
    // };
  },

  methods: {
    // switchToEmptyString() {
    //   this.editorData = "";
    //   tinymce.init({
    //     selector: "textarea",
    //     plugins: "image",
    //     toolbar: "image",
    // images_upload_url: "your/upload/script",
    // Add additional image settings as needed
    // });
    // },
    // switchToRealString() {
    //   this.editorData =
    //     "Lorem ipsum dolor sit amet, consectetur adipiscing elit.";
    // },
    // switchToNullValue() {
    //   this.editorData = null;
    // },
  },
};
</script>

<style>
</style>
