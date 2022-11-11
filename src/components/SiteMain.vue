<script>
import Jumbotron from "./Main_partials/Jumbotron.vue";
import CurrentSeriesList from "./Main_partials/CurrentSeriesList.vue";

export default {
    name: 'SiteMain',
    components: {
        Jumbotron,
        CurrentSeriesList
    }

}

</script>

<template>
    <main>
        <Jumbotron />
        <CurrentSeriesList />
    </main>
</template>

<style lang="scss" scoped>

</style>