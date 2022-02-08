<template>
    <header>
        <div class="container">
            <div class="logo">
            <img src="@/assets/construction_logo_retina.png" alt="">
            </div>
            <nav>
                <ul>
                    <li v-for="nav in nav" :key="nav.id">
                        <a :href="nav.url">
                            {{nav.label}}
                        </a>
                        
                    </li>
                    
                </ul>
                <div class="bottone">GET QUOTE</div>
            </nav>
        </div>
        
    </header>
</template>

<script>
export default {
    props: {
        nav: Array
    }
    
}
</script>

<style lang="scss" scoped>
@import '../style/variabileColors.scss';

header {
    height: 70px;
    background-color: $color-white;
    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: center;

        .logo {
            width: 40%;
            display: flex;
            justify-content: center;
            padding-right: 150px;

            img {
                margin-top: 10px;
                height: 50px;
            }
        }

        nav {
            width: 60px;
            padding-right: 200px;
            display: flex;

            ul {
                list-style: none;
                display: flex;
                justify-content: space-between;
                justify-content: center;
                line-height: 50px;

                li {
                    font-size: 12px;
                    padding: 10px;
                    cursor: pointer;
                    &:hover {
                        color: $color-white;
                        padding-bottom: 7px;
                        border-bottom: 2px $color-silver-dark solid;
                    }
                }

                a {
                    text-decoration: none;
                    color: $color-silver;
                }
            }

            .bottone {
                width: 70px;
            }
        }
    }
}

</style>