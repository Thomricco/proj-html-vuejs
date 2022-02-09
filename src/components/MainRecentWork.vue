<template>
    <div class="container">
        <div class="box-1">
            <div class="box-text">
                <p class="text">Explorer Recent Work</p>
                <div class="border"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate molestiae blanditiis provident, qui placeat culpa suscipit unde amet rerum, ipsum, tempore voluptatem! Impedi</p>
            </div>
            <div class="box-2">
                    <div class="afterbox">
                    <div class="box-img">
                        <div><img src="../assets/project2-featured-15013609-400x400.jpg" alt=""></div>
                    </div>
                    <div class="after">
                        <div class="icon-after">
                            <div class="box-icon"><i class="fas fa-link"></i></div>
                            <div class="box-icon"><i class="fas fa-search"></i></div>
                        </div>
                        <div class="text-after">
                            <p class="text-max">Florida Heath Facility<p>
                            <p class="text-small">Commercial</p>
                        </div>
                       
                    </div>
                </div>
                <div class="afterbox">
                    <div class="box-img">
                        <div><img src="../assets/project1-featured-294276386-400x400.jpg" alt=""></div>
                    </div>
                    <div class="after">
                        <div class="icon-after">
                            <div class="box-icon"><i class="fas fa-link"></i></div>
                            <div class="box-icon"><i class="fas fa-search"></i></div>
                        </div>
                        <div class="text-after">
                            <p class="text-max">Florida Heath Facility<p>
                            <p class="text-small">Commercial</p>
                        </div>
                       
                    </div>
                </div>
                <div class="afterbox">
                    <div class="box-img">
                        <div><img src="../assets/project3-featured-189023420-400x400.jpg" alt=""></div>
                    </div>
                    <div class="after">
                        <div class="icon-after">
                            <div class="box-icon"><i class="fas fa-link"></i></div>
                            <div class="box-icon"><i class="fas fa-search"></i></div>
                        </div>
                        <div class="text-after">
                            <p class="text-max">Florida Heath Facility<p>
                            <p class="text-small">Commercial</p>
                        </div>
                       
                    </div>
                </div>
            </div>
            
            
            <div class="view">
                <div class="bordo"></div>
                <div class="text-view">VIEW ALL PRODUCTS</div>
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
    .box-1 {
        width: 1200px;
        margin: 0 auto;
        .box-text {
            margin: 0 auto;
            width: 600px;
            margin-top: 20px;
            .border {
                margin: 0 auto;
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
        }
        
        .box-2 {
            margin: 0 auto;
            display: flex;
            justify-content: center;
            

            .afterbox {
                position: relative;
                margin-right: 17px;
                height: 250px;
                margin-top: 20px;
                &:hover {
                    .box-img {
                        display: none;
                    }
                }
                .box-img {
                    
                    margin-top: 20px;
                    position: absolute;
                    width: 250px;
                    height: 250px;
                    margin: 10px;
                    top: 0;
                    left: 0;
                    
                    
                        img{
                            width: 250px;
                            height: 250px;
                            margin: 10px;
                            padding: 10px;
                        }
                }
                .after {
                    margin-top: 20px;
                    background-color: $color-bright-sun;
                    width: 250px;
                    height: 250px;
                    margin-left: 20px;
                    border: 10px $color-white solid;
                    .icon-after {
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        margin-top: 50px;
                        
                        .box-icon {
                            width: 50px;
                            height: 50px;
                            border-radius: 50px;
                            text-align: center;
                            line-height: 50px;
                            background-color: $color-white;
                            margin: 10px;
                            i {
                                font-size: 20px;
                                color: $color-bright-sun;
                            }

                        }
                    }
                    .text-after {
                        text-align: center;
                        color: $color-white;
                        padding: 10px;
                        .text-max {
                            font-size: 15px;
                        }
                        .text-small {
                            margin-top: 10px;
                            font-size: 10px;
                        }
                    }
                    
                }
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
            .text-view {
                color: $color-silver-dark;
                width: 200px;
                font-size: 10px;

            }
        }
    }
}

</style>