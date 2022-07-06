<template>
<section>
    <div class="container">
        <button>SIGN-UP NOW</button>
        <div class="icons">
            <div>FOLLOW US</div>
        </div>
    </div>
</section>
</template>

<script>
export default {
 name: 'FooterBottom',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
    background-color: #303030;
    height: 80px;
    color: white;

    .container{
    margin: 0 auto;
    width: 70%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: rgba(211, 211, 211, 0.77);
    font-size: 9px;

    button{
        padding: 10px;
        background-color: #303030;
        border: 2px solid #0084f9;
        color: white;
    }

    .icons{
        display: flex;
        justify-content: space-between;
        align-items: center;
        
    }
    }

}
</style>
