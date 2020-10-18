<template>
  <div class="post-part single container">
    <prismic-embed :field="slice.primary.video" />
  </div>
</template>

<script>
export default {
  props: ["slice"],
  name: "text-slice",
};
</script>

<style lang="sass">
.textslice
  a
    text-decoration: underline
</style>