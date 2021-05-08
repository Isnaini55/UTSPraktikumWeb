# UTSPraktikumWeb

~~~
Nama  : Isnaini Rizkyana
NIM   : 311910254
Kelas : TI.19.C1
~~~

## Langkah-langkah membuat desain mockup :
Mencari mockup/sketsa desain web (dalam format psd, png, jpg, cdr, svg, dan lain-lain)

Contoh Sumber Referensi :
https://freebiesbug.com/psd-freebies/

![Freebug](https://user-images.githubusercontent.com/81541764/117523428-9e67bb00-afe2-11eb-9b4f-93c7d87d89dd.JPG)

atau https://www.graphberry.com/category/themes

![graphberry](https://user-images.githubusercontent.com/81541764/117523482-bf301080-afe2-11eb-9927-cef60deef9af.JPG)

## Memilih desain mockup
Mendownload Mockup/Sketsa desain WEB pada website dibawah ini :
https://www.free-css.com/free-css-templates/page265/fitcento

![SUMBER](https://user-images.githubusercontent.com/81541764/117524805-5a2be900-afe9-11eb-9bfd-76a45fedb8e5.JPG)


## Membuat HTML dan CSS dari desain tersebut

## Membuat Struktur Standar HTML
Struktur ini meliputi tag doctype, html, head, title, dan body seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Mockup Desain WEB</title>
	</head>
	<body>
		
	</body>
</html>
~~~


## Membuat Dokumen HTML

Persiapan membuat dokumen HTML dengan nama file index.html pada aplikasi VSCode

~~~
<!DOCTYPE html>
<html lang="en">
<head>
<!-- basic -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<!-- mobile metas -->
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1">
<!-- site metas -->
    <title>Mockup Desain WEB</title>
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta name="author" content="">	
<!-- bootstrap css -->
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<!-- style css -->
    <link rel="stylesheet" type="text/css" href="css/style.css">
<!-- Responsive-->
    <link rel="stylesheet" href="css/responsive.css">
<!-- fevicon -->
    <link rel="icon" href="images/fevicon.png" type="image/gif" />
<!-- Scrollbar Custom CSS -->
    <link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css">
<!-- Tweaks for older IEs-->
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css">
<!-- owl stylesheets --> 
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/owl.theme.default.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.css" media="screen">

</head>
<body>
	<!--header section start -->
    <div class="header_section">
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-3">
                    <div class="logo"><a href="index.html"><img src="images/logo.png"></a></div>
                </div>
                <div class="col-md-9">
                    <div class="menu_text">
                        <ul>
                            <li><a href="index.html">HOME</a></li>                                                    
                            <li><a href="about.html">ABOUT</a></li>
                            <li><a href="price.html">PACKAGE</a></li>
                            <li><a href="gym.html">TRAINING</a></li>
                            <li><a href="contact.html">CONTACT US</a></li>
                            <li><a href="#"><img src="images/search-icon.png"></a></li>
                            <div id="myNav" class="overlay">
                <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
                <div class="overlay-content">
                  <a href="index.html">HOME</a>
                  <a href="about.html">ABOUT</a>
                  <a href="price.html">PRICE</a>
                  <a href="gym.html">GYM</a>
                  <a href="class.html">CLASS</a>
                  <a href="contact.html">CONTACT US</a>
                  <a href="#">LOGIN</a>
                  <a href="#">REGISTER</a>
                </div>
                </div>
                <span  style="font-size:33px;cursor:pointer; color: #ffffff;" onclick="openNav()"><img src="images/toggle.png" class="toggle_menu"></span>
                </div>  
                </li>
                        </ul>
                    </div>
            </div>
        </div>
    </div>
    <!-- header section end -->
    <!-- banner section start -->
    <div class="banner_section layout_padding">
    	<div id="my_Controls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <div class="container">
    		<div class="banner_taital">
    			<h1 class="find_text">FIND EVERYTHING YOU NEED</h1>
    			<h2 class="crush_text">TO CRUSH YOUR FITNESS GOALS</h2>
    			<p class="long_text">It is a long established fact that a reader will be distracted by the readable content of a
                page when looking at its layout. The point of using Lorem Ipsum is that</p>
    		</div>
    		<div class="contact">
    			<div class="contact_bt"><a href="#">Contact Us</a></div>
    		</div>
    	</div>
    </div>
    <div class="carousel-item">
      <div class="container">
    		<div class="banner_taital">
    			<h1 class="find_text">FIND EVERYTHING YOU NEED</h1>
    			<h2 class="crush_text">TO CRUSH YOUR FITNESS GOALS</h2>
    			<p class="long_text">It is a long established fact that a reader will be distracted by the readable content of a
                page when looking at its layout. The point of using Lorem Ipsum is that</p>
    		</div>
    		<div class="contact">
    			<div class="contact_bt"><a href="#">Contact Us</a></div>
    		</div>
    	</div>
    </div>
    <div class="carousel-item">
      <div class="container">
    		<div class="banner_taital">
    			<h1 class="find_text">FIND EVERYTHING YOU NEED</h1>
    			<h2 class="crush_text">TO CRUSH YOUR FITNESS GOALS</h2>
    			<p class="long_text">It is a long established fact that a reader will be distracted by the readable content of a
                page when looking at its layout. The point of using Lorem Ipsum is that</p>
    		</div>
    		<div class="contact">
    			<div class="contact_bt"><a href="#">Contact Us</a></div>
    		</div>
    	</div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#my_Controls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#my_Controls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
    	
    </div>
    <!-- banner section end -->
    <!-- about section start -->
    <div class="about_section_2 layout_padding">
        <div class="container">
            <h1 class="about_text_2"><strong>ABOUT US</strong></h1>
            <p class="client_long_text">It is a long established fact that a reader will be distracted by the readable</p>
        </div>
    </div>
    <div class="about_section">
    	<div class="row">
    		<div class="col-md-6">
    			<div class="about_taital">
    				<h1 class="about_text">ABOUT OUR GYM</h1>
    				<p class="long_text_2">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and webIt is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web</p>
    				<div class="about_bt"><a href="#">ABOUT MORE</a></div>
    			</div>
    		</div>
    		<div class="col-md-6">
    			<div class="about_img"><img src="images/about-bg.png"></div>
    		</div>
    	</div>
    </div>
    <!-- about section end -->
    <!-- our service section start -->
    <div class="our_section layout_padding">
    	<div class="container">
    		<h1 class="our_text"><strong>OUR CLASSES</strong></h1>
    		<p class="client_long_text">It is a long established fact that a reader will be distracted by the readable</p>
    		<div class="row padding_top_0">
    			<div class="col-lg-4">
    				<div class="image_7"><a href="#"><img src="images/img-1.png"></a></div>
    				<h2 class="design_text">WEIGHTLIFTING</h2>
    				<p class="fact_text">It is a long established fact that a reader will be distracted by the readable</p>
    			</div>
    		    <div class="col-lg-4">
    		    	<div class="image_7"><a href="#"><img src="images/img-2.png"></a></div>
    				<h2 class="design_text">INDOOR CYCLING</h2>
    				<p class="fact_text">It is a long established fact that a reader will be distracted by the readable</p>
    		    </div>
    		    <div class="col-lg-4">
    		    	<div class="image_7"><a href="#"><img src="images/img-3.png"></a></div>
    				<h2 class="design_text">CORE POWER</h2>
    				<p class="fact_text">It is a long established fact that a reader will be distracted by the readable</p>
    		    </div>
    		    <div class="bt_main">
    		    	<div class="seemore_bt"><a href="#">See More</a></div>
    		    </div>
    		</div>
    		
    	</div>
    </div>
    <!-- our service section end -->
    <!-- project section start -->
    <div class="project_section layout_padding">
    	<div class="container">
    		<h1 class="partner_text">PARTNER<br> UP-DOUBLE POWER</h1>
    		<p class="lorem_ipsum_text">t is a long established fact that a reader will be distracted by the readable content 
                                        of a page when looking at its layout. The point of using Lorem Ipsum is tha</p>
            <div class="choice_main">
            	<div class="choose_bt"><a href="#">CHOOSE YOUR TRAINER</a></div>
            </div>            
    	</div>
    </div>
    <!-- project section end -->   
    <!-- our price section start -->   
    <div class="our_price_section layout_padding">
    	<div class="container">
    		<h1 class="our_price"><strong>OUR PRICE</strong></h1>
    		<p class="client_long_text">t is a long established fact that a reader will be distracted by the readable content 
            of a page when looking at its layout. The point of using Lorem Ipsum is tha</p>
            <div class="price_section_2">
            	<div class="row">
            		<div class="col-sm-12 col-lg-4">
            			<div class="beginner">
            				<h2 class="beginner_text">BEGINNER PLAN</h2>
            				<h1 class="plan_text">$40</h1>
            				<P class="access_text">Unlimited access to the gym</P>
            				<P class="access_text">3 classes per week</P>
            				<P class="access_text">One Year memberships</P>
            				<P class="access_text">FREE drinking package</P>
            				<P class="free_text">1 Free personal training</P>
            			</div>
            			<div class="select_boton">
            			    <div class="select_bt"><a href="#">SELECT PLAN</a></div>
            			</div>
            		</div>
            		<div class="col-sm-12 col-lg-4">
            			<div class="premium">
            				<h2 class="beginner_text">PREMIUM PLAN</h2>
            				<h1 class="plan_text">$40</h1>
            				<P class="access_text">access to the gym</P>
            				<P class="access_text">3 classes per week</P>
            				<P class="access_text">One Year memberships</P>
            				<P class="access_text">FREE drinking package</P>
            				<P class="free_text">1 Free personal training</P>
            			</div>
            			<div class="select_boton">
            			    <div class="premium_bt"><a href="#">SELECT PLAN</a></div>
            			</div>
            		</div>
            		<div class="col-sm-12 col-lg-4">
            			<div class="beginner">
            				<h2 class="beginner_text">ULTIMATE PLAN</h2>
            				<h1 class="plan_text">$40</h1>
            				<P class="access_text">Unlimited access to the gym</P>
            				<P class="access_text">3 classes per week</P>
            				<P class="access_text">One Year memberships</P>
            				<P class="access_text">FREE drinking package</P>
            				<P class="free_text">1 Free personal training</P>
            			</div>
            			<div class="select_boton">
            			    <div class="select_bt"><a href="#">SELECT PLAN</a></div>
            			</div>
            		</div>
            	</div>
            </div>
    	</div>
    </div> 
    <!-- our price section end -->   

    <!-- contact section start -->
    <div class="about_section_2 layout_padding">
        <div class="container">
            <h1 class="contact_text_2"><strong>CONTACT US</strong></h1>
            <p class="client_long_text">It is a long established fact that a reader will be distracted by the readable</p>
        </div>
    </div>
    <div class="contact_section">
    	<div class="row">
    		<div class="col-md-6 background_bg">
    			<div class="contact_bg">
    				<div class="input_main">
                       <div class="container">
                       	<h2 class="request_text">REQUEST A CALL BACK</h2>
                          <form action="/action_page.php">
                            <div class="form-group">
                              <input type="text" class="email-bt" placeholder="Your Name" name="Name">
                            </div>
                            <div class="form-group">
                              <input type="text" class="email-bt" placeholder="Email" name="Email">
                            </div>
                            <div class="form-group">
                              <input type="text" class="email-bt" placeholder="Phone" name="Email">
                            </div>
                            <form action="/action_page.php">
                                <div class="form-group">
                                  <textarea class="massage-bt" placeholder="Massage" rows="5" id="comment" name="text"></textarea>
                                </div>
                            </form>
                          </form>
                       </div> 
                    </div>
                    <div class="send_bt"><a href="#">SEND</a></div>
    			</div>
    		</div>
    		<div class="col-md-6">
                <div class="map-responsive">
                    <iframe src="https://www.google.com/maps/embed/v1/place?key=AIzaSyA0s1a7phLN0iaD6-UE7m4qP-z21pH0eSc&q=Eiffel+Tower+Paris+France" width="600" height="560" frameborder="0" style="border:0; width: 100%;" allowfullscreen></iframe>
                </div>
    	    </div>
    	</div>
    </div>
    <!-- contact section end -->
    <!-- footer section start -->
    <div class="footer_section layout_padding">
        <div class="footer_section_2">
    	    <div class="container">
    		    <div class="row map_addres">
    		    	<div class="col-sm-12 col-lg-4">
    		    		<div class="map_text"><img src="images/map-icon.png"><span class="map_icon">No.123 Chalingt Gates, Supper market New York</span></div>
    		    	</div>
                    <div class="col-sm-12 col-lg-4">
                    	<div class="map_text"><img src="images/phone-icon.png"><span class="map_icon">( +71 7986543234 )</span></div>
                    </div>
    		    	<div class="col-sm-12 col-lg-4">
    		    		<div class="map_text"><img src="images/email-icon.png"><span class="map_icon">demo@gmail.com</span></div>
    		    	</div>
    		    </div>
    		    <div class="social_icon">
    		    	<ul>
    		    		<li><a href="#"><img src="images/fb-icon.png"></a></li>
    		    		<li><a href="#"><img src="images/twitter-icon.png"></a></li>
    		    		<li><a href="#"><img src="images/in-icon.png"></a></li>
    		    		<li><a href="#"><img src="images/instagram-icon.png"></a></li>
    		    	</ul>
    		    </div>
    		    <p class="copyright_text">Copyright 2019 All Right Reserved By.<a href="https://html.design"> Free  html Templates</p>
    	    </div>
        </div>
    </div>
    <!-- footer section end -->






    <!-- Javascript files-->
    <script src="js/jquery.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.bundle.min.js"></script>
      <script src="js/jquery-3.0.0.min.js"></script>
      <script src="js/plugin.js"></script>
      <!-- sidebar -->
      <script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
      <script src="js/custom.js"></script>
      <!-- javascript --> 
      <script src="js/owl.carousel.js"></script>
      <script src="https:cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.js"></script>
      <script>
      $(document).ready(function(){
      $(".fancybox").fancybox({
         openEffect: "none",
         closeEffect: "none"
         });
         
         $(".zoom").hover(function(){
         
         $(this).addClass('transition');
         }, function(){
         
         $(this).removeClass('transition');
         });
         });
         </script> 


   <script>
    function openNav() {
    document.getElementById("myNav").style.width = "100%";
    }

    function closeNav() {
   document.getElementById("myNav").style.width = "0%";
   }
</script>



     
</body>
</html>
~~~

## Membuat dokumen CSS

Persiapan membuat dokumen CSS dengan nama file style.css pada aplikasi VSCode
~~~
/*--------------------------------------------------------------------- File Name: style.css ---------------------------------------------------------------------*/


/*--------------------------------------------------------------------- import Fonts ---------------------------------------------------------------------*/

@import url('https://fonts.googleapis.com/css?family=Rajdhani:300,400,500,600,700');
@import url('https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');

/*****---------------------------------------- 1) font-family: 'Rajdhani', sans-serif;
 2) font-family: 'Poppins', sans-serif;
 ----------------------------------------*****/


/*--------------------------------------------------------------------- import Files ---------------------------------------------------------------------*/

@import url(animate.min.css);
@import url(normalize.css);
@import url(meanmenu.css);
@import url(owl.carousel.min.css);
@import url(slick.css);
@import url(jquery-ui.css);
@import url(nice-select.css);

/*--------------------------------------------------------------------- skeleton ---------------------------------------------------------------------*/

* {
     box-sizing: border-box !important;
     transition: ease all 0.5s;
}

html {
     scroll-behavior: smooth;
     overflow-x: hidden !important;
}

body {
     color: #666666;
     font-size: 14px;
     font-family: Raleway;
     line-height: 1.80857;
     font-weight: normal;
     overflow-x: hidden !important;
}

a {
     color: #1f1f1f;
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

h1,
h2,
h3,
h4,
h5,
h6 {
     letter-spacing: 0;
     font-weight: normal;
     position: relative;
     padding: 0 0 10px 0;
     font-weight: normal;
     line-height: normal;
     color: #111111;
     margin: 0
}

h1 {
     font-size: 24px
}

h2 {
     font-size: 22px
}

h3 {
     font-size: 18px
}

h4 {
     font-size: 16px
}

h5 {
     font-size: 14px
}

h6 {
     font-size: 13px
}

*,
*::after,
*::before {
     -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
     box-sizing: border-box;
}

h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
     color: #212121;
     text-decoration: none!important;
     opacity: 1
}

button:focus {
     outline: none;
}

ul,
li,
ol {
     margin: 0px;
     padding: 0px;
     list-style: none;
}

p {
     margin: 20px;
     font-weight: 300;
     font-size: 15px;
     line-height: 24px;
}

a {
     color: #222222;
     text-decoration: none;
     outline: none !important;
}

a,
.btn {
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

img {
     max-width: 100%;
     height: auto;
}

 :focus {
     outline: 0;
}

.paddind_bottom_0 {
     padding-bottom: 0 !important;
}

.btn-custom {
     margin-top: 20px;
     background-color: transparent !important;
     border: 2px solid #ddd;
     padding: 12px 40px;
     font-size: 16px;
}

.lead {
     font-size: 18px;
     line-height: 30px;
     color: #767676;
     margin: 0;
     padding: 0;
}

.form-control:focus {
     border-color: #ffffff !important;
     box-shadow: 0 0 0 .2rem rgba(255, 255, 255, .25);
}

.navbar-form input {
     border: none !important;
}

.badge {
     font-weight: 500;
}

blockquote {
     margin: 20px 0 20px;
     padding: 30px;
}

button {
     border: 0;
     margin: 0;
     padding: 0;
     cursor: pointer;
}

.full {
     float: left;
     width: 100%;
}

.layout_padding {
     padding-top: 90px;
     padding-bottom: 0px;
}


.header_section {
    width: 100%;
    float: left;
    background-color: #03164c;
    height: auto;
    padding-top: 27px;
    padding-bottom: 5px;
}

.logo{ 
	width: 100%;
	float: left;
    text-align: center;
}

.menu_text {
    width: 100%;
    float: left;
}

.menu_text ul {
	margin: 0px;
	padding: 0px;
}

.menu_text li {
    float: left;
    padding-right: 90px;
    font-size: 18px;
    color: #ffffff;
}

.menu_text li a {
    color: #ffffff;
}

.menu_text li a:hover{
    color: #ffffff;
}

.overlay {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0, 0.9);
    overflow-x: hidden;
    transition: 0.5s;
}

.overlay .closebtn {
    position: absolute;
    top: 20px;
    right: 45px;
    font-size: 60px;
}
.overlay a {
    padding: 0px;
    text-decoration: none;
    font-size: 22px;
    color: #f1f1f1;
    display: block;
    transition: 0.3s;
}

.overlay-content {
    position: relative;
    top: 25%;
    width: 100%;
    text-align: center;
    margin-top: 30px;
}

.toggle_menu {
    top: -15px;
    position: relative;
    left: 85px;
}

.banner_section {
    width: 100%;
    float: left;
    background-image: url(../images/banner-bg.png);
    height: auto;
    background-size: contain;
    padding: 200px 0px 90px 0px;
    background-repeat: no-repeat;
    background-size: 100%;
}

.banner_taital {
    width: 100%;
    float: left;
    background-color: #626975;
    border-radius: 20px;
    padding: 20px 20px;
}

.find_text{
	width: 100%;
	float: left;
	font-weight: bold;
	font-size: 60px;
	color: #fffcf4;
	text-align: center;
}

.crush_text{
	width: 100%;
	float: left;
	font-weight: bold;
	font-size: 46px;
	color: #03164c;
	padding: 10px 30px;
	text-align: center;
}

.long_text{
	width: 100%;
	float: left;
	font-size: 20px;
	color: #060606;
	text-align: center;
}

.contact {
    width: 100%;
    float: left;
    margin-top: 50px;
}

.contact_bt {
    width: 20%;
    margin: 0 auto;
    background-color: #03164c;
    padding: 10px 0px;
    color: #fffcf4;
    text-align: center;
    border-radius: 10px;
    font-size: 20px;
}

.contact_bt a{ color: #fffcf4; }
.contact_bt a:hover{ color: #fffcf4; }


.carousel-control-prev-icon { background-image: url(../images/right-arrow.png); }

#my_Controls a.carousel-control-prev {
    position: absolute;
    left: 11%;
    top: 390px;
    background-color: #fff;
    color: #000;
}

#my_Controls a.carousel-control-next {
    position: absolute;
    left: 5%;
    top: 390px;
    background-color: #03164c;
}

.carousel-control-next-icon {
    background-image: url(../images/left-arrow.png);
}

#my_Controls .carousel-control-prev, #my_Controls .carousel-control-next {
    width: 65px;
    height: 65px;
    background: #fff;
    opacity: 1;
    font-size: 30px;
    color: #091e30;
    border-radius: 100%;
}

#my_Controls .carousel-control-prev, #my_Controls .carousel-control-next {
    width: 65px;
    height: 65px;
    background: #fff;
    opacity: 1;
    font-size: 30px;
    color: #091e30;
    border-radius: 100%;
}





.about_section {
    width: 100%;
    float: left;
    background-color: #000;
    margin-top: 70px;
}

.about_taital {
    width: 80%;
    float: right;
    margin-top: 120px;
}

.about_text {
    width: 100%;
    float: left;
    font-size: 40px;
    color: #ffffff;
    font-weight: bold;
}

.about_section_2{
    width: 100%;
    float: left;
}



.about_text_2 {
    width: 19%;
    margin: 0 auto;
    text-align: center;
    font-size: 40px;
    color: #0b0e13;
    border-bottom: 1px solid #49bcfe;
    text-align: center;
}

.contact_text_2 {
    width: 24%;
    margin: 0 auto;
    text-align: center;
    font-size: 40px;
    color: #0b0e13;
    border-bottom: 1px solid #49bcfe;
    text-align: center;
}

.long_text {
    width: 100%;
    float: left;
    font-size: 16px;
    color: #ffffff;
    margin-left: 0px;
}

.long_text_2 {
    width: 100%;
    float: left;
    font-size: 20px;
    color: #ffffff;
    margin-left: 0px;
    padding-top: 30px;
}

.about_bt {
    width: 34%;
    float: left;
    font-size: 19px;
    color: #ffffff;
    border-radius: 5px;
    background-color: #fe6703;
    height: 50px;
    font-weight: bold;
    text-align: center;
    padding-top: 9px;
    margin-top: 40px;
}

.about_bt a {
    color: #ffffff;
}

.about_bt a:hover{ color: #000; }

.about_img {
    width: 100%;
    float: left;
}

.about_main{ width: 100%; float: left; margin-bottom: 80px; }

.our_section {
    width: 100%;
    float: left;
    background-color: #ffffff;
    height: auto;
}

.our_text {
    width: 26%;
    margin: 0 auto;
    text-align: center;
    font-size: 40px;
    color: #0b0e13;
    border-bottom: 1px solid #49bcfe;
    text-align: center;
}

.our_text :after { position: relative; background-color: 4px solid #000; }

.client_long_text {
    width: 90%;
    margin: 0 auto;
    text-align: center;
    font-size: 17px;
    color: #040403;
    text-align: center;
    padding-top: 40px;
}

.padding_top_0 {
    padding-top: 50px;
}

.image_7 {
    width: 100%;
    float: left;
    text-align: center;
}

.design_text {
    width: 100%;
    float: left;
    font-size: 20px;
    color: #090a0b;
    margin-left: 0px;
    text-align: center;
    font-weight: bold;
    margin-top: 20px;
}

.fact_text {
    width: 100%;
    float: left;
    font-size: 18px;
    color: #090a0b;
    margin-left: 0px;
    text-align: center;
}

.bt_main {
    width: 30%;
    margin: 0 auto;
    text-align: center;
}

.seemore_bt {
    width: 50%;
    font-size: 20px;
    color: #fffcf4;
    border-radius: 5px;
    background-color: #041d2c;
    height: 50px;
    margin-top: 40px;
    padding-top: 7px;
    text-align: center;
    display: inline-block;
}

.seemore_bt a {
    color: #ffffff;
}

.seemore_bt a:hover {
    color: #fffcf4;
    background-color: #fe6703;
    padding: 13px 41px;
    border-radius: 4px;
}

.project_section {
    width: 100%;
    float: left;
    background-image: url(../images/img-4.png);
    height: auto;
    background-size: 100%;
    margin-top: 70px;
    padding-bottom: 80px;
    background-repeat: no-repeat;
}

.partner_text {
    width: 100%;
    float: left;
    font-size: 70px;
    color: #fffcf4;
    font-weight: bold;
}

.lorem_ipsum_text {
    width: 61%;
    float: left;
    color: #fffcf4;
    font-size: 18px;
    margin-left: 0;
}

.choice_main {
    width: 100%;
    float: left;
}

.choose_bt {
    width: 18%;
    float: left;
    background-color: #fe6703;
    color: #fffcf4;
    height: 50px;
    font-size: 14px;
    border-radius: 10px;
    text-align: center;
    padding-top: 14px;
}

.choose_bt a {
    color: #ffffff;
}
.choose_bt a:hover{ 
	color: #000; 
}

.our_price_section{
	width: 100%;
	float: left;
}

.our_price{
    width: 20%;
    margin: 0 auto;
    text-align: center;
    font-size: 40px;
    color: #0b0e13;
    border-bottom: 1px solid #49bcfe;
    text-align: center;
}

.price_section_2{
	width: 100%;
	float: left;
	margin-top: 50px;
}

.beginner {
    width: 100%;
    float: left;
    background-color: #022431;
    border-radius: 15px;
    height: auto;
    padding: 40px 30px;
}

.free_text {
    width: 100%;
    float: left;
    text-align: center;
    font-size: 16px;
    color: #fe6703;
    margin-left: 0px;
    margin-top: 0px;
    margin-bottom: 0;
}

.access_text{
	width: 100%;
	float: left;
	text-align: center;
	font-size: 16px;
	color: #fffcf4;
	margin-left: 0px;
	margin-top: 0px;
}

.beginner_text{
	width: 100%;
	float: left;
	color: #fffcf4;
	text-align: center;
	font-size: 18px;
	font-weight: bold;
}

.plan_text{
	width: 100%;
	float: left;
	text-align: center;
	font-size: 40px;
	color: #fffcf4;
	margin-left: 0px;
	margin-top: 0px;
}

.select_boton{
	width: 100%;
	float: left;
	margin-top: 30px;
}

.select_bt {
    width: 50%;
    margin: 0 auto;
    text-align: center;
    font-size: 18px;
    color: #fffcf4;
    background-color: #03164c;
    padding: 10px 0px;
    border-radius: 10px;
}

.select_bt a {
    color: #fffcf4;
}
.select_bt a:hover {
    color: #fffcf4;
    background-color: #fe6703;
    padding: 16px 28px;
    border-radius: 7px;
}

.premium{
    width: 100%;
    float: left;
    background-color: #03164c;
    border-radius: 15px;
    height: auto;
    padding: 40px 30px;
}

.premium_bt{
    width: 50%;
    margin: 0 auto;
    text-align: center;
    font-size: 18px;
    color: #fffcf4;
    background-color: #fe6703;
    padding: 10px 0px;
    border-radius: 10px;
}

.premium_bt a {
    color: #fffcf4;
}
.premium_bt a:hover{ 
	color: #000; 
}

.contact_section {
    width: 100%;
    float: left;
    margin-top: 90px;
}


.background_bg{
	width: 100%;
	float: left;
    height: auto;
    background-image: url(../images/contact-bg.png);
    background-size: 100%;
}

.contact_bg {
    width: 82%;
    float: right;
    padding-top: 80px;
    padding-bottom: 40px;
}

.request_text {
    width: 100%;
    float: left;
    font-size: 30px;
    color: #fffcf4;
    border-bottom: 0px solid#49bcfe;
    padding-top: 20PX;
}

.email-bt {
    background: transparent;
    border-bottom: 1px solid #fffcf4;
    border-top: 0px;
    border-left: 0px;
    border-right: 0px;
    color: #fffcf4 !important;
    width: 100%;
    height: 30px;
    font-size: 20px;
    padding: 20px 20px 20px 0px;
    margin-bottom: 10px;
}

.massage-bt {
    background: transparent;
    border-bottom: 1px solid #fffcf4;
    border-top: 0px;
    border-left: 0px;
    border-right: 0px;
    color: #fffcf4 !important;
    width: 100%;
    height: 85px;
    font-size: 20px;
    padding: 20px 20px 20px 0px;
}

.send_bt {
    width: 30%;
    float: left;
    background-color: #041d2c;
    color: #fffdf6;
    text-align: center;
    padding: 12px 0px;
    font-size: 18px;
    border-radius: 10px;
    margin-left: 10px;
}

.send_bt a {
    color: #fffdf6;
}

.send_bt a:hover {
    color: #fffdf6;
}

.footer_section {
    width: 100%;
    float: left;
    background-color: #041445;
    height: auto;
}

.newsletter_text {
    width: 100%;
    float: left;
    font-size: 20px;
    color: #ffffff;
    padding-left: 175px;
}

.mb-3, .my-3 {
    margin-bottom: 1rem!important;
    width: 65%;
    margin: 0 auto;
}

.input-group>.custom-select:not(:last-child), .input-group>.form-control:not(:last-child) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    height: 50px;
}

.input-group>.input-group-append>.btn, .input-group>.input-group-append>.input-group-text, .input-group>.input-group-prepend:first-child>.btn:not(:first-child), .input-group>.input-group-prepend:first-child>.input-group-text:not(:first-child), .input-group>.input-group-prepend:not(:first-child)>.btn, .input-group>.input-group-prepend:not(:first-child)>.input-group-text {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    background-color: #e05306;
    color: #fff;
    border: 0px;
}

.addres_text {
    width: 10%;
    margin: 0 auto;
    text-align: center;
    font-size: 20px;
    color: #fcf8f9;
    border-bottom: 1px solid #ffffff;
    padding-top: 25px;
}

.map_addres {
    width: 100%;
    float: left;
    padding-top: 50px;
    padding-bottom: 50px;
}

.map_text {
    width: 100%;
    float: left;
    font-size: 16px;
    color: #fffcf4;
    display: flex;
}

.map_icon {
    padding-left: 10px;
    padding-top: 10px;
}

.social_icon {
    width: 15%;
    margin: 0 auto;
    text-align: center;
}

.social_icon ul {
    margin: 0px;
    padding: 0px;
}

.social_icon li {
    float: left;
    padding-left: 10px;
}

.copyright_text {
    width: 100%;
    float: left;
    font-size: 14pt;
    color: #fffcf4;
    text-align: center;
    font-weight: 100;
    padding-top: 40px;
    margin-left: 0px;
}

.copyright_text a { color: #fffcf4; }
.copyright_text a:hover { color: #fe6703; }
~~~

