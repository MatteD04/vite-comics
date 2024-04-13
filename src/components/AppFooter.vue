<script>
  export default {
    name : 'AppFooter'
  }
</script>

<template>
    <div class="bg-footer">
        <div class="container">
            <div class="content-footer">
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
                <h1>contenuto</h1>
            </div>
        </div>
    </div>
    
    <div class="bg-last-footer">
        <div class="container footer-info">
            <div class="sign-up">
                <button>SIGN-UP NOW</button>
            </div>
            <div class="follow-us">
                <h3>FOLLOW US</h3>
                <div class="social">
                    <img src="../assets/img/footer-facebook.png">
                    <img src="../assets/img/footer-twitter.png">
                    <img src="../assets/img/footer-youtube.png">
                    <img src="../assets/img/footer-pinterest.png">
                    <img src="../assets/img/footer-periscope.png">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.assets-footer{
    img{
        width: 50%;
        overflow-y: hidden;
    }
}
.bg-footer{
    background-image: url('../assets/img/footer-bg.jpg');
    min-height: 300px;
    .container{
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: 100%;
        background-repeat: no-repeat;
    }
    h1{
        color: white;
    }
}

.footer-info{
    display: flex;
    justify-content: space-between;
    padding: 15px;
}
.follow-us{
    display: flex;
    align-items: center;
    gap: 25px;

    h3{
        color: rgb(0, 129, 199);
    }
}
.social{
    display: flex;
    gap: 20px;
}

.bg-last-footer{
    background-color: rgb(49, 49, 49);
    padding: 20px 0;
}
.sign-up{
    button{
        background-color: transparent;
        padding: 10px;
        color: white;
        border: 2px solid rgb(0, 129, 199);
        cursor: pointer;
    }
}
</style>