<template>
    <div class="container-section5 container">
        <div class="row">
            <div class=" col-xll-5 col-xl-9 col-lg-12 col-md-12 col-sm-12 col-xs-12  right-cont ">
                <img src="../assets/img/blog72x.jpg" alt="">
           </div>
           <div class=" col-xll-5 col-xl-3 col-lg-12 col-md-12 col-sm-12 col-xs-12 left-cont pt-5 ">
                <div class="container-scritte">
                    <h3>The best table in toen </h3>
                    <h1> NEW TORKS TIMES </h1>
                    <span class="material-symbols-outlined">star</span>
                    
                    <p>Pellentsque vitae viverra rius,sagittis. <br>
                        Venenatis ridiculus scelerisque nisi un urna nulla. <br>
                        sit tempor a et nisl, ac felis.
                    </p>
                    <a class="button" href="">read full article</a>
                  
                    
                </div>
                
            </div>

            <div class="row">
                <div class="col-6">
                    <div class="card-left " >
                        <div class=" scritte-2">
                            <h3>The best table in toen </h3>
                            <h1> NEW TORKS TIMES </h1>
                            <p>Pellentsque vitae viverra rius,sagittis. <br>
                            Venenatis ridiculus scelerisque nisi un urna nulla. <br>
                            sit tempor a et nisl, ac felis.
                        </p>
                    <a class="button" href="">read full article</a>
                  
                            

                        </div>
                    
                    </div>
                </div>
                
                <div class="col-6">
                    <div class="card-right" >
                        <div class=" scritte-2">
                            <h3>The best table in toen </h3>
                            <h1> NEW TORKS TIMES </h1>
                            <p>Pellentsque vitae viverra rius,sagittis. <br>
                            Venenatis ridiculus scelerisque nisi un urna nulla. <br>
                            sit tempor a et nisl, ac felis.
                        </p>
                    <a class="button" href="">read full article</a>
                  
                            

                        </div>
                    
                </div>
                </div>
                
            </div>




        </div>
    </div>
</template>

<script>
    export default {
        name:'SectionMain4'
    }
</script>

<style lang="scss" scoped>


.container-section5{
    margin-top: 50px;
}
    
 .left-cont{
        // padding: 0;
        margin: 0;
        background-color:rgb(3, 3, 3);
        color: white;
        display: flex;
        justify-content: center;
        width: calc(100% /2);
        

        .container-scritte{
           margin-top: 60px;
            text-align: start;
            h3{
                text-transform: uppercase;
                font-size: 15px;
              
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
        


    }


    img{
        width: 100%;
        padding: 0;
        margin: 0;
    }

// card left
.card-left {
    margin-top: 50px;
    background-image: url(../assets/img/info52x.jpg);
    background-size: 600px;
    background-repeat: no-repeat;
    height: 660px;
    display: flex;
    align-items: center;
    justify-content: center;
    .scritte-2{
        margin-top:0px;
            text-align: start;
            h3{
                text-transform: uppercase;
                font-size: 15px;
                color: white;
              
            }
            h1{
                text-transform: uppercase;
                font-size: 35px;
                padding-top: 10px;
                color: white;
            }
             
            p{
                overflow-wrap: initial;
                padding-top: 20px;
                padding-bottom: 30px;
                color: white;
                
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

.card-right{
    margin-top: 50px;
    background-image: url(../assets/img/info12x.jpg);
    background-repeat: no-repeat;
    background-size: 600px;
    height: 660px;
    display: flex;
    align-items: center;
    justify-content: center;
    .scritte-2{
        margin-top:0px;
            text-align: start;
            h3{
                text-transform: uppercase;
                font-size: 15px;
                color: white;
              
            }
            h1{
                text-transform: uppercase;
                font-size: 35px;
                padding-top: 10px;
                color: white;
            }
             
            p{
                overflow-wrap: initial;
                padding-top: 20px;
                padding-bottom: 30px;
                color: white;
                
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


</style>