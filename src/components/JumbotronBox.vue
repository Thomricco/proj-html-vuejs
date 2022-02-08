<template>
    <div class="container">
        <div class="jumbo-box">
            <h1>BUILDING INSPIRING SPACES</h1>
            <p>We Buil Inspiring Residential & Commercial Space</p>
            <div class="container-bottoni">
                <div class="bottone-one">EXPLORE RECENT WORK</div>
                <div class="bottone-two">GET A QUOTE TODAY</div>
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
    background: url(../assets/home-slider-62528242.jpg) no-repeat;
    background-size: cover;
    height: 500px;
    .jumbo-box {
        margin: 0 auto;
        width: 1200px;
        text-align: center;
        line-height: 430px;
        h1 {
            color: $color-white;
            font-size: 40px;
            height: 50px;
        }
        p {
            color: $color-bright-sun-text;
            font-size: 18px;
            height: 50px;
        }
        .container-bottoni {
            display: flex;
            justify-content: center;
            width: 1200px;
            height: 400px;
            padding-top: 50px;
            align-items: center;

            .bottone-one {
                width: 220px;
                height: 40px;
                text-align: center;
                background-color: $color-silver-dark;
                line-height:  30px;
                padding: 5px;
                font-size: 15px;
                color: $color-white;
                margin-left: 15px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-bright-sun;
                    color: $color-silver-dark;
                }
            } 
            .bottone-two {
                width: 220px;
                height: 40px;
                text-align: center;
                background-color: $color-bright-sun;
                line-height:  30px;
                padding: 5px;
                font-size: 15px;
                color: $color-silver-dark;
                margin-left: 15px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-silver-dark;
                    color: $color-white;
                }
            }                      
        }
    }
}

</style>