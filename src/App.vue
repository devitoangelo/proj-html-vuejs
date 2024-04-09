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

    <!-- resultsStudent -->
    <div class="info">
      <div class="results">
        <section class="statistics">
          6500
        </section>
        <section class="statistics">
          +
        </section>
        <section class="fs-3">
          Students
        </section>
        
        <!-- ResultOnlineCourse -->







      </div>
    </div>

    <!-- subtitle2 -->
    <div class="sub_2">
      <h3><strong>Recent Courses</strong></h3>
      <p>
        Whether you're considering a foundation course or an undergraduate degree master's <br> or a PhD, academics is a
        place where students thrive.
      </p>




    </div>








  </main>

</template>


<style>
/* jumbo */
.site_main {
  width: 100%;
  height: 40rem;
  background-image: url(/images/jumbo.png);
  background-size: cover;
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

.info {
  background-color: red;
  width: 100%;
  height: 100px;

  >.results {

    margin: auto;
    width: 65%;
    height: 100%;
    display: flex;
    align-items: center;
    gap: 1rem;
    
    >.statistics{
      font-size: 3rem;
      color: var(--color_statistics);
  
    }

  }


}


/* subtitle2 */
.sub_2 {
  text-align: center;

}
</style>
