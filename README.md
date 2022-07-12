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
            border: 5px solid burlywood;
        }
        .firstHeader{
            border-style: solid;
            padding: 5px;
        }
        .name{
            text-align: center;
            padding-top: 2rem;
        }
        .subTitle{
            display: inline-block;
            width:50%;
            padding-top: 0.5rem;
        }
        .location{
            display: inline-flex;
            text-align: right;
            padding-top: 0.5rem;
        }
        
        .closingStatement{
            text-align: center;
            padding-top: 0.5rem;
            padding-bottom: 2rem;
        }
        
        
        .menuDiv{
            padding-bottom: 2.5rem;
            border: 5px solid burlywood;
        }
        .menu{
            display: inline; /* the default for span */
            width: 100px;
            height: 100px;
            padding: 5px;
            text-align: center;
        }
        .educationMenu{
            padding: 1rem;
        }
        .experienceMenu{
            padding: 1rem; 
        }
        .skillsMenu{
            padding: 1rem;
        }
        .contactsMenu{
            padding: 1rem;
        }

        
        .body{
            border-style: solid;
            padding: 5px;
        }
        /* I truly struggled to amke these individual inline structures so I put them in a table*/
        .education{
            align-items: flex-start;
            display: inline-block;
            width:65%;
        }
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
            padding-left: 10%;
        }
        .link{
            display: center;
        }
        .image1{
            display: inline-block;
            margin-left: auto;
            margin-right: auto;
            border-radius: 50%;
            padding-top: 1rem;
            padding-left: 10%;
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
                <h4 class="subTitle"> Sub-Title (my position righ now) </h4> 
                <h4 class="location"> Some of my location </h4>
                <h4 class="closingStatement"> A little something about me </h4> <header>                                                      
            </header>
        </section>
    </div>

    <div class="menuDiv">
        <section class="menu">
            <h2> Menu </h2>
            <a class="educationMenu" href="#education"> Education </a>
            <a class="experienceMenu" href="#experience"> Experience </a>
            <a class="skillsMenu" href="#skills"> Skills </a>
            <a class="contactsMenu" href="contactHeading"> Contact Details </a>
        </section>
    </div>

    <div class="body">
        <table>
            <tr>
                <section class="education">
                    <h2 id="education"><ins> Education </ins></h2>
                    <section>
                        <h3> Intro to Web at CodeSpace</h3>
                        <p> Toss your dirty shoes in my washing machine heart?</p>
                    </section>
                    <section>
                        <h3> Most Recent 1 </h3>
                        <p> I wait for you, I don't know why, All I know is I can't hide, At this temperature you can take over my mind </p>
                    </section>
                </section>
            </tr>
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
                <img class="image1" src="images/call.jpg" alt="phone number" width="40px"; height="20px"> 
                <p class="phoneNumber"><ins><a href="tel:0682458716">+27 68 245 8716</a></ins></p>
            </footer>
        </section>
    </div>

    

  </body>
</html>