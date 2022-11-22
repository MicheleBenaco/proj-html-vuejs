<template>
    <main class="container">
        
        <SectionMain1/>
        <SectionMain2/>
    </main>
    <SectionMain3/>
    <main>
        <div class="text-center">
            <h1>What Critics are saying about us </h1>
        </div>
        <SectionMain4/>
    </main>
    <SectionMain5/>
    <div class="container space">
        <SectionMain6/>
    </div>
    <div class="space">
     <SectionMain7/>
    </div>
   
    <div class="space">
    <SectionMain8/>
    </div>
    <div>
        <SectionMain9/>
    </div>
</template>

<script>
import SectionMain1 from './SectionMain1.vue';
import SectionMain2 from './SectionMain2.vue';
import SectionMain3 from './SectionMain3.vue';
import SectionMain4 from './SectionMain4.vue';
import SectionMain5 from './SectionMain5.vue';
import SectionMain6 from './SectionMain6.vue';
import SectionMain7 from './SectionMain7.vue';
import SectionMain8 from './SectionMain8.vue';
import SectionMain9 from './SectionMain9.vue';

    export default {
    neme: "AppMain",
    components: { SectionMain1, SectionMain2, SectionMain3, SectionMain4, SectionMain5, SectionMain6, SectionMain7, SectionMain8, SectionMain9 }
}
</script>


<style lang="scss" >
@use '../assets/styles/partials/_variables.scss' as*;
@use '../assets/styles/main.scss' as*;
    main{
            padding-top: 100px;

            h1{
                padding: 30px;
                font-style: italic;
            }

    }

    .space{
        margin-bottom: 100px;
    }

</style>