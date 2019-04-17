<template>
  <v-app>
    
    <v-content id="body" class="grey lighten-4">
      <Header/>
    </v-content>

    <Footer/> 

  </v-app>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
import lechuga from '@/components/lechuga'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    lechuga

  },
  data () {
    return {
      //
    }  
  }
}
</script>
