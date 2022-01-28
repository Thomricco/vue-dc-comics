<template>
    <header>
        <div class="container">
            <div class="logo">
            <img src="@/assets/dc-logo.png" alt="">
            </div>
            <nav>
                <ul>
                    <li v-for="nav in nav" :key="nav.id">
                        <a :href="nav.url">
                            {{nav.label}}
                        </a>
                        
                    </li>
                    
                </ul>
            </nav>
        </div>
        
    </header>
</template>

<script>
export default {
    props: {
        nav: Array
    }
    
}
</script>

<style lang="scss" scoped>
@import '../style/variablecolors.scss';

header {
    
    height: 70px;
    
    background-color: $text-color-white;
    .container {
        width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: center;
            .logo {
            width: 40%;
            display: flex;
            justify-content: center;
            padding-right: 150px;
            
                img {
                    margin-top: 10px;
                    height: 50px;
                
                    
                }
            }

            nav {
                width: 60%;
                padding-right: 200px;

                ul {
                list-style: none;
                display: flex;
                justify-content: space-between;
                justify-content: center;
                line-height: 50px;

                    li {
                    //color: $text-color-gray-dark;
                    
                    font-size: 12px;
                    padding: 10px;
                    cursor: pointer;

                    &:hover {
                        color: rgb(41, 105, 224);
                        padding-bottom: 7px;
                        border-bottom: 2px $text-color-blue-clear solid;
                    }

                    a {
                        text-decoration: none;
                        color: $text-color-gray-dark;
                    }
                }
            }
        }

    }

}

</style>
