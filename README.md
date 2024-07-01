<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer-Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'Times New Roman', Times, serif;
        }
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 90px;
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
            color: rgb(135, 135, 210);
            size: 1.2rem;
        }
        .left {
            font-size: 1.5rem;
        }
        .first {
            display: flex;
            justify-content: space-around;
            margin: 150px 0;
            align-items: center;
        }
        .first > div {
            width: 30%;
        }
        .leftsection {
            font-size: 3rem;
        }

        .leftsection .btn{
            padding: 12px;
            background-color: #000121;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 15px;
            cursor: pointer;

        }
        .rightsection img {
            width: 80%;
        }
        .purple {
            color: rgb(170, 107, 228);
        }
        #element {
            color: rgb(170, 107, 228);
        }
        .second {
            max-width: 80vw;
            margin: auto;
            display: flex;
            justify-content: space-around;
        }
        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 40px 84px;
        }
        h1 {
            font-size: 2rem;
            text-align: center;
            margin-top: 30px;
        }
        .textgrey {
            color: grey;
        }
        .second div {
            margin-top: 40px;
        }
        .second > div {
            align-items: center;
        }
        .leftsection1 img {
            width: 200px;
            height: auto;
        }
        .rightsection1 {
            text-align: left;
            margin-left: 40px;
            font-size: 20px;
        }
        .third {
            max-width: 80vw;
            margin: auto;
            display: flex;
            justify-content: space-around;
        }
        .third div {
            margin-top: 40px;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 200px;
            height: 200px;
        }
        .third div img {
            max-width: 100%;
            max-height: 100%;
        }
        .logo2 img {
            width: 175px;
            height: 175px;
        }
        .logo4 img {
            width: 175px;
            height: 175px;
        }
        
        .fourth {
            width: 50%;
            margin: 40px auto;
            background-color: rgb(18, 18, 62);
            padding: 20px;
            border-radius: 8px;
            align-items: end;
        }
        .fourth form {
            display: flex;
            flex-direction: column;
            align-content: end;
        }
        .fourth form label {
            margin-bottom: 5px;
            font-size: 1rem;
        }
        .fourth form input,
        .fourth form textarea {
            margin-bottom: 10px;
            padding: 8px;
            border: none;
            border-radius: 5px;
            font-size: 0.9rem;
            background-color: #333;
            color: white;
        }
        .fourth form input[type="submit"] {
            background-color: rgb(170, 107, 228);
            color: white;
            cursor: pointer;
            font-size: 1rem;
            padding: 10px;
        }
        .fourth form input[type="submit"]:hover {
            background-color: rgb(135, 135, 210);
        }


        footer {
            background-color: rgb(18, 18, 62);
            color: white;
            padding: 10px 20px;
        }

        footer img{
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="left">Prem's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="#home" onclick="scrollToSection('home')">Home</a></li>
                    <li><a href="#About" onclick="scrollToSection('About')">About</a></li>
                    <li><a href="#skills" onclick="scrollToSection('skills')">Skills</a></li>
                    <li><a href="#projects" onclick="scrollToSection('projects')">Projects</a></li>
                    <li><a href="#section-four" onclick="scrollToSection('section-four')">Contact Me</a></li>
                </ul>
                
            </div>
        </nav>
    </header>

    <main>
        <section class="first">
    <div class="leftsection">
        Hi, My Name is <span class="purple">Prem</span>
        <div>and I am a </div>
        <span id="element"></span>
        <div class="buttons">
            <button class ="btn" onclick="window.open('resume-example.pdf')">Download Resume</button>
        </div>
    </div>
    <div class="rightsection">
        <img src="image1.png" alt="">
    </div>
</section>
        <hr>
        <h1 id="About">About Me</h1>
        <section id="About" class="second" >
            <div class="leftsection1">
                <img src="image3.png" alt="">
            </div>
            <div class="rightsection1">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique veritatis architecto animi delectus, asperiores, facilis autem deserunt quas natus necessitatibus, eum quidem sit alias at suscipit repudiandae nulla deleniti maiores!
              Iusto ab quidem voluptatem necessitatibus perspiciatis, cum aut hic accusantium tempore odit impedit. Assumenda quibusdam ad minima aut. Id neque dolores fuga tempora, nemo temporibus veniam perferendis iusto rem repellat.
              Earum placeat non nisi nostrum vitae qui sit cum iste consequatur voluptas ipsum est, consequuntur sequi dolore sed vero velit assumenda reiciendis odio? Voluptas odio at vitae repudiandae voluptate? Nemo.
              Consectetur commodi nisi, dolor illo assumenda deserunt quas error quidem, aspernatur quisquam soluta facilis tempora voluptatibus laboriosam id. Repellat ad quia ipsum iste quasi, facere autem soluta! In, qui a?
              Blanditiis cum cumque repellat nam nostrum nemo, in iure, dolorem iste fugit ipsum aliquam porro esse? Provident est consectetur vero ipsum perferendis quae ab, voluptatem consequatur fugiat porro quasi eaque.
            </div>
        
        </section>
        <hr>
        <h1 id="skills">Skills</h1>
        <section  id ="skills"class="third">
            <div class="logo1">
                <img src="htmllogo.png" alt="">
            </div>
            <div class="logo2">
                <img src="csslogo.png" alt="">
            </div>
            <div class="logo3">
                <img src="javascriptlogo.png" alt="">
            </div>
            <div class="logo4">
                <img src="clogo.png" alt="">
            </div>
            <div class="logo5">
                <img src="javalogo.png" alt="">
            </div>
        </section>

        <hr>
        <h1 id="section-four">Contact Me</h1>
        <section class="fourth">
            <form>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <input type="submit" value="Send Message">
            </form>           
        </section>

        <footer>
            <div style="display: flex; justify-content: space-between; align-items: center; padding: 20px;">
                <div>
                    <a href="https://www.linkedin.com/in/prem-ghundiyal-740853279/" target="_blank">
                        <img src="linkedin.png" alt="LinkedIn" style="width: 30px; height: 30px; margin-right: 10px;">
                    </a>
                    <a href="https://github.com/PREMGHUNDIYAL" target="_blank">
                        <img src="github.png" alt="GitHub" style="width: 30px; height: 30px; margin-right: 10px;">
                    </a>
                    <a href="https://www.instagram.com/" target="_blank">
                        <img src="instagram.png" alt="Instagram" style="width: 30px; height: 30px;">
                    </a>
                </div>
                <div>
                    &copy; 2024 Prem's Portfolio. All rights reserved.
                </div>
            </div>
    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['Computer Engineering Student', 'Web Developer', 'Video Editor'],
          typeSpeed: 50,
        });

        function scrollToSection(sectionId) {
            const section = document.getElementById(sectionId);
            section.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
