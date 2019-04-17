<template>
  <v-app>
    
    <v-content id="body" class="grey lighten-4">
      <Header/>
      <CTEreq/>
    </v-content>

    <Footer/> 

  </v-app>
</template>

<script>
import Header from '@/components/Header'
import Math from '@/components/Math'
import Footer from '@/components/Footer'
export default {
  name: 'App',
  components: {
    Header,
    Math,
    Footer,

  },
  data () {
    return {
      //
    }  
  }
}
</script>
