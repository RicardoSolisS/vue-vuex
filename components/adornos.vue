<template>
  <div>
<h3>Adornos</h3>      
<ul>
    <li>letras...80</li>
    <li>velas...50</li>
    <li>figuras...45</li>
</ul>    
  </div>
</template>

<script>
export default {
  name: 'adornos',
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

