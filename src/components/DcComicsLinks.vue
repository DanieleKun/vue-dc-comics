<template>
    <section class="comics-link">
        <a v-for="(image, i) in images" href="#" :key="i">
            <img :src="image.url" alt="">
            <h2>{{image.name}}</h2>
        </a>
    </section>
</template>

<script>
export default {
    name: 'DcComicsLinks',
    data(){
        return{
            images: [
                {
                    url: require("../assets/img/buy-comics-digital-comics.png"),
                    name: "Digital Comics"
                },
                 {
                    url: require("../assets/img/buy-comics-merchandise.png"),
                    name: "DC Merchandise"
                },
                 {
                    url: require("../assets/img/buy-comics-subscriptions.png"),
                    name: "Subscription"
                },
                 {
                    url: require("../assets/img/buy-comics-shop-locator.png"),
                    name: "Comic Shop Locator"
                },
                 {
                    url: require("../assets/img/buy-dc-power-visa.svg"),
                    name: "Dc Power Visa"
                },
            ]
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.comics-link {
    height: 150px;
    background-color: rgb(2, 130, 249);
    display: flex;
    justify-content: space-around;
    
    img{
        width: 100px;
        height: auto;
    }
}
</style>
  
  
