<template>
    <v-card>
      <v-tabs vertical>
        <v-tab>Chicken</v-tab>
        <v-tab>Beef</v-tab>
        <v-tab>Pork</v-tab>
        <v-tab>Fish</v-tab>
  
        <v-tab-item>
          <Chicken />
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-card-text>
             
            </v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-card-text>
              
            </v-card-text>
          </v-card>
        </v-tab-item>
      </v-tabs>
    </v-card>
  </template>
  
  <script lang="ts">
    import Vue from 'vue'
    import Chicken from '@/components/sandwiches/Chicken.vue';
  
    export default Vue.extend({
      name: 'meat',
  
      components: {
    Chicken
},
    })
  </script>
  
  <style scoped>
    .header{
        list-style: none;
        font-size: 20px;
        text-decoration: underline;

    }
  </style>