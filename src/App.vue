<template>
  <div class="container">
    <Main />
  </div>
</template>

<script>
import Main from "./components/main.vue";

export default {
  name: "App",
  components: { Main }
};
</script>

<style lang="scss">
body {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

</style>
