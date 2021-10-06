<template>
<div>

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
        <a href="">Home</a>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </div>



    
  </div>

  <div class="main">
 
<div class="title">
  
  
  <h1>I'm Moyowa</h1>
  <div class="pi">
   
  <p>Web Developer </p>

  <div class="fullstop">
  <p>.</p>
  </div>
  </div>

</div>

  </div>

  <div class="about" id="about">
  
    <div class="content">
      <h2>About Me<hr></h2>
      <div class="body">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos sapiente veniam culpa fugiat numquam temporibus voluptas ad obcaecati! 
          Excepturi dolor voluptas sequi voluptatem nemo atque quae nam earum explicabo dicta?</p>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laborum consequuntur fugit veritatis velit accusantium rerum atque modi libero sint, ratione nihil commodi. Necessitatibus molestias possimus, 
            delectus ullam doloremque totam soluta?</p>

      </div>
     
        <a href="https://drive.google.com/file/d/1s3XNpbtFk_X6Qj40mu5ocL1vPZ_QPuTK/view?usp=sharing"><button>View Resume</button></a>
     
    </div>

  </div>


  <div class="portfolio" id="portfolio">
    <div class="works">
      <div class="content">
      <h1>PORTFOLIO<hr></h1>
        <div class="gallery">

          <div class="work">

            <div class="img">
              <img src="../assets/project1.jpg" style="width:100%;" height="100%">
            </div>

         

         
          </div>

        </div>
        <b><a  href="https://github.com/Pope-Skittles">More Works</a></b>
    </div>
<!---------------
  
       ------>
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
  background-position-y: -71.5vh;
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
 
  width:65%;
  height:500px;
  margin-left:18%;
  color:white;
   background:#333b50
}
.about  h2{ 
  padding-top:5%;
  text-align: center;
}
.about .content .body{
  text-align:justify;
  width:80%;
  margin-top:5%;
  margin-left:10%;
}
  a{
  color:white;
}
a:hover{
  color:black;
}
.about .content button{
  margin-top:5%;
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
  height:auto;
  background:#333b50;
  color:white;
}
.portfolio b{
  text-align:center;
 
}

 .portfolio .works h1{
  text-align: center;
  margin-top:2%;
  margin-bottom:2%
}
.portfolio .works .content{
  width:100%;
  padding-top:2%;
  padding-bottom: 5%;;
}
.content .gallery{

  width:90%;
  height:auto;
  margin-left: 5%;;
  display: flex;;
}
.gallery .work{
  width:33%;
  height:400px;
  border:1px solid blue;
  background:rgb(2, 12, 46);
}





.works a{
  font-size: 20px;
  color:white;
  margin-left:45%;
  margin-bottom: 5%;
  
}
@media screen and (max-width: 480px) {
  .gallery .work{
    width: 95%;
    margin-left:2.5%;
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
  width:55%;
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
    margin-left:20%;
  }
  .about .content{
    width:98%;
    margin-left:1%;
  }
  .about .content button{
    width:40%;
    margin-left:30%;
  }
  .about  h2{ 
  padding-top:10%;
  }
  .about .content .body{
    margin-top:10%;
    width:90%;
    margin-left:5%;
  }
  .content .gallery{
    display:block;
  }

  .gallery .projects {
    width:95%;
    margin-top:2%;
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
</style>
