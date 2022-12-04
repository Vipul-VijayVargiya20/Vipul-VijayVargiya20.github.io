# Vipul-VijayVargiya20.github.io
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="./style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css"
    />
  </head>
  <body>
    <div class="container">
      <header class="flex">
        
        <nav>
          <ul class="flex">
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Service</a></li>
            <li><a href="#project">Portfolio</a></li>
            <li><a href="#contact">Contact Me</a></li>
          </ul>
          <div id="search" class="flex">
            <i class="fa-solid fa-magnifying-glass"></i>
            <input type="text" name="" id="" placeholder="Search..." />
          </div>
        </nav>
      </header>

      <div class="main flex">
        <div class="main-one">
          <h1>Hy! I am</h1>
          <span class="auto">VIPUL VIJAYVARGIYA</span>
          <p>
            my name is vipul vijayvargiya and i am working as a backend developer at functionup where i have learn a lot
            of skills HTML,CSS,JAVASCRIPT,NODEJS,MONGODB,DSA AND REACTJS along with this skill i have made a project also
            and gain a lot of experience in backend role.
          </p>
          <button>Hire Me</button>
        </div>
        <div class="main-two">
          <img src="./Images/IMG_20200312_213645.jpg" alt="" />
        </div>
      </div>

      <section class="projects" id="project">
        <h1>My Awesome <br /><span>Projects</span></h1>
        <p>
         i have made a real-time project of E-commerce website like amazon,flipkart and
          user may get a id and password through which they can place a order from a
          website and purchase a product of their own choice.
        </p>
        <button class="button">Download CV</button>
        <div class="projects-div flex div-1">
          <img src="./Images/Projects/5.png" alt="" />
          <h3>Ecommerce Website</h3>
          <p>
           It is a developed website which help user to purchase a product of their own choice
            and can gain a reward by shopping in this website
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-2">
          <img src="./Images/Projects/6.png" alt="" />
          <h3>Weather App</h3>
          <p>
           It is a project that show what is the condition of a weather in our city and update a live 
           result of a weather which help user to get a alert about the weather
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-3">
          <img src="./Images/Projects/7.png" alt="" />
          <h3>Star wars</h3>
          <p>
            This project show the name of authors and their movies they wrote or watch it show
            how many user have watched the same movie number of time along with details
          </p>
          <button>Live Preview</button>
        </div>
      </section>
      <br /><br />

      <section class="about flex" id="about">
        <div class="about-one">
          <h1>About me</h1>
          <span>VIPUL VIJAYVARGIYA</span>
          <p>
           I have completed my bachelors in BCOM from barkatullah university bhopal and after
            graduation i switch in technical field and gain a lot of knowledge in a tech field and
            also get a experience in a tech industry
          </p>
          <div class="btns">
            <button>Download CV</button>
            <button>Contact Me</button>
          </div>
        </div>
        <div class="about-two">
          <img src="./Images/vipul img.jpg" alt="" />
        </div>
      </section>
      <br /><br /><br />

      <section class="contact" id="contact">
        <h1>Let Us <span>Talk!</span></h1>
        <div class="box flex">
          <div>
            <i class="fa-solid fa-user"></i>
            <input type="text" placeholder="Name.." />
          </div>
          <div>
            <i class="fa-solid fa-envelope"></i>
            <input type="email" placeholder="Email.." />
          </div>
          <textarea
            name=""
            id=""
            cols="60"
            rows="5"
            placeholder="Enter your Message here...."
          ></textarea>
          <div>
            <input type="submit" class="send" value="Send" />
          </div>
        </div>
      </section>
      <footer class="flex" id="footer">
        
        <div class="social">
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-whatsapp"></i>
          <i class="fa-solid fa-phone"></i>
        </div>
      </footer>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
      var typed = new Typed(".auto", {
        strings: ["VIPUL VIJAYVARGIYA", "BACKEND Developer", "UI/UX Designer"],
        typeSpeed: 60,
        backSpeed: 70,
        loop: true,
      });
    </script>
  </body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Roboto:wght@500;700;900&display=swap');
