<template>
    <div v-editable="blok" class="px-4 text-blue">
       <h1 class="text-red-500 font-bold"> {{ blok.headline }}</h1>
    </div>
  </template>
   
  <script setup>
  defineProps({ blok: Object })

  
  </script>z