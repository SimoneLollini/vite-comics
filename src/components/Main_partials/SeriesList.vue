<script>
import DComics from "../data/dc-comics.js";
import SeriesElement from "../Main_partials/SeriesElement.vue"
export default {
    components: {
        SeriesElement,
    },
    data() {
        return {
            DcComics: DComics
        }
    }
}
</script>

<template>

    <section class="current_series">

        <div class="container">
            <div class="badge_title">CURRENT SERIES</div>


            <div class="row row-cols-6">
                <SeriesElement v-for="comic in DcComics" :image="comic.thumb" :series="comic.series" />
            </div>
        </div>
        <div class="d-flex justify-content-center">
            <button class="btn_primary">LOAD MORE</button>
        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.current_series {
    position: relative;
    padding-top: 4rem;



    .btn_primary,
    .badge_title {
        background-color: $primary;
        width: max-content;
        padding: 0.75rem 4rem;
        font-weight: 600;
        color: white;
        border: 0;
    }

    .badge_title {
        position: absolute;
        top: 0;
        translate: 0 -50%;
    }
}
</style>