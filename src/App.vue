<template>
  <div id="app">
    
      <app-text/>
      <app-caro/>
      <app-copy/>
      

    </div>
  
</template>




<script>

import mytext from "@/components/mytext.vue";
import caro from "@/components/caro.vue";
import copy from "@/components/copy.vue"
export default {
  
  components: {
   
    'app-text' : mytext,
    'app-caro' : caro,
    'app-copy' : copy
  }
}
</script>

<style>

</style>
