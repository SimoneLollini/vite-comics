<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
            menu: [
                {
                    text: 'CHARACTERS',
                    href: '#'
                },
                {
                    text: 'COMICS',
                    href: '#'
                },
                {
                    text: 'MOVIES',
                    href: '#'
                },
                {
                    text: 'TV',
                    href: '#'
                }, {
                    text: 'GAMES',
                    href: '#'
                },
                {
                    text: 'COLLECTIBLES',
                    href: '#'
                },
                {
                    text: 'VIDEOS',
                    href: '#'
                },
                {
                    text: 'FANS',
                    href: '#'
                }, {
                    text: 'NEWS',
                    href: '#'
                },
                {
                    text: 'SHOP',
                    href: '#'
                }
            ]
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <a href="/"><img src="../assets/img/dc-logo.png" alt=""></a>
            </div>
            <nav>
                <a :href="menu.href" v-for="menu in menu" :class="menu.text === 'COMICS' ? 'active_link' : ''">
                    {{ menu.text }}
                </a>
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