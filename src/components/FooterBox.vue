<template>
    <div class="container">
        <div class="box-container">
            <div class="box-1">
                <div class="img-logo"><img src="../assets/footer-logo.png" alt=""></div>
                <div class="text-1"><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non fuga deserunt nisi maiores eveniet ea fugiat illo. Fuga reprehenderit provident quibusdam, facilis recusandae eum pariatur tempora officia eligendi rem unde.</p></div>
                <div class="bottone">LEARN MORE</div>
            </div>
            <div class="box-2">
                
            </div>
            <div class="box-3">
                
            </div>
            <div class="box-4">
                
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
    background-color: $color-dark;
    .box-container {
        width: 1200px;
        height: 800px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .box-1 {
            width: 25%;
            height: 600px;
            padding: 20px;
            border: 1px white solid;
            .img-logo {
                img {
                    width: 150px;
                    
                }
            }
            .text-1 {
                color: $color-dove-gray;
                padding: 10px;
                font-size: 12px;
            }
            .bottone {
                width: 150px;
                height: 40px;
                text-align: center;
                background-color: $color-bright-sun;
                padding: 5px;
                font-size: 15px;
                color: $color-silver-dark;
                line-height: 30px;
                margin-top: 10px;
                margin-left: 10px;
                &:hover {
                    cursor: pointer;
                    background-color: $color-tuatara;
                    color: $color-white;
                }
            }

        }
        .box-2 {
            width: 25%;
            height: 600px;
            border: 1px white solid;
        }
        .box-3 {
            width: 25%;
            height: 600px;
            border: 1px white solid;
        }
        .box-4 {
            width: 25%;
            height: 600px;
            border: 1px white solid;
        }
    }
}

</style>