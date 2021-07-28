<template>
    <div>
        <h3> Filmes </h3>
        <ul>
            <li> {{nome}} | {{ano}} </li>
        </ul>
    </div>
</template>

<script>

export default {
  props: {
    nome: {
      type: String,
      require: true
    },
    ano: {
      type: Number,
      require: true
    }
  }
}
</script>
