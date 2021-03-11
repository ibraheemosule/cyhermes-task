<template>
  <section class="row">
    <div class="col-sm-6 uncolored">
      <h6 class="yellowColor"><small>Starts from</small></h6>
      <h6><small>NGN</small></h6>
      <h5>5,999,999.99</h5>
      <p><small>per annum</small></p>
      <h5 class="premium">Premium</h5>
      <ul>
        <li><small>100 Users </small></li>
        <li><small>All Modules</small></li>
      </ul>
    </div>
    <div class="col-sm-6 colored">
      <img :src="require('@/assets/image/check.jpg')" alt="check" />
      <div>
        <h5>Basic</h5>
        <p>
          <strong>30 days trial</strong> on our premium apps features and
          features
        </p>
      </div>
      <fieldset>
        <legend>
          <h6>INCLUDES</h6>
        </legend>
        <ul>
          <li>25 users</li>
          <li>All modules and features</li>
          <li>Unlimited commitees</li>
          <li>Unlimited roles creation</li>
        </ul>
      </fieldset>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.row {
  justify-content: center;
  .uncolored {
    padding: {
      top: 10%;
      left: 5%;
    }
    box-shadow: 0 20px 20px -2px #bfe4f062, -20px 0 20px -2px #bfe4f062;
    .yellowColor {
      color: #ffca00;
    }
    h6 {
      margin-bottom: 0;
      small {
        font: {
          weight: 700;
          size: 70%;
        }
      }
    }
    h5 {
      margin-bottom: 0;
      font: {
        weight: 800;
        size: 100%;
      }
    }
    p {
      text-shadow: 1px 0px rgba(128, 128, 128, 0.24);
      font: {
        weight: 700;
        size: 80%;
      }
    }
    .premium {
      margin-top: 5vmin;
    }
    ul {
      list-style-type: disc;
      color: #808080cb;
      padding: 0;
      li {
        display: inline-block;
        margin: 0 2% 0 0;
        font: {
          weight: 800;
          size: 70%;
        }
      }
      margin-right: 15px;
    }
  }
  .colored {
    background: #bfe4f062;
    border: 1px solid #bfd3ff;
    border-radius: 5px;
    padding: 5%;
    color: #808080cb;
    position: relative;
    img {
      position: absolute;
      border-radius: 50%;
      top: -5%;
      right: -4%;
      max-width: 12%;
      max-height: auto;
    }
    h5 {
      color: #4982ff;
      margin: 0;
      font: {
        size: 100%;
        weight: 800;
      }
    }
    p {
      font: {
        weight: 500;
        size: 70%;
      }
    }
    fieldset {
      border-top: 1px dashed #4982ff;
      margin: 2vmin 0 0 0;
      legend {
        width: 60px;
        margin-left: 0;
      }
      h6 {
        margin-top: 7px;
        font: {
          size: 40%;
          weight: 700;
        }
      }
      ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
        li {
          font: {
            size: 60%;
            weight: 700;
          }
        }
        li::before {
          content: "- ";
        }
      }
    }
  }
}
@media (max-width: 576px) {
  .col-sm-6 {
    margin-bottom: 3vh;
  }
}
</style>
