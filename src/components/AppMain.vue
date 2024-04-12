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
            <h4>DIGITAL COMICS</h4>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-merchandise.png"></div>
        <div>
            <h4>DC MERCHANDISE</h4>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-shop-locator.png"></div>
        <div>
            <h4>SUBSCRIPTION</h4>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-subscriptions.png"></div>
        <div>
            <h4>COMIC SHOP LOCATOR</h4>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-dc-power-visa.svg"></div>
        <div>
            <h4>DC POWER VISA</h4>
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
    margin: 50px 0;
    gap: 10px;
    color: white;
    img{
        width: 50px;
    }
}
</style>