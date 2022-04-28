<template>
<div id="App">

  <div id ="mobile" class="mobilenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav">&times;</a>
      <div class="ml"  @click="closeNav">
         <a href="#">Home</a>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </div>
  </div>
  <span class="mbutton" id="button" style="font-size:40px;cursor:pointer" @click="openNav">
  &#9776;</span>

  <div class="nav">
    
    <div class="left">
    <a href="">  Moyowa</a>
</div>

      <div class="right">
        <!-- <a href="" class="router">Home</a> -->
        <a href="#about" class="router">About Me</a>
        <a href="#portfolio" class="router">Portfolio</a>
        <a href="#contact" class="router">Contact</a>
      </div>



    
  </div>

  <div class="main">
 
<div class="title">
  
  
  <h1>I<span class="span">'</span>m Moyowa</h1>
  <div class="pi">
   
  <p>Web Developer <span class="span">.</span></p>
  </div>

</div>

  </div>

  <div class="about" id="about">
  
    <div class="content">
      <h2>About Me<hr></h2>
      <div class="mobilepic">
        <img src="../assets/4.jpeg">
          </div>  
      <div class="body">
        
       
        <p>Hi, I'm Moyowa Etchie, a confident and passionate web developer. I build interactive websites and web applications. I've always been passionate 
          about problem solving as this is what got me into coding</p>

            <p>My core skills are based on javascript, I am higly proficient in Vue.js, React and I'm also fluent in the Node and Express backend frameworks
          and I have also worked with the Mongo DB noSQL database on various projects.</p>
   

          <p>I usually spend my days coding or learning something new and now I seek new opportunities to develop my skills even further. </p>
      </div>
     
        <a href="https://drive.google.com/file/d/1s3XNpbtFk_X6Qj40mu5ocL1vPZ_QPuTK/view?usp=sharing" target="_blank"><button>View Resume</button></a>
     
    </div>

  </div>



  <div class="portfolio" id="portfolio">

    <div class="header">
      <h2>My Works<hr></h2>
    </div>

    <div class="projects">


        <!-- ------------ -->

        <!-- <a href="https://app.getspire.io"></a> -->
      <div class="project" id="first">

        <a href="https://app.getspire.io" target="_blank">
        <div class="link">
        <div class="langs">
          <p>Spirē </p>

          <div>
            <span>React</span>
            <span>Next.js</span>
            <span>Tailwind CSS</span>
          </div>



        </div>
        </div>
        </a>

      </div>


      <!-- ----------- -->


         



      <!-- ------------ -->


      <div class="project" id="second">
        <a href="https://todo-front-moyowa.vercel.app/" target="_blank">
       <div class="link">
        <div class="langs">

          <div class="des">
          <p>Todo Web Application</p>
         

          </div>

          <div><span>Vue.js</span>
          <span>Node.js</span>
          <span>Express</span>
          <span>MongoDB</span>
          
          </div>
        </div>
        </div>
        </a>

      </div>


      <!-- ----------- -->


   




      <!-- ------------ -->
      <div class="project" id="third">
        <a href="https://xdm-front.vercel.app/" target="_blank">
      
      <div class="link">

      


        <div class="langs">
          
          <div class="des">
          <p>HedgeHog</p>
          

       
          </div>



          <div>
            <span>Vue.js</span>
            <span>Chakra-ui</span>
          </div>
        </div>

      </div>
        </a>
      </div>


      <!-- ----------- -->

      <!-- ------------ -->
      <div class="project" id="fourth">
        <a href="https://e-commerce-moyowa.vercel.app/" target="_blank">
        <div class="link">
        <div class="langs">
          <p>Online Shop</p>

          <div>
            <span>React</span>
            <span>Next.js</span>
            <span>Tailwind CSS</span>
          </div>
        </div>
        </div>
        </a>
      </div>


      <!-- ----------- -->



    </div>
    

 

    
      <div class="git">
        <a href="https://github.com/Moyowaaaa" target="_blank"><p>See More <i class="fa fa-github" aria-hidden="true"></i></p></a>
      </div>

  </div>






  <div class="contact" id="contact">
    <div class="contbody">
      <h3>Contact</h3> <hr>


      <div class="contcontent">
        <div class="content">
                <p>I'm currently available to any work or project, send me an Email or message me on my socials and I will get back to you as soon as possible.</p>
                </div>

                <div class="links">
                   <a href="mailto:moyowa7@icloud.com" target="_blank"><i class="fa fa-envelope" aria-hidden="true"></i></a>
          <a href="https://www.linkedin.com/in/moyowa-etchie-665b51189" target="_blank"><i class="fa fa-linkedin"></i></a>
         <a href="https://github.com/Moyowaaaa" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
                    <a href="https://twitter.com/Etchie____" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                </div>
      </div>
    </div>
   


      <!------------------
       <div class="content">
      <p>I'm currently open to any work or project, send me an Email or message me on my socials and I will get back to you as soon as possible.</p>

        <div class="links">
          <a href="mailto:moyowa7@icloud.com"><i class="fa fa-envelope" aria-hidden="true"></i></a>
          <a href="https://www.linkedin.com/in/moyowa-etchie-665b51189"><i class="fa fa-linkedin"></i></a>
         <a href="https://github.com/Moyowaaaa"><i class="fa fa-github" aria-hidden="true"></i></a>
                    <a href="https://twitter.com/Etchie____"><i class="fa fa-twitter" aria-hidden="true"></i></a>
        </div>
        </div>

        ----------->
        
  </div>

 






  <footer>




    <div class="foot">
       <div class="L">
      <p>Copyright &copy; Moyowa</p>
    </div>
    &nbsp;
      
      <div id="demo"></div>
    </div>
   

  
   

   


  </footer>