*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
}
.flex{
    display: flex;
    align-items: center;
}
body{
    background-color: #1E1E1E;
}
.container{
    width: 100%;
    background-color: #1E1E1E;
    overflow-x: hidden;
    color: white;
}
.container header{
    width: 100%;
    height: 9vh;
    padding: 10px 60px;
    justify-content: space-between;
}
header .logo{
    font-size: 45px;
    font-weight: 600;
    width: 30%;
    margin-left: 100px;
}
.logo span{
    color: #FFDE59;
    font-size: 70px;
}
header nav{
    width: 70%;
    display: flex;
}
nav #search{
    width: 17%;
    position: relative;
}
#search i{
    position: absolute;
    color: #FFDE59;
    top: 8px;
    font-weight: bolder;
    font-size: 19px;
    left: 8px;
}
nav input{
    border-radius: 20px;
    outline: none;
    border: none;
    padding: 8px 15px;
    padding-left: 33px;
    border:2px solid #FFDE59;
    font-size: 16px;
    height: 13px;
    width: 100%;
}
header nav ul{
    justify-content: center;
    width: 70%;
}
nav ul li{
    list-style: none;
}
nav ul li a{
    text-decoration: none;
    font-size: 20px;
    padding: 10px 25px;
    font-weight:500;
    color: white;
}
nav ul li a:hover{
    color: #FFDE59;
}

.container .main{
    width: 100%;
    height: 80vh;
    justify-content: center;
}
.main .main-one{
    width: 45%;
    padding: 40px 30px;
    padding-left: 150px;
}
.main-one h1{
    font-size: 80px;
}
.main-one span{
    font-weight: 600;
    font-size: 60px;
    color: #FFDE59;
}
.main-one p{
    font-size: 17px;
    padding: 0px 0;
}
.main-one button{
    background-color: #FFDE59;
    outline: none;
    border: none;
    padding: 9px 35px;
    margin-top: 20px;
    cursor: pointer;
    font-size: 22px;
    box-shadow: 2px 2px 30px #0e0e0e79;
    font-weight: 600;
    border-radius: 50px;
    transition: all ease-out 0.2s;
}
.main-one button:hover{
    transform: scale(1.02);
}
.main .main-two{
    width: 50%;
}
.main-two img{
    width: 350px;
}
.projects{
    position: relative;
    width: 100%;
    height: 600px;
    padding: 150px 180px;
}
.projects h1{
    font-size: 50px;
    line-height: 49px;
    font-weight: 800;
}
.projects h1 span{
    color: #FFDE59;
}
.projects p{
    width: 35%;
    font-size: 17px;
    font-weight: 400;
    padding-top: 20px;
}
.projects .button{
    background-color: #FFDE59;
    padding: 9px 25px;
    margin-top: 20px;
    cursor: pointer;
    outline: none;
    border: none;
    font-size: 18px;
    color: black;
    font-weight: 600;
    border-radius: 50px;
}

.projects-div{
    width:300px;
    height: 360px;
    position: absolute;
    z-index: 100;
    flex-direction: column;
    margin: 10px;
    border-radius: 20px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    transition: all 0.2s ease-out;
}
.projects-div:hover{
    transform: rotate(10deg);
}
.div-1{
    top: 100px;
    left: 950px;
}
.div-2{
    bottom: 10px;
    right: 1000px;
}
.div-3{
    bottom: 10px;
    right: 600px;
}
.projects-div h3{
    font-size: 23px;
    padding:5px 30px;
    color: #FFDE59;
    font-family: 'Roboto', sans-serif;
}
.projects-div p{
    width: 80%;
    margin:0 auto;
    text-align: center;
}
.projects-div img{
    width: 100px;
    margin: 6px 0;
    border-radius: 50%;
}
.projects button{
    background-color: transparent;
    cursor: pointer;
    color: white;
    outline: none;
    border: 1px solid #FFDE59;
    padding: 7px 25px;
    font-weight: 500;
    font-size: 22px;
    border-radius: 0;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
    margin-top: 25px;
    border-radius: 50px;
}

.about{
    width: 100%;
    height: 400px;
    padding: 30px 50px;
    justify-content: center;
}
.about-one{
    width: 55%;
    padding: 0 60px;
}
.about-one h1{
    font-size: 50px;
}
.about-one p{
    padding: 10px 0;
    width: 95%;
    text-align: justify;
}
.about-one span{
    font-size: 30px;
    color: #FFDE59;
}
.about-two{
    width: 40%;
}
.about-two img{
    width: 200px;
}
.btns{
    margin: 15px 0;
}
.btns button{
    background-color: #FFDE59;
    padding: 8px 17px;
    font-size:18px;
    font-weight: 600;
    margin: 0 10px;
    cursor: pointer;
    transition: all ease-out 0.2s;
    outline: none;
    border: none;
}
.btns button:hover{
    transform: scale(1.02);
}

