<template>
  <div class="HeaderCom">
    <v-toolbar fixed app class="">
      <v-toolbar-side-icon @click="drawer=!drawer"></v-toolbar-side-icon>
      <v-toolbar-title class="headline text-uppercase mr-5">
        <span>PHN</span>
        <span class="subheading font-weight-light "> WHS TOOLS</span>
      </v-toolbar-title>

      <v-toolbar-items>

        <v-btn flat color="grey" class="">
          <v-icon>home</v-icon>
        </v-btn>

        <v-btn flat color="grey" class="px-4 ">
          <span>Registration</span>
        </v-btn>

        <v-divider vertical class="py-3" inset></v-divider>

        <v-btn flat color="grey">
          <span>Honors</span>
        </v-btn>
      </v-toolbar-items>

      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-text-field label="Search..." prepend-icon="search" class="mr-3"></v-text-field>
      </v-toolbar-items>
    </v-toolbar>
    <v-navigation-drawer v-model="drawer" color="red" app></v-navigation-drawer>
  </div>
</template>

<script>
  export default {
    data: () => ({
      drawer: false

    })
  }
</script>
