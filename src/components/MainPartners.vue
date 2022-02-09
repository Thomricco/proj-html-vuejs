<template>
    <div class="container">
        <div class="box">
            <div class="box-text">
                <p class="text">Trusted Partners</p>
                <div class="border"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa suscipit unde amet rerum, ipsum, tempore voluptatem! Impedi</p>
            </div>
            <div class="container-img">
                <div class="box-img">
                    <img src="../assets/home-logo11-219096700-320x202.png" alt="">
                </div>
                <div class="box-img">
                    <img src="../assets/home-logo10-219096700-320x202.png" alt="">
                </div>
                <div class="box-img">
                    <img src="../assets/home-logo2-219096700-320x202.png" alt="">
                </div>
                <div class="box-img">
                    <img src="../assets/home-logo1-219096700-320x202.png" alt="">
                </div>
                <div class="box-img">
                    <img src="../assets/home-logo9-219096700-320x202.png" alt="">
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
    .box {
        width: 1200px;
        margin: 0 auto;
        .box-text {
            margin: 0 auto;
            width: 600px;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding-top: 20px;
            text-align: center;
            .border {
            width: 150px;
            border: 1px $color-bright-sun-text solid;
            margin-top: 20px;
            margin-bottom: 20px;
            }
            .text {
                color: $color-silver-dark;
                font-size: 30px;
            }
            p {
                font-size: 12px;
                color: $color-silver-dark;
                margin-top: 10px;
            }
        }
        .container-img {
            display: flex;
            justify-content: center;
            margin: 0 auto;

            .box-img {
                

                img {
                    width: 200px;
                    height: 150px;
                    padding: 20px;
                    margin-top: 20px;
                }
            }

        }
        
    }
}

</style>