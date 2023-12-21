<script>
export default {
  name: 'Footer',


};
</script>

<template>
  <footer class="aliceblue">
    <div class="custom-container d-flex justify-content-between my-5">
      <div class="footer-caption p-3">
        <img src="../assets/img/35.png" alt="">
        <p>It is a long enstablished fact that a reader will be distracted by the readble content.</p>
        <p>Copyright @ 2018 <span>Softbox</span></p>
      </div>
      <div class="list">
        <ul>
          <li>
            <h6>Menu</h6>
          </li>
          <li>About Us</li>
          <li>Theme</li>
          <li>Features</li>
          <li>Pricing</li>
          <li>Blog</li>
        </ul>
      </div>
      <div class="list">
        <ul>
          <li>
            <h6>About Us</h6>
          </li>
          <li>About Softbox</li>
          <li>Roadmap</li>
          <li>How it work</li>
          <li>Team</li>
          <li>News</li>
        </ul>
      </div>
      <div class="list">
        <ul>
          <li>
            <h6>Quick Links</h6>
          </li>
          <li>About Us</li>
          <li>Theme</li>
          <li>Features</li>
          <li>Pricing</li>
          <li>Blog</li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style scoped lang="scss">
.footer-caption{
  width: calc(100% / 3);
}
footer{
  margin: 0;
  padding: 0;
}
.list{
  padding: 20px 0;
  line-height: 2.5;
  color: #8E989F;
  h6{
    color: black;
    font-size: 20px;
  }
}
</style>
