<template>
  <RecipeForm />
</template>

<script lang="ts">
  import Vue from 'vue'
import RecipeForm from '@/components/RecipeForm.vue';

  
  export default Vue.extend({
    name: 'Home',

    components: {
    RecipeForm
},
  })
</script>
