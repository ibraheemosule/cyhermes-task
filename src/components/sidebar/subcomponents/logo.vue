<template>
  <div class="row">
    <div class="logo">
      <img :src="require('@/assets/image/logo.png')" alt="cyhermes-logo" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.row {
  margin-bottom: 10vh;
  .logo {
    width: 12%;
    img {
      max-width: 100%;
      max-height: auto;
    }
  }
}
</style>