.contact{
    width: 100%;
    text-align: center;
    border-top: 1px solid rgba(255, 255, 255, 0.31);
    border-bottom: 1px solid rgba(255, 255, 255, 0.31);
    padding-top: 30px;
    padding-bottom: 70px;
}

.contact h1{
    font-size: 50px;
}
.contact h1 span{
    color: #FFDE59;
}
.contact .box{
    flex-direction: column;
    margin-top: 40px;
}
.box div{
    width: 40%;
    margin: auto;
}
.contact .box input{
    width: 90%;
    margin: auto;
    outline: none;
    border: none;
    background-color: #FFDE59;
    padding: 9px 40px;
    border-radius: 5px;
    margin: 10px;
    font-size: 16px;
}
.box div{
    position: relative;
}
.box div i{
    position: absolute;
    font-size: 20px;
    color: black;
    top: 20px;
    left: 20px;
}
.contact .box textarea{
    margin-top: 20px;
    background-color: transparent;
    padding: 10px 30px;
    color: white;
    font-size: 18px;
    border-radius: 20px;
    border: 1px solid #FFDE59;
    outline: none;
    margin-left: 30px;
}
.send{
    background: linear-gradient(#FFDE59 , #ddb100);
    font-size: 19px !important;
    font-weight: 600;
    cursor: pointer;
    margin: 30px auto !important;
}

footer{
    justify-content: space-between;
    padding: 10px 70px;
    background: linear-gradient(#FFDE59 , #ddb100);
    font-size: 20px;
    font-weight: 600;
    color: black;
}
footer .social i{
    font-size: 25px;
    margin: 0 3px;
    cursor: pointer;
}
.social i:hover{
    color: palevioletred;
}
///////////////////////
@media only screen and (max-width: 1000px)
.flex{
    display: flex;
    align-items: center;
}
body{
    background-color: #1E1E1E;
}
.container{
    width: 100%;
    background-color: #1E1E1E;
    overflow-x: hidden;
    color: white;
}
.container header{
    width: 100%;
    height: 9vh;
    padding: 10px 60px;
    justify-content: space-between;
}
header .logo{
    font-size: 45px;
    font-weight: 600;
    width: 30%;
    margin-left: 100px;
}
.logo span{
    color: #FFDE59;
    font-size: 70px;
}
header nav{
    width: 70%;
    display: flex;
}
nav #search{
    width: 17%;
    position: relative;
}
#search i{
    position: absolute;
    color: #FFDE59;
    top: 8px;
    font-weight: bolder;
    font-size: 19px;
    left: 8px;
}
nav input{
    border-radius: 20px;
    outline: none;
    border: none;
    padding: 8px 15px;
    padding-left: 33px;
    border:2px solid #FFDE59;
    font-size: 16px;
    height: 13px;
    width: 100%;
}
header nav ul{
    justify-content: center;
    width: 70%;
}
nav ul li{
    list-style: none;
}
nav ul li a{
    text-decoration: none;
    font-size: 20px;
    padding: 10px 25px;
    font-weight:500;
    color: white;
}
nav ul li a:hover{
    color: #FFDE59;
}

.container .main{
    width: 100%;
    height: 80vh;
    justify-content: center;
}
.main .main-one{
    width: 45%;
    padding: 40px 30px;
    padding-left: 150px;
}
.main-one h1{
    font-size: 80px;
}
.main-one span{
    font-weight: 600;
    font-size: 60px;
    color: #FFDE59;
}
.main-one p{
    font-size: 17px;
    padding: 0px 0;
}
.main-one button{
    background-color: #FFDE59;
    outline: none;
    border: none;
    padding: 9px 35px;
    margin-top: 20px;
    cursor: pointer;
    font-size: 22px;
    box-shadow: 2px 2px 30px #0e0e0e79;
    font-weight: 600;
    border-radius: 50px;
    transition: all ease-out 0.2s;
}
.main-one button:hover{
    transform: scale(1.02);
}
.main .main-two{
    width: 50%;
}
.main-two img{
    width: 350px;
}
.projects{
    position: relative;
    width: 100%;
    height: 600px;
    padding: 150px 180px;
}
.projects h1{
    font-size: 50px;
    line-height: 49px;
    font-weight: 800;
}
.projects h1 span{
    color: #FFDE59;
}
.projects p{
    width: 35%;
    font-size: 17px;
    font-weight: 400;
    padding-top: 20px;
}
.projects .button{
    background-color: #FFDE59;
    padding: 9px 25px;
    margin-top: 20px;
    cursor: pointer;
    outline: none;
    border: none;
    font-size: 18px;
    color: black;
    font-weight: 600;
    border-radius: 50px;
}

