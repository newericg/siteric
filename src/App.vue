<template>
  <v-app fluid >
      <img :src="require('./assets/BGimg.png')" id="bg" alt="">
      <Toolbar2/>
    <v-content>
      <Home/>
    </v-content>
    <Footer id="contato"/>
  </v-app>
</template>

<script>

import smoothscroll from 'smoothscroll-polyfill'
import Toolbar from './components/Toolbar'
import Header from './components/Header'
import Footer from './components/Footer'
import Parallax from './components/Parallax'
import Sobre from './components/Sobre'
import Programacao from './components/Programacao'
import Toolbar2 from './components/Toolbar2'
import Home from './components/Home'




export default {
  
  name: 'App',
  components: {
    
    Home,
    Toolbar,
    Footer,
    Parallax,
    Header,
    Sobre,
    Programacao,
    Toolbar2,
  },
  mounted(){
    smoothscroll.polyfill();
  },
  data () {
    return {
      //
    }
  }
};


  

</script>
<style>



.texto{
  text-align: center;
  font-family: 'Inconsolata', monospace;
}

#bg {
  position: fixed; 
  top: 0; 
  left: 0; 
	
  /* Preserve aspet ratio */
  min-width: 100%;
  min-height: 100%;
}

</style>
