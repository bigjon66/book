<template>
    <v-expansion-panels>
      <v-expansion-panel
        v-for="(item,i) in cookies"
        :key="i"
      >
        <v-expansion-panel-header>
          <b>{{item.type}}</b>
        </v-expansion-panel-header>
        <v-expansion-panel-content
             
        >
        <v-row>
            <v-col v-for="ingredient in item.ingredients"  >
                <h4 style="text-decoration:underline"><b>{{ingredient.name}}</b></h4> 
                <p>{{ingredient.amount +' '+ingredient.measuringUnit}}</p>
            </v-col>
        </v-row>
        <v-row>
            <v-col>
                <h3 style="text-decoration:underline">Directions</h3>
                <p class="description">{{item.directions}}</p>
            </v-col>
        </v-row>

        
        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
  </template>

  <script lang="ts">
  
    export default{
      name: 'Cookies',
      data(){
        return{
        
        cookies:[
            {
            type:'Choclate Chip',
            ingredients:[
                {name:'Butter',amount:1, measuringUnit:'cups'},
                {name:'White Sugar',amount:1,measuringUnit:'cups'},
                {name:'Brown Sugar', amount:1,measuringUnit:'cups'},
                {name:'eggs', amount:2},
                {name:'Vanilla extract', amount:2,measuringUnit:'teaspoons'},
                {name:'baking soda', amount:1,measuringUnit:'teaspoons'},
                {name:'hot water', amount:2,measuringUnit:'teaspoons'},
                {name:'salt',amount:0.5,measuringUnit:'teaspoons'},
                {name:'all-purpose flour', amount:3,measuringUnit:'cups'},
                {name:'Semi-sweet Choclate Chips', amount:2,measuringUnit:'cups'},
                {name:'Chopped Walnuts', amount:1,measuringUnit:'cups'}
            ],
            directions:' Mix ingredients in bowl and preheat oven to 350 degrees. Bake for about 10 minutes',
           },
            {type:'Peanut Butter',
            directions:'Preheat Oven to 350F degrees, and mix ingredients in bowl. Bake for about 10minutes',
            ingredients:[
            {name:'all-purpose flour', amount:1.5,measuringUnit:'cups'},
            {name:'Butter',amount:0.5, measuringUnit:'cups'},
            {name:'Peanut Butter',amount:1, measuringUnit:'cups'},
            {name:'Brown Sugar', amount:1,measuringUnit:'cups'},
            {name:'White Sugar', amount:0.5,measuringUnit:'cups'},
            {name:'Vanilla extract', amount:1,measuringUnit:'teaspoons'},
            {name:'eggs', amount:1},
            {name:'baking powder', amount:0.75,measuringUnit:'teaspoons'}
            ],
        },
            {
                type:'Almond Butter',
                directions:'Preheat oven to 350F degree, Mix ingredients together warm and make sure almond butter is extra creamy. Bake for 12-13 minutes',
                ingredients:[
                {name:'Flaxseed',amount:1,measuringUnit:'Tablespoon'},
                {name:'Water',amount:3,measuringUnit:'Tablespoon'},
                {name:'all-purpose flour', amount:1.5,measuringUnit:'cups'},
                {name:'baking soda', amount:0.5,measuringUnit:'teaspoons'},
                {name:'baking powder', amount:0.25,measuringUnit:'teaspoons'},
                {name:'Sea Salt', amount:0.50,measuringUnit:'teaspoons'},
                {name:'Coconut Oil', amount:0.50,measuringUnit:'cups'},
                {name:'Cane Sugar', amount:0.50,measuringUnit:'cups'},
                {name:'Brown Sugar', amount:0.50,measuringUnit:'cups'},
                {name:'Creamy Almond Butter', amount:0.75,measuringUnit:'cups'},
                {name:'Vanilla extract', amount:1,measuringUnit:'Teaspoons'},




                // {name:'',amount:0,measuringUnit:''}
                // {name:'',amount:0,measuringUnit:''}
                ]},
            {type:'Sugar Cookies',ingredients:'hello world'},
      ]
        }
      },
    }
  </script>

