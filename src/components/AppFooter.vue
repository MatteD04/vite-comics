<script>
  export default {
    name : 'AppFooter'
  }
</script>

<template>
    <div class="bg-footer">
        <div class="container">
            <div class="content-footer">
                <div>
                    <h1>contenuto</h1>
                </div>
            
                <div class="assets-footer">
                    <img src="../assets/img/dc-logo-bg.png">"
                </div>
            </div>
        </div>
    </div>
    
    <div class="bg-last-footer">
        <div class="container">
            <div>
                <button>SIGN-UP NOW</button>
            </div>
            <div>

            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.content-footer{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.assets-footer{
    img{
        width: 50%;
        overflow-y: hidden;
    }
}
.bg-footer{
    background-image: url('../assets/img/footer-bg.jpg');
    max-height: 300px;
}

.bg-last-footer{
    background-color: rgb(49, 49, 49);
}
</style>