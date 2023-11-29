<template>
  <div>
    <div>
      <form method="post">
        <textarea id="summernote" name="editordata"></textarea>
      </form>
    </div>
  </div>
</template>

<script>
// import Summernote from "summernote";
// import "summernote/dist/summernote.css";
export default {
  mounted() {
    var summernoteElements = document.querySelector("#summernote");

    new summernote(summernoteElements, {
      toolbar: [
        ["style", ["style", "bold", "italic", "underline", "clear", "h1"]],
      ],
      styleTags: [
        "h1",
        "h2",
        "h3",
        "p",
        {
          title: "Blockquote",
          tag: "blockquote",
          className: "blockquote",
          value: "blockquote",
        },
      ],
    });
  },
};
</script>

<style>
</style>