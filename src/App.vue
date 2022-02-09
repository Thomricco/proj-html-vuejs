<template>
  <div id="app">
    <header-nav :nav="nav"/>
    <jumbotron-box />
    <header-main />
    <main-box :icon="icon" />
    <main-number />
    <main-recent-work />
    <main-value />
    <home-owner />
    <main-news />
    <main-partners />
    <jumbo-footer />
    <footer-box :info="info" />

   
  </div>
</template>

<script>

import HeaderNav from './components/HeaderNav.vue'
import JumbotronBox from './components/JumbotronBox.vue'
import HeaderMain from './components/HeaderMain.vue'
import MainBox from './components/MainBox.vue'
import MainNumber from './components/MainNumber.vue'
import MainRecentWork from './components/MainRecentWork.vue'
import MainValue from './components/MainValue.vue'
import HomeOwner from './components/HomeOwners.vue'
import MainNews from './components/MainNews.vue'
import MainPartners from './components/MainPartners.vue'
import JumboFooter from './components/JumboFooter.vue'
import FooterBox from './components/FooterBox.vue'




export default {
  name: 'App',
  components: {
    HeaderNav,
    JumbotronBox,
    HeaderMain,
    MainBox,
    MainNumber,
    MainRecentWork,
    MainValue,
    HomeOwner,
    MainNews,
    MainPartners,
    JumboFooter,
    FooterBox,

   
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

    icon: [
      {
        id: '1',
        icon: 'fa-building',
        text: 'Buldings'
      },
      {
        id: '2',
        icon: 'fa-building',
        text: 'Renovate'
      },
      {
        id: '3',
        icon: 'fa-house',
        text: 'Construct'
      },
      {
        id: '4',
        icon: 'fa-truck',
        text: 'Exclusive'
      },
    ],

    info: [
        
        {
          id: '0371010656',
          location: 'Comporate Location',
          via: '1600 Amphitheatre Parkway',
          city: 'Londo WC1 1BA'
        },
        {
          id: '3098109658',
          location: 'Residential Location',
          via: '9521 Broadsberry Avenue',
          city: 'Paddington RC7 gZA'
        },
        {
          id: '3098109448',
          location: 'info@your-domain.com',
        },
        {
          id: '3098339448',
          location: 'Monday - Friday: 9:00 AM - 6:00 PM',
        },
        {
          id: '3338339448',
          location: 'Sunday - Sunday: 9:00 AM - 12:00 PM',
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
