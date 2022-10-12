<template>
    <v-card>
      <v-tabs
        background-color="red accent-4"
        center-active
        dark
      >
        <v-tab><v-btn to="/" color="red">Home</v-btn></v-tab>
        <v-tab><v-btn to="baking" color="red">Baking</v-btn></v-tab>
        <v-tab><v-btn to="/sandwich" color="red">Sandwiches</v-btn></v-tab>
        <v-tab><v-btn to="/tacos" color="red">Tacos</v-btn></v-tab>
        <v-tab>Five</v-tab>
        <v-tab>Six</v-tab>
        <v-tab>Seven</v-tab>
        <v-tab>Eight</v-tab>
        <v-tab>Nine</v-tab>
        <v-tab>Ten</v-tab>
        <v-tab>Eleven</v-tab>
        <v-tab>Twelve</v-tab>
        <v-tab>Thirteen</v-tab>
        <v-tab>Fourteen</v-tab>
        <v-tab>Fifteen</v-tab>
        <v-tab>Sixteen</v-tab>
        <v-tab>Seventeen</v-tab>
        <v-tab>Eighteen</v-tab>
        <v-tab>Nineteen</v-tab>
        <v-tab><v-btn to="/random" class="green">Public API's</v-btn></v-tab>
      </v-tabs>
    </v-card>
  </template>


 <script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    name: "HelloWorld",
    data: () => ({}),
})
</script>
