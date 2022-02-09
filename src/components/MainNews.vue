<template>
    <div class="container">
        <div class="box">
            <div class="box-text">
                <p class="text">Latest News</p>
                <div class="border"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa suscipit unde amet rerum, ipsum, tempore voluptatem! Impedi</p>
            </div>
            <div class="box-img">
                <div class="box-text-card">
                    <img src="../assets/blog-post-134132600-400x241.jpg" alt="">
                    <h3>Redeveloping Florida's Remote Southern Coast</h3>
                    <p class="data">Decembre 7th 2015</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt voluptas dignissimos a rem, suscipit neque voluptatum eveniet iure aliquam, fugiat molestiae laudantium. Aperiam, error. Inventore porro beatae accusantium non dolore.</p>
                </div>
                <div class="box-text-card">
                   <img src="../assets/blog-post-92486644-400x241.jpg" alt="">
                    <h3>Redeveloping Florida's Remote Southern Coast</h3>
                    <p class="data">Decembre 7th 2015</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt voluptas dignissimos a rem, suscipit neque voluptatum eveniet iure aliquam, fugiat molestiae laudantium. Aperiam, error. Inventore porro beatae accusantium non dolore.</p>
                </div>
                <div class="box-text-card">
                    <img src="../assets/blog-post-332773904-400x241.jpg" alt="">
                    <h3>Redeveloping Florida's Remote Southern Coast</h3>
                    <p class="data">Decembre 7th 2015</p>
                    <div class="bord"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt voluptas dignissimos a rem, suscipit neque voluptatum eveniet iure aliquam, fugiat molestiae laudantium. Aperiam, error. Inventore porro beatae accusantium non dolore.</p>
                </div>
            </div>
            <div class="view">
                <div class="bordo"></div>
                <p>VIEW ALL ARTICLES</p>
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
            padding-top: 20px;
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
            color: $color-silver-dark;
            margin-top: 10px;
        }
        .box-img {
            display: flex;
            justify-content: center;
            margin: 0 auto;
            margin-top: 20px;
            width: 250px;
            height: 450px;
            
            .box-text-card {
                width: 250px;
                height: 450px;
                margin: 10px;

                .data {
                    font-size: 7px;
                }

                img{
                    width: 250px;
                    height: 200px;
                    margin: 10px;
                }
            }
        }
        .view {
            display: flex;
            justify-content: center;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
            .bordo {
                width: 200px;
                height: 1px;
                border: 1px $color-white solid;
                margin-left: 205px;
                margin-right: 205px;
            }
            p {
                color: $color-silver-dark;
                width: 200px;
                padding-bottom: 20px;

            }
        }
    }
}

</style>