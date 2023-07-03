# personal portfolio website
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sanket - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap"
      rel="stylesheet" />
    <style>
      * {
        margin: 0%;
        padding: 0;
      }

      body {
        background-color: rgb(2, 2, 32);
        color: white;
        font-family: "Poppins", sans-serif;
      }

      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 80px;
        background-color: rgb(18, 18, 77);
      }

      nav ul {
        display: flex;
        justify-content: center;
      }
      nav ul li {
        list-style: none;
        margin: 0 23px;
      }
      nav ul li a {
        text-decoration: none;
        color: white;
      }
      nav ul li a:hover {
        color: rgb(153, 153, 243);
        font-size: 1.02rem;
      }
      main hr {
        border: 0;
        background-color: rgb(179, 139, 216);
        height: 1.2px;
        margin: 60px 84px;
      }
      .left {
        font-size: 1.5rem;
      }

      .firstsection {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 140px 0;
      }

      .firstsection > div {
        width: 30%;
      }

      .leftsection {
        font-size: 2rem;
      }
      .leftsection .button{
        padding: 50px 0;
      }
      .leftsection .btn {
        padding: 12px;
          background: rgb(30 30 77);
          color: white;
          border: 2px solid white;
          border-radius: 6px;
          font-size: 20px;
          cursor: pointer;
      }

      .rigthsection img {
        width: 80%;
      }
      .purple {
        color: rgb(167, 115, 216);
      }
      .text-gray {
        color: gray;
      }
      #element {
        color: rgb(167, 115, 216);
      }
      .Secondsection {
        max-width: 80vw;
        margin: auto;
        height: 80vh;
      }

      .Secondsection h1 {
        font-size: 1.9rem;
      }

      .Secondsection .box {
        background: white;
        width: 80vw;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }
      .Secondsection .vertical {
        height: 93px;
        width: 1px;
        background-color: white;
        margin: 0 6vw;
      }

      .image-top {
        width: 23px;
        position: relative;
        top: -32px;
        left: -9px;
      }

      .vertical-title {
        position: relative;
        top: 75px;
        width: 150px;
        font-size: 14px;
    }

      .vertical-desc {
        position: relative;
        top: 85px;
        color: grey;
        width: 150px;
        font-size: 9px;
      }
      footer{
        background-color: rgb(15 15 28);
      }
      .footer{
        display: flex;
        padding: 23px 123px;
        justify-content: space-evenly;
      }

      .footer ul{
        list-style: none;
      }

      .footer > div{
        width: 26%;
      }

      footer .footer-rights{
        text-align: center;
        color: gray ;
        padding: 12px;
      }
      
      @media screen and (max-width: 1400px){
        .box{
          flex-direction: column;
        }
        .Secondsection .vertical{
          height: unset;
        }
        .vertical-title, .vertical-desc{
          left: 45px;
        }
        .Secondsection .box{
          width: 50vw;
        }
        nav{
          flex-direction: column;
        }
        .firstsection{
          flex-direction: column-reverse;
        }
        .leftsection{
          width: 100%;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
        }
        .Secondsection {
          height: 141vh;
      }
        .rigthsection{
          width: 721px !important;
          display: flex;
          justify-content: center;
        }
        .rigthsection img{
          width: 50%;
          margin-bottom: 73px;
        }
        .image-top{
          top: 133px;
        }

        .Secondsection {
          display: flex;
          flex-direction: column;
          align-items: center;
        }
        body{
          min-width: fit-content;

        }

      }
      

    </style>
  </head>

  <body>
    <head>
      <nav>
        <div class="left">Sanket's Portfolio</div>
        <div class="right">
          <ul>
            <li><a href>Home</a></li>
            <li><a href>About</a></li>
            <li><a href>Projects</a></li>
            <li><a href>Contact Me</a></li>
          </ul>
        </div>
      </nav>
    </head>

    <main>
      <section class="firstsection">
        <div class="leftsection">
          <div>Hi My name is <span class="purple">Sanket</span></div>
          <div>and I am a Passionate</div>
          <span id="element"></span>
          <div class="button">
            <button class="btn">Download Resume</button>
            <button class="btn">Visit Github</button>
          </div>
        </div>
        <div class="rigthsection">
          <img src="bg.png.png" alt />
        </div>
      </section>
      <hr />
      <section class="Secondsection">
        <span class="text-gray">What I have done so far</span>
        <h1>Work Experience</h1>

        <div class="box">
          <div class="vertical">
            <img class="image-top" src="html.png.png" alt />
            <div class="vertical-title">Payment Form Using Html</div>
            <div class="vertical-desc">

              The form supports multiple payment options, including credit
              cards, debit cards, and digital wallets, offering flexibility to
              customers."
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="css.png.png" alt />
            <div class="vertical-title">CSS Developer</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
              quaerat delectus dolore porro a veritatis, beatae ipsa explicabo
              labore, maxime ipsam! Nam, est nesciunt iste illo esse quam.
              Aperiam, esse?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="hotstar.png" alt />
            <div class="vertical-title">Hotstar clone app</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
              quaerat delectus dolore porro a veritatis, beatae ipsa explicabo
              labore, maxime ipsam! Nam, est nesciunt iste illo esse quam.
              Aperiam, esse?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="Developer.png.png" alt />
            <div class="vertical-title"></div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
              quaerat delectus dolore porro a veritatis, beatae ipsa explicabo
              labore, maxime ipsam! Nam, est nesciunt iste illo esse quam.
              Aperiam, esse?
            </div>

          </div>
        </section>
      </main>

      <footer>
        <div class="footer">
          <div class="footer-first">
            <h3>Sanket's Developer Portfolio</h3>
          </div>
          <div class="footer-second">
            <ul>
              <li>Home</li>
              <li>About</li>
              <li>Services</li>
              <li>Contact</li>
            </ul>

          </div>
          <div class="footer-third">
            <ul>
              <li>Home</li>
              <li>About</li>
              <li>Services</li>
              <li>Contact</li>
            </ul>

          </div>
          <div class="footer-fourth">
            <ul>
              <li>Home</li>
              <li>About</li>
              <li>Services</li>
              <li>Contact</li>
            </ul>

          </div>
        </div>
        <div class=" footer-rights">
          Copyright &#169;sanketsportfolio.com | All rights reserved
        </div>
      </footer>

      <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
      <!-- Setup and start animation! -->
      <script>
      var typed = new Typed("#element", {
        strings: ["Web Developer", "Web Designer", "Video Editor"],
        typeSpeed: 50,
      });
    </script>
    </body>
  </html>

