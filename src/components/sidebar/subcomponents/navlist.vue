<template>
  <div class="row">
    <nav>
      <ul>
        <li class="active">
          <a>Trial & Pricing <span>-></span></a>
        </li>
        <li>
          <a>
            Payment Method
          </a>
        </li>
        <li class="dashed">
          <a><sup>_</sup> ------- <sup>_</sup></a>
        </li>
        <li>
          <a><small>Get Started...</small></a>
        </li>
      </ul>
    </nav>
  </div>
  <div class="row quote">
    <img :src="require('@/assets/image/quote.png')" alt="quote" />
    <blockquote
      cite="https://www.brainyquote.com/quotes/winston_churchill_124653"
    >
      success is not final; failure is not fatal it is the courage to continue
      that counts
    </blockquote>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.row {
  nav {
    color: #989797;
    font-weight: 600;
    width: 100%;
    ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
      li {
        margin-top: 15px;
        font-size: 80%;
        a {
          cursor: pointer;
          display: block;
          span {
            float: right;
          }
          small {
            font-weight: 700;
          }
        }
        a:hover {
          color: white;
        }
      }
      li.dashed {
        color: #ffca00;
      }
      li.active {
        color: white;
      }
    }
  }
  .quote {
    position: relative;
    margin-top: 60vh;
    padding: 10% 25%;
    border: 1px solid #4e4d4d;
    border-radius: 15px;
    blockquote {
      color: #a2a1a2;
      font: {
        weight: 500;
        size: 70%;
      }
    }
    img {
      max-width: 4vmax;
      max-height: auto;
      position: absolute;
      top: 20%;
      left: -6%;
      background: #222021;
      padding-top: 5%;
      padding-bottom: 5%;
    }
  }
}
@media (max-width: 576px) {
  .quote {
    margin-top: 30% !important;
  }
}
</style>
