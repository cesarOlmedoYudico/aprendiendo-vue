<template>
    <div id="mi-Componente">
        <hr/>
    <h1>Este es mi componente</h1>
    <h2>{{subtitulo}}</h2>
    <hr/>
</div>
</template>
<script>
    export default{
       name:"mi-Componente",
       data(){
        return{
            subtitulo:"soy el subtitulo de mi componente"
        }
       } 
    }
</script>