<template>
  <textarea id="editor" />
</template>

<script>
import { Jodit } from "jodit";
import "jodit/build/jodit.min.css";

export default {
  name: "Jodit",
  mounted() {
    const editor = new Jodit("#editor");
  },
};
</script>