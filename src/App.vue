<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style >
html{
  scroll-behavior: smooth;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;

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
/* width */
::-webkit-scrollbar {
  width: 6px;
  scroll-behavior: smooth;

}



#overflow::-webkit-scrollbar {
  margin-top:2%;
height: 5px;;
}
#overflow::-webkit-scrollbar-thumb {
  background: #333b50;
}
/* Track */
::-webkit-scrollbar-track {
  background: #f2eee6
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #333b50
  
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}

</style>
