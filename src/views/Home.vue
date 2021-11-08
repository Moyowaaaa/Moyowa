<template>
<div id="App">

  <div id ="mobile" class="mobilenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav">&times;</a>
      <div class="ml"  @click="closeNav">
         <a href="">Home</a>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </div>
  </div>
  <span class="mbutton" style="font-size:40px;cursor:pointer" @click="openNav">
  &#9776;</span>

  <div class="nav">
    
    <div class="left">
      Moyowa
</div>

      <div class="right">
        <a href="" class="router">Home</a>
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
      <div class="body">
        <p>Hi, I'm Etchie Moyowa, a passionate web developer, I build interactive websites and web applications. My core skills are based on javascript, I am higly proficient in Vue, React and Node javascript frameworks
          and I have also worked with the Mongo DB noSQL database
        </p>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium modi nobis eaque labore fugit recusandae in necessitatibus? Deleniti, voluptatem non? Voluptatibus error, sapiente alias dicta ut molestiae id natus accusamus!</p>

      </div>
     
        <a href="https://drive.google.com/file/d/1s3XNpbtFk_X6Qj40mu5ocL1vPZ_QPuTK/view?usp=sharing"><button>View Resume</button></a>
     
    </div>

  </div>



  <div class="portfolio" id="portfolio">

    <div class="header">
      <h2>Portfolio<hr></h2>
    </div>

     <div class="content">





        <div class="project">
          <div class="img">
            <img src="../assets/project1.jpg" style="width:100%;height:100%;" alt="">
          </div>
          <div class="des">
            <h3>HedgeHog<hr></h3>

            <p>Task Tracking Web Application</p>
            <div class="languages">
            
            </div>
            <a href="https://xdm-front-vercel.app">View</a>
          </div>

        

        </div>

        <div class="project">


          <!---------------------
          <div class="img">
            <img src="../assets/project1.jpg" style="width:100%;height:100%;" alt="">
          </div>
          <div class="des">
            <h3>HedgeHog<hr></h3>

            <p>Task Tracking Web Application</p>
            <div class="languages">
            
            </div>
            <a href="https://xdm-front-vercel.app">View</a>
          </div>


          ---------->
           <div class="upload">

              <div class="up">
                <div class="hourglass">
                  <span class="glyphicon glyphicon-hourglass"></span>
                </div>
                

                <p>Work Upload in Progress</p>
              </div>

          </div>
        
        
 
        </div>


        <div class="project">


          <!------------------------------
          <div class="img">
            <img src="../assets/project1.jpg" style="width:100%;height:100%;" alt="">
          </div>
          <div class="des">
            <h3>HedgeHog<hr></h3>

            <p>Task Tracking Web Application</p>
            <div class="languages">
            
            </div>
            <a href="https://xdm-front-vercel.app">View</a>
          </div>




          ----->
            <div class="upload">

              <div class="up">
                <div class="hourglass">
                  <span class="glyphicon glyphicon-hourglass"></span>
                </div>
                

                <p>Work Upload in Progress</p>
              </div>
              

          </div>
        

        </div>

      </div>


      

      <div class="git">
        <a href="https://github.com/Pope-Skittles"><p>See More <i class="fa fa-github" aria-hidden="true"></i></p></a>
      </div>

  </div>






  <div class="contact" id="contact">
    <div class ="cont">
      <h3>Contact<hr></h3>
       <div class="content">
      <p>I'm currently open to any work or project, send me an Email or message me on my socials and I will get back to you as soon as possible.</p>

        <div class="links">
          <a href="mailto:moyowa7@icloud.com"><i class="fa fa-envelope" aria-hidden="true"></i></a>
          <a href="https://www.linkedin.com/in/moyowa-etchie-665b51189"><i class="fa fa-linkedin"></i></a>
         <a href="https://github.com/Pope-Skittles"><i class="fa fa-github" aria-hidden="true"></i></a>
                    <a href="https://twitter.com/Etchie____"><i class="fa fa-twitter" aria-hidden="true"></i></a>
        </div>
        </div>
    </div>
  </div>

 






  <footer>

<p>Copyright &copy; Moyowa 2021</p>


  </footer>
</div>
</template>

<script>


export default {
  name: 'Home',
methods:{
  openNav() {
    document.getElementById("mobile").style.width = "100%";
},
closeNav() {
    document.getElementById("mobile").style.width = "0";
}
}
}
</script>

<style scoped>
body{
    background-color:#f2eee6;
}

