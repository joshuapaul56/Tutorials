TUTORIALS

<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Joshua Potfolio</title>
 </head>
 <body>
   <header>
      
      <nav>
         <a href="#about-section"> About</a>
         <a href="#portfolio-section"> Work</a>
         <a href="#contact-section"> Contact</a>
          </nav>
      <h1>Joshua Paul</h1>
   </header>
   <main>

<section class="about-section" id="about-section">
<div class="about-content">
   <h2>About Me </h2>
   <p>Joshua Paul Asogba is a multidisciplinary artist with a defined aesthetic,
       creating a cinematic experience through film, 
       design and photography. 
       Joshua is also an aspiring 
       Art director and Creative director 
       working with a band currently called The Roommates and also building  his own creative house JPSTUDIOS. Joshua is currently enrolled in San Jose State University majoring in Creative Arts and is learning about web design currently.  
</p>
</div>
</section>

<section class="portfolio-section" id="portfolio-section">
   <div class="portfolio-content"> 
   <h2>My Work</h2>
   </div> 
   <div class="portfolio-item">
   <img src="imagesporfolio/IMG_0351-2-2.jpg" alt="Portfolio Item 1">
   <h3>The Roommates Practice </h3>
   <p>Emmanuel</p>
   </div>
</section>
<section class="contact-section" id="contact-section">
   <div class="contact-content">
   <h2>Contact Me</h2>
   <p>Email:joshuapaulasogba@gmail.com </p>
   </div>
</section>
   </main>
   <footer>
<p> &copy; 2026 Joshua Paul Asogba </p>
   </footer>
 </body>
 </html>



/* CSS reset */

*{
    margin: 0px;
    padding: 0px;
}
/* respect user font size preferences */
html{
    font-size: 100%;
}

/*General CSS*/

body{

    background-color: blue;
    font-family: sans-serif;
    color: white;
    font-size: 1rem;
    line-height:1rem;
}



header  {
    padding: 6rem;
    margin-bottom: 3rem;
    background-color: red;
    border-bottom: white 3px solid;
    text-align: center;
}

header h1{
    font-size: 3rem;
}
nav{
    position: absolute;
    right:2rem;
    top: 2rem;
   
}
nav a{
    text-decoration: none;
    color:white;
display:inline-block;
margin: 0 1rem;
   
}


.about-section, .portfolio-section, .contact-section {
    margin-bottom: 5rem;
    padding: 2rem;
    border-radius: 1rem;
    box-shadow: 0 4px 8px white
}
.about-content, .portfolio-content, .contact-content {
    max-width: 60rem;
   margin:2rem auto;
   padding: 1rem;
 }
 
.portfolio-item{
    margin-bottom: 5rem;
 background-color:pink; 
 padding:2rem;
 text-align: center;
 border-radius: 2rem;
 box-shadow: 10px 10px 10px black;
}
.portfolio-item img{
    max-width:100%;
    margin:0 auto;
    display:block; 
    border-radius: 1rem;
    
}
.portfolio-item h3{
    margin-top: 1rem 0;
}  
.portfolio-item p{
    margin-top: 1.2rem 0;
}

.about-section{
    background-color: green;
}

.portfolio-section{ 
    background-color: blue;
}

footer{
    background-color: red;
    padding: .2rem;
    text-align: center;
}
footer p{
    font-size: 1rem;
}
