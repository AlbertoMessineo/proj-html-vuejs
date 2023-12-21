<script>
export default {
  name: "Maps",
};
</script>

<template>
  <div class="aliceblue">
    <div class="custom-container d-flex justify-content-center">
      <div class="title text-center my-5">
        <h4 class="my-3">Contact with our team</h4>
        <p>If you are planning on developing a product landing</p>
      </div>
    </div>
    <div class="custom-container d-flex">
      <!------------------------- 
        MAPS FROM GOOGLE MAPS
      ---------------------------->
      <div class="left col-7">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d179094.83720117967!2d9.012924861571737!3d45.462615350999286!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4786c1493f1275e7%3A0x3cffcd13c6740e8d!2sMilano%20MI!5e0!3m2!1sit!2sit!4v1703082705753!5m2!1sit!2sit"
          width="600"
          height="450"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
      <!------------------------
        RIGHT COLUMN WITH FORM 
        ------------------------->
        
      <div class="right col-5 mb-5 pb-5">
        <img src="../../assets/img/35.png" alt="softbox" id="softbox">
        <div class="address">
          <div class="big my-2">9840 Shore St.Fond Du Lac, WI 54935</div> 
          <p>0 1223 213 324</p>
          <p>mail@softbox.com</p>
        </div>
        <div class="icons d-flex gap-2">
          <div class="square">
            <i class="fa-brands fa-facebook-f"></i>
          </div>
          <div class="square">
            <i class="fa-brands fa-x-twitter"></i>
          </div>
          <div class="square">
            <i class="fa-brands fa-github">
            
            </i>
          </div>
          <div class="square">
            <i class="fa-brands fa-instagram"></i>
          </div>
        </div>
        <h5>Get in touch</h5>
        <form class="row g-3">
          <div class="col-md-6">
            <label for="inputPassword4" class="form-label"></label>
            <input
              type="password"
              class="form-control"
              id="inputPassword4"
              placeholder="Your Name"
            />
          </div>
          <div class="col-md-6">
            <label for="inputEmail4" class="form-label"></label>
            <input
              type="email"
              class="form-control"
              id="inputEmail4"
              placeholder="Your Email"
            />
          </div>

          <div class="col-12">
            <label for="inputAddress2" class="form-label"></label>
            <input
              type="text"
              class="form-control"
              id="inputAddress2"
              placeholder="Your Subject"
            />
          </div>
          <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label"></label>
            <textarea
              class="form-control"
              id="exampleFormControlTextarea1"
              placeholder="Your Message"
              rows="7"
            ></textarea>
          </div>
          <div class="col-12">
            <button type="submit" class="btn btn-primary">Send message</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
#softbox{
  margin-bottom: 60px;
}
.big{
  font-weight: 400;
  font-size: 25px;
}
.icons{
  margin: 30px 0;
}
.square{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 30px;
  height: 30px;
  padding: 4px;
  border: 1px solid #ebebeb;
  border-radius: 3px;
   .fa-brands{
    color: #377DFF;

   }
}
</style>
