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
    height: 80px;
    background-color: $color-white;
    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        .logo {
            width: 40%;
            display: flex;
            padding-left: 10px;

            img {
                margin-top: 10px;
                height: 50px;
            }
        }

        nav {
            width: 60%;
            display: flex;
            align-items: center;
            padding-left: 240px;

            ul {
                list-style: none;
                display: flex;
                justify-content: space-between;
                justify-content: center;
                line-height: 50px;

                li {
                    font-size: 12px;
                    padding: 15px;
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
                width: 100px;
                height: 30px;
                text-align: center;
                background-color: $color-bright-sun;
                line-height:  20px;
                padding: 5px;
                font-size: 12px;
                color: $color-silver-dark;
                margin-left: 15px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-dove-gray;
                    color: $color-white;
                }
            }
        }
    }
}

</style>