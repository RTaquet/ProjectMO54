<!--@Author: Jean Maccou, -->

<template>
  <router-view/>
</template>

<script>
import { getDatabase, ref, set } from "firebase/database";
import TheHeader from "./components/TheHeader.vue"
export default {
  components:{
   TheHeader
},
provide(){
  return{
    msg: this.msg
  }
},
computed:{
  
},
data() {
  return {
    
  }
},
}
</script>
<style scoped>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2fa72a;
}

</style>