</div>
</template>

<script>


export default {
  name: 'Home',
  created() {
     window.addEventListener("load", this.myfunction);
  },
methods:{
  openNav() {
    document.getElementById("mobile").style.width = "100%";
},
closeNav() {
    document.getElementById("mobile").style.width = "0";
},
     myfunction(){
    const element = new Date();
document.getElementById("demo").innerHTML = element.getFullYear();
  }
},

}
</script>

<style scoped>
body{
    background-color:#f2eee6;
}

.nav{
  background:
#f2eee6;
  margin:0%;
  height:auto;
  display:flex;
  font-size: 16px;

  
  width:100%;
}
.nav .left{
    font-weight: 600;
  color:black;
  margin-top:1%;
  margin-bottom:1%;
  margin-left:10%;
  width:20%;
}

.nav .left a{
  color:black;
  text-decoration:none;
}
.nav .left a:hover{
    border-bottom: 3px solid steelblue;
     transition: all ease-in-out .5s;
     
}
.nav .right{
   margin-top:1%;
  margin-bottom:1%;
  width:80%;
  margin-left:95vh;
    font-weight: 600;
}
.nav .right a{
  color:black;
  margin-left:5%;
  text-decoration: none;;
}
.router {
  color: inherit;
  text-decoration: underline 0.17em rgba(182, 137, 137, 0);

}

.router:hover {
  border-bottom: 3px solid steelblue;
   transition: all ease-in-out .5s;
}
.mobilenav {

    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
     background:#333b50;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
    display: none;
    
}

.mobilenav a {
    padding: 2% 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    font-weight: 550;
    color: black;
    display: block;
    transition: 0.3s;
    padding-top:5%
}

.mobilenav a:hover {
    color: #f1f1f1;
}
.mobilenav a:active {
    color: #f1f1f1;
}

.mobilenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
}
.mbutton{
  display:none;

  margin-top:5%;




}
.span{
  color:steelblue
}
.ml{
  margin-top:15%;
}




.main{
  background: linear-gradient(to bottom, transparent, transparent),url('../assets/4.jpeg') ;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-position-y: -53vh;
  background-position-x: 71vh;
  width:100%;
  height:100vh;
  background-color: #f2eee6;
  background-attachment: fixed;
  
  
}
.title{
  color:black;
  width:80%;
  margin-left:10%;
}
.title h1 {
  font-weight: 700;
  margin-top:-1px;
  padding-top:20%;
  margin-left:20%;
  font-Size:60px;
  position: sticky;
  
} 
.title p{
  padding-top:10%;
  margin-left:20%;
  font-size: 30px;;
  color:black;
  text-align:none;
}
.pi{
  display:flex;
}.pi .fullstop{
  padding-top:10%;
  font-size:20px;
}

