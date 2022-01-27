<template>
    <header>
        <div class="logo">
            <img src="@/assets/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
//@import './style/variablecolors.scss';

header {
    width: 1200px;
    height: 70px;
    display: flex;

    .logo {
        width: 40%;
        display: flex;
        justify-content: center;
        
        img {
            margin-top: 10px;
            height: 50px;
           
            
        }
    }

    nav {
        width: 60%;

        ul {
        list-style: none;
        display: flex;
        justify-content: space-between;
        justify-content: center;
        line-height: 50px;

        li {
            //color: $text-color-gray-dark;
            color: #333;
            font-size: 12px;
            padding: 10px;
            cursor: pointer;

            &:hover {
                color: rgb(41, 105, 224);
                padding-bottom: 7px;
                border-bottom: 2px rgb(41, 105, 224) solid;
            }
        }
    }
    }

}

</style>>
