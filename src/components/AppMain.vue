<script>
  export default {
    name : 'AppMain'
  }
</script>

<template>
    <div class="content">
        <div class="container">
            <div class="header-content">
                <h1>CONTENUTO 〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️〰️</h1>
            </div>
        </div>
    </div>

    <div class="main-options">
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>DIGITAL COMICS</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-merchandise.png"></div>
        <div>
            <h3>DC MERCHANDISE</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-shop-locator.png"></div>
        <div>
            <h3>SUBSCRIPTION</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-subscriptions.png"></div>
        <div>
            <h3>COMIC SHOP LOCATOR</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-dc-power-visa.svg"></div>
        <div>
            <h3>DC POWER VISA</h3>
        </div>
       </div>
    </div>
</template>

<style scoped lang="scss">
.content{
    background-color: black;
}
.header-content{
    padding: 40px 0;
    color: white;
}

.main-options{
    display: flex;
    gap: 50px;
    justify-content: center;
    background-color: rgb(0, 129, 199);
}
.card{
    display: flex;
    align-items: center;

    img{
        font-size: 30px;
    }
}
</style>