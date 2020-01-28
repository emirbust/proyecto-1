<template>
  <div id="app">
      <Encabezado></Encabezado>
      <Intermedio></Intermedio>
      <FinalPagina></FinalPagina>
    </div>
</template>

<script>
import Encabezado from './components/Encabezado.vue';
import Intermedio from './components/Intermedio.vue';
import FinalPagina from './components/FinalPagina.vue';

export default {
  name: 'app',
  components: {
    Encabezado,
    Intermedio,
    FinalPagina
    
  }
}
</script>

<style scoped>  
*{
  margin: 0;
  background: rgb(35, 131, 115);

}
</style>
