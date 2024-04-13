<script>
export default {
    name: 'SeriesCard',
    props: ['image','title']
}
</script>

<template>
    <div class="series-card">
        <div class="series-img"><img :src="image"></div>
        <div class="info-series"><h3>{{ title }}</h3></div>
    </div>
</template>

<style scoped lang="scss">
.series-card{
    width: calc((100% / 6) - 20px);
    margin-bottom: 40px;
}
.series-img{
    margin-bottom: 10px;
    img{
        width: 100%;
        height: 180px;
        overflow-y: hidden;
    }
}
.info-series{
    color: white;
}
</style>