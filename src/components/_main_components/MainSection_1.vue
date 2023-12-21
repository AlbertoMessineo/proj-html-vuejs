<script>
export default {
    name: "Main",
}
</script>
<template>
    <section class="custom-container d-flex">
        <div class="left col-6 text-start">
            <h3>Get tips tricks on how to skyrocket your sales.</h3>
            <p>Faff about only a quid blower I don't want no agro bleeding choimney pot burke tossercras nice one boot fanny!</p>
            <div class="infos d-flex shadows">
                <img src="../../assets/img/510.png" class="info-img " alt="small-img">
                <div class="caption">
                    <h6 class="colored">Reporting Analysis</h6>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. ad ex ipsa quos quaerat quibusdam velit amet eaque facere nam accusantium eligendi vero!</p>
                </div>
            </div>
            <div class="infos d-flex mt-4 pt-2">
                <img src="../../assets/img/511.png" class="info-img" alt="small-img">
                <div class="caption">
                    <h6>technical SEO adult</h6>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. ad ex ipsa quos quaerat quibusdam velit amet eaque facere nam accusantium eligendi vero!</p>
                </div>
            </div>
        </div>
        <div class="right col-6">
            <img src="../../assets/img/509.jpeg" class="ms-4" alt="">
        </div>
    </section>
</template>

<style scoped lang="scss">

section{
    margin-top: 150px;
    div{
        margin: 20px 0;

    }
}
/////////////////////// IMAGE
h3{
    font-size: 40px;
}
.info-img{
    height: 50px;
    margin: 15px;
    align-self: center;
}
////////////////////// CAPTION
.colored{
    color:#377DFF; ;
}
.shadows{
    -webkit-box-shadow: 2px 15px 9px 10px #D9D9D9; 
box-shadow: 2px 15px 9px 10px #D9D9D9;
}
h6{
    padding: 10px 0;
}
p{
    font-size: 14px;
    color: #838383;
}

</style>