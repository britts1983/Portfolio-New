<template>
  <div id="app">
   <Users/>

  </div>
</template>

<script>
import Users from './components/Users.vue'


export default {

  name: 'app',
  components: {
    Users,

  },

  head: {
    script: [
      { src: '@/assets/lib/jquery/jquery.min.js' },
      { src: '@/assets/js/main.js' },
      { src: '@/assets/assets/lib/jquery/jquery-migrate.min.js' },
      { src: '@/assets/lib/jquery/jquery-migrate.min.js' },
      { src: '@/assets/lib/popper/popper.min.js' },
      { src: '@/assets/lib/bootstrap/js/bootstrap.min.js' },
      { src: '@/assets/lib/easing/easing.min.js' },
      { src: '@/assets/lib/counterup/jquery.waypoints.min.js' },
      { src: '@/assets/lib/counterup/jquery.counterup.js' },
      { src: '@/assets/lib/owlcarousel/owl.carousel.min.js' },
      { src: '@/assets/lib/lightbox/js/lightbox.min.js' },
      { src: '@/assets/lib/typed/typed.min.js' },
      { src: '@/assets/lib/jquery/jquery-migrate.min.js' },
      { src: '@/assets/contactform/contactform.js' },

    ],

  }


}
</script>

<style>
.black{
  position:fixed;
  top:0;
  background:white;
  width:100%;
  height:60px;
  transition:500ms ease;

  }
.black.scrolled{
  background:#000;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
   @import './assets/css/style-green.css';
   @import './assets/css/style-orange.css';
   @import './assets/css/style-purple.css';
   @import './assets/css/style-red.css';
   @import './assets/css/style-sky-blue.css';
   @import './assets/css/style.css';
   @import './assets/css/style.css';
   @import './assets/lib/font-awesome/css/font-awesome.min.css';
   @import './assets/lib/animate/animate.min.css';
   @import './assets/lib/ionicons/css/ionicons.min.css';
   @import './assets/lib/owlcarousel/assets/owl.carousel.min.css';
   @import './assets/lib/lightbox/css/lightbox.min.css';
   @import './assets/lib/bootstrap/css/bootstrap.min.css';

</style>
