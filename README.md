# Resume
 My resumé

<!DOCTYPE html>
<html>
  <head>
    <title> Bukho's Resumé </title>
    <link rel="stylesheet" type="text/css" href="stylesheet.css">

    <style>
     body{
        background-color: black;
    }
    
    div{
        margin:30px;
        color: white;
        background-color: darkgray;
        font-family: "Courier New"
    }
        /*for some reason the header isn't working*/
        
    .header{
        background-image: url("background.jpg");
    }
    
    .facePict{
        display: block;
        margin-left: auto;
        margin-right: auto;
        border-radius: 50%;
    }
    
    .firstHeader{
        border-style: solid;
        padding: 5px;
    }
    
    .name{
        text-align: center;
    }
    
    .subTitle{
        display: inline-block;
        width:50%;
    }
    
    .location{
        display: inline-flex;
        text-align: right;
    }
    
    .closingStatement{
        text-align: center;
    }
    
    
    .body{
        border-style: solid;
        padding: 5px;
    }
    /* I truly struggled to amke these individual inline structures so I put them in a table*/
    .experience{
        align-items: flex-start;
        display: inline-block;
        width:75%;
    }
    
    .funThings{
        align-items: flex-end;
        display: inline-block;
        width:25%;
    }
    
    
    .footer{
        border-style: solid;
        padding: 5px;
    }
    
    .contactHeading{
        text-align: center;
    }
    
    .image{
        display: inline-block;
        margin-left: auto;
        margin-right: auto;
    }
    
    .link{
        display: center;
    }
    
    .image1{
        display: inline-block;
        margin-left: auto;
        margin-right: auto;
        border-radius: 50%;
    }
    
    .phoneNumber{
        display: inline-block;
        }
    </style>
    
  </head>


  <body>

    <div class="header">
        <section>
            <header class="firstHeader">
                <img class="facePict" src="images/myFace.jpg" alt="my face" width="150px" height="200px">
                <h1 class="name"><ins> Bukho Sibabalwe Cosa </ins></h1>
                <br>
                <h4 class="subTitle"> Sub-Title (my position righ now) </h4> 
                <h4 class="location"> Some of my location </h4>
                <br>
                <h4 class="closingStatement"> A little something about me </h4> <header>                                                      
            </header>
        </section>
    </div>



    <div class="body">
        <table>
            <tr>
                <section class="experience">
                    <h2 id="experience"><ins> Experience </ins></h2>
                    <section>
                        <h3> Most Recent</h3>
                        <p> treat me like I treat me</p>
                    </section>
                    <section>
                        <h3> Most Recent 1 </h3>
                        <p> I wait for you, I don't know why, All I know is I can't hide, At this temperature you can take over my mind </p>
                    </section>
                </section>
            </tr>
            <tr>
                <aside class="funThings">
                    <h2 id="skills"><ins> Skills</ins></h2>
                    <ul>
                        <li>a</li>
                        <li>list</li>
                        <li>item</li>
                    </ul>
                    <br>
                    <ul>
                        <li><a href="#experience">Experience</a></li>
                        <li><a href="#skills">Skills</a></li>
                    </ul>
                </aside>
                <!-- a line you will never see **queue evil laugh-->
            </tr>
        </table>
    </div>



    <div class="footer">
        <section>
            <footer>
                <h3 class="contactHeading"><ins> My contact details </ins></h3>
                <img class="image" src="images/Gmail-logo.png" alt="gmail symbol" width="40px"; height="20px">
                <a class="link" href="mailto: bukhosibscosa@gmail.com" target="_blank"> bukhosibscosa@gmail.com </a>
                <br>
                <img class="image1" src="images/call.jpg" alt="phone number" width="40px"; height="20px"> 
                <p class="phoneNumber"><ins><a href="tel:0682458716">+27 68 245 8716</a></ins></p>
            </footer>
        </section>
    </div>

    

  </body>
</html>

