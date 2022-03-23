<template>
  <header>
    <h1>{{ props.title }}</h1>
    <p>{{ props.description }}</p>
    </header>
</template>

<script setup>
   import {defineProps} from 'vue';
   const props = defineProps({
     title:{
       type: String,
       default:'Welcome!'
     },
     description:{
       type: String,
       default: 'What we are all about'
     }
   });
   </script>

   <style>
   h1 {
       width: 100%;
         
    background: yellow;
    
    color:gray;
    text-align: center;
   }
   </style>