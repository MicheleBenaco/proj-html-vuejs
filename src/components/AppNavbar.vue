<template>
    <nav class="container d-flex justify-content-between ">
        <div>
            <img src="../assets/img/logo-restaurant-2x-300x58.png" alt="">
        </div>
        <!-- lista Navbar -->
        <div>
            <ul class="d-flex">
                <li v-for="(link,index) in links" :key="index">
                    <a :href="link.url">{{link.text}}</a>
                </li>
            </ul>
            
        </div>
        
        
            
    </nav>
</template>

<script>
    export default {
        name:'AppNavbar',
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
    nav{
        overflow: hidden;
        top: 0;
        left: 0; 
       
        z-index: 99;
       
        ul{
           li{
                margin: 15px;
                list-style-type: none;
                
                a{
                    text-decoration: none;
                    color: rgb(206, 137, 137);
                }
           }
            
        }

    }



</style>