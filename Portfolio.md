code link for HTML FILE:
https://codepen.io/diptinayan/pen/pwPQJO.html

<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dipti Nayan</title>
     <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css?family=Maitree|Montserrat|Calligraffitti|Playfair+Display|Sahitya|Source+Sans+Pro|Ubuntu" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="50">
    <nav class="navbar navbar-inverse navbar-fixed-top">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>                        
                </button>
                <a class="navbar-brand lg-position" href="https://github.com/diptinayan" target="_blank"></a>
            </div>
            <div>
                <div class="collapse navbar-collapse tab-right" id="myNavbar">
                    <ul class="nav nav-pills navbar-nav">
                        <li class="pull-right"><a href="#contact">Contact</a></li>
                        <li class="pull-right"><a href="#portfolio">My Work</a></li>
                        <li class="pull-right"><a href="#about">About</a></li>
                        <li class="pull-right"><a href="#home">Home</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
    <!--Home Page-->
    <div id="home">
        <div class="home-page">
            <div class="block text-center">
                <h1 class="style-name">Dipti Nayan</h1>
                <h3 class="style-description">Learner & Reader</h3>
                <div class="btnList text-center">
                    <a class="btn btn-facebook btn-lg" href="https://www.facebook.com/profile.php?id=100009570404925" target="_blank"><i class="fa fa-facebook fa-fw"></i>Facebook</a>
                    <a class="btn btn-twitter btn-lg" href="https://twitter.com/dipti_nayan" target="_blank"><i class="fa fa-twitter fa-fw"></i>Twitter</a>
                    <a class="btn btn-linkedin btn-lg" href="https://www.linkedin.com/in/dipti-nayan-9746b1115/" target="_blank"><i class="fa fa-linkedin fa-fw"></i>LinkedIn</a>
                    <a class="btn btn-github btn-lg" href="https://github.com/diptinayan" target="_blank"><i class="fa fa-github fa-fw"></i>Github</a>
                    <a class="btn btn-freecodecamp btn-lg" href="https://www.freecodecamp.com/diptinayan" target="_blank"><i class="fa fa-free-code-camp fa-fw"></i>FreeCodeCamp</a>
                </div>
            </div>
        </div>
    </div>
    <!--End Of Home Page-->
    <!--About Page-->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center text-style">
                    <h2><strong>About Me</strong></h2>
                    <hr>
                </div>
            </div>
            <div class="row about-style">
                <div class="col-md-12 text-center about-info">
                    <p>I am an Engineering student looking for various opportunities to grow more. When I'm not in my element, in nature, I work on my web developing skills, with a future career in Web design/development a possibility.I also like to work on 
 Android Apps. And I like poetry.</p>
                    <br/>
                    <br/>
                    <p>My main interest at this time lies in frontend development with focus on HTML, CSS, Javascript and jQuery.And in the back-end development I devote myself in craetion of simple Apps. </p>
               </div>
            </div>
        </div>
    </div>
    <!--End Of Home Page-->
    <!--Portfolio Page-->
    <div id="portfolio">
        <div class="container">
            <div class="row">
                <div class="col-md-12 text-center text-style">
                    <h2><strong>My Portfolio</strong></h2>
                    <hr>
                </div>
            </div>
            <div class="row">
                <div class="col-sm-4 portfolio-item">
                  <!--Portfolio 1-->
                    <img src="http://hd.wallpaperswide.com/thumbs/california_road-t1.jpg" class="img-responsive" alt="#">
                </div>
                <div class="col-sm-4 portfolio-item">
                  <!-- Portfolio 2 -->
                    <img src="http://hd.wallpaperswide.com/thumbs/empty_road_3-t1.jpg" class="img-responsive" alt="#">
                </div>
                <div class="col-sm-4 portfolio-item">
                  <!--Portfolio 3 -->
                    <img src="http://hd.wallpaperswide.com/thumbs/android_7-t1.jpg" class="img-responsive" alt="#">
                </div>
                <div class="col-sm-4 portfolio-item">
                <!--Portfolio 4 -->
                    <img src="http://hd.wallpaperswide.com/thumbs/anonymous_mask_3-t1.jpg" class="img-responsive" alt="#">
                </div>
                <div class="col-sm-4 portfolio-item">
                <!--Portfolio 5 -->
                    <img src="http://hd.wallpaperswide.com/thumbs/offline-t1.jpg" class="img-responsive" alt="#">
                </div>
                <div class="col-sm-4 portfolio-item">
                <!--Portfolio 6 -->
                    <img src="http://hd.wallpaperswide.com/thumbs/jiuzhaigou_sichuan_china-t1.jpg" class="img-responsive" alt="#">
                </div>
            </div>
        </div>
    </div>
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center text-style">
                    <h2><strong>Contact Me</strong></h2>
                    <hr>
                </div>
            </div>
            <div class="wrapper">
                <form method="post" class="ccform">
                    <div class="ccfield-prepend">
                        <span class="ccform-addon"><i class="fa fa-user fa-2x"></i></span>
                        <input class="ccformfield" type="text" placeholder="Full Name" required>
                    </div>
                    <div class="ccfield-prepend">
                        <span class="ccform-addon"><i class="fa fa-envelope fa-2x"></i></span>
                        <input class="ccformfield" type="text" placeholder="Email" required>
                    </div>
                    <div class="ccfield-prepend">
                        <span class="ccform-addon"><i class="fa fa-mobile-phone fa-2x"></i></span>
                        <input class="ccformfield" type="text" placeholder="Phone">
                    </div>
                    <div class="ccfield-prepend">
                        <span class="ccform-addon"><i class="fa fa-info fa-2x"></i></span>
                        <input class="ccformfield" type="text" placeholder="Subject" required>
                    </div> 
                     <div class="ccfield-prepend">
                        <span class="ccform-addon"><i class="fa fa-comment fa-2x"></i></span>
                        <textarea class="ccformfield" name="comments" rows="6" placeholder="Message" required></textarea>
                    </div>
                    <div class="ccfield-prepend submit">
                        <input class="ccbtn" type="submit" value="Submit">
                    </div>
                </form>
            </div>
        </div>
    </div>
    <!-- Footer -->
    <div id="footer">
        <div class="container footer-position">
            <div class="row">
                <div class="col-md-12">
                  <span>&copy; coded by: Dipti Nayan</span>
                </div>
            </div>
        </div>
    </div>   
