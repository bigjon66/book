<template>
    <v-card>
      <v-tabs vertical>
        <v-tab>
          Cookies
        </v-tab>
        <v-tab>
          Cake
        </v-tab>
        <v-tab>
          Bread
        </v-tab>
  
        <v-tab-item>
          <v-card flat>
            <v-card-text>
                <Cookies />
            </v-card-text>
          </v-card>
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
              <p>
                Fusce a quam. Phasellus nec sem in justo pellentesque facilisis. Nam eget dui. Proin viverra, ligula sit amet ultrices semper, ligula arcu tristique sapien, a accumsan nisi mauris ac eros. In dui magna, posuere eget, vestibulum et, tempor auctor, justo.
              </p>
  
              <p class="mb-0">
                Cras sagittis. Phasellus nec sem in justo pellentesque facilisis. Proin sapien ipsum, porta a, auctor quis, euismod ut, mi. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nam at tortor in tellus interdum sagittis.
              </p>
            </v-card-text>
          </v-card>
        </v-tab-item>
      </v-tabs>
    </v-card>
  </template>

  <script>
import Cookies from '@/components/baking/Cookies.vue'

export default{
    name: "SideTabs",
    components: { Cookies }
}
  </script>