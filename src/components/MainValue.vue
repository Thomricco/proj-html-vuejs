<template>
    <div class="container">
        <div class="box">
            <div class="box-text">
                <p class="text">Our Core Values</p>
                <div class="border"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa suscipit unde amet rerum, ipsum, tempore voluptatem! Impedi</p>
            </div>
            <div class="box-img">
                <div class="icon">
                    <div class="box-font green"></div>
                    <p class="text-mini">Great Services</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolor quis earum </p>
                </div>
                <div class="icon">
                    <div class="box-font blue"></div>
                    <p class="text-mini">Highest Standerds</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolor quis earum </p>
                </div>
                <div class="icon">
                    <div class="box-font orange"></div>
                    <p class="text-mini">Professional team</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolor quis earum </p>
                </div>
                <div class="icon">
                    <div class="box-font yellow"></div>
                    <p class="text-mini">Creative Solutions</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus dolor quis earum </p>
                </div>
            </div>
            
        </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '../style/variabileColors.scss';
.container {
    margin: 0 auto;
    background-color: $color-silver;
    .box {
        width: 1200px;
        margin: 0 auto;
        .box-text {
            margin: 0 auto;
            width: 600px;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }
        .border {
            width: 150px;
            border: 1px $color-bright-sun-text solid;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        .text {
            color: $color-dove-gray;
            font-size: 30px;
        }
        p {
            font-size: 12px;
            text-align: center;
            color: $color-dove-gray;
            margin-top: 10px;
        }
        .box-img {
            display: flex;
            justify-content: center;
            text-align: center;
            margin-top: 20px;

            .icon {
            width: 250px;
            height: 250px;
            border-radius: 20px;
            padding: 30px;

                .box-font {
                    height: 70px;
                    width: 70px;
                    border-radius: 50px;
                    margin: 0 auto;
                    
                }
                .box-font.green {
                    background-color: cadetblue;
                    &:hover {
                        background-color: $color-bright-sun;
                    }
                }
                .box-font.blue {
                    background-color: cornflowerblue;
                    &:hover {
                        background-color: $color-bright-sun;
                    }
                }
                .box-font.orange {
                    background-color: orangered;
                    &:hover {
                        background-color: $color-bright-sun;
                    }
                }
                .box-font.yellow {
                    background-color: yellowgreen;
                    &:hover {
                        background-color: $color-bright-sun;
                    }
                }
                .text-mini {
                    font-size: 12px;
                    &:hover {
                        color: $color-bright-sun;
                    }
                }
                .bord {
                    margin: 0 auto;
                    width: 20px;
                    border: 1px $color-dove-gray solid;
                    color: $color-dove-gray;
                    margin-top: 10px;
                }
            }

        }
        
    }
}

</style>