# My-Portfolio-
this is my portfolio which I created using HTML and CSS 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <style>
      * { 
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins' cursive;
    text-decoration: none;
    list-style: none;
}   
.header{
position: fixed;
top: 0;
left: 0;
width: 100%;
padding: 35px 12%;
background:rgb(0,0,0,0.8);
backdrop-filter: blur(10px);
display: flex;
justify-content: space-between;
align-items: center;
z-index: 100;
}
.logo{
    font-size: 25px;
    color: white;
    font-weight: 600;
    transition: 0.3s ease;
}
.logo:hover{
    color: rgb(209, 11, 231);
    text-shadow: 0 0 25px rgb(126, 15, 217),
                 0 0 50px rgb(222, 12, 163);
                 transform: scale(1.1);
}
span{ color: orangered;}
.navbar{
    font-size: 18px;
    color: white;
    font-weight: 500;
    margin: 0 20px;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;
}
.navbar a:hover,
.navbar a.active
{
    color: orangered;
 border-bottom: 3px solid orangered ;
}
.contact{
    padding: 10px 28px;
    background-color: white;
    color: black;
    border: 2px solid transparent;
    border-radius: 8px;
    font-size: 16px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
}
.contact:hover{
    background-color: orangered;
    box-shadow: 0 0 25px orangered;
    color: white;
}
.home{
    width: 100%;
    min-height: 100vh;
    background: white;
    display: flex;
    align-items: center;
    gap: 7em;
    padding: 30px 12% 0 ;
}
.home-content{
     max-width: 800px;
    }
    .home-content h3{
        font-size: 42px;
    }
    .home-content h1{
        font-size: 62px;
        line-height: 1.2;
    }
    .home-content p{
        font-size: 18px;
        margin: 25px 0 30px;
    }
    .home-content:hover{
        color: rgb(11, 231, 205);
        text-shadow: 0 0 25px rgb(246, 186, 7),
                     0 0 50px rgb(222, 205, 12);
                     transform: scale(1.1);
    }
    .btn-box{
        width: 345px;
        display: flex;
        gap: 2em;
    }
    .btn-1{
        padding: 15px 28px;
        background-color: black;
        color: white;
        border: 2px solid transparent;
        border-radius: 8px;
        font-size: 18px;
        letter-spacing: 1px;
        font-weight: 600;
        transition: 0.3s ease;
        cursor: pointer;
    }
    .btn-1:hover{
        padding: 15px 28px;
        background-color: orangered;
        color: white;
        border: 2px solid black;
        border-radius: 8px;
        font-size: 18px;
        letter-spacing: 1px;
        font-weight: 600;
        transition: 0.3s ease;
        cursor: pointer;
    }
    .btn-2{
        padding: 15px 28px;
        background-color: orangered;
        color: white;
        border: 2px solid black;
        border-radius: 8px;
        font-size: 18px;
        letter-spacing: 1px;
        font-weight: 600;
        transition: 0.3s ease;
        cursor: pointer;
    }
    .btn-2:hover{
        background-color: white;
        color: orangered;
    }
    .img-box img{
        border-radius: 50%;
        width: 400px;
    }
   ::-webkit-scrollbar{
        width: 15px;
    }
    ::-webkit-scrollbar-thumb{
        background-color: orangered;
    }
    ::-webkit-scrollbar-track{
        background-color: rgba(0, 0, 0, 0.6);
        width: 50px;
    }
