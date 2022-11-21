<template>
    <main class="container">
        
        <SectionMain1/>
        <SectionMain2/>
    </main>
    <SectionMain3/>
</template>

<script>
import SectionMain1 from './SectionMain1.vue';
import SectionMain2 from './SectionMain2.vue';
import SectionMain3 from './SectionMain3.vue';

    export default {
    neme: "AppMain",
    components: { SectionMain1, SectionMain2, SectionMain3 }
}
</script>

<style lang="scss" scoped>

    main{
            padding-top: 100px;

            

    }

</style>