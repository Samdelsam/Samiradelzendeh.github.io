<template>
  <div class="hello">
    <h2>WoooW Look at meee !</h2>
    <h3>Im Online</h3>
    <h3>YooOOHooOOO</h3>
    <h3>Please be patient.I'm under constructions</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 40px 0 0;
  font-family: var(--secondary-font);
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
