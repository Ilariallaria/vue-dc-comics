<template>
    <section>
        <img src="../assets/jumbotron.jpg" alt="jumbotron">
    </section>
</template>

<script>
export default {
  name: 'MyBanner',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section{
        height: 260px;

        img{
            width: 100%;
            height: 100%;
            object-fit:cover;
            object-position: top;
        }
        
    }
</style>
