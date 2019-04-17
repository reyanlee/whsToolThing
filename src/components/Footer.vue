<template>
  <v-footer>
    <v-card class="flex flat tile">
      <v-card-title class="grey lighten-3 px-5 #E0E0E0--text">
        <strong>Waipahu High School</strong>
        <v-layout justify-center row wrap>
        <v-btn v-for="link in links" :key="link" color="grey" round flat>
          {{ link }}
        </v-btn>
        <v-btn color="grey" flat round class="px-5">
          <v-icon>code</v-icon>
        </v-btn>
        </v-layout>
        </v-card-title>
      </v-card>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      links: [
          'About',
          'Contact Us',
      ]

    })
  }
</script>
