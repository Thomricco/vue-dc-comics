<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
    <immagini-box />
    <header-main />
    <footer-box />
    <header-footer-box />
  </div>
</template>

<script>

import headerBox from './components/headerBox.vue'
import jumbotronBox from './components/jumbotronBox.vue'
import immaginiBox from './components/immaginiBox.vue'
import headerMain from './components/headerMain.vue'
import footerBox from './components/footerBox.vue'
import headerFooterBox from './components/headerFooterBox.vue'


export default {
  name: 'App',
  components: {
   headerBox,
   jumbotronBox,
   immaginiBox,
   headerMain,
   footerBox,
   headerFooterBox,
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';

</style>
