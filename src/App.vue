<script>
import AppHeader from './components/AppHeader.vue'


export default{
  components :{
    AppHeader
  }
}

</script>

<template>

  <AppHeader/>



  <main>
    <div class="site_main">
      <div class="title">
      

      </div>


    </div>








  </main>




 

</template>

<style>
.site_main{
  width: 100%;
  height: 500px;
  background-color: red;
  display: flex;
  justify-content: center;
  align-items: center;


  >.title{
  background-color:black;
    width: 50%;
    height: 200px;

    
  }
}

</style>
