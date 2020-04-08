<template>
  <div id="app">
    <div id="nav">
     <Header>
        
     </Header>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/layout/Header';

export default {
  name:"app",
  components:{
    Header,
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
}



#nav a {
  font-weight: bold;
  color: #42b983;
}

#nav a.router-link-exact-active {
  color: #2a4237;
}
</style>
