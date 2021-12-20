<template>
  <div class="user">
    <h1>This is a page for {{ username }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    username: {
      type: String,
      required: true,
    },
  },
};
</script>

<style lang="scss" scoped></style>
