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
        color: #8B321C;
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
                color: #8B321C;
                text-decoration: none;
                text-align: center;
                border: 1px solid #8B321C;
                padding: 10px 25px;
                display: inline-block;
                text-transform: uppercase;

                
            }
            .button:hover {
                     background-color:#8B321C;
                     color: black;
                     transition: 0.7s;
                  }
            
        }
    }

    .right-cont{
        padding: 0;
        margin: 0;
        width: calc(100% /2);
        height: 1000px;

        


    }


    img{
        width: 100%;
        padding: 0;
        margin: 0;
        height: 1000px;
        object-fit: cover;
    }


</style>