<template>
  <div id="app">

    <PageHeader/>

    <main>

      <PageContent/>
      <MyProduct/>

    </main>

  </div>
</template>

<script>
import PageHeader from "./components/PageHeader.vue"
import PageContent from "./components/PageContent.vue"
import MyProduct from "./components/MyProduct.vue"


export default {
  name: 'App',
  components: {
    PageHeader,
    PageContent,
    MyProduct,
  },
};
</script>

<style lang="scss">
@import './style/commons.scss';
</style>
