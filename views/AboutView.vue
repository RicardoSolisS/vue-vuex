<template>
  <div class="about">
    <h1>Area de pastelero</h1>
  </div>
      <pasadornos msg=""/>
        <passabores msg=""/>
               <pascontactocliente msg=""/>

</template>


<script>
// @ is an alias to /src

import pasadornos from '@/components/pasadornos.vue'
import passabores from '@/components/passabores.vue'
import pascontactocliente from '@/components/pascontactocliente.vue'


export default {
  name: 'HomeView',
  components: {

    pasadornos,
    passabores,
    pascontactocliente
  }
}
</script>