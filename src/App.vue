<template>
<input type="text" size="50" v-model="zielEingabe">
<button>Neu</button>
<h2>TODO</h2>
<p>
  <input type="radio" name="zielSelect" value="1">JavaScriptLernen
</p>
<button>Delete</button>
</template>

<script>
export default {
  name: 'ToDo',
  props: {msg: String},
  datat: function(){
    return { }
  },
  methods: {
    neuZiel(){ },
    deleteZiel(){ }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
