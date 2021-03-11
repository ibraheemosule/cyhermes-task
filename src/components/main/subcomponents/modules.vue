<template>
  <div class="container-fluid">
    <fieldset>
      <legend>
        <h6><sub>ALL MODULES</sub></h6>
      </legend>
      <div class="container-fluid">
        <div class="row">
          <iconOption :text="'Governance Portal'" :icon="'icon1.jpg'" />
          <iconOption :text="'Corporate Universe'" :icon="'icon2.jpg'" />
          <iconOption :text="'Contact Domain'" :icon="'icon3.jpg'" />
          <iconOption :text="'Investor relations'" :icon="'icon4.jpg'" />
          <iconOption :text="'Dispute Portfolio'" :icon="'icon5.jpg'" />
          <iconOption :text="'Minute Back'" :icon="'icon6.jpg'" />
          <iconOption :text="'Reporting Tool'" :icon="'icon7.jpg'" />
          <iconOption :text="'Attendance Register'" :icon="'icon8.jpg'" />
        </div>
      </div>
    </fieldset>
    <div class="row back">
      <div class="col-5">
        <a href="#"><small>Go back</small></a>
      </div>
      <div class="col-6">
        <button class="btn btn-warning"><strong>Continue</strong></button>
      </div>
    </div>
  </div>
</template>

<script>
import iconOption from "./_iconOptions.vue";
export default {
  components: {
    iconOption
  }
};
</script>

<style lang="scss" scoped>
.container-fluid {
  margin-top: 5vmin;
  fieldset {
    border: 1px solid #70707050;
    border: {
      right: none;
      left: none;
      bottom: 1px dashed #70707050;
    }
    padding-bottom: 5vmin;
    legend {
      width: 20%;
      margin-left: 5%;
      h6 {
        text-align: center;
        color: #aaa9aa;
        font: {
          weight: 700;
          size: 50%;
        }
      }
    }
  }
  .back {
    margin-top: 5vmin;
    justify-content: space-between;
    .col-5 {
      text-align: left;
      align-self: center;
      a {
        color: rgba(255, 136, 0, 0.836);
        font-weight: 700;
      }
    }
    .col-6 {
      text-align: right;
    }
  }
}
</style>
