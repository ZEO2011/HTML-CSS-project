# HTML-CSS-project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="Css/style.css">
    <title>Ziad Hatem</title>
    <link rel="icon" href="Images/wolf_king_by_muns11_df3ywnh-fullview.jpg">
    <link rel="stylesheet" href="Js/Code.js">
  <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

*{
   font-family: 'Poppins', sans-serif;
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   scroll-behavior: smooth;
}

/* Header */
header{
   background-color: #f0f0f0;
   width: 100%;
   position: fixed;
   z-index: 999;
   display: flex;
   justify-content: space-between;
   align-items: center;
   padding: 10px 200px;
}

/* Logo */
.logo{
   text-decoration: none;
   color: #3a6cf4;
   text-transform: uppercase;
   font-weight: 700;
   font-size: 1.8em;
}

/* navigation bar */
.navigation a{
   color: #3a6cf4;
   text-decoration: none;
   font-size: 1.1em;
   font-weight: 500;
   padding-left: 30px;
}

.navigation a:hover{
   color: #601cfc;
}
/* Main */
section {
   padding: 100px 200px;
}

.main {
   width: 100%;
   min-height: 100vh;
   display: flex;
   align-items: center;
   background: url(/Images/Main_Photo.jpg) no-repeat;
   background-size: cover;
   background-position: center;
   background-attachment: fixed;
}

.main h2 {
   color: #fff;
   font-size: 1.4em;
   font-weight: 500;
}

.main h2 span {
   display: inline-block;
   margin-top: 10px;
   color: #3a6cf4;
   font-size: 3em;
   font-weight: 600;
}

.main h3 {
   color: #fff;
   font-size: 2em;
   font-weight: 700;
   letter-spacing: 1px;
   margin-top: 10px;
   margin-bottom: 30px;
}
/* Main button */
.main-btn {
   color: #fff;
   background-color: #3a6cf4;
   text-decoration: none;
   font-size: 1.1em;
   font-weight: 600;
   display: inline-block;
   padding: 0.9375em 2.1875em;
   letter-spacing: 1px;
   border-radius: 15px;
   margin-bottom: 40px;
   transition: 0.7s ease;
}

.main-btn:hover {
   background-color: #f60a0ad5;
   transform: scale(1.1);
}

.social-icons a {
   color: #fff;
   font-size: 1.7em;
   padding-right: 30px;
}

/* Services */
.title {
   display: flex;
   justify-content: center;
   color: #3a6cf4;
   font-size: 2.2em;
   font-weight: 800;
   margin-bottom: 30px;
}

.content {
   display: flex;
   justify-content: center;
   flex-direction: row;
   flex-wrap: wrap;
}

.card {
   background-color: #fff;
   width: 21.25em;
   box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
   border-radius: 10px;
   padding: 25px;
   margin: 15px;
   transition: 0.7s ease;
}

.card:hover {
   transform: scale(1.1);
}

.card .icon {
   color: #3a6cf4;
   font-size: 8em;
   text-align: center;
}

#edit {
   padding-left: 25px;
}

#video {
   padding-left: 10px;
}

.info {
   text-align: center;
}

.info h3{
   color: #3a6cf4;
   font-size: 1.2em;
   font-weight: 700;
   margin: 10px;
}

/* Projects */
.projects {
   background-color: #000016;
}

.projects .content{
   margin-top: 30px;
}

.project-card {
   background-color: #fff;
   border: 1px solid #fff;
   min-height: 14em;
   width: 23em;
   overflow: hidden;
   border-radius: 10px;
   margin: 20px;
   transition: 0.7s ease;
}

.project-card:hover {
   transform: scale(1.1);
}

.project-card:hover .project-image {
   opacity: 0.9;
}

.project-image img{
   width: 100%
}

.project-info {
   padding: 1em;
}

.project-category {
   font-size: 0.8em;
   color: #000;
}

.project-title {
   display: flex;
   justify-content: space-between;
   text-transform: uppercase;
   font-weight: 800;
   margin-top: 10px;
}

.more-details {
   text-decoration: none;
   color: #3a6cf4;
}

.more-details:hover {
   color: #601cfc;
}

/* Contact */
.contact .icon{
   font-size: 4.5em;
}

.contact .info h3 {
   color: #000;
}

.contact .info p {
   font-size: 1.5em;
}

/* footer */
.footer {
   background-color: #000016;
   color: #fff;
   padding: 2em;
   display: flex;
   justify-content: space-between;
}

.footer-title {
   font-size: 1.3em;
   font-weight: 600;
}

.footer-title a span {
   color: #3a6cf4;
}

.footer-title a{
   text-decoration: none;
}

.footer .social-icons a{
   font-size: 1.3em;
   padding: 0 12px 0 0;
}

