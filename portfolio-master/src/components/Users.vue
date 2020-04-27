<template>
<body id="page-top" >
<nav class="navbar navbar-b navbar-trans navbar-expand-md fixed-top black" id="mainNav" style="position:fixed;">
  <div class="container" >
    <a class="navbar-brand js-scroll" href="#page-top"><img src="@/assets/img/vats1.png" class="img-fluid rounded b-shadow-a" alt="" style="width:90px;" ></a>
    <button class="navbar-toggler collapsed" type="button" data-toggle="collapse" data-target="#navbarDefault"
      aria-controls="navbarDefault" aria-expanded="false" aria-label="Toggle navigation" >
      <span></span>
      <span></span>
      <span></span>
    </button>
    <div class="navbar-collapse collapse justify-content-end" id="navbarDefault" >
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link js-scroll active" href="#home" style="color:black;">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll" href="#about" style="color:black;">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll" href="#service" style="color:black;">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll" href="#work" style="color:black;">Work</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll" href="#blog" style="color:black;">Hobbies</a>
        </li>
        <li class="nav-item">
          <a class="nav-link js-scroll" href="#contact" style="color:black;">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<!--/ Nav End /-->

<!--/ Intro Skew Star /-->
<div :style="{'background-image':'url(https://i.pinimg.com/originals/27/e4/86/27e4869dfbeaedc081af8546e3fb2405.jpg)'}" id="home" class="intro route bg-image" >

  <div class="overlay-itro"></div>
  <div class="intro-content display-table">
    <div class="table-cell">
      <div class="container">
        <!--<p class="display-6 color-d">Hello, world!</p>-->
        <h1 class="intro-title mb-4">Vatsonline</h1>
        <h6 style="font-size:13px;"> <span style="color:#ffce00; font-weight:bold;" >S</span>uccess is not a <span style="color:#ffce00;">D</span>estination,
        its a <span style="color:#ffce00;font-weight:bold;">J</span>ourney . . .</h6><br />
        <div class="typewriter">
        <p class="typewriter-text" style="font-size:14px;" >Web Developer |  Designer | AI Enthusiate | Traveller | Trekker<strong class="text-slider"></strong></p>
        <!-- <p class="pt-3"><a class="btn btn-primary btn js-scroll px-4" href="#about" role="button">Learn More</a></p> --></div>
      </div>
    </div>
  </div>
</div>
<!--/ Intro Skew End /-->

<section id="about" class="about-mf sect-pt4 route">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div class="box-shadow-full">
          <div class="row">
            <div class="col-md-6">
              <div class="row">
                <div class="col-sm-6 col-md-5">
                  <div class="about-img">
                    <img src="@/assets/img/testimonial-2.jpg" class="img-fluid rounded b-shadow-a" alt="" >
                  </div>
                </div>
                <div class="col-sm-6 col-md-7">
                  <div class="about-info">
                    <p><span class="title-s">Name: </span> <span>Britto Baby</span></p>
                    <p><span class="title-s">Profile: </span> <span>Software Engineer</span></p>
                    <p><span class="title-s">Email: </span> <span>brittobaby23@gmail.com</span></p>
                    <p><span class="title-s">Phone: </span> <span>(81) 080-9502-0336</span></p>
                  </div>
                </div>
              </div>
              <div class="skill-mf">
                <p class="title-s">Skill</p>
                <span>WEB DESIGNING</span> <span class="pull-right">90%</span>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="85" aria-valuemin="0"
                    aria-valuemax="100"></div>
                </div>
                <span>JAVASCRIPT</span> <span class="pull-right">90%</span>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0"
                    aria-valuemax="100"></div>
                </div>
                <span>PYTHON</span> <span class="pull-right">75%</span>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0"
                    aria-valuemax="100"></div>
                </div>
                <span>PHP/ JAVA</span> <span class="pull-right">70%</span>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 70%" aria-valuenow="50" aria-valuemin="0"
                    aria-valuemax="100"></div>
                </div>
                <span>DJANGO/ Vue Js</span> <span class="pull-right">60%</span>
                <div class="progress">
                  <div class="progress-bar" role="progressbar" style="width: 60%" aria-valuenow="90" aria-valuemin="0"
                    aria-valuemax="100"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="about-me pt-4 pt-md-0">
                <div class="title-box-2">
                  <h5 class="title-left">
                    About me
                  </h5>
                </div>
                <p class="lead">
                I spend my days crafting websites and creating Software. I worked as Research and Development Engineer at SA pvt ltd, currently positioned as Software Engineer at Agent-network, Shibuya.
                I have experience of Creating Super Dynamic Websites and Software.
                </p>
                <p class="lead">
                I’m constantly learning web technologies and other design related topics,
               currently playing around with Javascript Frameworks, Vue js and Machine Learning Stuffs. I’m skilled in many areas of design, development of AI and Web Departments.
                </p>

              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!--/ Section Services Star /-->
