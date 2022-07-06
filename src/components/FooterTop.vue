<template>
    <section>
      <div class="container">

        <div class="footer-menu">
          <div>
            <ul>
              <li class="title-menu">DC COMICS</li>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Viedeos</li>
              <li>News</li>
            </ul>
            <ul>
              <li class="title-menu">SHOP</li>
              <li>Schop DC</li>
              <li>Schop DC Collectibles</li>
            </ul>

          </div>

          <div>
            <ul>
              <li class="title-menu">DC</li>
              <li>Terms Of Use</li>
              <li>Privacy policy (News)</li>
              <li>Add Choise</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscription</li>
              <li>Talent Workshop</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
          </div>
          
          <div>
            <ul>
              <li class="title-menu">SITES</li>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Vise</li>
            </ul>
          </div>
        </div>

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
    color: rgba(211, 211, 211, 0.77);
    font-size: 9px;

        .footer-menu{
          width: 30%;
          display: flex;
          justify-content: space-between;

        .title-menu{
          font-size: 13px;
          font-weight: 600;     
          padding-top: 25px;
          padding-bottom: 10px;
          color: white;
        }

        li{
          line-height: 15px;
        }
      }

      .big-logo{
        width: 42%;
        height: 100%;
        background-image: url(../assets/dc-logo-bg.png);
        background-size: cover;
        background-position: center;
      }

    }
  }
</style>
