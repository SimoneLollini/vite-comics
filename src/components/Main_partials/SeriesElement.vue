<script>
export default {
    name: 'SerieElement',
    props: {
        image: String,
        series: String,
    },
}
</script>

<template>

    <div class="col position-relative">
        <img :src="image" :alt="series">
        <div class="text_wrapper">{{ series }}</div>
    </div>

</template>

<style lang="scss">
@use '../../assets/scss/partials/variables' as *;

.text_wrapper {
    position: absolute;
    bottom: 0;
    background-color: $dark;
    width: 90%;
    height: 30%;
    font-size: 12px;
}
</style>