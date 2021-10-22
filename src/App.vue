<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style >
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color:#f2eee6;
  overflow-x:hidden
  
}
body{
  margin:0px !important;
}

#nav {
 
}

#nav a {
  font-weight: bold;

}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
