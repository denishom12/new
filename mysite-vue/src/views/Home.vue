<template>
  <div class="home">
    <Upper></Upper>
    <div class="row">
      <img class="img1" src="../assets/denis.jpg" alt="">
      <div class="col-md-5 p-lg-5 mx-auto my-5">
        <h1 class="display-4 font-weight-normal">Двое великих программистеров</h1>
        <p class="lead font-weight-normal">И еще более великих, чем раньше. Совсем скоро они начнут создавать великолепные сайты. Хочешь проверить прогресс?</p>
        <a class="btn btn-outline-secondary" href="#">Жмакай на кнопку</a>
      </div>
      <img class="img1" src="../assets/lesha.jpg" alt="">
    </div>
    <Centrbllocks></Centrbllocks>
  <Foot></Foot>
  </div>
</template>

<script>


import Centrbllocks from "../components/centrbllocks";
import Foot from "../components/foot";
import Upper from "../components/upper";


export default {
  name: 'Home',
  components: {Upper, Foot, Centrbllocks},
  data(){

  }
}
</script>
<style>
  .row{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    flex-wrap: nowrap;
    position: relative;
  }
  .img1{
    width: 30%;
  }
  .home{
    overflow-x: hidden;
  }
</style>
