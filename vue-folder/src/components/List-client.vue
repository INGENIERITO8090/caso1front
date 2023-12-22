
<template>
<div>

</div>
</template>
<script>


import axios from "axios";

export default {

   name:"List_client" +
       "" ,
  data(){
     return{
       clientes:[]

     }
  },

async  created() {


   let url = "http://localhost:8080/cliente/all"

  axios.get(url).then(response => console.log(response))
   }
};
</script>
<style scoped>


</style>

