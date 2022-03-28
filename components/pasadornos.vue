<template>
  <div>
<h3>Adornos que faltan</h3>      
<ul>
    <li>letras</li>
    <li>velas</li>
    <li>figuras</li>
</ul>    
  </div>
</template>

<script>
export default {
  name: 'pasadornos',
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

