<script>

</script>


<template>
    <section>
        <div class="container">
            <a href="#">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </a>
            <a href="#">
                <img src="../../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>

            </a>
            <a href="#">
                <img src="../../assets/img/buy-comics-shop-locator.png" alt="">
                <span>SUBSCIPTION</span>

            </a>
            <a href="#">
                <img src="../../assets/img/buy-comics-subscriptions.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </a>
            <a href="#">
                <img src="../../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </a>

        </div>
    </section>
</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

section {
    background-color: $primary;

    .container {
        display: flex;
        justify-content: space-around;
        padding: 50px 0;

        a {
            text-decoration: none;

            span {

                font-size: $nav_size;
                color: white;
                padding-left: 10px;
            }

            img {
                height: 30px;
            }
        }

    }

}
</style>