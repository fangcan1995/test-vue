<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{message}}</h1>
    <h1>{{name}}</h1>
    <h1 >{{age}}</h1>
    <input v-model="name"/>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    age: Number,
    fangcan: Object
  },
  data(){
    return {
      message:'fangcan',
      name:''
    }
      
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