/* ABOUT*/
.about{
  background-color:#f2eee6;
  width:100%;
  height:auto;

 
}
.about .content{
  margin-top:2%;
  margin-bottom:2%;
  padding-bottom:5%;
 
  width:65%;
  height:auto;
  margin-left:18%;
  color:white;
   background:#333b50
}
.about  h2{ 
  padding-top:5%;
  text-align: center;
}
.about .content .body p {
  width:80%;
  font-size: 2vh;
  margin: 0px 10% 12px;
  margin-top:2vh;
  text-align:justify;
}
/*
.about .content .body{
  
  width:80%;
  margin-top:5%;
  margin-left:10%;
}*/
.about .content .body p{
  text-align:justify;
}
  a{
  color:white;
}
a:hover{
  color:black;
}
.about .content button{
  margin-top:5%;
  padding-top:1%;
  font-size: 15px;
  padding-bottom:1%;
  margin-left:40%;
  width:20%;
  background:#333b50;
  height:10%;
  border:none;
  border:2px solid steelblue;
  text-decoration:none;
}
.about .content button:hover{
  background:steelblue
}
.route{
  text-decoration: none;
  color:white;
}
.about .content .languages{
  display: flex;
}
.abimg{
 
   display:none;
}
.mobileeee{
  display: none;;
}

/* Portfolio */
.portfolio{
  padding-top:5%;
  background: #333b50;
   width:100%;
   height:auto
}
.portfolio .header{
  
  color: white;
  text-align:center
}

.git{
  width:100%;
  font-size: 20px;
  text-align: center;
  color:black;
  padding-top:10vh;
  padding-bottom:10vh;
}

.projects{
  width: 100%;

  height:auto;
  display:flex;
  justify-items: center;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  
}

.projects .project{
  height: 40vh;
  cursor: pointer;
  width:40%;
  margin-top:2%;
  margin-left: 2%;
 

}

.projects .project .link{
  height: 100%;
}
.projects .project .langs{
 
  position: absolute;
  color:white;
  bottom:0;
  height: 10vh;
  width:100%;
  padding:2%
}

.projects .project .langs p{
  padding-left: 5%;
 
  font-size: 20px;
}
.projects .project .langs div span{
  font-size:10px;
  margin-left:5%;
  width:auto;
  text-decoration: underline;
    /* background:black;
    border-radius: 10px;;
    padding-left:5%;
    padding-right: 5%;
    padding-top: 2%;
    padding-bottom: 2%;*/
} 
.projects .project .langs .des{
  display: flex;
  align-items: center;

}

.projects .project .langs .des .fa{
  position: absolute;
  font-size: 18px ;
  margin-left:7vw;
}


#first{
  background:url(../assets/Spire.png);
  background-size: cover;
}

#second {
  background: url(../assets/todos.png);
  background-size: cover;

}

#third{
  background:url(../assets/hedgehog.png);
  background-size: cover;
}

#fourth{
  background:url(../assets/shop.png);
  background-size: cover;
}

#third .langs, #second .langs{
  color:black;
}





/*----------- */

/*Contact */
.contact{
  height:auto
}
.contbody{
  background:#333b50;
  margin-bottom:5%;
  margin-top:5%;
  height:auto;

  width:60%;
  margin-left:20%;;
  color:white
}
.contcontent{
  text-align:center
}
.contact h3{
  padding-top:5%;  
  text-align: center;
}
.contcontent {
  height:300px
}
.contcontent .content{
  width:70%;
  margin-left:15%;
}
.contcontent p{
  margin-top:5%;
  margin-bottom: 5%;;
}
.links{
margin-top:5%;
}
.links a{
  font-size:20px;
  margin-left:5%;
}
.links a:hover{
  border-bottom:2px solid black;
}
/*--------------------*/
hr{
  width:3.25em
}


footer{
  width:100%;
  border:2px solid #333b50;;
  margin-top:5%;
  text-align:center;
  height:auto;
  margin-bottom:0;
  box-shadow: 20px;
}

.project {
position: relative;

}
.project:hover .overlay {
  opacity: 1;
}
html {
  scroll-behavior: smooth;
}

.overlay {
  position: absolute;

  top: 40;
  bottom: 0;
  left: 0;
  right: 0;
  height: 50%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: black;
  color:teal;
  border-bottom-left-radius:10px ;
    border-bottom-right-radius:10px ;
    text-align: center;
    margin-bottom:15px

}


.overlay button{
  color: teal;;
  margin-top:16px;  border:1px solid teal;
  background:transparent;
  width:auto;;

}
.overlay button:hover{
  background: #333b50;
  border: 1px solid #333b50;
  color:white
}
.overlay .button p{
  margin-left:10px;
}



footer{
  width:100%;
  border:2px solid #333b50;;
  margin-top:5%;
  text-align:center;
  height:auto;
  margin-bottom:0;
  box-shadow: 20px;
  background:#333b50;
  color:white;
  padding-top:2%;
  padding-bottom:1%;
  
}
.foot{
  text-align:center;
  display:flex;
  width:100%;
  justify-content: center;
  
}
.mobilepic{
  display:none;
}
.lang{
  color:teal;
}







