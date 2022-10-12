<template>
    <v-card flat>
            <v-container>
              <ul>
                <li class="header">Sandwiches</li>
                    <ul>
                        <li v-for="sandwich in Sandwiches">
                        {{sandwich}}
                        </li>
                    </ul>
              </ul>
            </v-container>
          </v-card>
</template>

<script lang="ts">
    import Vue from 'vue'
  
    export default Vue.extend({
      name: 'Chicken',
      data: () => ({
        Sandwiches:[
            'Grilled Chicken Sandwich',
            'Crispy Chicken Sandwich',
            'Southern Fried Chicken Sandwich',
            'Fried Pickled Chicken Sandwich',
            'Spicy Fried Jalepeno Chicken Sandwich',
        ]
  
      })
    })
  </script>