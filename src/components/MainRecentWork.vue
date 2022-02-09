<template>
    <div class="container">
        <div class="box">
            <div class="box-text">
                <p class="text">Explorer Recent Work</p>
                <div class="border"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa suscipit unde amet rerum, ipsum, tempore voluptatem! Impedi</p>
            </div>
            <div class="box-img">
                <div><img src="../assets/project2-featured-15013609-400x400.jpg" alt=""></div>
                <div><img src="../assets/project1-featured-294276386-400x400.jpg" alt=""></div>
                <div><img src="../assets/project3-featured-189023420-400x400.jpg" alt=""></div>
            </div>
            <div class="view">
                <div class="bordo"></div>
                <p>VIEW ALL PRODUCTS</p>
                <div class="bordo"></div>
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
    background-color: $color-white;
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
            margin-top: 20px;
            
            img{
                width: 250px;
                height: 250px;
                margin: 10px;
            }
        }
        .view {
            display: flex;
            justify-content: center;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 100px;
            .bordo {
                width: 200px;
                height: 1px;
                border: 1px $color-silver solid;
                margin-left: 205px;
                margin-right: 205px;
            }
            p {
                color: $color-silver-dark;
                width: 200px;

            }
        }
    }
}

</style>