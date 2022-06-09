<template>

    <div class="cards">
        <img :src="details.thumb" alt="details.series">
        <h4>{{details.series}}</h4>
    </div>

</template>

<script>
export default {
    name: 'DcCardComics',
    props: {
        details: Object
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