<section id="service" class="services-mf route">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div class="title-box text-center">
          <h3 class="title-a">
            Services
          </h3>
          <p class="subtitle-a">
            CAREER | FUTURE
          </p>
          <div class="line-mf"></div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-monitor"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">Web Design</h2>
            <p class="s-description text-center">
              Got a Strong hands of knowledge in Using Web Related technologies like HTMl,Css3,
              Javascript, PHP, Jquery. currently intrested in Frameworks like Django and Vue js.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-code-working"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">Coding</h2>
            <p class="s-description text-center">
              A passion started 6 years before when i Choose Diploma, from then till now i was assisting in most of the project as core developer.

            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-camera"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">Adobe Design</h2>
            <p class="s-description text-center">
              One of the most used software for designing Prototype are Adobe and Zeplin. I am using this from past 1 year to develop the design for various projects.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-android-phone-portrait"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">Responsive Design</h2>
            <p class="s-description text-center">
              A website is said to be responsive, if it supports different Screen size. Have developed various resposive websites which supports small and large screens.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-paintbrush"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">R&D</h2>
            <p class="s-description text-center">
              I started my carrer as R&D Engineer at SA Pvt ltd, bangalore. where my job was to code, develop and Assist IoT and Robotic Devices.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="service-box">
          <div class="service-ico">
            <span class="ico-circle"><i class="ion-stats-bars"></i></span>
          </div>
          <div class="service-content">
            <h2 class="s-title">Testing</h2>
            <p class="s-description text-center">
              Its a good habit of getting some knowledge of testing like the software used for testing, Scripts and the best methods thats is used
              for testing.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!--/ Section Services End /-->

<div class="section-counter paralax-mf bg-image" style="background-image: url(img/counters-bg.jpg)">
  <div class="overlay-mf"></div>
  <div class="container">
    <div class="row">
      <div class="col-sm-3 col-lg-3">
        <div class="counter-box counter-box pt-4 pt-md-0">
          <div class="counter-ico">
            <span class="ico-circle"><i class="ion-checkmark-round"></i></span>
          </div>
          <div class="counter-num">
            <p class="counter">20</p>
            <span class="counter-text">WORKS COMPLETED</span>
          </div>
        </div>
      </div>
      <div class="col-sm-3 col-lg-3">
        <div class="counter-box pt-4 pt-md-0">
          <div class="counter-ico">
            <span class="ico-circle"><i class="ion-ios-calendar-outline"></i></span>
          </div>
          <div class="counter-num">
            <p class="counter">2</p>
            <span class="counter-text">YEARS OF EXPERIENCE</span>
          </div>
        </div>
      </div>
      <div class="col-sm-3 col-lg-3">
        <div class="counter-box pt-4 pt-md-0">
          <div class="counter-ico">
            <span class="ico-circle"><i class="ion-ios-people"></i></span>
          </div>
          <div class="counter-num">
            <p class="counter">3</p>
            <span class="counter-text">TOTAL PUBLICATIONS</span>
          </div>
        </div>
      </div>
      <div class="col-sm-3 col-lg-3">
        <div class="counter-box pt-4 pt-md-0">
          <div class="counter-ico">
            <span class="ico-circle"><i class="ion-ribbon-a"></i></span>
          </div>
          <div class="counter-num">
            <p class="counter">8</p>
            <span class="counter-text">AWARD WON</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!--/ Section Portfolio Star /-->
