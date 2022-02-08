<template>
    <div class="container-box">
        <div class="container">
            <div v-for="icon in icon" :key="icon.id" class="box-img">
                <div class="box-font"><i class="fa-regular fa-building"></i></div>
                <p class="text">{{icon.text}}</p>
                <p>Adipisci repellendus vel sequi quas aliquid labore sit, laboriosam </p>
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
            background-color: $color-papmps;
            margin-left: 30px;
            border-radius: 20px;
            padding: 30px;

            .box-font {
                height: 50px;
                width: 50px;
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

</style>