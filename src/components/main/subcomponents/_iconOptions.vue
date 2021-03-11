<template>
  <div class="col-sm-4">
    <div class="container-fluid">
      <a class="row" href="#">
        <span class="col-6 image">
          <img :src="require('@/assets/image/' + icon + '')" alt="icon" />
        </span>
        <span class="col-6 text">
          <span>{{ text }}</span>
        </span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    icon: String,
    text: String
  }
};
</script>

<style lang="scss" scoped>
.col-sm-4 {
  margin-bottom: 2vh;
  .row {
    color: #808080cb;
    text-decoration: none;
    span {
      font: {
        size: 80%;
        weight: 600;
      }
    }
    .image {
      display: flex;
      justify-content: flex-end;
      align-items: start;
      img {
        max-width: 60%;
        max-height: auto;
      }
    }
    .text {
      display: flex;
      align-items: center;
    }
  }
  .row:hover {
    background-color: #fffae5;
  }
}
</style>
