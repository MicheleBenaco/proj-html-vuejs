<template>
    <div>
      <AppNavbar/>
      <AppJumbo/>

    </div>
</template>

<script>
import AppNavbar from './AppNavbar.vue';
import AppJumbo from './AppJumbo.vue';

    export default {
    name: "AppHeader",
    components: { AppNavbar, AppJumbo }
}
</script>

<style lang="scss" scoped>

</style>