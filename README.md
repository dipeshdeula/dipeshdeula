<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dipesh CV's</title>

    <!-- faviicon -->
    <link rel="icon" type="images/png" href="images/DD_logo.png">

    <!-- Bootstrap 5 CDN Links -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom File's Link -->
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="responsive-style.css">



    <!-- Include jQuery UI CSS -->
    <link rel="stylesheet" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
      <!-- Include jQuery UI -->
      <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
    <!-- Include Slick CSS -->
    <link rel="stylesheet" type="text/css"
        href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" />
    <link rel="stylesheet" type="text/css"
        href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick-theme.min.css" />
    <!-- Include Lightbox CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css">

</head>

<body data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="90">
    <!-- navbar section -->
    <header class="header_wrapper">
        <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top ">
            <div class="container">
                <a href="#" class="navbar-brand">
                    <!-- Dipesh<span>CV</span></span> -->
                    <img decoding="async" src="images/DD_logo.png" alt="DD_logo" class="img-fluid">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle Navigation">
                    <div class="navbar-toggler-icon"></div>
                </button>
                <div class="collapse navbar-collapse justify-content-end " id="navbarNav">
                    <ul class="navbar-nav menu-navbar-nav">
                        <li class="nav-item">
                            <a href="#home" class="nav-link active" aria-current="page">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="#about" class="nav-link">About</a>
                        </li>

                        <li class="nav-item">
                            <a href="#services" class="nav-link">services</a>
                        </li>

                        <li class="nav-item">
                            <a href="#gallery" class="nav-link">Gallery</a>
                        </li>
                        <li class="nav-item">
                            <a href="#video-carousel" class="nav-link">Video</a>
                        </li>
                        <li class="nav-item">
                            <a href="#contact" class="nav-link">Contact</a>
                        </li>

                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <!--Navbar section exit -->

    <main>
        <!--Banner section-->
        <section id="home" class="banner_wrapper mt-5 ">
            <div class="container">
                <div class="row">
                    <div class="col-lg-7 order-lg-1 order-2 banner-content">
                        <h3 class="d-flex-inline position-relative text-secondary"><span class="animate-text">&lt;Hello
                                World ----/&gt;</span></h3>
                        <h1 class="text-uppercase">I am Dipesh Deula</h1>

                        <h5 class="text-uppercase text-secondary text-bold animate-full-text">Fullstack Web Developer
                        </h5>

                        <div class="mt-5">
                            <a href="#" class="main-btn primary-btn">Hire Me</a>
                            <a href="#" class="main-btn secondary-btn ms-4">Get CV</a>
                        </div>
                        <div class=" d-flex mt-3 ">
                            <div class="hstack gap-3">
                                <a href="https://www.facebook.com/profile.php?id=100076440164466" class="nav-link">
                                    <i class="fab fa-facebook fa-2x"></i>
                                </a>
                                <a href="https://www.linkedin.com/in/dipesh-deula-245608258/" class="nav-link">
                                    <i class="fab fa-linkedin fa-2x"></i>
                                </a>
                                <a href="https://github.com/dipeshdeula" class="nav-link">
                                    <i class="fab fa-github fa-2x"></i>
                                </a>
                            </div>
                        </div>


                    </div>

                    <div class="col-lg-5 order-lg-2 order-1">
                        <div class="top-right-img">
                            <img src="images/depesh-hero.png" alt="dipesh_hero_img" class="img-fluid">

                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- end of banner section -->

        <!-- about section -->
        <section id="about" class="about_wrapper bg-dark">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-7 mb-4 mb-lg-0">
                        <img decoding="async" src="images/dipesh-about-section.png" alt="dipesh-about-section"
                            class="img-fluid">
                    </div>
                    <div class="col-lg-5 mb-4 mb-lg-0">
                        <ul class="nav nav-tabs" id="myTab" role="tablist">
                            <li class="nav-item">
                                <a class="nav-link active" id="about-tab" data-toggle="tab" href="#about-content"
                                    role="tab" aria-controls="about-content" aria-selected="true">About Me</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="skills-tab" data-toggle="tab" href="#skills-content" role="tab"
                                    aria-controls="skills-content" aria-selected="false">Skills</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="experience-tab" data-toggle="tab" href="#experience-content"
                                    role="tab" aria-controls="experience-content" aria-selected="false">Experience</a>
                            </li>
                        </ul>
                        <div class="tab-content" id="myTabContent">
                            <!-- About Me Content -->
                            <div class="tab-pane fade show active mt-4" id="about-content" role="tabpanel"
                                aria-labelledby="about-tab">
                                <h3>Let's Introduce Myself</h3>
                                <p>Hello World ! I'm Dipesh Deula, a dedicated <span
                                        class="text-bold text-primary">Full-Stack Developer</span> currently
                                    studying in the 5th semester of my Bachelor's in Computer Applications at Hetauda
                                    School of Management and Social Sciences, Hetauda, Makawanpur
                                </p>
                                <p>I excel in bringing creative ideas to life through code, firmly believing that
                                    <span class="text-primary">"Discipline > Motivation"</span> is the key to
                                    success.Check out my projects to see my work in action,
                                    and don't hesitate to connect with me for collaboration opportunities.
                                </p>
                                <a href="#" class="main-btn primary-btn mt-4">Download CV</a>
                            </div>
                            <!-- Skills Content -->
                            <div class="tab-pane fade mt-4" id="skills-content" role="tabpanel"
                                aria-labelledby="skills-tab">
                                <h3>Skills</h3>
                                <p><span class="text-primary">"Discipline > Motivation"</span>
                                    is the key to success. My projects showcase my work in action,
                                    and I am open to collaboration opportunities.<span class="text-primary"> My skill
                                        set includes:</span>
                                </p>
                                <div class="progress-wrapper">
                                    <div class="col-md-12">
                                        <h3>Soft Skills</h3>
                                        <ul class="text-primary">
                                            <li>Adaptability</li>
                                            <li>Critical Thinking</li>
                                            <li>Collaboration</li>
                                            <li>Communication</li>
                                            <li>Handling Pressure</li>
                                            <li>Problem Solving</li>
                                        </ul>
                                    </div>

                                    <h3>Technical Skill</h3>
                                    <div class="skill">
                                        <span>Canva</span>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" style="width: 80%;"
                                                aria-valuenow="80" aria-valuemin="0" aria-valuemax="100">80%</div>
                                        </div>
                                    </div>
                                    <div class="skill">
                                        <span>HTML / CSS</span>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" style="width: 95%;"
                                                aria-valuenow="95" aria-valuemin="0" aria-valuemax="100">95%</div>
                                        </div>
                                    </div>
                                    <div class="skill">
                                        <span>JavaScript</span>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" style="width: 88%;"
                                                aria-valuenow="88" aria-valuemin="0" aria-valuemax="100">88%</div>
                                        </div>
                                    </div>
                                    <div class="skill">
                                        <span>Asp.net</span>
                                        <div class="progress">
                                            <div class="progress-bar" role="progressbar" style="width: 89%;"
                                                aria-valuenow="89" aria-valuemin="0" aria-valuemax="100">89%</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- Experience Content -->
                            <div class="tab-pane fade mt-4" id="experience-content" role="tabpanel"
                                aria-labelledby="experience-tab">
                                <div class="col-md-12">
                                    <div class="row">
                                        <h3>My Experience</h3>
                                        <div class="experience-item">
                                            <div class="row">
                                                <div class="custom-line border-top my-3"></div>
                                                <div class="col-md-4">
                                                    <div class="date">2076-2078</div>
                                                    <div class="position">Content Writer</div>
                                                </div>
                                                <div class="col-md-8">
                                                    <div class="company">Hetauda Sandesh</div>
                                                    <div class="address">Hetauda-4, Makwanpur</div>
                                                </div>
                                                <div class="custom-line border-top my-3"></div>

                                                <div class="col-md-4">
                                                    <div class="date">2080-present</div>
                                                    <div class="position">President</div>
                                                </div>

                                                <div class="col-md-8">
                                                    <div class="company">IT Club of HSMSS</div>
                                                    <div class="address">Hetauda-4, Makwanpur</div>
                                                </div>
                                                <div class="custom-line border-top my-3"></div>
                                                <div class="col-md-4">
                                                    <div class="date">2081-present</div>
                                                    <div class="position">Backend Developer Intern</div>
                                                </div>
                                                <div class="col-md-8">
                                                    <div class="company">KutumbaTech</div>
                                                    <div class="address">Hetauda-4, Makwanpur</div>
                                                </div>
                                                <div class="custom-line border-top my-3"></div>
                                            </div>
                                        </div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>


            </div>
        </section>

        <!-- end of about section -->

        <!--Service Section-->
        <section id="services" class="services_wrapper">
            <div class="container">
                <div class="row">
                    <div class="col-sm-12 text-center mb-5">
                        <h2>SERVICE OFFERS</h2>
                        <p>We provide a range of services to help you achieve the results you're after.
                            From UI/UX design to mobile app development, our team is here to support your needs.
                        </p>
                    </div>

                    <div class="col-lg-3 col-sm-6 mb-4">
                        <div class="card rounded-2 border-2 text-center py-5 px-3">
                            <div>
                                <img src="images/uiux_desing.png" alt="UI/Ux_Design" class="img-fluid">

                            </div>
                            <h5 class="text-uppercase mt-4 mb-3">UI/UX DESIGN</h5>
                            <p>Creating intuitive and engaging user experiences for your digital products.</p>

                        </div>

                    </div>

                    <div class="col-lg-3 col-sm-6 mb-4">
                        <div class="card rounded-2 border-2 text-center py-5 px-3">
                            <div>
                                <img src="images/mobile_app.png" alt="app-development" class="img-fluid">

                            </div>
                            <h5 class="text-uppercase mt-4 mb-3">Mobile App Development</h5>
                            <p>Developing high-quality mobile application to meet your business needs</p>

                        </div>

                    </div>

                    <div class="col-lg-3 col-sm-6 mb-4">
                        <div class="card rounded-2 border-2 text-center py-5 px-3">
                            <div>
                                <img src="images/web_developmen.png" alt="web-development" class="img-fluid">

                            </div>
                            <h5 class="text-uppercase mt-4 mb-3">Web Developement</h5>
                            <p>Building responsive and robust websites tailored to your requirements.</p>

                        </div>

                    </div>

                    <div class="col-lg-3 col-sm-6 mb-4">
                        <div class="card rounded-2 border-2 text-center py-5 px-3">
                            <div>
                                <img src="images/seo.png" alt="seo_Optimization" class="img-fluid">

                            </div>
                            <h5 class="text-uppercase mt-4 mb-3">Seo Optimize</h5>
                            <p>Enhancing your online presence through effective SEO strategies</p>

                        </div>

                    </div>

                </div>
            </div>
        </section>

        <!--End of service section-->

        <!-- gallery section -->

        <section id="gallery" class="gallery_wrapper bg-info">
            <div class="container">
                <h1>Certificates</h1>
                <div class="card">
                    <a href="images/frontend_coursera_certificate.png" data-lightbox="gallery"
                        data-title="Frontend Coursera Certificate">
                        <img src="images/frontend_coursera_certificate.png" alt="Frontend Coursera Certificate">
                    </a>
                </div>
                <div class="card">
                    <a href="images/game_coursera_certificate.png" data-lightbox="gallery"
                        data-title="Game Coursera Certificate">
                        <img src="images/game_coursera_certificate.png" alt="Game Coursera Certificate">
                    </a>
                </div>
                <div class="card">
                    <a href="images/IPVC_participation_certificate.png" data-lightbox="gallery"
                        data-title="IPVC Participation Certificate">
                        <img src="images/IPVC_participation_certificate.png" alt="IPVC Participation Certificate">
                    </a>
                </div>
                <div class="card">
                    <a href="images/prompt_eng_certificate.png" data-lightbox="gallery"
                        data-title="Prompt Engineering Certificate">
                        <img src="images/prompt_eng_certificate.png" alt="Prompt Engineering Certificate">
                    </a>
                </div>
                <div class="card">
                    <a href="images/python_certificate.png" data-lightbox="gallery" data-title="Python Certificate">
                        <img src="images/python_certificate.png" alt="Python Certificate">
                    </a>
                </div>
                <div class="card">
                    <a href="images/python_clg_bootcamp.jpg" data-lightbox="gallery" data-title="python_clg_bootcamp">
                        <img src="images/python_clg_bootcamp.jpg" alt="python_clg_bootcamp">
                    </a>
                </div>

                <div class="card">
                    <a href="images/worst_ux_participation.jpg" data-lightbox="gallery"
                        data-title="worst_ux_participation">
                        <img src="images/worst_ux_participation.jpg" alt="worst_ux_participation">
                    </a>
                </div>

                <div class="card">
                    <a href="images/worst_ux_achievement.jpg" data-lightbox="gallery" data-title="worst_ux_achievement">
                        <img src="images/worst_ux_achievement.jpg" alt="worst_ux_achievement">
                    </a>
                </div>
                <div class="card">
                    <a href="images/UI _Ux certificate.png" data-lightbox="gallery" data-title="UI _Ux certificate">
                        <img src="images/UI _Ux certificate.png" alt="UI _Ux certificate">
                    </a>
                </div>
            </div>
        </section>

        <!--End of gallery Section-->

        <!-- Video Carousel Section -->
        <section id="video-carousel">
            <div id="videoCarousel" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                    <!-- Slide 1 -->
                    <div class="carousel-item active">
                        <div class="embed-responsive embed-responsive-16by9">
                            <iframe class="embed-responsive-item"
                                src="https://www.youtube.com/embed/qz0aGYrrlhU?si=qQu34PbP_kTwAmRi"
                                allowfullscreen></iframe>
                        </div>
                    </div>
                    <!-- Slide 2 -->
                    <div class="carousel-item">
                        <div class="embed-responsive embed-responsive-16by9">
                            <iframe class="embed-responsive-item"
                                src="https://www.youtube.com/embed/NWnBxQjssvQ?si=bJ7ePOfmeV3pifd5"
                                allowfullscreen></iframe>
                        </div>
                    </div>
                    <!--Slide 3-->
                    <div class="carousel-item">
                        <div class="embed-responsive embed-responsive-16by9">
                            <iframe src="https://www.youtube.com/embed/-qfEOE4vtxE?si=6GuqLcAsNGsiwcwj"
                                allowfullscreen></iframe>
                        </div>
                    </div>
                </div>

                <!-- Controls -->
                <a class="carousel-control-prev" href="#videoCarousel" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#videoCarousel" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
        </section>

        <!--End of video section-->

        <!--contact section -->

        <section class="contact bg-dark" id="contact">
            <div class="container ">
                <div class="row justify-content-center flex-column flex-md-row">
                    <div class="col-md-6 text-center">
                        <div class="card-group">
                            <div class="card">
                                <h2 class="card-header bg-primary text-light">Have a great idea?</h2>
                                <div class="card-body">
                                    <img src="images/contactDipesh.png" alt="contact_Dipesh" class="img-fluid">
                                    <h2 class="card-title">Let's Talk About Your Project</h2>
                                </div>
                                <button class="card-footer main-btn primary-btn">Contact ME</button>

                            </div>

                        </div>
                    </div>
                    <div class="col-md-6 text font-primary ">
                        <h3 class="text-light">Your Details</h3>
                        <form novalidate>

                            <div class="form-floating">
                                <input type="email" id="email" class="form-control" />
                                <label for="email">Email</label>
                                <div class="invalid-feedback">Invalid email</div>
                                <div class="valid-feedback">Correct email</div>

                            </div>
                            <div class="form-floating mt-3">
                                <input type="text" class="form-control" id="firstName" />
                                <label for="firstName" class="form-label">First Name</label>
                            </div>

                            <div class="form-floating mt-3">
                                <input type="text" class="form-control" id="lastName" />
                                <label for="lastName" class="form-label">Last Name</label>
                            </div>

                            <div class="form-floating mt-3">
                                <input type="number" minlength="10" class="form-control" id="contactNumber" />
                                <label for="contactNumber" class="form-label">Contact Number</label>
                            </div>

                            <div class="form-floating mt-3">
                                <input type="date" class="form-control" id="date" />
                                <label for="date" class="form-label">Date </label>
                            </div>
                            <div class="form-floating mt-3">
                                <input type="text" class="form-control" id="projectTitle" />
                                <label for="projectTitle" class="form-label">Project Title</label>
                            </div>

                            <div class="form-floating mt-3">
                                <textarea name="projectDescription" id="projectDescription" class="form-control"
                                    style=" height:10rem;  resize:none"></textarea>
                                <label for="projectDescription" class="form-label">Project Description</label>
                            </div>

                            <div class="form-floating input-group mt-3">
                                <div class="input-group-text">$</div>
                                <input type="number" id="projectBudget" class="form-control" />
                                <div class="input-group-text">.00</div>
                                <label for="projectBudget" class="form-label ms-4">Project Budget</label>
                            </div>

                            <div class="form-check mt-3 text-secondary">
                                <input type="checkbox" class="form-check-input" id="termsAndConditions">
                                <label for="termsAndConditions" class="form-check-label">Accept Terms and
                                    Conditions</label>
                            </div>

                            <input type="submit" class="form-control mt-3 mx-auto btn-primary" value="Submit">


                        </form>

                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact">
        <div class="container">
            <div class="row">
                <div class="footer-content col-lg-5">
                    <div class="mt-3 m-3">
                        <h3>Connect With Me!</h3>
                        <div class="hstack gap-3 ms-4">

                            <a href="https://www.facebook.com/profile.php?id=100076440164466" class="nav-link">
                                <i class="fab fa-facebook fa-2x "></i>
                            </a>
                            <a href="https://www.linkedin.com/in/dipesh-deula-245608258/" class="nav-link">
                                <i class="fab fa-linkedin fa-2x"></i>
                            </a>
                            <a href="https://github.com/dipeshdeula" class="nav-link">
                                <i class="fab fa-github fa-2x"></i>
                            </a>
                            <a href="https://www.instagram.com/deula_dipesh/" class="nav-link">
                                <i class="fab fa-instagram fa-2x"></i>
                            </a>
                        </div>
                    </div>
                    <div class="footer-links">
                        <h3>Quick Links</h3>
                        <ul class="nav flex-column">
                            <li class="nav-item"><a href="#home" class="nav-link">Home</a></li>
                            <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                            <li class="nav-item"><a href="#gallery" class="nav-link">Gallery</a></li>
                            <li class="nav-item"><a href="#video" class="nav-link">Video</a></li>
                        </ul>
                    </div>
                    <div class="footer-about">
                        <h3>About This Portfolio</h3>
                        <p>This is my professional online portfolio to showcase my skills and areas of my expertise.</p>
                    </div>
                </div>
                <div class="footer-bottom  col-ld-4">
                    <span class="d-flex mx-auto"><img src="images/DD_logo.png" alt="DD_logo_footer">
                        <p class="ms-2 mt-4">&copy; 2024 DIPESH DEULA CV. All rights reserved.</p>
                    </span>
                </div>
            </div>
        </div>
    </footer>



    <script src="script.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <!-- Include jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!--Jquery animation-->
    <script src="jquery_animat.js"></script>
    <!-- Include Slick JS -->
    <script type="text/javascript"
        src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
    <!-- Include Lightbox JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/js/lightbox.min.js"></script>

    <!-- Bootstrap 5 JS CDN Links -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/2.9.2/umd/popper.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.0/js/bootstrap.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    



</body>

</html>

<h1 align="center">Hi 👋, I'm DIPESH DEULA</h1>
<h3 align="center">A passionate frontend developer | Tech enthusiast | T shaped Learner </h3>

- 🌱 I’m currently learning **asp.net**

- 💬 Ask me about **html,css,js,python,java,c#,**

- 📫 How to reach me **deuladipesh94@gmail.com**

- ⚡ Fun fact **I think HTML is best programming language**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/dipesh deula" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="dipesh deula" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>
