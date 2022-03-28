<template>
  <div class="home">
    <adornos msg=""/>
        <sabores msg=""/>
               <contactocliente msg=""/>
    <infopasteleria msg=""/>

    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import infopasteleria from '@/components/infopasteleria.vue'
import adornos from '@/components/adornos.vue'
import sabores from '@/components/sabores.vue'
import contactocliente from '@/components/contactocliente.vue'


export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    infopasteleria,
    adornos,
    sabores,
    contactocliente
  }
}
</script>
