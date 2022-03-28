<template>
  <div>
<h3>Sabores</h3>      
<ul>
    <li>chocolate...380</li>
    <li>fresa...520</li>
    <li>vainilla...145</li>
</ul>    
  </div>
</template>

<script>
export default {
  name: 'sabores',
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
