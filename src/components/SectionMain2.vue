<template>
    <section class="section">
            <div class="row">
                <div class="col-4 d-flex justify-content-center">
                <div class="">
                    <img src="../assets/img/sushi-1.png" alt="" class="img-sushi pb-4">
                    <h3 class="text-center"> THE BEST TABLE IN TOWN</h3>
                    <p class="text-center">Sed acnean egestas ut aliquam turpis mauris.
                        miolestie, Vitae tellus tempor sem id tempus
                        neque, tellus turpis turpis. Morbi tortor id
                        gravida aliquet.</p>
                        <div class="text-center"><a class="button" href="">Explore the menu </a></div>
                        
                </div>
                
                    
                </div>



                <div class="col-4 d-flex justify-content-center">
                <div class="">
                    <img src="../assets/img/sushi-2.png" alt="" class="img-sushi pb-4">
                    <h3 class="text-center"> PERFECT FOR GROUPS </h3>
                    <p class="text-center">Sed acnean egestas ut aliquam turpis mauris.
                        miolestie, Vitae tellus tempor sem id tempus
                        neque, tellus turpis turpis. Morbi tortor id
                        gravida aliquet.</p>
                        <div class="text-center"><a class="button" href=""> MAKE A RESARVATION</a></div>
                        
                </div>
                
                    
                </div>
                


                <div class="col-4 d-flex justify-content-center">
                <div class="">
                    <img src="../assets/img/sushi-3.png" alt="" class="img-sushi pb-4">
                    <h3 class="text-center"> FRESH PRODUCE EVERYDAY</h3>
                    <p class="text-center">Sed acnean egestas ut aliquam turpis mauris.
                        miolestie, Vitae tellus tempor sem id tempus
                        neque, tellus turpis turpis. Morbi tortor id
                        gravida aliquet.</p>
                        <div class="text-center"><a class="button" href="">LEARN MORE ABOUT US</a></div>
                        
                </div>
                
                    
                </div>
                
                
            </div>
            
        </section>
</template>

<script>
    export default {
        name:'SectionMain2'
    }
</script>

<style lang="scss" scoped>
    .section{
                padding-top: 150px;

                h3{
                   padding-bottom: 30px;
                }

                p{
                    padding-bottom: 10px;
                }


                .img-sushi{
                    display: block;
                     margin-left: auto;
                    margin-right: auto;
                   
                }
                .button{
                color: black;
                text-decoration: none;
                border: 1px solid black;
                padding: 10px 25px;
                display: inline-block;
                text-transform: uppercase;

                
            }
            .button:hover{
                border: 2px solid black;
            }



            }
</style>