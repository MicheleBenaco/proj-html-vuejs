<template>
    <jumbotron class="jumbo">
           <div class="row">
            <div class=" col-xll-5 col-xl-5 col-lg-12 col-md-12 col-sm-12 col-xs-12 left-cont pt-5 ">
                <div class="container-scritte animate__animated animate__fadeInLeft ">
                    <div class="logo">
                         <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="">
                     </div>
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

           <div class=" col-xll-7 col-xl-7 col-lg-12 col-md-12 col-sm-12 col-xs-12  right-cont ">
            <div>
            <ul class="d-flex justify-content-end cont-dx">
                <li v-for="(link,index) in links" :key="index">
                    <a :href="link.url">{{link.text}}</a>
                </li>
            </ul>
            
        </div>
               
           </div>

            
           </div>
    </jumbotron>
</template>

<script>
    export default {
        name:'AppJumbo',
        data() {
            return {
                links:[
                    {
                    text: "Home",
                    url: "#",
                    current: false,
                },
                {
                    text: "Culinary History",
                    url: "#",
                    current: true,
                },
                {
                    text: "Our Menu",
                    url: "#",
                    current: false,
                },
                {
                    text: "Takeout",
                    url: "#",
                    current: false,
                },
                {
                    text: "Bulletin",
                    url: "#",
                    current: false,
                },
                {
                    text: "Reservations",
                    url: "#",
                    current: false,
                },
                {
                    text: "Videos",
                    url: "#",
                    current: false,
                },

                ]
            }
        },
    }
</script>

<style lang="scss" scoped>

.jumbo{

    .left-cont{
        // padding: 0;
        margin: 0;
        background-color:rgb(3, 3, 3);
        color: white;
        margin: 0 auto;
        display: flex;
        justify-content: center;
        align-items: center;

        .logo{
        min-width: 30%;
        max-width: 60%;
        margin-top: -300px;
            
        }
        

        .container-scritte{
            h3{
                text-transform: uppercase;
                font-size: 20px;
                margin-top: 140px;
              
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

            .button:hover {
                     background-color:#f1f2f5;
                     color: black;
                     transition: 0.7s;
                  }
                
            
        }
    }

    .right-cont{
        padding: 0;
        margin: 0;
        background-image: url(../assets/img/slider52x.jpg);
        background-size: 1500px;
        background-repeat: no-repeat;
        height: 1000px;

        .cont-dx{
            margin-top: 50px;
            margin-right: 120px;
        }
        ul{
           li{
                margin: 15px;
                list-style-type: none;
                
                a{
                    text-decoration: none;
                    text-transform: uppercase;
                    color: rgb(248, 241, 241);
                }
           }
            
        }
        

    }


    img{
        width: 100%;
        padding: 0;
        margin: 0;
    }
}

</style>