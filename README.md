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
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate
            molestiae impedit amet repellat soluta nisi quaerat, temporibus
            consequuntur. Necessitatibus, dolorem.
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
          Lorem ipsum dolor sicing elit. Molestias officiis veniam reprehenderit
          minima praesentium provident eos aperiam excepturi doloribus impedit.
        </p>
        <button class="button">Download CV</button>
        <div class="projects-div flex div-1">
          <img src="./Images/Projects/5.png" alt="" />
          <h3>Ecommerce Website</h3>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quasi, ex!
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-2">
          <img src="./Images/Projects/6.png" alt="" />
          <h3>Weather App</h3>
          <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facere,
            debitis.
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-3">
          <img src="./Images/Projects/7.png" alt="" />
          <h3>Food App</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis,
            nulla!
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
            Lorem Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Praesentium nemo quae deserunt aliquam expedita tempore! Laudantium,
            nobis. Commodi, quod ad. Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Illum iusto sequi dolores nulla quibusdam
            architecto porro officiis, delectus tenetur neque? Quasi ex pariatur
            modi laudantium ipsam officia numquam corrupti, inventore sequi
            consequatur cum ad ducimus aliquid, necessitatibus voluptas. Autem,
            sint. ipsum dolor sit amet consectetur adipisicing elit. Mollitia
            ore.
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
