<template>
  <div>
<h3>Sabores por hace</h3>      
<ul>
    <li>chocolate</li>
    <li>fresa</li>
    <li>vainilla</li>
</ul>    
  </div>
</template>

<script>
export default {
  name: 'passabores',
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
