<template>
  <div>
    <div>
      <h1 style="text-align: center">Tiny</h1>
      <!-- <h4>Not Working</h4> -->
      <!-- <Tiny /> -->
      <new-tiny :newConfig="okay" />
    </div>
    <hr />
  </div>
</template>

<script>
import newTiny from "@/components/Tiny/newTiny.vue";
export default {
  components: {
    newTiny,
  },
  data() {
    return {
      okay: "asdas",
    };
  },
};
</script>

<style>