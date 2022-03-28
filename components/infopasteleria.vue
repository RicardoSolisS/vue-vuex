<template>
  <div>
    <p>Dirección Avenida Uruguay 493</p>
    <p>Telefono 782828282</p>
    <p>De lunes a sabado de 9 a 6</p>
  </div>
</template>

<script>
export default {
  name: 'infopasteleria',
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
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

