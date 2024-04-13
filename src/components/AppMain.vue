<script>
import SeriesCard from './SeriesCard.vue';

export default {
    name : 'AppMain',
    components: {
        SeriesCard
    },
    data() {
        return{
            series: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        };
    }
}
</script>

<template>
    <div class="content">
        <div class="container current-series">
           <SeriesCard v-for="serie in series" :title="serie.series" :image="serie.thumb"></SeriesCard>
        </div>
        <div class="more">
            <button>LOAD MORE</button>
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
    padding: 40px 0;
    .more{
        text-align: center;
        button{
            background-color: rgb(0, 129, 199);
            padding: 10px 50px;
            border: none;
            cursor: pointer;
            color: white;

        }
    }
}
// .header-content{
//     padding: 40px 0;
//     color: white;
// }
.current-series{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
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
        width: 40px;
    }
}
</style>