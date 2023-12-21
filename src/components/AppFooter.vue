<script>
export default {
  name: 'Footer',


};
</script>

<template>
  <footer>
    <div class="custom-container d-flex justify-content-between">
      <div class="footer-caption">
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
</style>
