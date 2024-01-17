<!DOCTYPE html>
<html lang="en">
<head>
    <title>Kabil Pranav K ~ Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="zyxf5OP.png">
    <style>
        *{
    padding: 0px;
    margin: 0px;
}

.header{
    height: 60px;
    width: 100%;
    background-color: aliceblue;
    display: flex;
    justify-content: center;
    align-items:center;
    padding-left: 10px;
    font-size:xx-large;
}

.header1{
    height: 40px;
    width: 100%;
    list-style: none;
    display: flex;
    padding-left:800px;
    column-gap: 20px;
    justify-content:space-evenly;
    align-items: center;
}

.t{
    color: black;
    text-decoration: none;
    font-size: medium;
}

.header2{
    height: 300px;
    width: 100%;
    background-color: aliceblue;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.img{    
    background-color:aliceblue;
    padding: 16px 30px;
    padding-right: 150px;
}

.name{
    font-size:xx-large;
    color: darkgray;
    padding-left: 150px;
    font-weight: 700;
}

.text{
    padding-left: 150px;
}

.text2{
    padding-left: 150px;
}

.clg{
    color: black;
    text-decoration: none;
    padding-left: 150px;
}

.header3{
    background-color: aliceblue;
    height: 250px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.ser{
    background-color: aliceblue;
    padding-top: 20px;
    padding-left: 40px;
    font-size: x-large;
    font-weight: 600;
}

.html{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    row-gap: 10px;
    box-shadow: 0 0 4px black;
    border-radius: 15px;
    background-color: white;
}

.icon{
    font-size:xx-large;
    align-self: center;
}

.py{
    font-size:xx-large;
    align-self: center;
}

.cicon{
    font-size:xx-large;
    align-self: center;
}

.Python{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    row-gap: 10px;
    box-shadow: 0 0 4px black;
    border-radius: 15px;
    background-color: white;
}

.C{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    row-gap: 10px;
    box-shadow: 0 0 4px black;
    border-radius: 15px;
    background-color: white;
}

.web{
    font-weight: 700;
}

.vp{
    background-color: darkgray;
    border-radius: 5px;
}

.vp:hover{
    background-color: aliceblue;
    color: black;
}

.b1{
    color: black;
    text-decoration: none;
}
    </style>
</head>
<body>
    
    <div>
        <div class="header">
            <pre>Kabil's Portfolio</pre>
            <div class="header1">
                <a href="https://github.com/Kabil-Pranav-K" class="t"> <i class="fa-brands fa-github"></i></a>
                <a href="https://www.linkedin.com/in/kabil-pranav-k-982b55217/" class="t"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://www.instagram.com/kabil_pranav_k/" class="t"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
    </div>
    
    <div class="header2">
        <ul>
            <p class="text">I am,</p><br>
            <p class="name">Kabil Pranav K</p>
            <br>
            <p class="text2">Developer | Passionate Coder | Seeking Intern</p>
            <br>
            <a href="https://www.amrita.edu/" class="clg">Student at Amrita Vishwa Vidyapeetham</a>
        </ul>
        <img src="kabil.jpg" height="300px" alt="Kabil.jpg" class="img">
    </div>

    <p class="ser">Services I Provide</p>
    
    <div class="header3">
        <div class="html">
            <i class="fa-brands fa-html5 icon"></i>
            <p class="web">Web Development</p>
            <p>Web Page | Hosting | Contact Forms</p>
            <p>As a Full stack Developer I am well versed<br>
                 in html/css, react and javascript. Click on<br>
                 the button below to view my porjects.
            </p>
            <button type="button" class="vp"> 
                <a class="b1" href="file:///C:/Htmlcss/first.html">View Projects</a>
            </button>
        </div>
        <div class="Python">
            <i class="fa-brands fa-python py"></i>
            <p class="web">Python</p>
            <p>Machine learning | Digital Image Processing | Kivy</p>
            <p>I am well versed in Python programming. <br>
               Machine learning, kivy and Digital Image Processing <br>
               are the techniques I am well aware of.</p>
            <button type="button" class="vp"> 
                <a class="b1" href="file:///C:/Htmlcss/first.html">View Projects</a>
            </button>
        </div>
        <div class="C">
            <i class="fa-solid fa-c cicon"></i>
            <p class="web">C Program</p>
            <p>C | Embedded C</p>
            <p>I am well versed in C programming. <br>
               And I know Embedded C program as well<br>
               LPC2148 and MSP432 are the microcontroller <br>
               in which I have done the Embedded C programming.</p>
            <button type="button" class="vp"> 
                <a class="b1" href="file:///C:/Htmlcss/first.html">View Projects</a>
            </button>
        </div>
    </div>

</body>
</html>
