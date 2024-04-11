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

    <div class="content">
        <div class="container">
            <div class="header-content">
                <h1>CONTENUTO 〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️</h1>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.header-bar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 25px 0;
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
}

.content{
    background-color: black;
}
.header-content{
    padding: 40px 0;
    color: white;
}
</style>