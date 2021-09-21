<template>
  <div>



<div class="content">
  <div class="header">
      <h2>About</h2>
      <h3>Me</h3>
    </div>
     <hr>



     <div class="body">



<div class="right">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, eius eum aut impedit animi vitae dolores quasi dolorem, perferendis blanditiis repudiandae repellat harum reprehenderit! Corrupti sit doloremque necessitatibus maxime fugit.</p>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum maiores expedita earum, quaerat accusamus cumque quas. Aspernatur, inventore dolore odit aliquam fuga eligendi esse eum cum sunt delectus nisi ipsa?</p>

  <!------------------
  <button>Download CV </button>

  ------>
</div>




</div>

</div>

<div class="experience">
  <div class="ab">

    <h2>Experience</h2>
    
    <div class="body">
      <p>Work Experience</p>
    </div>
  
    



  </div>
</div>
    



  <footer>

<p>Copyright &copy; Moyowa 2021</p>


  </footer>
  </div>
</template>


<style scoped>
.content{
  width:80%;
  margin-left:10%;
  border:2px solid steelblue;
  margin-top:5%;
  height:auto;
  background:#333b50
}
.header{
  margin-top:2%;
  display:flex;
  width:100%;
  font-size: 20px;;

}
h2{
  margin-left:45%;
  font-size: 25px;;
  color:white
}
h3{
 
  padding-left:5px;
  color:steelblue;
  
}
hr{
  width:3.25em
}
.body{
  margin-top:2%;
  margin-bottom:5%;
  display:flex;
}

.body .right{
  width:80%;
  margin-left:10%;
  color:white
}
.body .right button{
  margin-top:10%;
  margin-left:40%;
   width:20%;
  background:#333b50;
  height:20%;
  border:none;
  border:2px solid steelblue;
  text-decoration:none;
}
.body .right button:hover{
   background:steelblue
}
.experience{
  margin-top:2%;
  width:100%;
}
.ab{
  width:80%;
  margin-left:10%;
  border: 2px solid black;;
  height:auto;
  background:#333b50;
  color:white;
 
  
}


/* ----------*/
footer{
  width:100%;
  border:2px solid red;
  margin-top:9%;
  text-align:center;
  height:auto;
  margin-bottom:0;
  box-shadow: 20px;
   background:#333b50;
  color:white;
}
footer p{
  margin-top:2%;
  margin-bottom:2%;
}
/*------------*/


/*-- Mobile Devices --*/
@media screen and (max-width: 480px) {
  .content{
    margin-top:10%;
    width:96%;
    margin-left:2%;
    height:auto
  };
  .body .right{
    width:90%;
  }
  .body .right button{
    width:40%;
    margin-left:30%;
    margin-bottom:10%;
  }
  h2{
    margin-left:35%;
  }
  footer{
    margin-top:45%
  }
}
</style>