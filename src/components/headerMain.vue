<template>
    <div class="box">
        <div class="box-logo">
            <div class="img-box">
                <img src="@/assets/buy-comics-digital-comics.png" alt="">
                <span> DIGITAL COMICS </span>
            </div>
        </div>
        <div class="box-logo">
            <div class="img-box">
                <img src="@/assets/buy-comics-merchandise.png" alt="">
                <span> DC MERCHANDISE </span>
            </div>
        </div>
        <div class="box-logo">
            <div class="img-box">
                <img src="@/assets/buy-comics-subscriptions.png" alt="">
                <span> SUBSCRIPTIONS </span>
            </div>
        </div>
        <div class="box-logo">
            <div class="img-box">
                <img src="@/assets/buy-comics-shop-locator.png" alt="">
                <span> COMIC SHOP LOCATOR </span>
            </div>
        </div>
        <div class="box-logo">
            <div class="img-box">
                <img src="@/assets/buy-dc-power-visa.svg" alt="">
                <span> DC POWER VISA </span>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

.box {
    display: flex;
    background-color: rgb(41, 105, 224);
    justify-content: space-between;
    justify-content: center;

    .box-logo {
        height: 150px;

        .img-box {
            height: 50px;
            margin-top: 50px;
            display: flex;
            
            img {
                height: 50px;
                margin-left: 15px;
                padding: 10px;
                

            }

            span {
                font-size: 12px;
                color: #fff;
                line-height: 50px;
                margin-right: 20px;
            }
        
        }
    }
}

</style>>

