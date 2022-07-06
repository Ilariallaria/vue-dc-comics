<template>
    <section>
      <div class="container">
        <div>ciao</div>
        <div class="big-logo"></div>
      </div>
    </section>
</template>

<script>
export default {
  name: 'FooterTop',


}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  section{
    height: 260px;
    background-image: url(../assets/footer-bg.jpg);
    
    .container{
    margin: 0 auto;
    width: 70%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;

      .big-logo{
        width: 45%;
        height: 100%;
        background-image: url(../assets/dc-logo-bg.png);
        background-size: cover;
        background-position: center;
      }

    }
  }
</style>
