<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.0-11/css/all.min.css">
    <link href="https://fonts.googleapis.com/css?family=Nunito&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>

    <title>About</title>

    <style>
        /* Style for Navbar Starts */
        
        .navbar-custom li a {
            color: #000;
        }
        
        .btn-success {
            background-color: #2DCE89;
            color: #fff;
            border: thin solid #2dce89;
        }
        
        .btn-success:hover {
            background-color: #2DCE89;
            color: #fff;
            border: thin solid #2dce89;
        }
        
        .custom-toggler .navbar-toggler-icon {
            background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0,0,0, 0.7)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
        }
        
        .custom-toggler.navbar-toggler {
            border-color: #000;
        }
        /* Style for Navbar Ends */
        /* Style for Footer Starts */
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Nunito', sans-serif;
        }
        
        a {
            text-decoration: none;
        }
        
        .deep {
            background: #3A0842;
            color: #fff;
        }
        
        .deep #slink {
            background: #44CF6C;
            border-radius: 10px;
            color: white;
            padding: 10px 70px;
        }
        
        .deep li a {
            text-decoration: none;
            color: #fff;
            font-size: 16px;
            line-height: 30px;
        }
        
        .deep li {
            list-style: none;
        }
        
        .deep li a:hover {
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: none;
        }
        
        .icons i {
            font-size: 26px;
            height: 50px;
            width: 50px;
            padding: 10px 20px;
            color: white;
        }
        
        .icons i.fa.fa-twitter:hover {
            color: #00aced;
        }
        
        .icons i.fa.fa-facebook:hover {
            color: #3b5598;
        }
        
        .icons i.fa.fa-instagram:hover {
            color: #ed3833;
        }
        /* Style for Footer Ends */
        /* Body Style */
        
                .banner {
            background-image: url('https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570915217/startng/Rectangle_7_ak5zc2.png');
            background-position: center center;
            background-repeat: no-repeat;
            background-size: cover;
        }
        
        .loren-ipsum {
            background-image: url('https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570916337/startng/Rectangle_10_pwiqsf.png');
            background-position: center center;
            background-repeat: no-repeat;
            background-size: cover;
            text-align: center;
        }
        .loren-ipsum .buttonC {
            width: 100%;
            margin: 0 auto;
        }
        .loren-ipsum .btn {
            background-color: #44CF6C;
            margin-right: 20px;
            width: auto;
        }
        
        .priviledge {
            background-color: #FCFCFC;
        }
        
        .started {
            background-color: #FCFCFC;
        }
        
        .global-reach {
            background-image: url('https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570920182/startng/Rectangle_57_xdcvbs.png');
            background-position: center center;
            background-repeat: no-repeat;
            background-size: cover;
            color: #3A0842;
        }
        .rHeader {
            color: #3A0842;
            font-weight: bold;
            font-size: 1.6em;
        }
        .rText {
            font-family: 'Open Sans', sans-serif;
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 176.4%;
            letter-spacing: 0.655606px;
        }
        .strong {
            font-weight: bold;
            color: #000;
        }
        /* Body Style Ends */
   
        /*carousel styling starts here*/
        .carousel {
            margin: 50px auto;
        }
        .carousel-inner .item {
            shape-image-threshold: 30%;
            border-radius:50%; 
        }
        .carousel-caption {
            font-size:14px;
            font-weight: normal;
            margin-bottom: 1px;
            top-padding: 10px;
            color: #3A0842;
            font-family:'Open Sans', sans-serif;
        }
        }
        .carousel .left, .carousel .right {
            background: transparent;
            color: black;
            margin-left: -20px;
        }
            @media screen and (min-width: 800px){
                .carousel {
                    width: 600px;
                    margin: 10px auto;
                }
                .carousel .left{
                    margin-left: -100px;
                    background: transparent;
                    color: black;
                }
                .carousel .right {
                    margin-right: -100px;
                    background: transparent;
                    color: black;
                }
            }
            @media screen and (min-width: 1000px){
                .carousel .left {
                    margin-left: -200px;
                }
                .carousel .right {
                    margin-right: -200px;
                }
            }
        /*carousel styling ends here*/
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-custom bg-custom">
        <div class="container">
            <a href="index.html" class="navbar-brand"><img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570873250/startng/Logo_1_ib5bjh.png" class="img-fluid" alt="logo" width="150px"></a>
            <button class="navbar-toggler float-right custom-toggler" type="button" data-toggle="collapse" data-target="#navbar9" style="color: #000;">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="navbar-collapse collapse" id="navbar9">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item mr-5">
                        <a class="nav-link" href="about.html">About Us</a>
                    </li>
                    <li class="nav-item mr-5">
                        <a class="nav-link" href="courses.html">Courses</a>
                    </li>
                    <li class="nav-item mr-5">
                        <a class="nav-link" href="hireGrad.html">Hire A Grad</a>
                    </li>
                    <li class="nav-item mr-5">
                        <a class="nav-link" href="contactus.html">Contact Us</a>
                    </li>
                    <li class="nav-item mr-5">
                        <a class="btn btn-success nav-link px-5" href="register.html" style="color: #fff;">Start
                            Learning</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container-fluid banner pt-5 pb-5">
        <div class="col-md-6 offset-md-3 text-center pt-5 pb-5 mb-5">
            <p class="pb-5 mb-5" style="color: #3A0842;">A platform for learning programming <br> where anyone, anywhere in the world <br> can join and become
                <br> a better programmer
            </p>
        </div>
    </div>

    <div class="container-fluid pt-5 mt-5 mb-5 pb-5">
        <div class="row align-items-center">
            <div class="col-md-6 pb-5">
                <h4 class="pl-5" style="color: #7F5A83;">Courses</h4>
                <p class="pl-5" style="color: #3A0842;">Interns are able to select from the number of courses we offer:
                   <br>Machine Learning <br>
                    Digital Marketing<br>
                    Front End development<br>
                    Back end Development<br>
               </p>
                <ul class="pl-5 ml-3" style="color: #44CF6C;">
                    <li>100% Online</li>
                    <li>Flexible Online Learning</li>
                    <li>Earn a Course Certificate</li>
                </ul>
                <a class="btn btn-success ml-5 pl-5 pr-5" href="register.html">Start Learning</a>
            </div>
            <div class="col-md-6">
                <img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570915745/startng/Rectangle_9_w0iucz.png" class="img-fluid">
            </div>
        </div>
    </div>

    <div class="container-fluid loren-ipsum pt-5 pb-5">
        <div class="col-md-6 offset-md-3 text-center">
            <p style="color: #fff;">You can have access to our free courses in Web development, Machine learning, and Digital Marketing. 
                                                       We have also made available paid courses that would give maximum and intense information about any course you will be interested in and you will have the opportunity to get your hands on 
                                                        enough practicals and projects of which at the end of the course, certificates will be issued. </p>
        </div>
        <div class="col-md-4 offset-md-4">
            <div class="row buttonC">
                <div class="col-xs-6">
                    <a href="courses.html" class="btn btn-success pr-5 pl-5">Free Courses</a>
                </div>
                <div class="col-xs-6">
                    <a href="courses.html" class="btn btn-success pr-5 pl-5">Paid Courses</a>
                </div>
            </div>
        </div>
    </div>

    <section id="carousel" >
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
            
        </ol>
                      
        <!-- Wrapper for slides -->
        <div class="carousel-inner" role="listbox">
            <div class="item active" >
                    <img src="https://res.cloudinary.com/crowdtechie/image/upload/v1571755724/mercyyeny_asnkzu.png" alt="carousel image" style="width:100%;">
                    <div class="carousel-caption">
                    <p>Managing tasks and having to deliver meeting up with deadlines in a few days under pressure is not a big deal anymore. I say a big thank you to the organizers of the HNG program and the sponsors.</p> 
                    <h4>Moses Obanega </h4>
                    <h5>Front end track<br> From Imo state </h5>
                    </div>
            </div>
            <div class="item">
                    <img src="https://res.cloudinary.com/crowdtechie/image/upload/v1571756321/udimceo_roelk2.png"  alt="carousel image" style="width:100%;">
                    <div class="carousel-caption">
                    	<p>I came into HNG with zero knowledge in programming and I'll be leaving with so much knowledge acquired in programming, now I can be called a front end web developer. Thanks to HNG.</p>
                    	<h4>Sydney Collins</h5>
                        <h5> Front End track <br>From Cameroon</h5>
                    </div>
            </div>
            <div class="item">
                    <img  src="https://res.cloudinary.com/crowdtechie/image/upload/v1571756342/mercymage_ezz8bj.png" alt="carousel image" style="width:100%;">
                    <div class="carousel-caption">
                    	<p>One of the many things learned during the HNG program is collaborating with people online effectively. And I won't forget to commend the efforts of the mentors who we could reach out to when we are faced with some big problems. Lol. </p>
                    	<h4>Ibrahim Adamu</h4>
                        <h5>Machine Learning track<br>From Kano</h5>
                    </div>
            </div>
        </div>
                      
        <!-- Left and right controls -->
          <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
            <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
            <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
            </a>
        </div>
        </section>
        
