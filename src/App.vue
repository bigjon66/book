<template>
  <v-app>
    <top-nav />
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import TopNav from './components/TopNav.vue';


export default Vue.extend({
    name: "App",
    data: () => ({
    //
    }),
    components: { TopNav }
});
</script>
