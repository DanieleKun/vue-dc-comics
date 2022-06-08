<template>
  <div id="app">
    <DcHeader/>
    <main>
      <MainDcComics/>
      <DcComicsLinks/>
    </main>
    <DcFooter/>
    <DcFooterSocial/>
  </div>
</template>

<script>
import DcHeader from './components/DcHeader.vue'
import MainDcComics from './components/MainDcComics.vue'
import DcComicsLinks from './components/DcComicsLinks.vue'
import DcFooter from './components/DcFooter.vue'
import DcFooterSocial from './components/DcFooterSocial.vue'

export default {
  name: 'App',
  components: {
    DcHeader,
    MainDcComics,
    DcComicsLinks,
    DcFooter,
    DcFooterSocial
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
 /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
