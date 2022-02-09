<template>
    <div class="container">
        <div class="box-container">
            <div class="box-1">
                <div class="img-logo"><img src="../assets/footer-logo.png" alt=""></div>
                <div class="text-1"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non fuga deserunt nisi maiores eveniet ea fugiat illo. Fuga reprehenderit provident quibusdam, facilis recusandae eum pariatur tempora officia eligendi rem unde.</p></div>
                <div class="bottone">LEARN MORE</div>
            </div>
            <div class="box-2">
                <h5>LATEST TWEETS</h5>
                <div class="mini-box">
                    <div class="mini-box-left">
                        <div class="logo"><img src="../assets/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt=""></div>
                        <div class="mini-text">
                            <div>ThemeFusion</div>
                            <span>@Theme_Fusion</span>
                        </div>
                        
                    </div>
                    <div class="mini-box-right"><img class="mini-logo" src="../assets/image (1).svg" alt=""></div>
                    
                </div>
                <p>Do you need sublime WordPress hosting for your next website? Take advantage of esclusive partner offers
                    thet we have secured just for you, & lauch your site in second with <span class="color">#avada</span> on WP Engine hosting & get 30% Off this Black Friday <span class="color">bit.ly/3kjLLE2 #BlackFriday2020</span>
                </p>
                <img  class="immagine-mini" src="../assets/En2TRxLW4AEiWUN.jpeg" alt="">
                <div class="container-icons">
                    <div class="box-icon-1"><i class="far fa-heart"></i><i class="far fa-share-square"></i></div>
                    <div class="box-icon-2">22h</div>
                </div>
                
            </div>
            <div class="box-3">
                <h5>CONTACT US TODAY</h5>
                <div v-for="info in info" :key="info.id" class="container-dinamic">
                    <div class="dinamic-left"><i class="fas fa-globe"></i></div>
                    <div class="dinamic-right">
                        <ul>
                            <li>{{info.location}}</li>
                            <li>{{info.via}}</li>
                            <li>{{info.city}}</li>
                        </ul>
                    </div>
                </div>
                
            </div>
            <div class="box-4">
                <h5>FIND US</h5>
                <img class="mappe" src="../assets/construction_map_pin.png" alt="">
                
            </div>
        </div>

        <div class="copyright">
            <div class="copy-left">
                <p>COPYRIGHT 2012 - 2015 AVEDA THEME BY THEME FUSION  |  ALL RIGHTS RESERVED  |  POWERED BT WPRDPRESS</p>
            </div>
            <div class="copy-right">
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-twitter"></i>
                <i class="fab fa-youtube"></i>
                <i class="fab fa-instagram"></i>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {
    props: {
        info: Array
    }
    
}
</script>

<style lang="scss" scoped>
@import '../style/variabileColors.scss';
.container {
    background-color: $color-dark;
    margin: 0 auto;
    .box-container {
        width: 1200px;
        height: 400px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .box-1 {
            margin-top: 100px;
            width: 25%;
            height: 400px;
            padding: 20px;
            
            .img-logo {
                img {
                    width: 150px;
                    
                }
            }
            .text-1 {
                color: $color-dove-gray;
                padding: 10px;
                font-size: 12px;
                word-spacing: 3px;
                line-height: 20px;
            }
            .bottone {
                width: 150px;
                height: 40px;
                text-align: center;
                background-color: $color-bright-sun;
                padding: 5px;
                font-size: 15px;
                color: $color-silver-dark;
                line-height: 30px;
                margin-top: 10px;
                margin-left: 10px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-tuatara;
                    color: $color-white;
                }
            }

        }
        .box-2 {
            padding-top: 50px;
            width: 25%;
            height: 400px;
            
            h5 {
                margin-top: 20px;
                color: $color-bright-sun-text;
            }
            .mini-box {
                display: flex;
                justify-content: space-between;
                .mini-box-left {
                    width: 80%;
                    height: 30px;
                    padding: 20px;
                    font-size: 10px;
                    display: flex;
                    .logo {
                        
                        img{
                            width: 30px;
                            border-radius: 30px;
                        }
                    }
                    .mini-text{
                        color: $color-white;
                        padding-left: 5px;
                    }

                }
                .mini-box-right {
                    width: 20%;
                    height: 30px;
                    margin-top: 20px;
                    padding-left: 30px;
                    .mini-logo {
                        width: 15px;
                    }

                    
                }
            }
            p {
                color: $color-white;
                padding-right: 5px;
                padding-left: 55px;
                font-size: 10px;
                .color {
                    color: #045287;
                }
            }
            .immagine-mini {
                width: 300px;
                padding-top: 20px;
                padding-right: 10px;
                padding-left: 55px;
            }
            .container-icons {
                display: flex;
                justify-content: space-between;
                .box-icon-1 {
                    margin-left: 50px;
                    font-size: 12px;
                    color: #3c4d63;
                    i {
                        margin: 5px
                    }

                }
                .box-icon-2 {
                    color: #3c4d63;
                    margin: 5px;
                    font-size: 12px;

                }
            }
            
        }
        .box-3 {
            padding-top: 50px;
            width: 25%;
            height: 400px;
            
            h5 {
                margin-left: 10px;
                margin-top: 20px;
                color: $color-bright-sun-text;
            }
            .container-dinamic {
                display: flex;

                .dinamic-left {
                    padding: 10px;
                    font-size: 12px;
                    color: $color-dove-gray;
                }
                .dinamic-right {
                    padding: 10px;
                    font-size: 12px;
                    color: $color-dove-gray;
                    line-height: 20px;
                    ul {
                        list-style: none;
                    }

                }
            }
        }
        .box-4 {
            padding-top: 50px;
            width: 25%;
            height: 400px;
            
            h5 {
                margin-top: 20px;
                color: $color-bright-sun-text;
            }
            .mappe {
                margin-top: 20px;
                width: 250px;
            }
        }
    }
    .copyright {
        height: 70px;
        background-color: rgb(0, 0, 0);
        display: flex;
        justify-content: space-between;
        align-items: center;
        .copy-left {
            color: $color-dove-gray;
            font-size: 10px;
            padding-left: 50px;

        }
        .copy-right {
            color: $color-dove-gray;
            font-size: 10px;
            padding-right: 50px;
            i {
                margin-right: 10px;
            }

        }

    }
}

</style>