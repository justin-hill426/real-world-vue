<template>
  <div>
    Icon

    <h1>I love it</h1>
  </div>
</template>

<script>
import feather from "feather-icons";
export default {
  computed: {
    svg() {
      return feather.icons["activity"].toSvg({ class: "icon" });
    },
  },
};
</script>

<style scoped></style>
