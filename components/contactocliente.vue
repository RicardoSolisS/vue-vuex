<template>
  <div>
  
<h3>Pa saber a donde entregar</h3>
<form action="/accion.js" id="form1" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre">
    <label for="tel1">Teléfono</label>
    <input type="tel" id="tel1" name="tel1" maxlength="10">
    <label for="correo1">Correo</label>
    <input type="email" id="correo1" name="correo1">
    <input type="submit" value="Submit">
    <input type="reset">
</form>    
  </div>
</template>

<script>
export default {
  name: 'contactocliente',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

a {
  color: #42b983;
}
</style>
