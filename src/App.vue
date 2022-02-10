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
        i: 'far',
        icon: 'fa-building',
        text: 'Buldings'
      },
      {
        id: '2',
        i: 'fas',
        icon: 'fa-sync',
        text: 'Renovate'
      },
      {
        id: '3',
        i: 'fas',
        icon: 'fa-home',
        text: 'Construct'
      },
      {
        id: '4',
        i: 'fas',
        icon: 'fa-truck',
        text: 'Exclusive'
      },
    ],

    info: [
        
        {
          id: '0371010656',
          location: 'Comporate Location',
          via: '1600 Amphitheatre Parkway',
          city: 'Londo WC1 1BA',
          i: 'fas',
          icon: 'fa-globe',

        },
        {
          id: '3098109658',
          location: 'Residential Location',
          via: '9521 Broadsberry Avenue',
          city: 'Paddington RC7 gZA',
          i: 'fas',
          icon: 'fa-home',
        },
        {
          id: '3098109658',
          location: '1.800.458.556 / 1.800.532.2112',
          i: 'fas',
          icon: 'fa-phone',

        },
        {
          id: '3098109448',
          location: 'info@your-domain.com',
          i: 'far',
          icon: 'fa-envelope',
      
        },
        {
          id: '3098339448',
          location: 'Monday - Friday: 9:00 AM - 6:00 PM',
          i: 'fas',
          icon: 'fa-clock',
        },
        {
          id: '3338339448',
          location: 'Sunday - Sunday: 9:00 AM - 12:00 PM',
          i: 'fas',
          icon: 'fa-clock',
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
