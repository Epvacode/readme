<!DOCTYPE html>

 <html lang="en">

	<head>

		<title>Epvacode/welcome</title>
        <meta name="viewport" content="width=device-width">
		<meta name= "keywords" content="wordpress, html, css, javascript, php, python, ruby, nodejs, angularjs, computer science, motivation, laptops, learning programming, web design, logo , article writing, online"/>
		<meta name="description" content="learning web development from scratch, building a website for your business"/>
		<meta name="revised" content="epvacode, 4/12/2018"/>
		<meta http-equiv="refresh" content="#"/>
		<meta name="author" content="Anenye Anthony Chinedu"/>
		<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
		<!-- remember  to add cokies-->
		<link rel="stylesheet" type="text/css" href="style.css" media="all"/>
        <script src="main.js"></script>
		<!--<link rel="stylesheet" type="text/css" href="htmlpage.css" media="all"/>-->
     </head>
     
     <body>
         <header>
             <div class="container">
                 <nav>
                    <ul>
                     <li id="current"><a href="index.html">Home</a></li>
                     <li><a href="About.html">About</a></li>
                     <li><a href="Services.html">Services</a></li>
                    </ul>
                </nav>
                <div id="branding">
                    <h1><a id ="new brand" href="index.html"><span id="e-styling"> EPVACODE </span></a>Web Solutions</h1>
                </div> 
             </div>
                
         </header>
         <section id="showcase">
             <div class="container">
                 <button id="date" type="button" onclick="document.getElementById('demo').innerHTML=Date()">View Date And Time!</button>
                 <p id="demo"></p>
                 <h1>Website Developement Solutions.</h1>
                 <p><b>We not only get your massages across, but with a dedication to visual beauty and cutting edge functionality. </b></p><br><br>
                  <a id="get-work" href="#work">V</a>
                 
             </div>
             
         </section>
         <section id="news-letter">
             <div class="container">
                 <h1>Subscribe To Our News Letter</h1>
                <form>
                     <input type="email" placeholder="Enter Email...">
                     <button class="btn1"  type="submit">Subscribe</button>
                 </form>
             </div>
         </section>
         <section id="boxes">
             <div class="container">
                 <div id="work">
                     <h1>PORTFOLIO</h1>
                 </div>
                 <div class="box">
                     <img src="game.jpg.jpg">
                     <h3>HTML</h3>
                     <p>learn the basic of Html and build your own application</p>
                 </div>
                 <div class="box">
                     <img src="com.jpg">
                     <h3>HTML</h3>
                     <p>learn the basic of Html and build your own application</p>
                 </div>
                 <div class="box">
                     <img src="idea.jpg.jpg">
                     <h3>HTML</h3>
                     <p>learn the basic of Html and build your own application</p>
                 </div>
             </div>
         </section>
         <footer>
             <p id="p-footer">EPVACODE web solution @copyright 2019</p>
             <a href="#"><img src="facebook-icon.png"></a>
             <a href="#"><img src="instagram-icon.png"></a>
         </footer>

     </body>
     
</html>
