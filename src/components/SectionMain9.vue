<template>
    <div class="section d-flex align-items-center justify-content-start">
        <div class="main-cont debug">
            <div class="container-scritte">
                <div class="d-flex justify-content-between  pt-5 ">
                    <h1>BRAISED ABALONE</h1>
                    <h6>$52</h6>
                </div>
                <p class="pt-5 ">Eget voltsn vite qis rutrem bladit <br> sed. Quam nulla sit lacina
                    voltsn vite qis rutrem bladit <br> sed Quam nulla sit lacin
                    qis <br> rutrem bladit
                    vite qis rutrem bladit 
                    </p>
                    <a class="button" href=""> view the menu </a>
            </div>
            
        </div>

    </div>
</template>

<script>
    export default {
        name:'SectionMain9'
    }
</script>

<style lang="scss" scoped>
    .debug{
        border: 1px solid black;
    }
.section{
    background-image: url(../assets/img/hero42x.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    width: 100%;
    min-height: 950px;

    .main-cont{
        background-color: black;
        color: white;
        max-width:600px;
        height: 700px;
        margin: 200px;
        .container-scritte{
            padding: 60px;
            h1{
                font-size: 60px ;
            }
            p{
                flex-wrap: wrap;
                margin-top: 50px;
                margin-bottom: 30px;
                font-size: 20px;
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
}

</style>