/*-- Mobile Devices --*/
@media screen and (max-width: 480px) {
  .nav{
    display:none;
  }
 
  .title{
    margin-left:2%;
  }
  .title h1 {
    padding-top:30vh;
  }
  .pi{
    margin-left:1vh
  }
  .pi .fullstop{
    display: none;;
  }

  .title p{
    margin-left:17%;
  }
  .about .content{
    width:100%;
    margin-left:1%;
  }
  .about .content button{
    width:40%;
    height:40px;
    margin-left:30%;
    margin-bottom:5%
  }
  .about  h2{ 
  padding-top:10%;
  }
  .about .content .body{
    margin-top:35%;
    width:90%;
    margin-left:5%;
  }


  .contact .cont{
    width:98%;
    margin-left:1%;
  }
  .cont .content p{
    width:100%; 
    text-align: justify;
  }
  
  .contact h3{
    padding-top:15%;
  }
  .content .links a{
    padding-top:20%;
    margin-right:5%;
  }
  .works a{
    margin-left:40%;
  }
  .mbutton{
  display: initial;
  width:50px;
  margin-left:85%;
}
.ml{
  text-align:center;
}
   .portfolio {
    height:auto;
    width:100%
  }
   .mobilenav {
    display:block;
    position: fixed;
    padding-top: 15px;}
  .mobilenav a {font-size: 18px;
  color:black;
  }
  .abimg{
    display:block;
    width:100%;
  }
  .abim{
  width:100%;
  height:100%;
}
.contbody{
  width:100%;
  margin-left:0;
}
.contcontent .content{
  width:90%;
  margin-left:5%;
}
.links{
margin-top:10%;
}
.links a{
  font-size:20px;
  margin-left:5%;
}
.project{
  border-radius:5px
}
.mobileeee{
  display:block;
  width:90%;
  margin-left:5%;
  height:60vh;
}
.portlang .lang{
  margin-left:20%;
  margin-top:5%;
}
.mobilepic{
  display: block;
  width:90%;
  margin-left:5%;
  height:350px;
  margin-bottom:5%
}
.mobilepic img{
  width:100%;
}
.project{
   height:auto
   
}

.project img{
  height:30vh
  
}
.project .bod{
  display:block;

}
.bod h3{
  color:white;
  text-align:center
}
.m-link{
  margin-top:10%;
  margin-left:30%;
  width:40%;
}
.m-link p{
  text-align: center;
  
  color:white;
  padding-top:2%;
  padding-bottom:2%;
  
  font-weight: 600;
  border:1px solid teal;
   border-radius: 2px;;
  
}
.body .lang{
  border:1px solid red;
  width: 100%;;
  text-align:none
}
.single{
  margin-left:5%;
  height:auto;
  width:100%;
  margin-top:10%;
  display:flex;
}
.l p{
  margin:5px;
  font-size:12px;
  color: teal;;
  
}
.single .l{
  width:auto;
  margin-left: 2%;
   
   text-decoration-color: teal;
   text-decoration: underline;
}
.overlay{
  display:none;
}
.projects .project{
  margin-top:5%;
  width: 80%;
  height: 30vh;

}
#second{
 
  background-position-x: -10vh
}

#third .langs{
  padding-top:5px;
}
#fourth .langs{
  padding-top:5px
}


}
/* ------------ */
@media screen and (min-width: 768px) and (max-width:1020px)

{
  .nav{
    display:none;
  }
  .about .content{
    width:100%;
    margin-left:0px
  }
  .mobilenav {
    display:block;
    
    padding-top: 15px;}
  .mobilenav a {font-size: 18px;
  color:black;
  }
  .main{
    background-attachment: fixed;
    background-image:none;
  }

  .contact .cont {
    width:99%;
    margin-left:2px;
  }
  .mbutton{
    display:inline;
    padding-top:5%;
    margin-left:90%;
  }
  .mobilenav a{
  
    font-size:30px;
  }
  
  .portfolio {
    height:auto;
    width:100%
  }
  .portfolio .content {
    display:flex;;
    flex-wrap: wrap;
  }
  .overlay{
  display:none;
}
.projects .project{
  margin-top:5%;
  width: 80%;
  height: 40vh;
}
}
@media screen and (max-width: 1024px) {
  .nav .right{
    margin-left:45%;
  }
  .main{
    background-position-y: -40vh !important;
  background-position-x: 71vh;
  }
  .contact .cont{
    width:90%;
    margin-left:5%;  
  }
  .about .content{
    width:99%;
    margin-left:5px;
  }
  .overlay{
  display:none;
}
}




</style>
