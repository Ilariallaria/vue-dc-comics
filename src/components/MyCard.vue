<template>
    <div class="card-wrapper">
        <img class="single-card" :src="productDetail.thumb" :alt="productDetail.series">
        <h2 class="single-title">{{productDetail.series}}</h2>
    </div>
</template>

<script>
export default {
name: "MyCard",

props:{
    productDetail: Object
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    .card-wrapper{
        width: calc((100% / 6) - 20px);
        margin: 10px;


        .single-card{
            background-color: lightgreen;
            object-fit: cover;
            object-position: top;
            width: 100%;
            aspect-ratio: 1/1;
            overflow-y: hidden;
            
        }

        .single-title{
            width: 130px;
            font-size: 10px;
            text-transform: uppercase;
            margin-top: 10px
        }
    }
</style>
