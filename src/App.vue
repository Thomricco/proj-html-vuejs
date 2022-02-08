<template>
  <div id="app">
    <header-nav :nav="nav"/>
    <jumbotron-box />
    <headera-main />
    <footer-box />
   
  </div>
</template>

<script>

import HeaderNav from './components/HeaderNav.vue'
import JumbotronBox from './components/JumbotronBox.vue'
import HeaderaMain from './components/HeaderMain.vue'
import FooterBox from './components/FooterBox.vue'


export default {
  name: 'App',
  components: {
    HeaderNav,
    JumbotronBox,
    FooterBox,
    HeaderaMain,

   
  },
data () {
  return {
    nav: [
      {
        id: '6077493791',
        label: 'HOME',
        url: '/'
      },
      {
        id: '9815795645',
        label: 'ABOUT',
        url: '/'
      },
      {
        id: '1914470843',
        label: 'SERVICE',
        url: '/'
      },
      {
        id: '6148128000',
        label: 'WORK',
        url: '/'
      },
      {
        id: '0371010656',
        label: 'ARTICLES',
        url: '/'
      },
      
    ],
    
    
  };
},
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import './style/main.scss';

</style>
