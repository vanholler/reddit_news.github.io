<template>
  <v-app id="inspire">
  <div id="app">

   <posts/>
   
  </div>
  </v-app>
</template>

<script>
import axios from 'axios'
import posts from '@/components/posts'


export default {
  name: 'home',
  components: {
    posts
  },
  data() {
  return {
   
  }
},

}
</script>

<style>
 #inspire {
  background-color: #424242;
 }  
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  

}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>



