<template>
  <div id="app">

    <header>

      <PageHeader/>

    </header>

    <main>

      <PageContent/>
      <MyProduct/>

    </main>

    <footer>
      
      <FooterTop/>
      <FooterBottom/>

    </footer>

  </div>
</template>

<script>
import PageHeader from "./components/PageHeader.vue"
import PageContent from "./components/PageContent.vue"
import MyProduct from "./components/MyProduct.vue"
import FooterTop from "./components/FooterTop.vue"
import FooterBottom from "./components/FooterBottom.vue"


export default {
  name: 'App',
  components: {
    PageHeader,
    PageContent,
    MyProduct,
    FooterTop,
    FooterBottom,
  },
};
</script>

<style lang="scss">
@import './style/commons.scss';
</style>
