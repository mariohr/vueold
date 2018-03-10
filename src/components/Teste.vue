<template>
  <div class="teste">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'teste',
  data () {
    return {
      msg: 'aqui eh o teste'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: big;
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
  color: #35495E;
}
</style>
