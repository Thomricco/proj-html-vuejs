<template>
    <div class="container">
        <div class="box">
            <div class="box-img">
                <i></i>
                <div class="number">3534</div>
                <p class="text">PLANNING APPLICATIONS</p>
            </div>
            <div class="box-img">
                <i></i>
                <div class="number">896</div>
                <p class="text">COMPLETED PROJECT</p>
            </div>
            <div class="box-img">
                <i></i>
                <div class="number">272</div>
                <p class="text">TRAINED PROFESSIONALS</p>
            </div>
            <div class="box-img">
                <i></i>
                <div class="number">29</div>
                <p class="text">INTERNATIONAL OFFICE</p>
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
    background: url(../assets/home-244125289.jpg) no-repeat;
    background-size: cover;
    .box {
        margin: 0 auto;
        margin-top: 50px;
        width: 1200px;
        height: 400px;
        display: flex;
        justify-content: center;
        align-items: center;

        .box-img {
            margin-left: 40px;
            text-align: center;

            .number {
                font-size: 40px;
                color: $color-bright-sun-text;
            }
            .text {
                color: $color-white;
                font-size: 10px;

            }

        }
    }
}

</style>