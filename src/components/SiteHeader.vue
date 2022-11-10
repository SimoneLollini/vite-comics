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
                <a href="#">COMICS</a>
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

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;

    a {
        margin-left: 1.1rem;
        text-decoration: none;
        color: $light_dark;
        font-size: $nav_size;
    }

    .logo {
        padding: 20px;

        img {
            width: 80px;
        }
    }

}
</style>