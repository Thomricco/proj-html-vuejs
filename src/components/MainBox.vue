<template>
    <div class="container-box">
        <div class="container">
            <div v-for="icon in icon" :key="icon.id" class="box-img">
                <div class="box-font"><i :class="`${icon.i} ${icon.icon}`"></i></div>
                <p class="text">{{icon.text}}</p>
                <p>Adipisci repellendus vel sequi quas aliquid labore sit, laboriosam </p>
                <div class="after">
                    <div class="text-after">ARTULLY CRAFTED</div>
                    <p>Adipisci repellendus vel sequi quas aliquid labore sit, laboriosam </p>
                    <div class="bottone">GET QUOTE</div>
                </div>
            </div>
            
            
        </div>

    </div>
    
</template>

<script>
export default {
    props: {
        icon: Array
    }
    
}
</script>

<style lang="scss" scoped>
@import '../style/variabileColors.scss';

.container-box {
    margin: 0 auto;
    .container {
        margin: 0 auto;
        width: 1200px;
        display: flex;
        justify-content: center;
        text-align: center;
        color: $color-dove-gray;
       
        
        
        

        .box-img {
            width: 250px;
            height: 250px;
            background-color: $color-silver;
            margin-left: 30px;
            border-radius: 20px;
            padding: 30px;
            position: relative;
            &:hover {
                .after  {
                display: block;
                }
            }
          
            

            .box-font {
                height: 50px;
                width: 50px;
                border: 1px black solid;
                border-radius: 50px;
                margin: 0 auto;
                line-height: 50px;
                font-size: 20px;
                
            }
            .text {
                padding: 15px;
                font-size: 25px;
            }


        }
        .after {
            width: 250px;
            height: 250px;
            background-color: $color-bright-sun;
            
            border-radius: 20px;
            padding: 30px;
            position: absolute;
            top: 0;
            left: 0;
            display: none;
            .text-after {
                font-size: 20px;
                padding: 15px;
            }
            .bottone {
                width: 100px;
                height: 30px;
                text-align: center;
                background-color: $color-bright-sun-text-2;
                line-height:  20px;
                padding: 5px;
                font-size: 12px;
                color: $color-silver-dark;
                margin-left: 50px;
                margin-top: 10px;
                cursor: pointer;
               
            }
            

        }
    }
    
}

</style>