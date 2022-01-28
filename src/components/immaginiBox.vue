<template>
    <div class="container">

        <div class="box">
            <div class="button">CURRENT SERIES</div>
            <div v-for="(immagini, index ) in immagini" :key="index" class="box-immagini">
                <img :src="immagini.thumb" alt="" class="immagine">
                <div class="text">{{immagini.series}}</div>
            </div>
            <div class="button-two">LOAD MORE</div>
            
        </div>
        
    </div>
</template>

<script>
export default {
    props: {
        immagini: Array
    }
    
}
</script>

<style lang="scss" scoped>

.container {
    height: 650px;
    background-color: #333;
    
    .box {
        width: 1000px;
        height: 600px;
        margin: 0 auto;
        //border: 1px #fff solid;
        position: relative;
        display: flex;
        justify-content: space-between;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        .button {
            position: absolute;
            top: -25px;
            left: 5px;
            width: 170px;
            height: 40px;
            color: #fff;
            background-color: rgb(41, 105, 224);
            text-align: center;
            line-height: 40px;
        }
        .button-two {
            position: absolute;
            bottom: 1px;
            width: 170px;
            height: 40px;
            color: #fff;
            background-color: rgb(41, 105, 224);
            text-align: center;
            line-height: 40px;
        }
        .box-immagini {
            margin: 5px;
           
            

            
            .immagine {
                width: 150px;
                height: 150px;
                
                
            }
            .text {
                color: #fff;
                font-size: 11px;
                width: 150px;
                height: 30px;
                margin-top: 5px;
            }
        }
    }
}

</style>>
