<template>
  <div>
    <h1>lista filme</h1>
    <p>Treinando comunicação entre componentes vue</p>
    <strong> campo passado via props,  nome :{{ nome }} </strong>
  </div>

</template>

<script>
export default {
  props: {
    nome: String
  }
}
</script>

<style scoped>
div {
  background: green
}

h1 {
  background: #fff
}
</style>
