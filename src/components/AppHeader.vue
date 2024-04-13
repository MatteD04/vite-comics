<script>
  export default {
    name : 'AppHeader'
  }
</script>

<template>
    <div class="container">
        <div class="header-bar">
            <div class="logo">
                <img src="../assets/img/dc-logo.png">
            </div>
            <nav class="navigation">
                <ul>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#" class="active">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIBLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </div>

</template>

<style scoped lang="scss">
.header-bar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 15px 0;
}
.navigation{
    ul{
        list-style: none;
        display: flex;
        gap: 25px;
    }
    a {
        text-decoration: none;
        color: black;
    }
    .active{
        color: rgb(0, 129, 199);
    }
}
</style>