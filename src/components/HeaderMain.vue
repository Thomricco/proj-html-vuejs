<template>
    <div class="container">
        <div class="header-contain">
            <p>Do You Have A Construction Project We Can Help With?</p>
            <div class="bottone">GET A FREE QUOTE</div>
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
    background-color: $color-bright-sun;
    .header-contain {
        padding-top: 20px;
        width: 1200px;
        margin: 0 auto;
        height: 80px;
        text-align: center;
        font-size: 20px;
        line-height: 80px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
            p {
                height: 60px;
            }
            .bottone {
                width: 150px;
                height: 30px;
                text-align: center;
                line-height:  20px;
                padding: 5px;
                font-size: 12px;
                background-color: $color-tuatara;
                color: $color-white;
                margin-left: 15px;
                border: 1px $color-white solid;
                &:hover {
                    cursor: pointer;
                    background-color: $color-white;
                    color: $color-silver-dark;
                    border: 1px $color-silver-dark solid;
                    
                }
            }
    }
}

</style>