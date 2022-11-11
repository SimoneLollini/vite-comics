<script>

import DComics from "../data/dc-comics.js";
export default {
    components: {

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
                <div class="col position-relative" v-for="comic in DcComics">
                    <img :src="comic.thumb" alt="">
                    <div class="text_wrapper">{{ comic.series }}</div>
                </div>
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

    .text_wrapper {
        position: absolute;
        bottom: 0;
        background-color: $dark;
        width: 90%;
        height: 30%;
        font-size: 12px;
    }

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