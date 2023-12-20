<script>
import Jumbotron from './Jumbotron.vue';
import AppHeaderCard from './AppHeaderCard.vue';
export default {
  name: 'Header',
  components: {
    Jumbotron,
    AppHeaderCard,
  }

 
};
</script>

<template>
    <header>
        <div class="header text-center container d-flex justify-content-between p-2">
            <img src="../assets/img/logo-2.png" alt="logo_header" id="logo-header">
            <nav>
                <ul class="d-flex m-3 gap-2">
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
                        <button class="btn btn-primary">Get Started</button>
                    </li>
                </ul>
            </nav>
        </div>
        <Jumbotron />
        <div class="container d-flex pt-5">
            <AppHeaderCard />
            <AppHeaderCard />
            <AppHeaderCard />
        </div>
    </header>
</template>

<style scoped lang="scss">
#logo-header{
    height: 50px;
}

</style>
