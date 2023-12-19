<script>

export default {
  name: 'Jumbotron',


};
</script>

<template>
<div class="container-big d-flex justify-content-between mx-auto mb-5 p-5">
  <div class="left col-5">
    <h2 class="m-2">The biggest platform for your growth.</h2>
    <p class="m-2 py-2">There are many variations of passages of lorem ipsum available, but majorities have suffered alteration in some form</p>
    <button class="btn btn-primary mt-5 ms-2 py-2">Read More</button>
  </div>
  <div class="right col-7">
    <img src="../assets/img/27-1.png" alt="people-jumbo" class="jumbo-img">
  </div>
</div>

</template>

<style scoped lang="scss">
.container-big{
  height: 492px;
  background-color: #F2F7FF;
  border-radius: 5px;
  .left{
    line-height: 2.3;
    h2{
      font-size: 60px;
    }
    p{
      color: #8E989F;
      font-size: 18px;
    }
  }
  .right{
    position: relative;
    .jumbo-img{
      width: 770px;
      position: absolute;
      top: -25px;
      right: 1px;
    }
  }

}


</style>
