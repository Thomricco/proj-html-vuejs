<template>
    <div class="container">
        <div class="container-box">
            <div class="box-one">
                    
                <p class="text">Bulding Ispiring Spaces</p>
                <div class="border"></div>
                <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa s</p>
                
            </div>
            <div class="box-two">
                <div class="bottone">GET A FREE QUOTE</div>
                <p>Only takes a few seconds!</p>


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
    background: url(../assets/about-call-to-action-57862405.jpg) no-repeat;
    background-size: cover;
    background-position: center;
    .container-box {
        margin: 0 auto;
        width: 1200px;
        height: 400px;
        display: flex;
        align-items: center;
        
        .box-one {
            width: 60%;
            height: 200px;
            padding-left: 200px;
            
            
            .text {
                color: $color-white;
                font-size: 30px;
                margin-top: 40px;
                
            }
            .border {
                width: 150px;
                border: 1px $color-bright-sun-text solid;
                margin-top: 20px;
                margin-bottom: 20px;
            }
            .lorem {
                font-size: 14px;
                color: $color-white;
                margin-top: 20px;
            }
        }
        .box-two {
            width: 40%;
            height: 200px;
            .bottone {
                width: 220px;
                height: 40px;
                text-align: center;
                background-color: $color-bright-sun;
                padding: 5px;
                font-size: 15px;
                color: $color-silver-dark;
                margin-left: 15px;
                line-height: 30px;
                margin-top: 80px;
                margin-left: 100px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-tuatara;
                    color: $color-white;
                }
            }
            p {
                margin-left: 150px;
                font-size: 10px;
                color: $color-white;
            }   
        }
        
    }
}

</style>