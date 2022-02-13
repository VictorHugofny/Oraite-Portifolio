<template>
  <div class="home">
    <Homepage/>
    <Sobre/>
    <Projetos/>
    <ListaProjetos/>
    <Formulario/>
    <Contatos/>
  </div>
</template>

<script>
// @ is an alias to /src
import Homepage from '@/components/Home.vue'
import Sobre from '@/components/Sobre.vue'
import Projetos from '@/components/Projetos.vue'
import ListaProjetos from '@/components/ListaProjetos.vue'
import Formulario from '@/components/Formulario.vue'
import Contatos from '@/components/Contatos.vue'
export default {
  name: 'Home',
  components: {
    Sobre,
    Homepage,
    Projetos,
    ListaProjetos,
    Formulario,
    Contatos
    
  }
}
</script>
