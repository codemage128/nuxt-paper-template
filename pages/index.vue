<template>
  <b-container fluid>
    <b-row>
      <b-col md="6" lg="8" class="login-bg p-0">
        <div class="black-opacity" />
        <b-container class="coin-bg-container bv-example-row bv-example-row-flex-cols">
          <b-row align-v="center" class="h-100 justify-content-center mx-2 p-5 main-container">
            <b-col>
              <h1 class="text-uppercase">
                Get Free
              </h1>
              <h1 class="font-weight-bold text-uppercase">
                <span class="title">Robux</span>
                Today
              </h1>
              <h5>
                By downloading apps, completing Quizes, or watching videos. NO password required.
              </h5>
            </b-col>
          </b-row>
        </b-container>
      </b-col>
      <b-col md="6" lg="4">
        <div class="p-3">
          <div class="header mb-5">
            <img src="/images/main-logo.png">
          </div>
          <div class="login-section pt-5">
            <form action="javascript:void(0)" method="post" @submit="login">
              <b-form-group>
                <h4 class="font-weight-bold">
                  Enter your Roblox username
                </h4>
                <h6 class="my-4">
                  All the robux you make will be sent to this username, so make sure its correct!
                </h6>
                <b-form-input placeholder="Enter Username" />
                <b-button type="submit" class="mt-4" variant="success" size="lg" block>
                  Login
                </b-button>
              </b-form-group>
            </form>
          </div>
          <div class="footer-section mt-5 px-3">
            We are not affiliated with any of the games or companies shown on this website. Use of any logos or trademarks are for reference purposes only. By utilizing the website, you agree to be bound by the terms of service.
          </div>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import Swal from 'sweetalert2'
export default {
  layout: 'guest',
  methods: {
    login () {
      Swal.fire({
        icon: 'warning',
        title: "Are you sure that's your username?",
        text: 'All the robux you make will be sent to this username, so make sure its correct!',
        showCancelButton: true,
        confirmButtonColor: '#d33',
        cancelButtonColor: '#3085d6',
        confirmButtonText: 'Yes',
        cancelButtonText: 'No'
      }).then((result) => {
        this.$router.push('/earn')
      })
    }
  }
}
</script>

<style scoped>
  span.title{
    color: rgb(17, 205, 105);
  }

  .main-container h1{
    font-size:80px;
  }

  .main-container h5{
    font-size:20px;
  }

  .login-bg{
    height:100vh;
    background: url(/images/login-bg.jpg);
    background-position:center center;
    background-size: cover;
  }

  .black-opacity{
    height: 100%;
    width: 100%;
    top: 0px;
    position: absolute;
    background-color: rgba(10, 19, 52, 0.75);
  }

  .coin-bg-container{
    background: url(/images/coins_bg.png);
    background-size: cover;
    height: 100%;
    width: 100%;
    top: 0px;
    position: absolute;
    color: rgb(255, 255, 255);
  }

  .footer-section{
    color: rgba(13, 34, 49, 0.7);
  }

</style>
