<template>
    <jumbotron class="jumbo">
           <div class="row">
            <div class=" col-xll-6 col-xl-3 col-lg-12 col-md-12 col-sm-12 col-xs-12 left-cont pt-5 ">
                <div class="container-scritte">
                    <h3>The best table in toen </h3>
                    <h1> FINE DINING</h1>
                    <h1> EXPERIENCE</h1>
                    <p>Pellentsque vitae viverra rius,sagittis. <br>
                        Venenatis ridiculus scelerisque nisi un urna nulla. <br>
                        sit tempor a et nisl, ac felis.
                    </p>
                    <a class="button" href="">Explore the menu </a>
                  
                    
                </div>
                
            </div>

           <div class=" col-xll-6 col-xl-9 col-lg-12 col-md-12 col-sm-12 col-xs-12  right-cont ">
                <img src="../assets/img/slider52x.jpg" alt="">
                <h4 class="">california rols - $22</h4>
           </div>

            
           </div>
    </jumbotron>
</template>

<script>
    export default {
        name:'AppJumbo'
    }
</script>

<style lang="scss" scoped>

.jumbo{

    .left-cont{
        // padding: 0;
        margin: 0;
        background-color:rgb(3, 3, 3);
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        

        .container-scritte{
            text-align: start;
            h3{
                text-transform: uppercase;
                font-size: 20px;
              
            }
            h1{
                text-transform: uppercase;
                font-size: 80px;
                padding-top: 10px;
            }
             
            p{
                overflow-wrap: initial;
                padding-top: 20px;
                padding-bottom: 30px;
                
            }
            
            .button{
                color: white;
                text-decoration: none;
                text-align: center;
                border: 1px solid white;
                padding: 10px 25px;
                display: inline-block;
                text-transform: uppercase;

                
            }
            
        }
    }

    .right-cont{
        padding: 0;
        margin: 0;
        position: relative;

        h4{
            color: white;
            position: absolute;
            left:330px;
            bottom: -830px;
            text-transform: uppercase;
            font-size: 15px;
        }


    }


    img{
        width: 100%;
        padding: 0;
        margin: 0;
    }
}

</style>