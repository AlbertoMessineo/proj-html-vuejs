<script>
export default {
  name: "Grid",
};
</script>

<template>
  <section class="bg">
    <div class="custom-container grid-header d-flex justify-content-between">
      <div class="left">
        <h3>Popular features that your business needs</h3>
        <p>
          Faff about only a quid blower I don't want no agro bleeding choimney pot
          burke tossercras nice one boot fanny!
        </p>
      </div>
      <div class="right">
        <button class="btn btn-primary">Explore more features</button>
      </div>
    </div>
  <!-- //////////////////////////////////GRID -->
    <div class="custom-container grid">
      <div class="row d-flex justify-content-center gap-5 m-4">
        <div class="box col-2">
          <h5>Customized Invoices</h5>
          <div class="logo blu">
              <i class="fa-solid fa-signal"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5>Stock Management</h5>
          <div class="logo orange">
              <i class="fa-regular fa-paper-plane"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5>Receivables and payables</h5>
          <div class="logo green">
              <i class="fa-solid fa-user-plus"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5> Manage Buying</h5>
          <div class="logo blu">
              <i class="fa-solid fa-user-check"></i>
          </div>
        </div>
      </div>
      <div class="row d-flex justify-content-center gap-5 m-4">
          <div class="box col-2">
          <h5>Powerful & Secure</h5>
          <div class="logo orange">
              <i class="fa-solid fa-signal"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5>Fastest return Filing</h5>
          <div class="logo green">
              <i class="fa-regular fa-paper-plane"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5>Monthly Detailed</h5>
          <div class="logo blu">
              <i class="fa-solid fa-user-plus"></i>
          </div>
        </div>
        <div class="box col-2">
          <h5>Product Management</h5>
          <div class="logo orange">
              <i class="fa-solid fa-user-check"></i>
          </div>
        </div>
      </div> 
    </div>
    <!-- ////////////////////////////////GRID END     -->
  </section>
</template>

<style scoped lang="scss">
.bg{
  height: 70vh;
  background-image: url('../../assets/img/14.png');
  background-position:-360px;
  background-repeat: no-repeat;
}
.grid-header {
  margin-top: 120px;
  line-height: 2;
}
h3 {
  font-size: 40px;
}
p {
  font-size: 14px;
  color: #838383;
}
.box{
    height: 160px;
    -webkit-box-shadow: 2px 5px 17px 25px #D1D1B6; 
    box-shadow: 2px 5px 8px 8px #D1D1B6;
}

</style>
