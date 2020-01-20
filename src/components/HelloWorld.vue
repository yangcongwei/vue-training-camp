<template>
  <div class="hello">
    <ul v-if="show">
      <!-- <li  v-for="index in 10" :key="index" v-if="indexisActive">
        {{index}}        
      </li> -->
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld', 
  data(){
    return{
      show:true,
    }
  },
  props: {
    msg: String
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
