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
                    <div class="box-font"></div>
                    <p class="text"></p>
                    <br>
                    <p class="text"></p>
                </div>
                <div class="icon">
                    <div class="box-font"></div>
                    <p class="text"></p>
                    <br>
                    <p class="text"></p>
                </div>
                <div class="icon">
                    <div class="box-font"></div>
                    <p class="text-mini">Lorem ipsum dolor sit amet </p>
                    <br>
                    <p class="text"></p>
                </div>
                <div class="icon">
                    <div class="box-font"></div>
                    <p class="text"></p>
                    <br>
                    <p class="text"></p>
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
        height: 300px;
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
            color: $color-silver-dark;
            font-size: 30px;
        }
        p {
            font-size: 12px;
            text-align: center;
            color: $color-silver-dark;
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
            margin-left: 30px;
            border-radius: 20px;
            padding: 30px;

                .box-font {
                    height: 100px;
                    width: 100px;
                    border: 1px black solid;
                    border-radius: 50px;
                    margin: 0 auto;
                    
                }
                .text {
                    padding: 15px;
                    font-size: 25px;
                }
            }

        }
        
    }
}

</style>