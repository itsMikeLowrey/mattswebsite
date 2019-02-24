<template>
<div class="back">
  <v-flex class="hidden-sm-and-down intro" xs12 style="position:relative;height:100vh;">
           <v-flex class="title" xs8 offset-xs2 pa-4>
           <div class="display-4 white--text text-xs-center " >
             Matthew Murphy
           </div>
           <br>
           <div class="text-xs-center">

             <v-btn flat class="buttonOpt">Cars</v-btn>
             <v-btn flat class="buttonOpt">Motorcycles</v-btn>
             <v-btn flat class="buttonOpt">Space Talk</v-btn>
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
.title{
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgb(169,169,169,.9);
  /* border-radius: 3%; */
}
.buttonOpt {
  color:  black;
  font-size: 1.4rem;
}
</style>
