<script>

</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <a href="/"><img src="../assets/img/dc-logo.png" alt=""></a>
            </div>


            <nav>
                <a href="/">CHARACTERS</a>
                <a class="active_link" href="#">COMICS</a>
                <a href="#">MOVIES</a>
                <a href="#">TV</a>
                <a href="#">GAMES</a>
                <a href="#">COLLECTIBLES</a>
                <a href="#">VIDEOS</a>
                <a href="#">FANS</a>
                <a href="#">NEWS</a>
                <a href="#">SHOP</a>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

header {
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .active_link {
            border-bottom: 3px solid $primary;
        }

        nav {
            a {
                display: inline-block;
                margin-left: 1.1rem;
                text-decoration: none;
                color: $light_dark;
                font-size: $nav_size;
                padding: 60px 0;
            }
        }


        .logo {
            padding: 20px;

            img {
                width: 80px;
            }
        }

    }

}
</style>