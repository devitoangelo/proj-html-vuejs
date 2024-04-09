<script>
import AppHeader from './components/AppHeader.vue'


export default {
  components: {
    AppHeader
  }
}

</script>

<template>

  <AppHeader />



  <main>
    <!-- jumbo -->
    <div class="site_main">
      <div class="title">
        <h1>Professional Development For <br>
          Coaches And Leaders</h1>
      </div>
      <div class="ciao">
        <button class="btn button">
          Learn More
        </button>

      </div>







    </div>








  </main>






</template>

<style>
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
    font-size: xx-large;
  }

  >.ciao {
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
</style>
