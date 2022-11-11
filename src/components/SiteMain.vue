<script>
import Jumbotron from "./Main_partials/Jumbotron.vue";
import SeriesList from "./Main_partials/SeriesList.vue";

export default {
    name: 'SiteMain',
    components: {
        Jumbotron,
        SeriesList
    }

}

</script>

<template>
    <main>
        <Jumbotron />
        <SeriesList />
    </main>
</template>

<style lang="scss" scoped>

</style>