.nav{
  background:
#f2eee6;
position: sticky;
  margin:0%;
  height:auto;
  display:flex;
  font-size: 16px;
}
.nav .left{
    font-weight: 600;
  color:black;
  margin-top:1%;
  margin-bottom:1%;
  margin-left:10%;
  width:20%;
}
.nav .right{
   margin-top:1%;
  margin-bottom:1%;
  width:80%;
  margin-left:90vh;
    font-weight: 600;
}
.nav .right a{
  color:black;
  margin-left:5%;
  text-decoration: none;;
}
.router {
  color: inherit;
  text-decoration: underline 0.17em rgba(255, 255, 255, 0);

}
.router:active {
  background: #c42376;
}
.router:hover {
  text-decoration-color: #441180;
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
}

.mobilenav a {
    padding: 2% 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    font-weight: 550;
    color: black;
    display: block;
    transition: 0.3s;
}

.mobilenav a:hover {
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
  position:sticky;
  margin-top:5%;
}
.span{
  color:steelblue
}

@media screen and (max-height: 450px) {
 
  .mobilenav {
    display:block;
    
    padding-top: 15px;}
  .mobilenav a {font-size: 18px;
  color:black;
  }

}


.main{
  background: linear-gradient(to bottom, transparent, transparent),url('../assets/4.jpeg') ;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-position-y: -52vh;
  background-position-x: 71vh;
  width:100%;
  height:100vh;
  background-color: #f2eee6;
  
  
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
  font-size: 15px;
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
/* Portfolio */
.portfolio{
   background:#333b50;
   width:100%;
   height:100vh
}
.portfolio .header{
  padding-top:2%;
  color: #f1f1f1;
  text-align:center
}
.portfolio .content {
  display: flex;
  width:100%;

  height:auto;

}
.portfolio .content .project{
  margin-left:4%;
  display:block;
  margin-top:1%;
  width:28%;
  height:65vh;
 
 
  border:1px solid black;
}
.content .project .img{
  height:50%;
}
.content .project .des{
  height: 50%;
  border:1px solid black;
  background: #010101;
   

}
.project .des h3 , p{
  text-align:center;
  color:white;
}
.project .des .languages{
  display:flex;
  margin-top:10px;
  margin-bottom: 25px;
  color:steelblue;
}
.des .languages li{
  margin-left: 15px;
}
.des a{
  margin-left:2vh
}
.des a:hover{
  
  color:white;
}
.git{
  width:100%;
  font-size: 20px;
  text-align: center;
  color:white;
  padding-top:10vh;
  padding-bottom:10vh;
}

.upload {
  width:100%;
  height: 100%;
  background: black;;
}
.upload .up {
  color: steelblue;
  text-align:center;
  padding-top:15vh
}

 .up .hourglass {
  font-size: 80px;;
}



@media screen and (max-width: 480px) {
 .portfolio .content {
   display:block;
 }
 .portfolio .content .project{
   width:90%;
   margin-left:5%;
 }
 .portfolio{
   height:auto
}
}

/*----------- */

/*Contact */
.contact{
  background-color:#f2eee6;
  width:100%;

  height:auto
}
.contact .cont{
  margin-top:1%;
  margin-bottom:1%;
  height:500px;
  width:60%;
  margin-left:20%;
  color:white;
  background:#333b50
}
.contact h3{
  margin-top:5%;
  padding-top:10vh;
  text-align: center;
}
.cont .content{
  width:80%;
  margin:10%;
  margin-top:10vh;
}
.cont .content p{
  line-height:25px;
}
.content .links {
    margin-top:10%;
  text-align:center;
}
.content .links a{

  font-size: 25px;;
   color:white;
  margin-left:5%;
}
.content .links a:hover{
  color:teal;
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
  background:#333b50;
  color:white;
}
footer p{
  margin-top:2%;
  margin-bottom:2%;
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
    margin-top:10%;
    width:90%;
    margin-left:5%;
  }


  .gallery .projects {
    width:95%;
    margin-left:5%;
    margin-top:5%;
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

}
/* ------------ */
@media screen and (max-width: 768px) {
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
  .portfolio .content .project{
    width:40%;
    margin-left:7%;
    margin-top:5%
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
  
}
@media screen and (max-width: 480px) {
   .portfolio {
    height:auto;
    width:100%
  }
  .portfolio .content {
    display:flex;;
    flex-wrap: wrap;
  }
  .portfolio .content .project{
    width:90%;
    margin-left:5%;
    margin-top:5%
  }
}


</style>
