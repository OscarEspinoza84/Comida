
<template>
  <div>
    <img :src="url" alt="name">
        <h2> {{ nombre }} </h2>
        <h3> {{costo}}</h3>
        <p> {{descripcion}} </p>
        <a v-bind:href="url" target="_blank">Ordenar</a>
  </div>
    
</template>

<style scoped>
   div{
       display: inline-block;
       text-align: center;
       border: 2px solid #000000;
       padding: 2%;
       border-radius: 1px;
       margin: 5px;
     }
    img{
      width: 40px;
      padding: 40px;
      background: rebeccapurple;
    }
    a{
      text-decoration: none;
      color: rgb(1, 0, 0);
      background: #f0ec0e;
      padding: 0.3rem;
      border-radius: 5px;
      border: 2px solid #593102;

    }

    




</style>




<script>

   export default {
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
        descripcion:{
          String,
        },
        costo:{
          String
        }
    },
    
};

</script>
