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
    color: rgb(175, 175, 175);
    font-weight: 600;
    width: 100%;
    ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
      li {
        margin-top: 15px;
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
      }
      li.dashed {
        color: rgba(255, 255, 0, 0.822);
      }
      li.active {
        color: white;
      }
    }
  }
  .quote {
    margin-top: 90%;
    padding: 10% 25%;
    border: 1px solid gray;
    border-radius: 15px;
    blockquote {
      color: white;
      font: {
        weight: 500;
        size: 70%;
      }
    }
  }
}
</style>
