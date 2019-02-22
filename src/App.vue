<template>
  <v-app>
    <!-- <v-toolbar app>
      <div class="ml-5 hidden-sm-and-down"></div>
      <div class="ml-2 hidden-md-and-down"></div>
      <v-toolbar-title class="display-1">Matthew Murphy</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down mr-5">
          <v-btn flat class="buttonOpt">Cars</v-btn>
          <v-btn flat class="buttonOpt">Motorcycles</v-btn>
          <v-btn flat class="buttonOpt">Space Talk</v-btn>
        </v-toolbar-items>
    </v-toolbar> -->

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

<style scoped>

.buttonOpt {
  color:  black;
  font-size: 1.4rem;
}
</style>
