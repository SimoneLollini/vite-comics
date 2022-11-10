<script>
import FooterNavBar from "../components/Footer_partials/FooterNavBar.vue";
import FooterSocial from "../components/Footer_partials/FooterSocial.vue";


export default {
    name: 'SiteFooter',
    components: {
        FooterNavBar,
        FooterSocial,

    }
}
</script>

<template>
    <footer>
        <FooterNavBar />
        <FooterSocial />
    </footer>
</template>

<style lang="scss" scoped>

</style>