<template>
  <main class="col-sm-8">
    <div class="container">
      <welcome />
      <card-content />
      <progress-bar />
      <modules />
    </div>
  </main>
</template>

<script>
import CardContent from "./subcomponents/cardContent.vue";
import Welcome from "./subcomponents/welcome.vue";
import progressBar from "./subcomponents/progressBar.vue";
import modules from "./subcomponents/modules.vue";

export default {
  components: {
    Welcome,
    CardContent,
    progressBar,
    modules
  }
};
</script>

<style lang="scss" scoped>
.col-sm-8 {
  background: rgba(255, 255, 255, 0.897);
  padding: 5%;
}
</style>
