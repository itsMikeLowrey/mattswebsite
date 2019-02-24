<template>
<div class="back">
  <v-flex class="hidden-sm-and-down intro" xs12 style="position:relative;height:100vh;">
           <v-flex class="title toolbar" xs12>
           <div class="display-1 white--text text-xs-center " >
             Matthew Murphy
           </div>
           </v-flex>
           <v-flex class="buttons toolbar" xs12>
             <div class="text-xs-center">

               <v-btn flat class="buttonOpt">Cars</v-btn>
               <v-btn flat class="buttonOpt">Space Talk</v-btn>
               <v-btn flat class="buttonOpt"><router-link to="/all">All Post</router-link></v-btn>
             </div>
           </v-flex>

  </v-flex>
</div>
</template>

<script>
export default {
  components: {

  }
}
</script>
<style scoped>
a {
  text-decoration: none;
  color: white;
}
.back {
  /* The image used */
  background-image: url('~@/assets/websiteBackground.jpg');
  /* Full height */
  height: 100%;
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

}
.toolbar{
  background-color: rgb(105,105,105);
}
.title{
height: 6vh;
  /* border-radius: 3%; */
}
.buttons {
  color:  black;
  font-size: 1.4rem;
}
</style>
