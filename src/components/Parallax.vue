<template>
  <v-parallax dark :src="require('../assets/BGsite2.jpg')">
    <v-layout align-center column justify-center>
      <v-layout row mb-4 class="white--text">
        <v-flex d-flex sm10 xs10 text-center>
          <h1>Programação</h1>
        </v-flex>
        <v-flex pt-3 mt-4 d-flex sm10 xs10 class="texto">
          <h4>
            


          </h4>

        </v-flex>

      </v-layout>

    </v-layout>
  </v-parallax>
</template>


<script>
  import Sobre from './Sobre'
  import Programacao from './Programacao'


  export default {

    name: 'App',
    components: {


      Sobre,
      Programacao,

    },
  }
</script>