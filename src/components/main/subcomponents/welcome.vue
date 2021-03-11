<template>
  <header class="row">
    <div class="col-sm-8">
      <h6><small>HEY, TERRY</small></h6>
      <h4>Start your <i>30 days</i> Trial</h4>
      <p><small>select your preferred package below</small></p>
    </div>
    <div class="col-sm-4">
      <div>
        <h6><small>NGN</small></h6>
        <h4>1,999,999</h4>
        <p>Total <small>(EXCLUDES VAT)</small></p>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.row {
  .col-sm-8 {
    color: #a7a7a7;
    h6 {
      color: #929192;
      small {
        font: {
          weight: 700;
          size: 70%;
        }
      }
    }
    h4 {
      font-weight: 900;
      color: #222021;
      i {
        color: #ffca00;
      }
    }
    p {
      text-shadow: 1px 0px rgba(128, 128, 128, 0.24);
      font: {
        weight: 700;
        size: 100%;
      }
    }
  }
  .col-sm-4 {
    color: #4982ff;
    display: flex;
    justify-content: flex-end;
    h6 {
      margin: 10px 0 0 0;
      color: #4982ff;
      font: {
        size: 90%;
      }
    }
    h4 {
      letter-spacing: -1px;
      font-weight: bolder;
      margin: 0;
      color: #4982ff;
    }
    p {
      margin: 0;
      margin-bottom: 5vh;
      color: rgba(0, 0, 0, 0.897);
      font: {
        weight: 700;
        size: 90%;
      }
      small {
        font: {
          weight: 500;
          size: 60%;
        }
      }
    }
  }
}
</style>
