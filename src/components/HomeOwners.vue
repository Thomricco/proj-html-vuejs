<template>
    <div class="container">
        <div class="box">
            <div class="box-text">
                <p class="text">Our Home Owners Say</p>
                <div class="border"></div>
                <img src="../assets/home-testimonial-113165296.jpg" alt="">
                <p class="italic">"No man but feels more of a man in the world if he have a bit of ground that he can call his own. However small it is on the surface, it is for thousand miles deep: and that is a very handsome property."</p>
                <h5>HARRY SMITH - NEW HOME OWNER</h5>
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
    background: url(../assets/home-parallax-144609983.jpg) no-repeat;
    background-size: cover;
    .box {
        width: 1200px;
        height: 600px;
        margin: 0 auto;
        .box-text {
            text-align: center;
            padding: 150px;
            width: 850px;
            margin: 0 auto;
            .text {
                color: $color-white;
                font-size: 30px;
                margin: 20px;
            }
            .border {
                width: 150px;
                border: 1px $color-bright-sun-text solid;
                margin: 0 auto;
            }
            img {
                width: 100px;
                height: 100px;
                border: 1px black solid;
                border-radius: 50%;
                margin: 0 auto;
                margin-top: 20px
            }
            .italic {
                color: $color-white;
                padding: 20px;
                font-style: italic;
            }
            h5 {
                color: $color-white;
            }

        }
    }
}

</style>