<section id="work" class="portfolio-mf sect-pt4 route">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div class="title-box text-center">
          <h3 class="title-a">
            Works
          </h3>
          <p class="subtitle-a">
            PROJECTS | PASSION
          </p>
          <div class="line-mf"></div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-1.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/AI.jpg" alt="" class="img-fluid" style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Cyberbullying Project</h2>
                  <div class="w-more">
                    <span class="w-ctegory">Machine Learning</span> / <span class="w-date">1 May. 2017</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                    <a href="https://github.com/britto-baby"><span class="ion-social-github" style="font-size:32px;"></span></a>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-2.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/dev.jpg" alt="" class="img-fluid"  style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Image Search by Tag </h2>
                  <div class="w-more">
                    <span class="w-ctegory">Deep Learning</span> / <span class="w-date">18 oct. 2017</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                    <a href="https://github.com/britto-baby"><span class="ion-social-github" style="font-size:32px;"></span></a>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-3.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/des.jpg" alt="" class="img-fluid" style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Online BookstoreHome </h2>
                  <div class="w-more">
                    <span class="w-ctegory">Web Design . Test</span> / <span class="w-date">12 Jan. 2016</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                  <a href="https://github.com/britto-baby"><span class="ion-social-github" style="font-size:32px;"></span></a>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-4.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/ai1.jpeg" alt="" class="img-fluid" style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Blood Image Analysis</h2>
                  <div class="w-more">
                    <span class="w-ctegory">Machine Learning</span> / <span class="w-date">7 Jan. 2020</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                    <span class="ion-ios-plus-outline"></span>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-5.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/web.jpg" alt="" class="img-fluid" style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Hackathon WebPage</h2>
                  <div class="w-more">
                    <span class="w-ctegory">Web Design . Test</span> / <span class="w-date">1 jun. 2019</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                    <a href="https://github.com/britto-baby"><span class="ion-social-github" style="font-size:32px;"></span></a>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="work-box">
          <a href="img/work-6.jpg" data-lightbox="gallery-mf" style="text-decoration:none;">
            <div class="work-img">
              <img src="@/assets/img/ioy.jpg" alt="" class="img-fluid" style="height:220px; width:345px;">
            </div>
            <div class="work-content">
              <div class="row">
                <div class="col-sm-8">
                  <h2 class="w-title">Smart car parking Asst</h2>
                  <div class="w-more">
                    <span class="w-ctegory">IoT Development</span> / <span class="w-date">30 Aug. 2018</span>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="w-like">
                  <a href="https://github.com/britto-baby"><span class="ion-social-github" style="font-size:32px;"></span></a>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>

    </div>
  </div>
</section>
<!--/ Section Portfolio End /-->

<!--/ Section Blog Star /-->
<section id="blog" class="blog-mf sect-pt4 route">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div class="title-box text-center">
          <h3 class="title-a">
            Hobbies
          </h3>
          <p class="subtitle-a">
            Life, is a collection of comma's. There are no fullstops, It's all comma's
          </p>
          <div class="line-mf"></div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="card card-blog">
          <div class="card-img">
            <a href="blog-single.html"><img src="@/assets/img/trav.jpg" alt="" class="img-fluid"></a>
          </div>
          <div class="card-body">
            <div class="card-category-box">
              <div class="card-category">
                <h6 class="category">Travel</h6>
              </div>
            </div>
            <h3 class="card-title"><a href="blog-single.html">Ladakh, North India.</a></h3>

          </div>
          <div class="card-footer">
            <div class="post-author">
              <a href="#">
                <img src="@/assets/img/testimonial-2.jpg" alt="" class="avatar rounded-circle">
                <span class="author">Britto</span>
              </a>
            </div>
            <div class="post-date">
              <span class="ion-ios-clock-outline"></span> 2 days
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card card-blog">
          <div class="card-img">
            <a href="blog-single.html"><img src="@/assets/img/scub.jpg" alt="" class="img-fluid" style="height:235px; width:348px;"></a>
          </div>
          <div class="card-body">
            <div class="card-category-box">
              <div class="card-category">
                <h6 class="category">Scuba Diving</h6>
              </div>
            </div>
            <h3 class="card-title"><a href="blog-single.html">Andaman and Nicobar Island</a></h3>

          </div>
          <div class="card-footer">
            <div class="post-author">
              <a href="#">
                <img src="@/assets/img/testimonial-2.jpg" alt="" class="avatar rounded-circle">
                <span class="author">Britto</span>
              </a>
            </div>
            <div class="post-date">
              <span class="ion-ios-clock-outline"></span> 2 days
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card card-blog">
          <div class="card-img">
            <a href="blog-single.html"><img src="@/assets/img/trek.jpg" alt="" class="img-fluid" style="height:235px; width:348px;"></a>
          </div>
          <div class="card-body">
            <div class="card-category-box">
              <div class="card-category">
                <h6 class="category">Trekking</h6>
              </div>
            </div>
            <h3 class="card-title"><a href="blog-single.html">Munnar, Kerala</a></h3>

          </div>
          <div class="card-footer">
            <div class="post-author">
              <a href="#">
                <img src="@/assets/img/testimonial-2.jpg" alt="" class="avatar rounded-circle">
                <span class="author">Britto </span>
              </a>
            </div>
            <div class="post-date">
              <span class="ion-ios-clock-outline"></span>  2 days
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!--/ Section Blog End /-->

