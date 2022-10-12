<template>
    <div>
        <SideTabs />
    </div>
</template>
  
  <script lang="ts">
    import Vue from 'vue'
    import SideTabs from '@/components/baking/SideTabs.vue';

  
    export default Vue.extend({
      name: 'Home', 
      components: {
    SideTabs
},
    })
  </script>