.projects-div{
    width:300px;
    height: 360px;
    position: absolute;
    z-index: 100;
    flex-direction: column;
    margin: 10px;
    border-radius: 20px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    transition: all 0.2s ease-out;
}
.projects-div:hover{
    transform: rotate(10deg);
}
.div-1{
    top: 100px;
    left: 950px;
}
.div-2{
    bottom: 10px;
    right: 1000px;
}
.div-3{
    bottom: 10px;
    right: 600px;
}
.projects-div h3{
    font-size: 23px;
    padding:5px 30px;
    color: #FFDE59;
    font-family: 'Roboto', sans-serif;
}
.projects-div p{
    width: 80%;
    margin:0 auto;
    text-align: center;
}
.projects-div img{
    width: 100px;
    margin: 6px 0;
    border-radius: 50%;
}
.projects button{
    background-color: transparent;
    cursor: pointer;
    color: white;
    outline: none;
    border: 1px solid #FFDE59;
    padding: 7px 25px;
    font-weight: 500;
    font-size: 22px;
    border-radius: 0;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
    margin-top: 25px;
    border-radius: 50px;
}

.about{
    width: 100%;
    height: 400px;
    padding: 30px 50px;
    justify-content: center;
}
.about-one{
    width: 55%;
    padding: 0 60px;
}
.about-one h1{
    font-size: 50px;
}
.about-one p{
    padding: 10px 0;
    width: 95%;
    text-align: justify;
}
.about-one span{
    font-size: 30px;
    color: #FFDE59;
}
.about-two{
    width: 40%;
}
.about-two img{
    width: 200px;
}
.btns{
    margin: 15px 0;
}
.btns button{
    background-color: #FFDE59;
    padding: 8px 17px;
    font-size:18px;
    font-weight: 600;
    margin: 0 10px;
    cursor: pointer;
    transition: all ease-out 0.2s;
    outline: none;
    border: none;
}
.btns button:hover{
    transform: scale(1.02);
}

.contact{
    width: 100%;
    text-align: center;
    border-top: 1px solid rgba(255, 255, 255, 0.31);
    border-bottom: 1px solid rgba(255, 255, 255, 0.31);
    padding-top: 30px;
    padding-bottom: 70px;
}

.contact h1{
    font-size: 50px;
}
.contact h1 span{
    color: #FFDE59;
}
.contact .box{
    flex-direction: column;
    margin-top: 40px;
}
.box div{
    width: 40%;
    margin: auto;
}
.contact .box input{
    width: 90%;
    margin: auto;
    outline: none;
    border: none;
    background-color: #FFDE59;
    padding: 9px 40px;
    border-radius: 5px;
    margin: 10px;
    font-size: 16px;
}
.box div{
    position: relative;
}
.box div i{
    position: absolute;
    font-size: 20px;
    color: black;
    top: 20px;
    left: 20px;
}
.contact .box textarea{
    margin-top: 20px;
    background-color: transparent;
    padding: 10px 30px;
    color: white;
    font-size: 18px;
    border-radius: 20px;
    border: 1px solid #FFDE59;
    outline: none;
    margin-left: 30px;
}
.send{
    background: linear-gradient(#FFDE59 , #ddb100);
    font-size: 19px !important;
    font-weight: 600;
    cursor: pointer;
    margin: 30px auto !important;
}

footer{
    justify-content: space-between;
    padding: 10px 70px;
    background: linear-gradient(#FFDE59 , #ddb100);
    font-size: 20px;
    font-weight: 600;
    color: black;
}
footer .social i{
    font-size: 25px;
    margin: 0 3px;
    cursor: pointer;
}
.social i:hover{
    color: palevioletred;
}
