<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shivam's Portfolio</title>
    <link rel="icon" href="" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=DynaPuff:wght@400..700&family=Neuton:ital,wght@0,200;0,300;0,400;0,700;0,800;1,400&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" type="image/png" href="/pngs/logo.jpg"/>
    <link rel="stylesheet" href="/style.css" />
    <link rel="stylesheet" href="/style1.css">
  </head>
  <body>
    <header>
      <div class="navbar">
        <nav>
          <ul>
            <li><a href="#Home" id="logo">Shivam's Portfolio</a></li>
            <li><a href="#Home">Home</a></li>
            <li><a href="#About">About</a></li>
            <li><a href="#Skills">Skills</a></li>
            <li><a href="#contact">Contact Us</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <main>
      <section id="home">
        <div class="para">
          <h1 class="hello">HELLO EVERYONE!</h1>
          <p class="new">I'm a passinated web developer and designer</p>

          <img src="" alt="" />
        </div>
      </section>

      <section id="About">
        <h1>ABOUT</h1>
        <p>
          I am a front-end developer with a strong interest in user experience,
          responsive design, and clean code. I enjoy turning ideas into reality
          using HTML, CSS, and JavaScript.
        </p>
      </section>

      <section id="Skills">
        <h1 class="kpop">SKILLS</h1>
        <div id="cards">

       
        <div class="card1">
        <img src="/pngs/html.png" alt="htmllogo" height="200px"></img>
        <h1>HTML</h1>
        <p>
          Specialitation in HTML!
        </p>
        </div>
        


        <div class="card2">
             <img src="/pngs/css3.png" alt="csslogo" height="200px" ></img>
        <h1>CSS</h1>
        <p>
          Specialitation in CSS!
        </p>
        </div>


        <div class="card3">
             <img src="/pngs/javascript.png" alt="jslogo" height="200px" ></img>
        <h1>JAVASCRIPT</h1>
        <p>
          Specialitation in JAVASCRIPT!
        </p>
        </div>


        <div class="card4">
             <img src="/pngs/Python.png" alt="pythonlogo" height="200px"></img>
        <h1>PYTHON</h1>
        <p>
          Specialitation in PYTHON!
        </p>
        </div>


        <div class="card5">
             <img src="/pngs/java.png" alt="javalogo" height="200px" ></img>
        <h1>JAVA</h1>
        <p>
          Specialitation in JAVA!
        </p>
        </div>
        <div class="card6">
             <img src="/pngs/react.png" alt="reactlogo" height="200px" ></img>
        <h1>REACT JS</h1>
        <p>
          Specialitation in REACT JS!
        </p>
        </div>
        <div class="card7">
             <img src="/pngs/mongodb.png" alt="mongodblogo" height="200px" ></img>
        <h1>MONGO DB</h1>
        <p>
          Specialitation in MONGO DB!
        </p>
        </div>

        </div>
      </section>

      <section id="contact">
        <h1 class="joj">CONTACT US</h1>
        <form action="/action.php">
        
        <div class="contacts">
          <h1 id="logout">login</h1>

          <label for="name">Name</label>
          <input type="text" id="name" placeholder="Enter Your Name " />

          <label for="email">Email id</label>
          <input type="email" id="email" placeholder="Enter Your Email id" />

          <label for="mob">Phone no.</label>
          <input type="tel" id="mob" placeholder="Enter Your Phone No. ">

        <div class="button">
          <button>Send Message</button>
        </div>

          </form>
        </div>

      </section>
    </main>

    <footer class="footer">

        <p >&copy ; 2025 Shivam kumar. All Rights Reserved.</p>
        <p  class="copy">Made With <span class="heart"> &hearts;</span> By Shivam Kumar !</p>

      </footer>





  </body>
</html>
