<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  import Vue from 'vue'
  import Component from 'vue-class-component'

  @Component
  export default class Hello extends Vue {
    msg = 'Welcome to Your Vue.js App'

    mounted () {
      alert('mounted')
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
