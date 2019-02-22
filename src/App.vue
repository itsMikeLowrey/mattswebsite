<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title>Matt Murphy</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn flat>Cars</v-btn>
          <v-btn flat>motorcycles</v-btn>
          <v-btn flat>Space Talk</v-btn>
        </v-toolbar-items>
    </v-toolbar>

    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  components: {

  },
  data () {
    return {
      //
    }
  }
}
</script>
