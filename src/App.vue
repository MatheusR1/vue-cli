<template>
  <div id='app'>
    <Head nome='eai boy'/>
    <lista-filmes
      v-for='item in filmes'
      :key='item.id'
      v-bind='item'
    />
  </div>
</template>

<script>
import Head from './components/Head'
import ListaFilmes from './components/ListaFilmes'

export default {
  name: 'App',
  components: {
    Head,
    ListaFilmes
  },
  data () {
    return {
      filmes: [
        { id: '01', nome: 'A Ameaça Fantasma', ano: 1999 },
        { id: '02', nome: ' Ataque dos Clones', ano: 2002 },
        { id: '03', nome: 'Guerras Clônicas', ano: 2008 },
        { id: '04', nome: 'A Vingança dos Sith ', ano: 2005 }
      ]
    }
  }
}
</script>
<style scoped>

</style>
