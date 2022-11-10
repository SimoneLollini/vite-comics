<script></script>

<template>
    <section class="link">
        <div class="container">
            <div class="row">
                <div class="col-6 left">
                    <div class="row">
                        <div class="col-4">
                            <div class="wrapper COMICS">
                                <h6>DC COMICS</h6>
                                <a href="#">Characters</a>
                                <a href="#">Comics</a>
                                <a href="#">Movies</a>
                                <a href="#">TV</a>
                                <a href="#">Games</a>
                                <a href="#">Videos</a>
                                <a href="#">News</a>

                            </div>
                            <div class="wrapper SHOP">
                                <h6>SHOP</h6>
                                <a href="#">Shop DC</a>
                                <a href="#">Shop DC Collectibles</a>
                            </div>

                        </div>
                        <div class="col-4">
                            <div class="wrapper DC">
                                <h6>DC</h6>
                                <a href="#">Terms Of Use</a>
                                <a href="#">Privacy policy (New)</a>
                                <a href="#">Ad Choices</a>
                                <a href="#">Advertising</a>
                                <a href="#">Jobs</a>
                                <a href="#">Subscriptions</a>
                                <a href="#">Talent Workshops</a>
                                <a href="#">CPSC Certificates</a>
                                <a href="#">Ratings</a>
                                <a href="#">Shop Help</a>
                                <a href="#">Contact Us</a>


                            </div>
                        </div>
                        <div class="col-4">
                            <div class="wrapper SITES">
                                <h6>SITES</h6>
                                <a href="#">DC</a>
                                <a href="#">MAD Magazine</a>
                                <a href="#">DC Kids</a>
                                <a href="#">DC Universe</a>
                                <a href="#">DC Power Visa</a>
                            </div>
                        </div>
                        <div class="col-4">
                        </div>
                    </div>
                </div>
                <div class="col-6 right">

                </div>

            </div>
        </div>
    </section>
    <section class="social">
        <div class="container d-flex align-items-center justify-content-between">
            <a href="#" class="btn btn-outline-primary text-white">SIGN UP NOW!</a>
            <div class="wrapper_social d-flex align-items-center">
                <h6 class="text-primary">FOLLOW US</h6>
                <img src="../../assets/img/footer-facebook.png" alt="">
                <img src="../../assets/img/footer-twitter.png" alt="">
                <img src="../../assets/img/footer-youtube.png" alt="">
                <img src="../../assets/img/footer-pinterest.png" alt="">
                <img src="../../assets/img/footer-periscope.png" alt="">

            </div>
        </div>
    </section>

</template>

<style lang="scss" scoped>
@use '../../assets/scss/partials/variables' as *;

.col-6 {
    display: flex;
    align-items: center;
}

section.link {
    background-image: url(../../assets/img/footer-bg.jpg);
    background-size: cover;
    background-repeat: no-repeat;


    .col-6.right {
        background-image: url(../../assets/img/dc-logo-bg.png);
        background-size: cover;
        background-position: center;
    }

    .col-4 {
        .wrapper {
            padding: 1rem 0;

            h6 {
                color: white;
            }

            display: flex;
            flex-direction: column;

            a {
                text-decoration: none;
                color: rgba(177, 177, 177, 0.823);
                font-size: 13px;
            }
        }

    }

}

section.social {
    background-color: $dark;
    padding: 1rem 0;

    img {
        margin-left: 1rem;
    }
}
</style>