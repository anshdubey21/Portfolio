# Portfolio
My portfolio website

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ansh - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(17, 1, 51);
            color: white;
            font-family: 'Poppins', sans-serif;
        }
        nav{
            display:flex;
            justify-content: space-around;
            align-items: center;
            height:80px;
            background-color:rgb(47, 47, 126) ;
        }
        nav ul{
            display: flex;
            justify-content: center;
        }
        nav ul li{
            list-style:none;
            margin:0 23px;
        }
        nav ul li a{
            text-decoration:none;
            color:white
        }
        nav ul li a:hover{
           color:rgb(84, 84, 236);
           font-size: 1.07rem;
        }

        main hr{
            border:0;
            background:#9c97f1;
            height: 1.2px;
            margin: 60px 84px;
        }


        .left{
            font-size: 1.6rem;
        }
        .firstsection{
            display:flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }
        .firstsection > div{
            width:30%;
        }
        .leftsection{
            font-size: 3rem;
        }
        .leftsection .buttons{
            padding: 33px;
        }
         
        .leftsection.btn{
            padding: 12px;
            background: #1e2167;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;

        }

        

        .rightsection img{
            width:80%;
            margin: 50px 0;
           
        }
         .purple{
            color: rgb(251, 4, 242); 
         }
         .text-gray{
            color: gray;
         }
        #element{
            color: rgb(251, 4, 242); 
        }
        .secondsection{
            max-width: 80vw;
            margin:auto;
            height: 80vh;
        }
        .secondsection h1{
            font-size: 1.9rem;
        }
        .secondsection .box{
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display:flex;
        }
        .secondsection .vertical{
            height: 93px;
            width: 1px; 
            background-color: white;
            margin:0 140px;
        }
        .image-top{
            width: 45px;
            position: relative;
            top: -32px;
            left: -9px;
        }
        .vertical-title{
            position: relative;
            top: 75px;
            width: 150px;

        }
        .vertical-desc{
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 10px;
        }
        footer{
            background-color:rgb(47, 47, 126);
            
        }
        .footer{
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }
        .footer ul{
            list-style: none;
        }
        .footer>div{
            width: 223px;
        }
        footer .footer-rights{
            text-align: center;
            color: gray;
            padding: 12px;
        }
    </style>
</head>
 
<body>
    <header>
        <nav>
            <div class="left"> Ansh's Portfolio</div>
            <div class="right"></div>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">services</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact Me</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="firstsection">
        <div class="leftsection">
                Hi,My name is <span class="purple"> Ansh</span>

                <div>and I am a passionate</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>
        </div>
            </div class="rightsection">
              <img src="bg.png.png" alt="">
            
        </div>
        </section>
<hr>
        <section class="secondsection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">

                

                <div class="vertical">
                    <img class="image-top"src="developer.png.png" alt="">
                    <div class="vertical-title">
                       WEB-DEVELOPMENT
                    </div>
                    <div class="vertical-desc">
                        I have done certified course from "My captain" in web development also I have 1.5 years of Experience how to make a basic wesite page.
                    </div>
                  </div>

                <div class="vertical">
                    <img class="image-top"src="developer.png.png" alt="">
                    <div class="vertical-title">
                       UI/UX Design
                    </div>
                    <div class="vertical-desc">
                        I have done certificate course from "My captain" in UI/UX also i have 8 months of Experience and i have made one of the project in UI/UX know as pin point app in figma.
                    </div>
                  </div>

                <div class="vertical">
                    <img class="image-top"src="developer.png.png" alt="">
                    <div class="vertical-title">
                       MARKETING & BUSINESS-DEVELOPMENT
                    </div>
                    <div class="vertical-desc">
                        I have successfully completed the HRM period training with the "lernx" and also i have done campus ambassador program with "my captain" in Marketing and business development & sales.
                    </div>
                  </div>
              <div class="vertical">
                <img class="image-top"src="developer.png.png" alt="">
                <div class="vertical-title">
                   C++ PROGRAMMING
                </div>
                <div class="vertical-desc">
                    I have done a certificate course from "coursera" in c++ programming language.
                </div>
              </div>
              
            </div>
        </section>
    </main>

    <footer>
       <div class="footer">
        <div class="footer-first">
            <h3>Ansh's Developer Portfolio</h3>
        </div>
        <div class="footer-second">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
                <li>services</li>
            </ul>
        </div>
        <div class="footer-third">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
                <li>services</li>
            </ul>
        </div>
        <div class="footer-fourth">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
                <li>services</li>
            </ul>
        </div>
       </div>
    <div class="footer-rights"> 
        Copywrite &#169; Anshportfolio.com | All rights reserved
    </div>
    </footer>
    
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Graphic Designer', 'UI/UX Designer', 'Marketing','Web Developer'],
      typeSpeed: 50,
    });
  </script>

</body>

</html>
