<template lang="pug">
  .layout-default
    Nuxt
</template>

<script lang="ts">
export default {}
</script>

<style lang="scss">
@import "normalize.css";
@import "~assets/scss/base";

.layout-default {
  margin: 1.5rem;

  @include breakpoint(l) {
    margin: 0;
  }

  @include breakpoint(xl) {
    margin: 0 auto;
    max-width: 1400px;
  }
}
</style>
