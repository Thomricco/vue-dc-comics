<template>
    <header>
        <div class="container">
            <div class="bottone"> 
            <div class="sing-up">SING-UP NOW!</div>
            </div>
            <nav>
                <div class="follow">FOLLOW US</div>
                <img src="@/assets/footer-facebook.png" alt="">
                <img src="@/assets/footer-twitter.png" alt="">
                <img src="@/assets/footer-youtube.png" alt="">
                <img src="@/assets/footer-pinterest.png" alt="">
                <img src="@/assets/footer-periscope.png" alt="">
            </nav>
        </div>
        
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
//@import './style/variablecolors.scss';

header {
    height: 70px;
    background-color: #333;
    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        .bottone {
        width: 40%;
        display: flex;
        justify-content: center;
        margin-left: 20px;
        

            .sing-up {
                margin-top: 15px;
                text-align: center;
                line-height: 40px;
                width: 150px;
                height: 40px;
                border: 2px rgb(41, 105, 224) solid;
                color: #fff;
            }
            
            
        }

        nav {
            width: 60%;
            display: flex;
            justify-content: center;
            align-items: center;
            
            .follow {
                margin-top: 5px;
                color: rgb(41, 105, 224);
                line-height: 70px;
                margin-right: 20px;

            }
            img {
                    height: 25px;
                    line-height: 70px;
                    margin-right: 20px;
                }

            
        }

    }


}

</style>>