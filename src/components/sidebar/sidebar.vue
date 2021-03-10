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
  background: rgba(24, 24, 24, 0.897);
  padding: 5%;
  height: 100%;
  position: relative;
}
</style>
