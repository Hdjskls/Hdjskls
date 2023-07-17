- 👋 Hi, I’m @Hdjskls
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Hdjskls/Hdjskls is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charsert="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Rohit - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap"
      rel="stylesheet"
    />

    <style>
      * {
        margin: 0;
        padding: 0;
      }
      body {
        background-color: rgb(0, 0, 33);
        color: white;
        font-family: "poppins", sans-serif;
      }
      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 80px;
        background-color: rgb(18, 18, 62);
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
        color: lavender;
        font-size: 1.4rem;
      }
      main hr {
        border: 0;
        background: #9c97f1;
        height: 1.2px;
        margin: 60px 84px;
      }
      .left {
        font-size: 1.5rem;
      }
      .firstSection {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 130px 0;
      }

      .firstSection > div {
        width: 30%;
      }
      .leftSection {
        font-size: 3rem;
        margin: 70px 0;
      }
      .rightSection img {
        width: 80%;
      }
      .purple {
        color: rgb(170, 107, 228);
      }
      .text-gray {
        color: gray;
      }
      #element {
        color: rgba(170, 107, 228);
      }
      .secondSection {
        max-width: 80vw;
        margin: auto;
        height: 80vh;
      }
      .secondSection h1 {
        font-size: 1.9rem;
      }
      .secondSection .box {
        background: white;
        width: 77vw;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }

      .secondSection .vertical {
        height: 93px;
        width: 1px;
        background-color: white;
        margin: 0 100px;
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
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <div class="left">Rohit's Portfolio</div>
        <div class="right">
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Services</a></li>
            <li><a href="/">Projects</a></li>
            <li><a href="/">Contact me</a></li>
          </ul>
        </div>
      </nav>
    </header>
    <main>
      <section class="firstSection">
        <div class="leftSection">
          Hi,My name is <span class="purple">Rohit</span>
          <div>and I am a passionate</div>
          <div>Web Developer</div>
          <span id="element"></span>
        </div>
        <div class="rightSection">
          <img src="bg.png" alt="" />
        </div>
      </section>
      <hr />

      <section class="secondSection">
        <span class="text-gray">What I have done so far</span>
        <h1>Work Experience</h1>

        <div class="box">
          <div class="vertical">
            <img class="image-top" src="developer.png" alt="" />
            <div class="vertical-text">HTML Developer (2010-2012)</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero
              unde omnis ullam,enim facilis possimus accus. Dolores mollitia
              odio quos. Facilis, incidunt?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="developer.png" alt="" />
            <div class="vertical-text">HTML Developer (2010-2012)</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero
              unde omnis ullam,enim facilis possimus accus. Dolores mollitia
              odio quos. Facilis, incidunt?
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="developer.png" alt="" />
            <div class="vertical-text">HTML Developer (2010-2012)</div>
            <div class="vertical-desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero
              unde omnis ullam,enim facilis possimus accus. Dolores mollitia
              odio quos. Facilis, incidunt?
            </div>
          </div>
        </div>
      </section>
    </main>
    <script>
      var typed = new Typed("#element", {
        strings: ["<i>First</i> sentence.", "&amp; a second sentence."],
        typeSpeed: 50,
      });
    </script>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
      var typed = new Typed("#element", {
        strings: [
          "Web Developer",
          "Graphic Designer",
          "Web Designer",
          "Video Editor",
        ],
        typeSpeed: 50,
      });
    </script>
  </body>
</html>
