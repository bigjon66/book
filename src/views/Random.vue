<template>
    <PublicRequests />
</template>

<script lang="ts">
    import Vue from 'vue'
import PublicRequests from '../components/random/PublicRequests.vue'
  
    
    export default Vue.extend({
      name: 'Random',
  
      components: {
    PublicRequests
},
    })
  </script>
  