<!--/ Section Contact-Footer Star /-->
<section class="paralax-mf footer-paralax bg-image sect-mt4 route" style="background-image: url(img/overlay-bg.jpg)">
  <div class="overlay-mf"></div>
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div class="contact-mf">
          <div id="contact" class="box-shadow-full">
            <div class="row">
              <div class="col-md-6">
                <div class="title-box-2">
                  <h5 class="title-left">
                    Send a Message
                  </h5>
                </div>
                <div>
                    <form action="" method="post" role="form" class="contactForm">
                    <div id="sendmessage">Your message has been sent. Thank you!</div>
                    <div id="errormessage"></div>
                    <div class="row">
                      <div class="col-md-12 mb-3">
                        <div class="form-group">
                          <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
                          <div class="validation"></div>
                        </div>
                      </div>
                      <div class="col-md-12 mb-3">
                        <div class="form-group">
                          <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" data-rule="email" data-msg="Please enter a valid email" />
                          <div class="validation"></div>
                        </div>
                      </div>
                      <div class="col-md-12 mb-3">
                          <div class="form-group">
                            <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" data-rule="minlen:4" data-msg="Please enter at least 8 chars of subject" />
                            <div class="validation"></div>
                          </div>
                      </div>
                      <div class="col-md-12 mb-3">
                        <div class="form-group">
                          <textarea class="form-control" name="message" rows="5" data-rule="required" data-msg="Please write something for us" placeholder="Message"></textarea>
                          <div class="validation"></div>
                        </div>
                      </div>
                      <div class="col-md-12">
                        <button type="submit" class="button button-a button-big button-rouded">Send Message</button>
                      </div>
                    </div>
                  </form>
                </div>
              </div>
              <div class="col-md-6">
                <div class="title-box-2 pt-4 pt-md-0">
                  <h5 class="title-left">
                    Get in Touch
                  </h5>
                </div>
                <div class="more-info">
                  <p class="lead">
                  Life is a combination of commitments and enjoyment, It's always pleasure to meet some one new and learning new things from him. <br />
                  Make friends | Enjoy | Learn and Apply

                  </p>
                  <ul class="list-ico">
                    <li><span class="ion-ios-location"></span> 101, Mitia 3-18-27, Adachi-ku kohoku Tokyo</li>
                    <li><span class="ion-ios-telephone"></span> (81) 080-9502-0336</li>
                    <li><span class="ion-email"></span> brittobaby23@gmail.com</li>
                  </ul>
                </div>
                <div class="socials">
                  <ul>
                    <li><a href="https://www.facebook.com/brittobaby23"><span class="ico-circle"><i class="ion-social-facebook" style="color:black"></i></span></a></li>
                    <li><a href="https://www.instagram.com/vatsonline/"><span class="ico-circle"><i class="ion-social-instagram" style="color:black"></i></span></a></li>
                    <li><a href="https://github.com/britto-baby"><span class="ico-circle"><i class="ion-social-github" style="color:black"></i></span></a></li>
                    <li><a href="https://www.linkedin.com/in/britto-baby-2377a5137"><span class="ico-circle"><i class="ion-social-linkedin" style="color:black"></i></span></a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="copyright-box">
            <p class="copyright">&copy; Copyright <strong>Vtechies</strong>. All Rights Reserved</p>
            <div class="credits">
              <!--
                All the links in the footer should remain intact.
                You can delete the links only if you purchased the pro version.
                Licensing information: https://bootstrapmade.com/license/
                Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/buy/?theme=DevFolio
              -->
              Designed by <a href="https://bootstrapmade.com/">Britto</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</section>

<a href="#" class="back-to-top"><i class="fa fa-chevron-up"></i></a>

</body>

</template>
<!-- JavaScript Libraries -->
<script src="./assets/lib/jquery/jquery.min.js"></script>
<script src="./assets/lib/jquery/jquery-migrate.min.js"></script>
<script src="./assets/lib/popper/popper.min.js"></script>
<script src="./assets/lib/bootstrap/js/bootstrap.min.js"></script>
<script src="./assets/lib/easing/easing.min.js"></script>
<script src="./assets/lib/counterup/jquery.waypoints.min.js"></script>
<script src="./assets/lib/counterup/jquery.counterup.js"></script>
<script src="./assets/lib/owlcarousel/owl.carousel.min.js"></script>
<script src="./assets/lib/lightbox/js/lightbox.min.js"></script>
<script src="./assets/lib/typed/typed.min.js"></script>
<!-- Contact Form JavaScript File -->
<script src="./assets/contactform/contactform.js"></script>

<!-- Template Main Javascript File -->
<script src="./assets/js/main.js"></script>
<script>
export default{
  name:'Users',
}

</script>


<style>
.typewriter {
  font-family: Roboto, monospace;
	display: inline-block;
}

.typewriter-text {
  display: inline-block;
  overflow: hidden;
  letter-spacing: 1px;
 animation: typing 5s steps(30, end), blink .75s step-end infinite;
  white-space: nowrap;
  font-size: 30px;
  font-weight: 700;
  border-right: 4px solid orange;
  box-sizing: border-box;
}

@keyframes typing {
    from {
        width: 0%
    }
    to {
        width: 100%
    }
}

@keyframes blink {
    from, to {
        border-color: transparent
    }
    50% {
        border-color:#ffce00;
    }
}
</style>
