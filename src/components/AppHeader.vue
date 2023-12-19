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
    <div class="header">
        <img src="../assets/img/logo-2.png" alt="logo_header" id="logo-header">
        <nav>
            <ul>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
                <li>prova</li>
            </ul>
        </nav>
    </div>
    <Jumbotron />
</template>

<style scoped lang="scss">
.header{
    display: flex;
    ul{
        display: flex;
    }
}
</style>
