<script setup>
const name= `Vue dinamico`;
const styleColor=`color: blue`;
</script>


<template>
  <h1>Hola {{name.toUpperCase()}}</h1><br>
  <h2 :style="styleColor">soy azul</h2>
</template>




<style>
  h1{
    color:red;
  }
</style>