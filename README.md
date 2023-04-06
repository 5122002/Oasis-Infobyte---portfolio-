<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/9de58bab44.js" crossorigin="anonymous"></script>
</head>

<bod>
    <div id=" header ">
        <div class="container ">
            <nav>
                <P class="logo"><span>Sachi</span>.Portfolio</P>
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#About ">About</a></li>
                    <li><a href="#Services">Services</a></li>
                    <li><a href="#Portfolio ">Portfolio</a></li>
                    <li><a href="#Contact ">Contact</a></li>
                    <i class=" fas fa-sharp fa-solid fa-circle-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fas fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text ">

                <p>Software Enginneer</p>
                <h1>Wellcome,<br>I`m <span>Sachi</span > Meshram <br>From Nagpur.</h1>
            </div>
        </div>

    </div>



    
    <!--------------about------------------------->

    <div id="About ">
        <div class="contanier " >
            <div class="row ">
                <div class="about-col-1 ">
                    <img src="C:\Users\Sachi\OneDrive\Desktop\OASIS INFOBYTE\level-1 (task-2) PORTFOLIO\mine.jpg ">
                </div>
                <div class="about-col-2 ">
                    <h1 class ="sub-title"> About Me</h1>
                    <p>My name is Sachi Dilip Meshram. I'm perusing Engineering branch computer science at Cummins College of Engineering for Women's Nagpur. I'm veery passionate about my education. I'm actively involved in extra curriculum activities which were held in our board level. I'm also a member of insternshala I work there as campus ambassador also I grabbed same opportunity of campus ambassador with Great Learning academy. My interest is in web development & software development. I have work on project "E-voting " which is a web site where we can identify the user weather is capable of voting or not & proceed further or they'll register themselves.  I have done basic non programming languages such as HTML, CSS, Js, React.Js, Node.Js. I have also learn programming languages such as C, C++, java. i have more hunger to learn more about languages.  Apart from education, My hobbies are reading books, poetry. explore new ways to learn. I like to Dancing, Drawing, listening to the broadcast n music. i love to explore new cities & to see our natural & our Indian culture as well foreign cultures.</p>
                    <div class="tab-titles ">
                        <p class="tab-links active-links " onclick="opentab( 'skills') ">Skills</p>
                        <p class="tab-links " onclick="opentab( 'experience') ">Experience</p>
                        <p class="tab-links " onclick="opentab( 'education') ">Education</p>
                    </div>
                    <div class='tab-contents active-tab' id="skills ">
                        <ul>
                             <li>
                                <span>Web-Desiner</span><br>Designing Web/App interface
                    </li>
                    <li>
                        <span>software-Desiner</span><br>Web/App Developement
                    </li>
                    <li>
                        <span>App Developement</span><br>Bulding Android/ios application
                    </li>
                    </ul>
            </div>

            <div class="tab-contents " id="experience ">
                <ul>
                    <li>
                        <span>2023- Current</span><br>Interni at OasisInfoByte (1Month)<br>Interni at Maharashtra Remote Sensing Applications Centre(Nagpur).
                    </li>
                    <li>
                        <span>2021-2022</span><br>Campus Ambassador at InsternShala & GreatLearning
                    </li>
                </ul>
            </div>
            <div class="tab-contents " id="education ">
                <ul>
                    <li>
                        <span>2018</span><br>10th Board.
                    </li>
                    <li>
                        <span>2018-2020</span><br>12th board.
                    </li>
                    <li>
                        <span>2020-2024</span><br>software Engineering(Student).
                    </li>
                </ul>
            </div>


        </div>
    </div>
    </div>
    </div>




    <!------------------------services------------------->
    <div id="Services ">
        <div class="container ">
            <h1 class="sub-title ">My Services</h1>
            <div class="services-list ">
                <div>
                    <i class="fa-solid fa-code "></i>
                    <h2 class="a ">Web Designing</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis ab architecto aliquam incidunt nihil minus suscipit porro sed cupiditate totam nesciunt esse, corporis atque commodi amet quia voluptate deleniti enim.</p>
                    <a href="# ">learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-crop-simple "></i>
                    <h2 class="b">UI/UX Designing</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis ab architecto aliquam incidunt nihil minus suscipit porro sed cupiditate totam nesciunt esse, corporis atque commodi amet quia voluptate deleniti enim.</p>
                    <a href="# ">learn more</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store-ios"></i>
                    <h2 class="c">App Developer</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis ab architecto aliquam incidunt nihil minus suscipit porro sed cupiditate totam nesciunt esse, corporis atque commodi amet quia voluptate deleniti enim.</p>
                    <a href="#">learn more</a>
                </div>

            </div>
        </div>
    </div>




    <!--------------portfolio-------------->
    <div id="Portfolio ">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="C:\Users\Sachi\OneDrive\Desktop\OASIS INFOBYTE\level-1 (task-2) PORTFOLIO\a16df5e1ec68630bc17a9ec0d7c45b32.jpg ">
                    <div class="layer ">
                        <h3>Social Media App</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus quam distinctio totam eligendi nisi aliquam quo, rem aut itaque tempora! Asperiores porro eius mollitia officia ea, aut nulla illum inventore.</p>
                        <a href="# "><i class="fa-sharp fa-solid fa-link "></i></a>
                    </div>
                </div>
                <div class="work ">
                    <img src="C:\Users\Sachi\OneDrive\Desktop\OASIS INFOBYTE\level-1 (task-2) PORTFOLIO\music.jpg ">
                    <div class="layer ">
                        <h3>Music App</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus quam distinctio totam eligendi nisi aliquam quo, rem aut itaque tempora! Asperiores porro eius mollitia officia ea, aut nulla illum inventore.</p>
                        <a href="# "><i class="fa-sharp fa-solid fa-link "></i></a>
                    </div>
                </div>
                <div class="work ">
                    <img src="C:\Users\Sachi\OneDrive\Desktop\OASIS INFOBYTE\level-1 (task-2) PORTFOLIO\online.shopping.jpg ">
                    <div class="layer ">
                        <h3> Online Shopping App</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus quam distinctio totam eligendi nisi aliquam quo, rem aut itaque tempora! Asperiores porro eius mollitia officia ea, aut nulla illum inventore.</p>
                        <a href="# "><i class="fa-sharp fa-solid fa-link "></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn ">See More</a>
        </div>
    </div>




    <!------------------contact-------------------->
    <div id="Contact">
        <div class="container">
            <div id="row ">
                <div class="contact-left ">
                    <h1 class="sub-title ">Contact Me</h1>
                    <p><i class="fa-sharp fa-solid fa-paper-plane "></i>contact@examp.com</p>
                    <p><i class="fa-solid fa-phone-volume "></i> 0987654321</p>

                    <div class="social-icon ">
                        <a href=" "><i class="fa-brands fa-instagram "></i></a>
                        <a href=" "> <i class="fa-brands fa-facebook "></i></a>
                        <a href=" "><i class="fa-brands fa-linkedin "></i></a>
                        <a href=" "> <i class="fa-brands fa-twitter "></i></a>
                    </div>
                    <a href="... " download class="btn btn2 ">Download CV</a>
                </div>
                <div class="contacts-right ">

                    <form name="submit-to-google-sheet">
                        <input type=" text " name="Name " placeholder="Your Name " required>
                        <input type="email " name="E-mail " placeholder="Your Email " required>
                        <textarea name="message " rows="6 " placeholder="Your Message "></textarea>
                        <button type="submit " class="btn btn3 ">Submit</button>
                        </form#>
                        <span id="msg"></span>
                </div>

            </div>

        </div>
        <div class="copyright ">
            <P>Copyright@Sachi.Portfolio</P>
        </div>
    </div>







    <script>
        var tablinks = document.getElementByClassName(" tab-links ");
        var tabcontents = document.getElementByClassName("tab-contents ");

        function opentab(tabname) {
            for (tablink of tablinks) {
                tablink.classList.remove("active-link ");
            }
            for (tabcontent of tabcontents) {
                tabcontent.classList.remove("active-tab ");
            }
            event.currentTarget.classList.add("active-link ");
            document.getElementById(tabname).classList.add("active-tab ");
        }
    </script>
    <script>
        var sidemenu = document.getElementById("sidemenu ");

        function openmenu() {
            sidemenu.style.right = "0 ";
        }

        function closemenu() {
            sidemenu.style.right = "-200px ";
        }
    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbwEfAmD770HN1Bd4zodshKeQW57D1MV454XdZKXt3rujcVLfLYW1uhu_kKllsobkvXW/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
        form.addEventListener('submit', e => {
            e.preventDefault()
            fetch(scriptURL, {
                    method: 'POST',
                    body: new FormData(form)
                })
                .then(response => {
                    msg,
                    innerHTML = "Thank you !"
                    setTimeout(function() {
                        msg.innerHTML = ""
                    }, 5000)
                    form.reset()

                })
                .catch(error => console.error('Error!', error.message))
        })
    </script>
    </body>