<section class="privilege">
    <div class="container-fluid pt-5 pb-5">
        <div class="col-md-6 offset-md-3 text-center">
            <h5 style="color: #3A0842;">On Start.ng, you are privileged to</h5>
        </div>
        <div class="row mt-5 pt-3">
            <div class="col-md-6">
                <div class="row">
                    <div class="col-md-4">
                    	<div class="text-center">
                        <img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570918022/startng/Group_412_furoek.png" class="img-fluid img-responsive">
                        </div>
                    </div>
                    <div class="col-md-8">
                        <p style="color: #3A0842">Learn from the Best Teachers</p>
                        <p>We hire Tutors with 100% knowledge on each track. Interns are provided best and appropriate advice from tutors based on their experiences.
                        </p>
                    </div>
                </div>
            </div>
            
         <!-- <div class="col-md-2"></div> -->
            <div class="col-md-6">
                <div class="row">
                    <div class="col-md-4">
                    	<div class="text-center">
                        <img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570918022/startng/Group_414_pycdu8.png" class="img-fluid img-responsive">
                        </div>
                    </div>
                    <div class="col-md-8">
                        <p style="color: #3A0842">Join Online Developer Community</p>
                        <p>A 24-hour functioning online community is made available for interns to learn from each other and communicate with senior developers. They also would not miss out on important information about events and meetups.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="row md-5 pt-3">
            <div class="col-md-6">
                <div class="row">
                    <div class="col-md-4">
                    	<div class="text-center">
                        <img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570918022/startng/Group_412_furoek.png" class="img-fluid img-responsive">
                        </div>
                    </div>
                    <div class="col-md-8">
                        <p style="color: #3A0842">Get Academic and Technical Support</p>
                        <p>Interns are exposed to updated usage of some technologies and effective training on their usage is provided.
                        </p>
                    </div>
                </div>


            </div>
     <!-- <div class="col-md-2"></div>   -->
            <div class="col-md-6">
                <div class="row">
                    <div class="col-md-4">
                    	<div class="text-center">
                        <img src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570918022/startng/Group_414_pycdu8.png" class="img-fluid img-responsive">
                        </div>
                    </div>
                    <div class="col-md-8">
                        <p style="color: #3A0842">Earn a Certifcate</p>
                        <p>Interns are eligible for a certificate if only they get to a certain stage of the internship.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container-fluid pt-5 pb-5">
        <div class="col-md-6 offset-md-3 text-center">
            <p style="color: #3A0842;">Hi</p>
            <p style="color: #3A0842;">Do you know you can Enrol for</p>
            <p style="color: #3A0842; font-weight: bold;">FREE COMPLETE BEGINNER SOFTWARE DEVELOPMENT TRAINING</p>
            <a href="register.html" class="btn btn-success pl-5 pr-5">Start Learning</a>
        </div>
    </div>

    <div class="container-fluid started">
        <div class="row align-items-center">
            <div class="col-md-6 pb-2">
                <img class="img-fluid" src="https://res.cloudinary.com/sgnolebagabriel/image/upload/v1570919824/startng/Group_360_s7w45n.png">
            </div>
            <div class="col-md-6 text-center pb-2">
                <h4 style="color: #7F5A83; font-weight: bold;">How It All Started</h4>
                <p>The Internship was born out of passion and dedication to see aspiring youths attain their goals in the tech world by becoming software developers.</p>
                <p>The co-founder Mark Essien initiated this Internship in 2017, and since then, the vision has remained the same - massively accelerate Nigerians and Africans becoming software developers. 
                       And doing this in a way that is open for all, no barriers and no bias. The only limitation should be your own willingness to continue.</p>
            </div>
        </div>
    </div>

   <div class="container-fluid global-reach pt-5 pb-5">
        <div class="col-md-6 offset-md-3 text-center pt-5">
            <h4 class="pb-3 rHeader">Our Global Reach</h4>
            <p class="pb-4 rText">Start.ng is the leading online learning platform for programming courses nationwide
                and across Africa and the world. Our goal is to eradicate illetracy across Africa, equipping each
                students with knowledge and character needed to excel anywhere
                in the world.</p>
            <p class="pb-3 strong">Most Sought after Programming Skills </p>
            <p class="pb-3 strong">Experienced Qualified Teachers</p>
            <p class="pb-5 strong">Access to the Largest Online Developer Community</p>
            <a href="curriculum.html" class="btn btn-secondary pl-5 pr-5 mb-3"
                style="background-color: #3A0842; border: thin solid #3A0842;">Explore Start.ng</a>
        </div>
    </div>

    <!-- Footer -->
    <div class="container-fluid text-white deep">
        <footer>
            <div class="container">
                <div class="row">
                    <div class="col-md-12 mt-3 mb-4">
                        <img src="https://res.cloudinary.com/juwon-tech/image/upload/v1570818437/Logo_1_oyasky.png" alt="">
                    </div>
                </div>

                <div class="row pb-4">
                    <div class="col-lg-4 col-md-12 mb-3">
                        <h4 class='mb-4'>Ready to take the Leap?</h4>
                        <a href="register.html" class='btn btn-success px-5 py-2 mb-5'>Start!</a>
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-6 col-xs-6 my-2">
                        <li><a href="about.html">About Us</a></li>
                        <li><a href="courses.html">Our Course</a></li>
                        <li><a href="hireGrad.html">Hire a Grad</a></li>
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-6 col-xs-6 my-2">
                        <li><a href="curriculum.html">Curriculum</a></li>
                        <li><a href="blog2.html">Blog</a></li>
                        <li><a href="blog1.html">Student Stories</a></li>

                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-6 col-xs-6 my-2">
                        <li><a href="search.html">Find a Course</a></li>
                        <li><a href="#">Our Partners</a></li>
                        <li><a href="contactus.html">Contact Us</a></li>
                    </div>
                    <div class="col-lg-2 col-md-3 col-sm-6 col-xs-6 my-2">
                        <li><a href="help.html">FAQ</a></li>
                        <li><a href="termsOfService.html">Terms of Service</a></li>
                        <li><a href="privacy-policy.html">Privacy Policy</a></li>
                    </div>
                </div>

            </div>
    </div>
    <div class="container-fluid text-white py-2" style="background: #2E0435; width:100%;">
        <div class="container text-right">
            <div class="row icons">
                <div class="col-md-12 ">
                    <a href=""><i class='fab fa-twitter' aria-hidden="true"></i></a>
                    <a href=""><i class='fab fa-instagram' aria-hidden="true"></i></a>
                    <a href=""><i class="fab fa-facebook" aria-hidden="true"></i></a>
                </div>
            </div>
        </div>
        </footer>
    </div>

    <!-- End of Footer -->

    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.15.0/umd/popper.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/js/bootstrap.min.js"></script>
</body>

</html>
