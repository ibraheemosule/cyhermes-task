<template>
  <div class="row">
    <div class="col-12">
      <h6>Add more users</h6>
      <p>NGN99,999 <small>per user</small></p>
    </div>
    <div class="col-12 progress-value">
      <span>0</span>
      <span class="value"> 100</span><span style="float: right">>100</span>
    </div>
    <div class="col-12">
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          aria-valuenow="100"
          aria-valuemin="0"
          aria-valuemax="1000"
        ></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
div.row {
  margin-top: 5px;
  color: #929192;
  .progress-value {
    color: black;
    font-size: 60%;
    .value {
      margin: 0 0 10px 8%;
      font-size: 120%;
      color: #4982ff;
    }
  }
  .col-12 {
    h6 {
      margin: {
        bottom: 0;
        top: 0px;
      }
      font: {
        weight: 700;
        size: 90%;
      }
    }
    p {
      font: {
        size: 80%;
        weight: 700;
      }
      small {
        font-weight: 700;
      }
    }
  }
  margin-top: 50px;
  .progress {
    height: 3px;
  }
  .progress-bar {
    width: 10%;
  }
}
//overwriting bootstrap conflicting style
div.row[data-v-5259d527] {
  margin-top: 5px;
}
div.row[data-v-fe6aa1f2] {
  margin-top: 0;
}
</style>
