<template>
    <div class="container1">
        <div class="row ">
            <div class="col-4 col-md-12 card d-flex align-items-center">
                <div class="cont-scritte ">
                    <h1>HORS D'OEUVIRS</h1>
                    <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> ASHIN SALAMON NIGIRI</h2>
                            <p>$48</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> UMI MASU SALAD</h2>
                            <p>$28</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> ASHIN SALAMON NIGIRI</h2>
                            <p>$18</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> TEMAKI WITH CRAB</h2>
                            <p>$13</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> CALIFORNIA ROLLS</h2>
                            <p>$23</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                </div>
                
                
            </div>

            <div class="col-4 col-md-12 center-card  d-flex align-items-center justify-content-center">
                <div class="cont-scritte-center ">
                    <h1>MAIN COURSE</h1>
                    <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> BRAISED ABALONE</h2>
                            <p>$52</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> TWICE COOKED PORK</h2>
                            <p>$41</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5  ">
                        <h2> ASHIN SALAMON NIGIRI</h2>
                            <p>$22</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2>KUNG PAO CHICHEN</h2>
                            <p>$38</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> CHAR SIU SUSHIS</h2>
                            <p>$40</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                </div>
            
                
            </div>

            <div class="col-4 col-md-12 card  d-flex align-items-center ">
                <div class="cont-scritte ">
                    <h1>DESSERT</h1>
                    <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2>CHOCOLATE BALL CAKE</h2>
                            <p>$48</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> LIME PIE WHIT CRUST</h2>
                            <p>$10</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> RASBERRY PEAR CAKE</h2>
                            <p>$22</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> CAFFE AU LAIT</h2>
                            <p>$18</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                     <div class="d-flex justify-content-between align-items-center pt-5 ">
                        <h2> CAKE WHIT RASBERRY </h2>
                            <p>$8</p>
                    </div>
                     <p>Eget voltsn vite qis rutrem bladit sed. Quam nulla sit lacina</p>
                </div>
            
                
            </div>
            
        </div>


    </div>
</template>

<script>
    export default {
        name:'SectionMain8'
    }
</script>

<style lang="scss" scoped>
    .debug{
        border: 1px solid red;
    }

    .container1{
        margin: 0 auto;
        max-width: 2000px;
        padding: 80px;
        .card{
        background-color: rgb(234, 229, 229);
        width: calc(100% / 3);
        height: 1000px;
           
    }

    .center-card{
        color: white;
        height: 1000px;
        width: calc(100% / 3);
        margin-top: -60px ;
        background-image: url(../assets/img/misc22x.jpg);
        background-size: cover;
        background-repeat: no-repeat;
            .cont-scritte-center{
                width: 300px;
                h1{
                        font-size: 30px;
                        padding-top: 0px;
                        padding-bottom: 40px;
                    }
                    h2{
                        font-size: 20px;
                    }
            }
    }

    .cont-scritte{
                width: 300px;
               
                padding: 10px;
                    h1{
                        font-size: 30px;
                        padding-top: 40px;
                        padding-bottom: 40px;
                    }
                    h2{
                        font-size: 20px;
                    }

            }



    }
    

</style>