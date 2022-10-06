<script setup>
const name= `Vue dinamico`;
const styleColor=`color: blue`;
const objetoFruta ={
            name: "Manzana",
            price: "$1.00",
            description: "Una manzana",
      }
</script>


<template>
  <h1>Hola {{name.toUpperCase()}}</h1><br>
  <h2 :style="styleColor">soy azul</h2>

<li v-for="value in objetoFruta" :key="value">
  {{value}}
</li>

</template>




<style>
  h1{
    color:red;
  }
</style>