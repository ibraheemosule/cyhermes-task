<template>
  <div class="container-fluid">
    <page />
  </div>
</template>

<script>
import page from "./components/page.vue";

export default {
  name: "App",
  components: { page }
};
</script>

<style lang="scss" scoped>
body {
  font-family: "Roboto", sans-serif !important;
}
@media (min-width: 576px) {
  .container-fluid {
    padding-left: 0;
  }
}
</style>
