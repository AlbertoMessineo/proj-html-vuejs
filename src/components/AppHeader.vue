<script>
import Jumbotron from './Jumbotron.vue';
export default {
  name: 'Header',
  components: {
    Jumbotron,
  }

 
};
</script>

<template>
    <div class="header text-center container d-flex justify-content-between">
        <img src="../assets/img/logo-2.png" alt="logo_header" id="logo-header">
        <nav>
            <ul class="d-flex">
                <li>
                    <a href="">Home</a>
                </li>
                <li>
                    <a href="">About us</a>
                </li>
                <li>
                    <a href="">Feature</a>
                </li>
                <li>
                    <a href="">Testimonials</a>
                </li>
                <li>
                    <a href="">Contact US</a>
                </li>
                <li>
                    <a href="">icona 1</a>
                </li>
                <li>
                    <a href="">icona 2</a>
                </li>
                <li>
                    <button>Get Started</button>
                </li>
            </ul>
        </nav>
    </div>
    <Jumbotron />
</template>

<style scoped lang="scss">

</style>
