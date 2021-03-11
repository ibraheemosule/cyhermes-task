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

<style lang="scss">
body {
  font-family: "Roboto", sans-serif;
}
</style>
