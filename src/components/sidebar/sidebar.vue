<template>
  <div class="col-sm-4">
    <div class="container">
      <logo />
      <navlist />
    </div>
  </div>
</template>

<script>
import logo from "./subcomponents/logo.vue";
import Navlist from "./subcomponents/navlist.vue";
export default {
  components: {
    logo,
    Navlist
  }
};
</script>

<style lang="scss" scoped>
.col-sm-4 {
  background: #222021;
  padding: 5%;
}
</style>