</body>
</html>

code link for CSS:
https://codepen.io/diptinayan/pen/pwPQJO.css

html{
    background: url(http://unsplash.com/photos/wkRHXxsZTvc/download?force=true) no-repeat 50% 50% fixed; 
    background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    -webkit-background-size: cover;
}

body{
    margin: 0 auto;
    font-family: 'Sahitya', cursive, sans-serif;
}

#home{
    height: 500px !important;
}

#portfolio{
    height: 600px !important;
}
#contact{
    height: 680px !important;
}

#about, #portfolio, #contact{
    padding-top: 70px;
}

#home{
    height: 100%;
    width: 100%;   
    position: absolute;
    top: 0px;
    left: 0px;
    display: block;   
}

#about{
    height: 100%;
    width: 100%;
    position: absolute;
    top: 100%;
    left: 0px;
    display: block;    
}

#portfolio{
    height: 100%;
    width: 100%;
    position: absolute;
    top: 200%;
    left: 0px;
    display: block;
}

#contact{
    height: 100%;
    width: 100%;
    position: absolute;
    top: 320%;
    left: 0px;
    display: block;   
}

.navbar{   
    position: fixed;
    top: 0px;
    left: 0px;
    width: 100%;
    height: 60px;
    background-color: dimgray !important;
    z-index: 100;
    display: block;   
}

nav ul{
    padding-top: 7px;
}

nav li{
    float: right;
}

nav li a{ 
    text-decoration: none;
    color: white;
    font-size: 20px;
    font-weight: 700;
    margin-right: 20px;
    color: darkgrey;
    background-color: dimgrey;
    font-family: 'Sahitya', cursive, sans-serif;
}

.lg-position{
    padding-top: 20px !important;
}

.text-style{
    font-family: 'Sahitya', cursive, sans-serif;
    font-weight: 800;
}


.tab-right{
    float: right;
    padding-bottom: 10px;
}

/*Home Page*/

.home-page{
    padding-top: 150px;
    font-family: 'Sahitya', cursive, sans-serif;
    font-weight: 800;

}

.style-name{
    font-size: 90px;
    color: gray;
}

.style-description{
    font-size: 35px;
    padding-bottom: 25px;
    color: darkgrey;
}

hr{
    height: 3px !important;
    background-color:darkgray;
}

.btn{
    color: #fff;
}

.btn{
    color: #fff !important;
}

.btn-facebook, 
.btn-twitter, 
.btn-linkedin, 
.btn-github, 
.btn-freecodecamp {
    font-size: 1.6em;
    background-color: dimgrey;
}

.btnList{
    padding-top: 30px;
}

.btn-facebook:hover{
    background-color: #3B5998;
}

.btn-twitter:hover{
    background-color: #00ACEE;
}

.btn-linkedin:hover{
    background-color: #007BB6;
}

.btn-github:hover{
    background-color: #444444;
}

.btn-freecodecamp:hover{
    background-color: #006400;
}

.block{
    border: 2px thin solid;
}

/*About*/
.about-info{
    font-size: 22px;
    color:#000;
    font-family: 'Sahitya', cursive, sans-serif;
}

.about-style{
    border: thin solid;
    color: darkgrey;
    opacity: 0.7;
    padding-top: 40px;
    padding-bottom: 30px;
    background-color: gainsboro;
    border-radius: 0.5%;
}
     
/*Portfolio*/

.portfolio-item{
    padding-bottom: 20px;
    margin-right: auto;
    margin-left: auto;
    width: auto;
}
 
.portfolio-item:hover{
    transition: 0.5s;
    opacity: 0.5;
}

/*Contact*/
@import url(https://fonts.googleapis.com/css?family=Lato:300,400,700);

/* Form CSS*/
.ccform {
    margin: 0 auto;
    width: 600px;
}

.submit{
    padding-left: 50px;
}
.ccfield-prepend{
	margin-bottom:10px;
	width:100%;
}

.ccform-addon{
	color:000000; 
	float:left;
	padding:8px;
	width:8%;
	text-align:center;
  padding-top: 15px;
}

.ccformfield {
	color:#000000; 
	background-color: beige;
	border:none;
	padding:15.5px;
	width:91.9%;
	display:block;
	font-family: 'Lato',Arial,sans-serif;
	font-size:14px;
}

.ccformfield {
	font-family: 'Lato',Arial,sans-serif;
}
.ccbtn{
	display:block;
	border:none;
	background:grey;
	color:darkgray;
	padding:12px 25px;
	cursor:pointer;
	text-decoration:none;
	font-weight:bold;
}
.ccbtn:hover{
	background-color: darkolivegreen;
}

/*Footer*/

#footer{
    position:fixed;
    height:50px;
    background-color:dimgray;
    bottom:0px;
    left:0px;
    right:0px;
    margin-bottom:0px;
}

.footer-position{
    font-family: 'Sahitya', cursive, sans-serif;
    color: darkgray;
    font-size: 15px;
    margin-top: 15px;
    text-align: center;
}
