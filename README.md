# LandingPage
.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content=
        "width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Landing Page</title>
</head>

<body>
    <nav>
        <div class="heading">LDRP Institute of Technology and Research</div>
        <span class="sideMenuButton" 
            onclick="openNavbar()">
            &#9776
        </span>

        <div class="navbar">
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <div class="sideNavigationBar" 
        id="sideNavigationBar">
        <a href="#" class="closeButton" 
            onclick="closeNavbar()">
            &#x274C
        </a>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Sign Up</a>
    </div>

    <div class="line" id="Home">
        <div class="side1">
            <h1>LDRP-ITR</h1>
            <button>
                <a href=
"https://www.ldrp.ac.in/">
                    Explore More
                </a>
            </button>
        </div>
        <div class="side2">
            <img src=
"data:image/jpeg;base64,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"width="500">
        </div>
    </div>

    <section class="about" id="My Projects">
        <div class="content">
            <div class="title">
                <span>Courses</span>
            </div>
            <div class="boxes">
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            B.E. in Computer Engineering
                        </a>
                    </div>
                    <p>
                        LDRP Institute of Technology and Research offers a 4 years B.E. in Computer Engineering course at the UG level.the entry requirements -45.0% in 12th .The total tution fee for this cousre is 456000 for the entire duration of the course.
                    </p>
                </div>
                <div class="box">

                    <div class="topic">
                        <a href="" target="_blank">
                            Master of Business Administrate
                        </a>
                    </div>
                    <p>
               LDRP Institute of Technology and Research offers a 2 years Masterof Business Administrate course at the UG level.the entry requirements -50.0% in graduation .The total tution fee for this cousre is 190000 for the entire duration of the course.

                    </p>
                </div>

                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            Master of Computer Application
                        </a>
                    </div>
                    <p>
    LDRP Institute of Technology and Research offers a 2 years Master of Computer Application course at the UG level.The course offers admission to 60 student.The total tution fee for this cousre is 190000 for the entire duration of the course.

                    </p>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="content">
            <div class="title"><span>Sign Up</span></div>
            <div class="contactMenu">
                <div class="input1">
                    <div class="label1">Your Name</div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Name here">
                    </div>
                    <div class="label1">
                        <label>Your Email</label>
                    </div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Email here">
                    </div>
                    <div class="label1">
                        <label>Your Password</label>
                    </div>
                    <div class="input2">
                        <input type="text" 
                            placeholder="Enter your Password here">
                    </div>
                    <div class="button">
                        <button>Sign Up</button>
                    </div>
                </div>
                <div class="input3">
                    <div class="rightside1">
                        <div class="title1">
                            <span>
                                Contact Us
                            </span>
                        </div>
                        <div class="content1">
                          KH,%,RD No.5,Sector 15,Gandhinagar,Gujarat 382016
                        </div>
                        <div class="title1">
                            <span>More Information</span>
                        </div>
                        <div class="content1">
                            LDRP-ITR was estabalished in 2006.It was estabalished as an Institute of Technical education imparting undergraduate and postgraduate education.It offers BE,MBA,and MC A programs and facilities.Thank you for choosing and supporting us!
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer section -->
    <footer>
        <div class="footer">
            <span>
                Created By HELI PATEL
                
            </span>
        </div>
    </footer>
    <script src="index.js"></script>
</body>

</html>
