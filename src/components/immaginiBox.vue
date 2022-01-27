<template>
    <div class="container">

        <div class="box">
            <div class="button">CURRENT SERIES</div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">ACTION COMICS</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">AMERICANVAMPIRE 1976</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">ACQUAMAN</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATGIRL</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMAN</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMAN BEYORD</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMANSUPERMAN</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMANSUPERMAN
                    ANNUAL
                </div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMAN: THE JOKER WAR
                    ZONE
                </div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMAN: THREE JOKERS</div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">BATMAN: WHITHE KNIGHT
                    PREDENTS: HARLEY QUINN
                </div>
            </div>
            <div class="box-immagini">
                <div class="immagine"></div>
                <div class="text">CATWOMAN</div>
            </div>
            
        </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

.container {
    height: 600px;
    background-color: #333;
    
    .box {
        width: 1200px;
        height: 600px;
        margin: 0 auto;
        //border: 1px #fff solid;
        position: relative;
        display: flex;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        .button {
            position: absolute;
            top: -25px;
            left: 30px;
            width: 170px;
            height: 40px;
            color: #fff;
            background-color: rgb(41, 105, 224);
            text-align: center;
            line-height: 40px;
        }
        .box-immagini {
            margin: 20px;

            
            .immagine {
                width: 150px;
                height: 150px;
                border: 1px #fff solid;
                
            }
            .text {
                color: #fff;
                font-size: 11px;
                width: 150px;
                margin-top: 5px;
            }
        }
    }
}

</style>>