/* For phone */
@media (max-width:1023px){
   header{
      padding: 12px 20px;
   }

   .navigation a{
      padding-left: 10px;
   }

   .title{
      font-size: 1.8em;
   }

   section{
      padding: 80px 20px;
   }

   .main-content h2{
      font-size: 1em;
   }

   .main-content h3{
      font-size: 1.6em;
   }

   .content{
      flex-direction: column;
      align-items: center;
   }



}

@media (max-width:641px){
   body{
      font-size: 12px;
   }

   .main-content h2{
      font-size: 0.8em;
   }

   .main-content h3{
      font-size: 1.4em;
   }
}

@media (max-width:300px){
   body{
      font-size: 10px;
   
   }
} 
   </style>
</head>
<body>
    <!-- Header -->
    <header type="submit">
        <a href="#main" class="logo">Ziad</a>
        <nav class="navigation">
            <a type="submit" href="#services">Services</a>
            <a type="submit" href="#projects">Projects</a>
            <a type="submit" href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Main -->
    <section id="main" class="main">
        <div>
            <h2>Hello, I'm Ziad<br><span>Web developer</span></h2>
            <h3>I'am a new programer</h3>
            <a href="#projects" class="main-btn">View my work</a>
            <div class="social-icons">
                <a href="https://github.com/z499" aria-label="github" name="github" class="github"><i class="fab fa-github"></i></a>
                <a href="https://www.facebook.com/profile.php?id=100082514971304" aria-label="facebook" name="facebook" class="facebook"><i class="fab fa-facebook"></i></a>
                <a href="https://twitter.com/ziadhatem2011" aria-label="twitter" name="twitter" class="twitter"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </section>
    <!-- Services -->
    <section class="cards" id="services">
        <h2 class="title">Services</h2>
        <div class="content">
            <div class="card">
                <div id="edit" class="icon">
                    <i class="fas fa-edit"></i>
                </div>
                <div class="info">
                    <h3>This is a test</h3>
                    <p>I builded this card just for learn, so don't read this paragraph</p>
                </div>
            </div>
            <div class="card">
                <div id="video"  class="icon">
                    <i class="fas fa-video"></i>
                </div>
                <div class="info">
                    <h3>This is a test</h3>
                    <p>I builded this card just for learn, so don't read this paragraph</p>
                </div>
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fas fa-graduation-cap"></i>
                </div>
                <div class="info">
                    <h3>This is a test</h3>
                    <p>I builded this card just for learn, so don't read this paragraph</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Projects -->
    <section class="projects" id="projects">
        <h2 class="title">Projects</h2>
        <div class="content">
            <div class="project-card">
                <div class="project-image">
                    <img src="images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">I builded ping pong game in python</p>
                    <strong class="project-title">
                        <span>Python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <img src="images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">Script Writing & Video Production</p>
                    <strong class="project-title">
                        <span>python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <img src="images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">I builded a Space Invaders in Python</p>
                    <strong class="project-title">
                        <span>python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <img src="images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">Script Writing & Video Production</p>
                    <strong class="project-title">
                        <span>python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <img src="images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">Script Writing & Video Production</p>
                    <strong class="project-title">
                        <span>python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <img src="Images/wallpaperflare.com_wallpaper (4).jpg" alt="ziad"/>
                </div>
                <div class="project-info">
                    <p class="project-category">Script Writing & Video Production</p>
                    <strong class="project-title">
                        <span>python</span>
                        <a href="#" class="more-details">More details</a>
                    </strong>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact -->
    <section class="cards contact" id="contact">
        <h2 class="title">Let's work together</h2>
        <div class="content">
            <div class="card">
                <div class="icon">
                    <i class="fas fa-phone"></i>
                </div>
                <div class="info">
                    <h3>Phone</h3>
                    <p>+201117351878</p>
                </div>
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fas fa-envelope"></i>
                </div>
                <div id="email" class="info">
                    <h3>Email</h3>
                    <p>hatemziad50@gmail.com</p>
                </div>
            </div>
        </div>
    </section>
    <!-- footer -->
    <footer class="footer">
        <p class="footer-title">Copyrights @<a href="https://github.com/z499"><span>Ziad hatem</span></a></p>
        <div class="social-icons">
            <a aria-label="github" href="https://github.com/z499" name="github" class="github"><i class="fab fa-github"></i></a>
            <a aria-label="facebook" href="https://www.facebook.com/profile.php?id=100082514971304" name="facebook" class="facebook"><i class="fab fa-facebook"></i></a>
            <a aria-label="twitter" href="https://twitter.com/ziadhatem2011" name="twitter" class="twitter"><i class="fab fa-twitter"></i></a>
        </div>
    </footer>
</body>
</html>
