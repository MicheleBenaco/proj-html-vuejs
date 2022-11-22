<template>
    <div class="footer">
            <div class="d-flex justify-content-center  cont-img">
                <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="">
                
            </div>
            <div class="d-flex cont-scritta">
                    <p class="text-center">Meris nul
                            im soclerisque netus viverra dui.
                            fougiat in nam in feugiat. Ipsum odio etiam
                            fougiat in nam in feugiat. Ipsum odio etiam
                            lisis amet valputate.</p>
                </div>
                <div class="d-flex justify-content-center align-items-center  ">
                    <img src="../assets/img/footer-facebook.png" alt="" class="space">
                    <img src="../assets/img/footer-twitter.png" alt="" class="space">
                    <img src="../assets/img/footer-pinterest.png" alt="" class="space">
                    <img src="../assets/img/footer-youtube.png" alt="" class="space">
                    <img src="../assets/img/footer-periscope.png" alt="" class="space">

                </div>

    </div>

                
                <div class="cont-black d-flex justify-content-center align-items-center ">
                    <h6 class="">Copyright 2012-2019 avada | All rights reserverd ! powered by Boolean | Lebon</h6>
                </div>
</template>

<script>
    export default {
        name:'AppFooter'
    }
</script>

<style lang="scss" scoped>
.debug{
    border: solid 1px red;
}
    .footer{
        background-image: url(../assets/img/footer2x.jpg);
        width: 100%;
        background-size: cover;
        background-repeat: no-repeat;
        height: 1000px;

       .cont-img{
            padding-top: 350px;
       }

       .cont-scritta{
            padding-top: 50px;
        margin: 0 auto;
        color: white;
        width: 500px;
       }
        
       .space{
        padding-top: 50px;
        margin: 10px;
       }
       
    }

    .cont-black{
        width: 100%;
        background-color: black;
        min-height: 200px;
        color: white;
        
        h6{
            font-size: 15px;
        }
       }

</style>