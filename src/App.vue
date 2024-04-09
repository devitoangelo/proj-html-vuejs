<script>
import AppHeader from './components/AppHeader.vue'




export default {
  components: {
    AppHeader,

  }
}

</script>

<template>

  <AppHeader />



  <main>
    <!-- jumbo -->
    <div class="site_main">
      <div class="title">
        <h1 style="font-size: 3rem;">Professional Development For <br>
          Coaches And Leaders</h1>
      </div>
      <div class="input">
        <button class="btn button">
          Learn More
        </button>

      </div>

    </div>

    <!-- subtitle -->

    <h2 style="text-align: center;">
      Since 2000, weve been partnering with education leaders to
      <div class="subtitle">

        <nav style=" color:var(--color_subtitle);margin-right: 1rem;">increase equity and achievement</nav> for all
        students.

      </div>
    </h2>


    <!-- container_card -->

    <div class="container">
      <div class="row">
        <div class="col ">
          <div class="card card_">
            <img class="img" src="/images/svg-0.svg" alt="">
            <div class="card-body">
              <div class="card-title">
                <h1 class="card_title"> <strong>Online Coaching</strong></h1>
                <p style="text-align: center;">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio, alias.
                </p>
              </div>
            </div>
          </div>
        </div>
        <!-- card 2 -->
        <div class="col ">
          <div class="card card_">
            <img class="img" src="/images/svg-0.svg" alt="">
            <div class="card-body">
              <div class="card-title">
                <h1 class="card_title"> <strong>Consultation</strong></h1>
                <p style="text-align: center;">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio, alias.
                </p>
              </div>
            </div>
          </div>
        </div>
        <!-- card 3 -->
        <div class="col ">
          <div class="card card_">
            <img class="img" src="/images/svg-0.svg" alt="">
            <div class="card-body">
              <div class="card-title">
                <h1 class="card_title"> <strong>Life Programs</strong></h1>
                <p style="text-align: center;">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio, alias.
                </p>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- results -->
  












  </main>

</template>


<style>
/* jumbo */
.site_main {
  width: 100%;
  height: 1000px;
  background-image: url(/images/jumbo.png);
  background-size: contain;
  background-repeat: no-repeat;

  >.title {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 30%;

  }

  >.input {
    text-align: center;

    >.button {
      border: 1px solid #cccc;
      border-radius: 0;
      width: 150px;

    }

    >.button:hover {
      border: 1px solid black;

    }
  }

}

/* subtitle */

.subtitle {
  justify-content: center;
  display: flex;

}



/* container_card */

.card_ {
  display: flex;
  align-items: center;
  border: none;
  background-color: #ffffff;
  border: 1px solid #ffffff;

  >.img {
    width: 50px;
  }
}

.card_title {
  font-size: 1rem;
  text-align: center;

}

/* results */

</style>
