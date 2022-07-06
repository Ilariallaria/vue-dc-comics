<template>
  <section>
    <div class="container">
      <div>
        <img src="../assets/buy-comics-digital-comics.png" alt="DIGITAL COMIC">
        <span>DIGITAL COMICS</span>
      </div>
      <div>
        <img src="../assets/buy-comics-merchandise.png" alt="DC MERCHANDISE">
        <span>DC MERCHANDISE</span>
      </div>
      <div>
        <img src="../assets/buy-comics-subscriptions.png" alt="SUBSCRIPTION">
        <span>SUBSCRIPTION</span>
      </div>
      <div>
        <img src="../assets/buy-comics-shop-locator.png" alt="COMICS SHOP LOCATOR">
        <span>COMICS SHOP LOCATOR</span>
      </div>
      <div>
        <img src="../assets/buy-dc-power-visa.svg" alt="DC POWER VISA">
        <span>DC POWER VISA</span>
      </div>
      
    </div>
  </section>
</template>

<script>
export default {
  name: 'MyProduct',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  section{
  height: 110px;
  background-color: #0084f9;

    .container{
    margin: 0 auto;
    width: 70%;
    height: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: white;

      div{
        display: flex;
        align-items: center;

        img{
        width: auto;
        height: 35px;
        display: inline;

        }

        &:last-child img{
            height: 25px;
        }

        span{
          padding-left: 10px;
          font-size: 9px;
        }
      

      }

    }


  }

</style>
