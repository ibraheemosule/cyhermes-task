<template>
  <div class="container-fluid">
    <div class="row">
      <sidebar />
      <main-content />
    </div>
  </div>
</template>

<script>
import sidebar from "./sidebar/sidebar.vue";
import mainContent from "./main/mainContent.vue";
export default {
  components: {
    sidebar,
    mainContent
  }
};
</script>

<style></style>
