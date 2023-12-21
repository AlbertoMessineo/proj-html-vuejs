<script>
export default {
  name: "Testimonials",
};
</script>

<template>
  <section class="bg-testimonials">
    <div class="custom-container d-flex justify-content-center">
      <div class="title text-center my-5">
        <h4 class="my-3">Our Testimonials</h4>
        <p>
          If you are planning on developing a product landing app or website,
          take a look at this beautiful-crafted
        </p>
      </div>
    </div>
    <div class="custom-container d-flex justify-content-between gap-4">
      
        <div
          class="testimonial-card col-6 p-2 d-flex flex-column align-items-center"
        >
          <div class="border-circle m-4">
            <img src="../../assets/img/26.jpeg" alt="person-1" class="circle" />
          </div>
          <div class="name">
            julia Aann
            <span> - COO Softbox </span>
          </div>
          <p class="p-3">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero
            ratione dicta facere necessitatibus alias consectetur placeat maxime
            nam assumenda odio aspernatur atque aut eos rem laborum ipsam nihil,
            veniam eius?
          </p>
        <div class="bg-card-1"></div>
        <div class="bg-card-2"></div>
        </div>
      
      <div
          class="testimonial-card col-6 p-2 d-flex flex-column align-items-center"
        >
          <div class="border-circle m-4">
            <img src="../../assets/img/27.jpeg" alt="person-1" class="circle" />
          </div>
          <div class="name">
            Mac Znder
            <span> - Manager Softbox </span>
          </div>
          <p class="p-3">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero
            ratione dicta facere necessitatibus alias consectetur placeat maxime
            nam assumenda odio aspernatur atque aut eos rem laborum ipsam nihil,
            veniam eius?
          </p>
        <!-- <div class="bg-card-1"></div>
        <div class="bg-card-2"></div> -->
        </div>
    </div>
    <div class="custom-container d-flex justify-content-center text-center my-4">
      <div class="small-circle blu m-1"></div>
      <div class="small-circle black m-1"></div>

    </div>
  </section>
</template>

<style scoped lang="scss">
section{
  padding:50px 0;
}
.bg-testimonials{
  background-image: url('../../assets/img/15.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-color: aliceblue;
}
.position {
  position: relative;
}

.testimonial-card {
  background-color: white;
  border-radius: 3px;
  -webkit-box-shadow: 0px 7px 9px 12px #cccccc;
  box-shadow: 0px 7px 9px 12px #cccccc;
  z-index: 1;
}
// .bg-card-1{
//     border: 1px solid black;
//     width: 350px;
//     height: 100px;
//     background-color: #f1f1f1;
//     position: absolute;
//     bottom: 1px;
//     left: 1px;
//     z-index: 0;
// }

.border-circle{
  background-color: white;
  -webkit-box-shadow: 0px 0px 15px 10px #D9D9D9; 
box-shadow: 0px 0px 15px 10px #D9D9D9;
border-radius: 100px;
}
.circle{
  border: 3px solid white;
  border-radius: 100px;
  width: 50px;
}
.name{
  color: black;
  font-weight: 500;
  margin: 20px 0;
  span{
    color: #9b9b9b;
    font-weight: 300;
  }
}
.small-circle{
  width: 10px;
  height: 10px;
  border-radius: 100%;
}
.blu{
  background-color: #377DFF;
}
.black{
  background-color: black;
}
</style>
