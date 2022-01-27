<template>
    <footer>
        <div class="box">
            <div class="nav-left">
                <div class="box-1">
                    <div class="title">DC COMICS</div>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Tv</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        
                    </ul>
                    <div class="title">SHOP</div>
                    <ul>
                        <li>d</li>
                        <li>d</li>
                    </ul>
                </div>
                <div class="box-1">
                    <div class="title">DC</div>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy Polici (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshop</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                        
                    </ul>
                </div>
                <div class="box-1">
                    <div class="title">SITES</div>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>Tv</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                        
                    </ul>
                </div>
                

            </div>
            <div class="nav-right">
                <img src="@/assets/dc-logo-bg.png" alt="">
            </div>
        </div>
        

    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

footer {
    height: 300px;
    background: url('../assets/footer-bg.jpg') no-repeat;
    background-size: cover;

    .box {
        margin: auto 0;
        width: 1200px;
        display: flex;

        .nav-left {
            width: 60%;
            display: flex;
            justify-content: center;
            
            
            .box-1 {
                margin-left: 70px;
                margin-top: 30px;
                .title {
                    color: #fff;
                    margin-top: 20px;
                    margin-bottom: 12px;
                }
                ul {
                    list-style: none;

                    li {
                        color: #777;
                        font-size: 10px;
                        padding: 3px;

                    }
                }
            }
        }
        .nav-right {
            width: 40%;
            img {
                width: 300px;
                padding-bottom: 100px;
            }
    
        }
    }

    
}

</style>>
