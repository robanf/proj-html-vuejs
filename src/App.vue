<template>
  <div id="app">
    <Header/>
    <Main :array="lezioni"/>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  },
  data(){
      return{
          lezioni:[
            {
              img:'cat_2-272x161.jpg',
              type:'Art',
              name:'Roba di arte',
              vote:3,
              time:'4 hours',
              cost:45.99,
              special:'new',
              feat:true,
            },
               {
              img:'course-preview-272x161.jpg',
              type:'Software Development',
              name:'Diventa un programmatore esperto',
              vote:5,
              time:'9 hours',
              cost:0,
              special:'hot',
              feat:false,
            },
               {
              img:'photo-1496307042754-b4aa456c4a2d-272x161.jpeg',
              type:'Electronic',
              name:'Come diventare un dj, le basi della musica',
              vote:0,
              time:'5 hours',
              cost:49,
              special:'special',
              feat:true,
            },
               {
              img:'photo-1475452779376-caebfb988090-272x161.jpeg',
              type:'Bicycling',
              name:'i migliori percorsi montuosi',
              vote:4,
              time:'2 hours',
              cost:20,
              special:'',
              feat:false,
            }
          ]
      }
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300&display=swap');
@import '@/style/general.scss';

</style>
