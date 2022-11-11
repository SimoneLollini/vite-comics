<script>
import DComics from "../data/dc-comics.js";
export default {
    name: 'CurrentSeriesList',
    components: {
        DComics,
    }
}
</script>

<template>
    <div class="row row-cols-6">
        <div class="col" v-for="comic in DComics">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                alt="">
        </div>
    </div>
</template>

<style lang="scss" scoped>

</style>