.about{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 12% 8%;
    gap: 1em;
    background: rgb(0, 0, 0);
}
.about-img img{
    position: relative;
    width: 400px;
    box-shadow: 0 0 25px rgb(160, 7, 225), 
                0 0 50px rgb(232, 5, 114);
    border-radius: 50%;
}
.about-content h2{
    text-align: center;
    color: white;
    font-size: 42px;
}
.heading{
    color: white;
    text-align: left;
    font-size: 42px;
    text-align: center;
}
.para{
    color: white;
    font-size: 20px;
    margin: 1em;
    font-family: sans-serif;
    text-align: center;
}
.contact-form h2{
    text-align: center;
    margin-top: 3em;
    margin-bottom: 1em;
    font-size: 36px;
}
.contact-form form{
    max-width: 50em;
    margin: 1rem auto;
    text-align: center;
    margin-bottom: 3em;
}
.contact-form form .input-box{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
.contact-form form .input-box input,.contact-form form textarea {
    width: 100%;
padding: 1.5em;
font-size: 18px;
color: black;
background: white;
border-radius: .8rem;
margin: 1rem 0; 
resize: none;
}
.footer{
    position: relative;
    bottom: 0;
    width: 100%;
    padding: 40px 0;
    background-color: black;
}
.social{
    text-align: center;
    padding-bottom: 25px;
    color: white;
}
.social a{
    font-size: 24px;
    color: white;
    border: 2px solid orangered;
    width: 40px;
    height: 40px;
    line-height: 38px;
    display: inline-block;
    text-align: center;
    border-radius: 50%;
    margin: 0 8px;
    box-shadow: inset0 0 10px orangered , 0 0 10px orangered;
    transition: 0.3s ease;
}
.social a:hover{
    transform: scale(1,2) translateY(-10px);
    color: rgb(242, 236, 234);
    border: 2px solid orangered;
}
.footer ul{
    margin-top: 0;
    padding: 0;
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 0;
    text-align: center;
}
.footer ul li a{
    color: white;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;
}
.copyright {
    margin-top: 15px;
    text-align: center;
    font-size: 12px;
    color: white;

}
       /* Added smooth scrolling for better user experience */
        HTML {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>
    <header class="header"> 
        <a href="#" class="logo"> <span>RIY</span>ANSH</a>
        <nav class="navbar">
            <!-- Updated href attributes to point to specific sections by their IDs -->
            <a href="#portfolio" class="active">Portfolio</a>
            <a href="#about" class="navbar">About Me</a>
            <a href="#experience" class="navbar">Experience</a>
            <a href="https://github.com/RIYANSH24" target="_blank" class="navbar">Projects</a>
            <a href="#education" class="navbar">Education</a>
        </nav>
        <a href="#contact" class="contact">Contact Me</a>
    </header>
    <!-- Added id="portfolio" to allow navigation to this section -->
    <section id="portfolio" class="home">
        <div class="home-content">
            <h3>HI</h3>
            <h1> I'm  <span> RIYANSH <br></span>  BBA DM Student </h1>
            <p> Hey there! I’m Riyansh Gupta, a BBA student specializing in Digital Marketing with a passion for technology and sports. Skilled in front-end development and Tally ERP, Let’s connect!</p>
            <div class="btn-box">
                <!-- Updated buttons to use links for smooth navigation -->
                <button class="btn-1"><a href="#about" style="text-decoration: none; color: inherit;">About Me</a></button>
                <button class="btn-2"><a href="#experience" style="text-decoration: none; color: inherit;">Experience</a></button>
            </div>
        </div>
        <div class="img-box">
            <img src="PORTFOLIOimg.jpg.jpg" alt="">
        </div>
    </section>
    <!-- Added id="about" to allow navigation to this section -->
    <section id="about" class="about">
        <div class="about-img">
            <img src="p2.jpg" alt="" style="border-radius: 50%; width: 400px;">
        </div>
        <div class="aboutcontent">
            <h2 class="heading">ABOUT<span>ME</span></h2>
            <pre class="para"> 
            <br>
            Hi, I’m Riyansh Gupta 
            A BBA student specializing in Digital Marketing with a strong interest in technology and sports.
            <br>
            Alongside my studies, I’ve developed basic front-end development skills and am proficient in Tally ERP 9 and Tally Prime.
            I graduated from Virendra Public School,
             I was proud to earn a silver medal in wrestling and a gold medal in tug-of-war during school competitions.
             Currently, I serve as the head volunteer of my college sports club, leading and organizing various events.   
            When I’m not working on academic or club responsibilities,
             I enjoy exploring new opportunities to grow my skills and collaborate on exciting projects.            
            Let’s connect and create something impactful!
            </pre>
            <!-- Button to navigate to the experience section -->   
        </div>
    </section>
    <!-- Added id="contact" to allow navigation to this section -->
    <section id="contact" class="contact-form">
        <h2 class="contact-me"> Contact <span>Me </span></h2>
        <form action="#">
            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email">
            </div>
            <div class="input-box">
                <input type="number" placeholder="Phone number">
                <input type="text" placeholder="Subject">
            </div>
            <textarea cols="30" rows="10" placeholder="Your Message"></textarea>
            <input type="submit" value="Send Message" class="btn-1">
        </form>
    </section>
    <footer class="footer">
        <div class="social">
            <a href="https://www.instagram.com/riyanshxgupta17?igsh=MWNkMmRqcnJrYTBiMQ==" target="_blank"><i class='bx bxl-instagram-alt'></i></a>
            <a href="https://www.linkedin.com/in/riyansh-gupta-2a49b8315/" target="_blank"><i class='bx bxl-linkedin-square'></i></a>
            <a href="https://github.com/RIYANSH24" target="_blank"><i class='bx bxl-github'></i></a>
        </div>
        <ul class="list">
            <!-- Footer links updated to point to specific sections -->
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#">Privacy Policy</a></li>
        </ul>
        <p class="copyright"> © 2024 RIYANSH All Rights Reserved</p>
    </footer>
</body>
</html>
