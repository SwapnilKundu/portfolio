<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css"> 

</head>
<body>
  <div id="header">
    <div class="container">
        <nav>
            <img src="images/logo1.png" class="logo" width="40" height="60">
            <ul id="sidemenu">
                <li><a href ="#header">Home</a></li>
                <li><a href ="#about">About</a></li>
                <li><a href ="#Services">Services</a></li>
                <li><a href ="#portfolio">Portfolio</a></li>
                <li><a href ="#contact">Contact</a></li>
                <i class="fas fa-times" onclick="closemenu()"></i>
           </ul>
            <i class="fas fa-bars"onclick = "openmenu()"></i>
        </nav>
        <div class="header-text">
            <p>A CS undergrad </p>
            <h1>Hi, I'm <span>Swapnil Kundu</span> <br> from Bangladesh</h1>
        </div>
    </div>
  </div>





  <div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/Aboutme4.jpg" alt="Profile Image">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title"><br>About Me</h1>
                <p>
                    <br><br><br><br>Hi, I'm Swapnil Kundu Argha, a Computer Science and Engineering student at <a href="http://www.kuet.ac.bd/" target="_blank">Khulna University of Engineering & Technology (KUET)</a>. Leaving Cox’s Bazar Medical College behind,I'm driven by a passion for technology.Currently a Senior Executive at <a href="https://www.facebook.com/KBEC.official">KUET Business and Entrepreneurship Club (KBEC)</a>, and Assistant Director of Content and Ideation at <a href="https://scontent.fjsr8-1.fna.fbcdn.net/v/t39.30808-6/414475463_878653704262850_605489790676270348_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=dd5e9f&_nc_eui2=AeG7qaCzWQGluZMTMKWtrD6ipcnI0dawWuilycjR1rBa6PLkHzdtJERiOyrmRQaxy3TT_q5vz9qIQ5m4l8xfiGP6&_nc_ohc=qg8Pu4EAUVYAX9avaA_&_nc_ht=scontent.fjsr8-1.fna&oh=00_AfBZ6Lqa5248mqS64WxhR3KxGRhN1UCrqkgUgA0V5dsZlw&oe=65AF45DF">HULT PRIZE, KUET</a>.I also serve as Finance Secretary at <a href="#link-to-GMA">Greater Mymensingh Association,KUET</a>, and hold the position of দপ্তর সম্পাদক at <a href="#link-to-theater">কুয়েট থিয়েটার</a>.Balancing technology and leadership,I aim to make a positive impact in both academic and extracurricular pursuits.Let's connect and explore the possibilities!
                </p>

                <div class="tab-titles">
                    <p class="tab-links active" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experience')">Experience</p>
                    <p class="tab-links"onclick="opentab('education')">Education</p>
            </div>
            <div class="tab-contents active-tab"id ="skills">
                <ul>
                    <li><span>Clubs</span><br>Assistant Director of Contents of KBEC</li>
                    <li><span>Webs Development</span><br>Web app Development</li>
                    <li><span>App development</span><br>Building Android/JAVA project</li>
                </ul>
            </div>
            <div class="tab-contents" id ="experience">
                <ul>
                    <li><span>2022-Current</span><br>An Active member of KBEC</li>
                    <li><span>2023-Semester 2.2</span><br>App Development by JAVA</li>
                    <li><span>2024-Semester 3.1</span><br>Web Development by HTML,CSS,JAVA</li>
                    <li><span>2022-Current</span><br>An Active member of KBEC</li>

                </ul>
            </div>
            
            <div class="tab-contents" id ="education">
                <ul>
                    <li><span>2018</span><br>SSC from Mymensingh Zilla School,Mymensingh</li>
                        <li><span>2020</span><br>HSC from Ananda Mohan College,Mymensingh</li>
                        <li><span>From March,2022</span><br>Currently studying BSc in CSE department</li>
                </ul>
            </div>    
        </div>
    </div>
  </div>




  <div id="Services">
    <div class ="container">
    <h1 class="sub-title">My Services</h1>
    <div class ="services-list">

        <div>
            <i class="fa-solid fa-code"></i>
            <h2>
                Web Design
            </h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, est! Aliquam, asperiores optio rerum aliquid, quo impedit saepe sint iure repellendus minima corporis culpa mollitia, consequatur odio fuga necessitatibus dolore.

            </p>
            <a href="#">Learn more</a>
        </div>
        <div>
            <i class="fa-solid fa-crop"></i>
            <h2>
                UI/UX Design
            </h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, est! Aliquam, asperiores optio rerum aliquid, quo impedit saepe sint iure repellendus minima corporis culpa mollitia, consequatur odio fuga necessitatibus dolore.

            </p>
            <a href="#">Learn more</a>
        </div>
        <div>
            <i class="fa-brands fa-app-store"></i>
            <h2>
                
                App Design
            </h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe, est! Aliquam, asperiores optio rerum aliquid, quo impedit saepe sint iure repellendus minima corporis culpa mollitia, consequatur odio fuga necessitatibus dolore.

            </p>
            <a href="#">Learn more</a>
        </div>
        </div>
    </div>
  </div>




<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>

        <div class ="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3><b>Scoial Media App</b></h3>
                    <p> The app connects you to the talented people around the world. Download it from play store</p>
                    <a href ="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3><b>Music App</b></h3>
                    <p> The app connects you to the talented people around the world. Download it from play store</p>
                    <a href ="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3><b>Online Shop App</b></h3>
                    <p> The app connects you to the talented people around the world. Download it from play store</p>
                    <a href ="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>

        </div>
        <a href="#" class ="btn">See more</a>
    </div>
</div>




<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>swapnilkundu01@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>01871978907</p>
                <div class="socal-icons">
                    <a href="https://www.facebook.com/swapnil.kundu.90/"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://www.instagram.com/swapnil2441139/"><i class="fa-brands fa-twitter-square"></i></a>
                    <a href="https://call.whatsapp.com/voice/oAxOkq7IUG3ndQV7ZXiJVs"><i class="fa-brands fa-whatsapp"></i></a>
                    <a href=""><i class="fa-brands fa-linkedin"></i></a>
                    
                </div>
                <a href="images/my-cv.pdf"class = "btn btn2" >Download CV</a>
            </div>
            <div class="contact-right">
                <form>
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type ="email" name="email" placeholder="Your Email" required>
                    <textarea name ="Message" rows="6" placeholder ="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                
            </div>
        </div>
    </div>
    <div class="copyright">
            <p>Copyright © kundu.Made with HTML,CSS and JS</p>
    </div>
</div>


  
</body>
</html>
