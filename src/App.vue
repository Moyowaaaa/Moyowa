<template>
  <div id="app">
    
    <router-view/>
  </div>
</template>

<style >

@font-face{
  font-family: "space-grotesk";
  src: local("space-grotesk"),
  url(../fonts/SpaceGrotesk-VariableFont_wght.ttf) format("truetype");
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin:0 !important;
  padding: 0 !important;
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
@media screen and (min-width:1024px){
  html{
    scroll-behavior: smooth;
  }
}


</style>
