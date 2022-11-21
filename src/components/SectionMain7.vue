<template>
    <div class="row">
        <div class=" col-xll-7 col-xl-9 col-lg-12 col-md-12 col-sm-12 col-xs-12  right-cont ">
                <img src="../assets/img/slider72x-scaled.jpg" alt="">
           </div>
           <div class=" col-xll-5 col-xl-3 col-lg-12 col-md-12 col-sm-12 col-xs-12 left-cont pt-5 ">
                <div class="container-scritte">
                    <h3>The best table in toen </h3>
                    <h1> TAKEOUT NOW AVAILABLE</h1>
                    
                    <p>Pellentsque vitae viverra rius,sagittis. <br>
                        Venenatis ridiculus scelerisque nisi un urna nulla. <br>
                        sit tempor a et nisl, ac felis.
                    </p>
                    <a class="button" href="">read full article</a>
                  
                    
                </div>
                
            </div>
        
    </div>
</template>

<script>
    export default {
        name:'SectionMain7'
    }
</script>

<style lang="scss" scoped>
.left-cont{
        // padding: 0;
        width: calc(100% /2);
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
                font-size: 40px;
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
        width: calc(100% /2);

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


</style>