<script>
  export default {
    name : 'AppMain'
  }
</script>

<template>
    <div class="main-options">
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>DIGITAL COMICS</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>DC MERCHANDISE</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>SUBSCRIPTION</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>COMIC SHOP LOCATOR</h3>
        </div>
       </div>
       <div class="card">
        <div><img src="../assets/img/buy-comics-digital-comics.png"></div>
        <div>
            <h3>DC POWER VISA</h3>
        </div>
       </div>
    </div>
</template>

<style>
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
        font-size: 10px;
    }
}
</style>