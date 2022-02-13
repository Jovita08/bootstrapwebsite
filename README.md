# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home Page:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

  <!-- ======= Top Bar ======= -->
  <section id="topbar" class="d-flex align-items-center">
    <div class="container d-flex justify-content-center justify-content-md-between">
      <div class="contact-info d-flex align-items-center">
        <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">adg.brpd.nic.in</a>
        <i class="bi bi-phone-fill phone-icon"></i>+91-11-2678 8255
      </div>
      <div class="social-links d-none d-md-block">
        <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
      </div>
    </div>
  </section>

  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex align-items-center">
      <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img"></a>
      <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
          <li class="dropdown"><a href="./aboutus.html"><span>About Us</span></a>
          <li class="dropdown"><a href="./training.html"><span>Research & CA</span></a>
          <li><a class="nav-link scrollto " href="./index.html#portfolio">DOPO</a></li>
          <li><a class="nav-link scrollto" href="#team">Training</a></li>
          <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">SPC</a></li>
              <li><a href="#">Modernization</a></li>
              <li><a href="#">NPM</a></li>
              <li><a href="#">SPD</a></li>
              <li><a href="#">Admin</a></li>
              <li><a href="#">SP Conf. & Police Expo</a></li>
              <li><a href="#">Publication/ Reports</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
          </li>
          <li><a class="getstarted scrollto" href="./index.html#contact">Gallery</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header><!-- End Header -->

  <!-- ======= Hero Section ======= -->
  <section id="hero" style="height: 65vh;">
         <img class="carousel-item active" src="./img/BPRDSlider1.jpg">
  </section><!-- End Hero -->

  <main id="main">

    <section id="why-us" class="why-us" style="padding-top: 30px;">
      <div class="container" style="background-color: #b3cae4; padding-top: 30px;" >

        <div class="row no-gutters">
          <h3 class="bi bi-laptop" style="text-align: center;">What's New</h3>
          <div class="col-lg-4 col-md-6 content-item">
            <span>01</span>
            <h4>Internship</h4>
            <p>Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23. Last date: 28/02/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Internship.pdf">Apply Here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>02</span>
            <h4>Bureau Darpan</h4>
            <p>From : 05/01/2022 To: 31/03/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/BureauDarpan.pdf">View PDF here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>03</span>
            <h4>Webinar</h4>
            <p>	Proceedings of the Webinar on Woman Safety with Sensitivity From: 04/01/2022 to 31/12/2024</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Adv%20of%20PGVPant%202021-22.pdf">View PDF here</a></p>
          </div>
        </div>

      </div>
    </section><!-- End News & Events Section -->


    <!-- ======= News & Events Section ======= -->
    <section id="why-us" class="why-us" style="padding-top: 30px;">
      <div class="container" style="background-color: #b3cae4; padding-top: 30px;">

        <div class="row no-gutters" >
          <h2 class="bi bi-chevron-right" style="text-align: center; padding-top: 20px;">News & Events</h2>
          <div class="col-lg-4 col-md-6 content-item">
            <span>01</span>
            <h4>Internship</h4>
            <p>Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23. Last date: 28/02/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Internship.pdf">Apply Here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>02</span>
            <h4>Bureau Darpan</h4>
            <p>From : 05/01/2022 To: 31/03/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/BureauDarpan.pdf">View PDF here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>03</span>
            <h4>Adv of PGVPant 2021-22</h4>
            <p>	पंडित गोविंद वल्लभ पंत पुरस्कार योजना वर्ष 2021-22 का विज्ञापन।. From : 18/11/2021 To: 31/03/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Adv%20of%20PGVPant%202021-22.pdf">View PDF here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>04</span>
            <h4>Police Aur Seva</h4>
            <p>Do Visit our Ploice Aur Seva Channel on YouTube</p>
            <p><a href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow/videos">See the channel here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>05</span>
            <h4>Yoga at Workplace</h4>
            <p>Why is yoga good for you?Yoga improves strength, balance and flexibility.Slow movements and deep breathing increase blood flow and warm up muscles, while holding a pose can build strength.</p>
            <p><a href="https://bprd.nic.in/WhatsNews_Description.aspx?News_id=10308">Watch the video here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>06</span>
            <h4>Cyber Cases Manual</h4>
            <p>Investigative Workflow Manual on Cyber Harassment Cases</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/BPRD%20Cyber%20harassment%20cases%206-3-21.pdf">See the PDF here</a></p>
          </div>

        </div>

      </div>
    </section><!-- End News & Events Section -->


    <!-- ======= Gallery Section ======= -->
    <section id="portfolio" class="portfolio">
      <div class="container">

        <div class="section-title">
          <h2>GALLERY</h2>
          <p>View the latest photos and videos of BPRD here.</p>
        </div>

        <div class="row portfolio-container">

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/gallery2.jfif" class="img-fluid" alt="">
              
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/foundation.jfif" class="img-fluid" alt="">

            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="./img/gallery/spc.jfif" class="img-fluid" alt="">

            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/ips.jfif" class="img-fluid" alt="">

            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="./img/gallery/expo.jfif" class="img-fluid" alt="">

            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/conf.jfif" class="img-fluid" alt="">

            </div>
          </div>
        </div>
      </div>
    </section><!-- Gallery Section -->

  
    <!-- ======= Contact Section ======= -->
    <section id="contact" class="contact">
      <div class="container">

        <div class="section-title">
          <h2>Contact Us</h2>
        </div>

        <div class="row">

          <div class=" d-flex align-items-stretch">
            <div class="info">
              <div class="address">
                <i class="bi bi-geo-alt" style="background-color: rgb(50, 82, 129);"></i>
                <h4>Location:</h4>
                <p>Bureau of Police Research and Development
                  Ministry of Home Affairs,
                  NH-8, Mahipalpur
                  New Delhi (India)</p>
              </div>

              <div class="email">
                <i class="bi bi-envelope" style="background-color: rgb(50, 82, 129);"></i>
                <h4>Email:</h4>
                <p>adg.brpd.nic.in</p>                 
              </div>

              <div class="phone">
                <i class="bi bi-phone" style="background-color: rgb(50, 82, 129);"></i>
                <h4>Call:</h4>
                <p>+91-11-2678 8255</p>
              </div>
            </div>

          </div>
        </div>

      </div>
    </section><!-- End Contact Section -->

  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Developed by <a href="https://bootstrapmade.com/">Virgil Jovita.A</a>
      </div>
    </div>
  </footer><!-- End Footer -->

    <!-- Vendor JS Files -->
  <!-- Vendor JS Files -->
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>
  <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <!-- Template Main JS File -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="./js/main.js"></script>
</body>
</html>
```
### About Us Page:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

 <!-- ======= Top Bar ======= -->
 <section id="topbar" class="d-flex align-items-center">
  <div class="container d-flex justify-content-center justify-content-md-between">
    <div class="contact-info d-flex align-items-center">
      <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">adg.brpd.nic.in</a>
      <i class="bi bi-phone-fill phone-icon"></i>+91-11-2678 8255
    </div>
    <div class="social-links d-none d-md-block">
      <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
      <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
      <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
      <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
    </div>
  </div>
</section>

<!-- ======= Header ======= -->
<header id="header" class="d-flex align-items-center">
  <div class="container d-flex align-items-center">
    <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img-fluid"></a>
    <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
    <nav id="navbar" class="navbar">
      <ul>
        <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
        <li class="dropdown"><a href="./aboutus.html"><span>About Us</span> <i class="bi bi-chevron-down"></i></a>
          <li class="dropdown"><a href="./training.html"><span>Research & CA</span> <i class="bi bi-chevron-down"></i></a>
        <li><a class="nav-link scrollto " href="./index.html#portfolio">DOPO</a></li>
        <li><a class="nav-link scrollto" href="#team">Training</a></li>
        <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
          <ul>
            <li><a href="#">SPC</a></li>
            <li><a href="#">Modernization</a></li>
            <li><a href="#">NPM</a></li>
            <li><a href="#">SPD</a></li>
            <li><a href="#">Admin</a></li>
            <li><a href="#">SP Conf. & Police Expo</a></li>
            <li><a href="#">Publication/ Reports</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </li>
        <li><a class="getstarted scrollto" href="./index.html#contact">Gallery</a></li>
      </ul>
      <i class="bi bi-list mobile-nav-toggle"></i>
    </nav><!-- .navbar -->

  </div>
</header><!-- End Header -->

  
 <!-- ======= About Us Section ======= -->
 <section id="about" class="about">
  <div class="container">

    <div class="section-title">
      <h2>About Us</h2>
    </div>

    <div class="row">
      <div class="col-lg-3 order-1 order-lg-1">
        <div class="list-group">
          <ul class="list-group">
            <li class="list-group-item">Awards/Medals</li>
            <li class="list-group-item">Work Allocation</li>
            <li class="list-group-item">Organization</li>
            <li class="list-group-item">Draft Legislation</li>
            <li class="list-group-item">Citizens Corner</li>
          </ul>
        </div>
      </div>
      <div class="col-lg-9 pt-4 pt-lg-0 order-2 order-lg-1 content">
        <h3>Evolution of BPRD</h3>
        <p>
          1. The Government of India vide Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:<br>

          To take direct and active interest in the issues<br>
          To promote a speedy and systematic study of the police problems,<br>
          To apply science and technology in the methods and techniques used by police.<br>
          In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau. <br>
          
          2.The Bureau was established with the following two divisions initially with a well laid out charter of duties:<br>
          
          Research, Statistics and Publication<br>
          Development.<br>
          Training is a vital and growing requirement to improve the competency of police forces in the country. The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave several recommendations. The government of India in accepting its recommendations created a Training Division (1973) in addition to the two divisions already existing to function under the Bureau.<br>
          The forensic science services comprising CFSLs & GEsQD under the Development Division grew over a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.<br>
          Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.<br>
          During the year 2008, the Government of India further decided to create National Police Mission under the administrative control of BPR&D to transform the police forces in the country into effective instrument for maintenance of internal security and facing the challenges in future, by equipping them with the necessary material, intellectual and organizational resources.<br>
          <br>SEPARATION:<br>
          
          1. Though the Institute of Criminology and Forensic Science (ICFS) was established under the overall supervision and guidance of BPR&D as part of the same exercise, it was allowed to function as a separate entity in 1976: since the ultimate objective of setting up the Institute was to develop a full-fledged academic institution for furthering studies in Criminology and forensic science. The same which has been re-christened in the year 1991 is now functioning as Lok Nayak Jai Prakash Narayan (LNJN), National Institute of Criminology and Forensic Science from 1982. The institute provides training courses for officers of the criminal justice system in the two subjects i.e. Criminology and Forensic Science and carries out research.<br>
          
          2. Growth dynamics took over and the need to specialize in each area arose. The National Police Commission (1977) also recommended certain measures requiring implementation. Simultaneously technological innovations particularly computers held promises of support to many areas of crime control and crime detection besides processing statistical data for the purpose of analysis. The Government of India, therefore, decided to establish a National Crime Records Bureau in 1986 build another Resolution and entrusted statistics and publications work of the Research Division to the newly constituted Bureau along with the plans for their computerization.<br>
          
          3. In an identical move brought about by compulsions of growth, the Government of India decided to give an independent status to the Forensic Science Division by creating a Forensic Science Directorate having an autonomous status under the direct control of the Ministry of Home Affairs.<br>
        </p>
      </div>
    </div>
  </div>
</section><!-- End About Us Section -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Developed by <a href="https://bootstrapmade.com/">Virgil Jovita.A</a>
      </div>
    </div>
  </footer><!-- End Footer -->

  <!-- Template Main JS File -->
  <script src="./js/main.js"></script>
</body>
</html>
```
### Training Page:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

 <!-- ======= Top Bar ======= -->
 <section id="topbar" class="d-flex align-items-center">
  <div class="container d-flex justify-content-center justify-content-md-between">
    <div class="contact-info d-flex align-items-center">
      <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">adg.brpd.nic.in</a>
      <i class="bi bi-phone-fill phone-icon"></i>+91-11-2678 8255
    </div>
    <div class="social-links d-none d-md-block">
      <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
      <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
      <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
      <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
    </div>
  </div>
</section>

<!-- ======= Header ======= -->
<header id="header" class="d-flex align-items-center">
  <div class="container d-flex align-items-center">
    <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img-fluid"></a>
    <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
    <nav id="navbar" class="navbar">
      <ul>
        <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
        <li class="dropdown"><a href="./aboutus.html"><span>About Us</span> <i class="bi bi-chevron-down"></i></a>
          <li class="dropdown"><a href="./training.html"><span>Research & CA</span> <i class="bi bi-chevron-down"></i></a>
        <li><a class="nav-link scrollto " href="./index.html#portfolio">DOPO</a></li>
        <li><a class="nav-link scrollto" href="#team">Training</a></li>
        <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
          <ul>
            <li><a href="#">SPC</a></li>
            <li><a href="#">Modernization</a></li>
            <li><a href="#">NPM</a></li>
            <li><a href="#">SPD</a></li>
            <li><a href="#">Admin</a></li>
            <li><a href="#">SP Conf. & Police Expo</a></li>
            <li><a href="#">Publication/ Reports</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </li>
        <li><a class="getstarted scrollto" href="./index.html#contact">Gallery</a></li>
      </ul>
      <i class="bi bi-list mobile-nav-toggle"></i>
    </nav><!-- .navbar -->

  </div>
</header><!-- End Header -->

  
 <!-- ======= About Us Section ======= -->
 <section id="about" class="about">
  <div class="container">

    <div class="section-title">
      <h2>Training</h2>
    </div>

    <div class="row">
      <div class="col-lg-3 order-1 order-lg-1">
        <div class="list-group">
          <ul class="list-group">
            <li class="list-group-item">Domestic Courses</li>
            <li class="list-group-item">Foreign Courses</li>
            <li class="list-group-item">Training Calendar</li>
            <li class="list-group-item">Training Material</li>
            <li class="list-group-item">Miscellaneous</li>
            <li class="list-group-item">Training Policy</li>
            <li class="list-group-item">CDTI</li>
            <li class="list-group-item">Training Division</li>
            <li class="list-group-item">Union Home Minister Trophy</li>
            <li class="list-group-item">Training Symposium</li>
            <li class="list-group-item">Miscellaneous</li>
            <li class="list-group-item">Union Home Minister Training Medal</li>
            <li class="list-group-item">CAPT, Bhopal</li>
            <li class="list-group-item">UHM Medal For Excellence in Investigation</li>
            <li class="list-group-item">Publications</li>
            <li class="list-group-item">Online Course</li>
          </ul>
        </div>
      </div>
      <div class="col-lg-9 pt-4 pt-lg-0 order-2 order-lg-1 content">
        <h3>Training</h3>
        <p>
            The Training Division of the Bureau of Police Research & Development is responsible for comprehensive in-service training of Police personnel in the country on common subjects related to the police training across the country. Besides, it also coordinates training of Indian police personnel abroad and within the country by Foreign Security agencies. BPR&D in co-ordination with Ministry of External Affairs (MEA) facilitates training of foreign police personnel in India. Being the nodal agency of the Ministry of Home Affairs, Government of India on issues related to Police training, it has the important task of standardizing training methodology and framing training policies for skill up-gradation of Police officers of all ranks.<br><br>

            BPR&D also supervises the five Central Detective Training Schools (CDTS) located at Chandigarh, Kolkata, Hyderabad, Jaipur and Ghaziabad, which run courses for central/state police officers in the field of Scientific Investigation. A Central Academy for Police Training (CAPT) established by BPR&D, at Bhopal conducts training programs for DySSP rank officers. Under training intervention scheme BPR&D conducts specialized training programs on various aspects of investigation with an aim to create a pool of trained police investigators on specialized area of investigation in every district of the country. Training Division also reviews Training Methodology and conducts assessment of future needs for police training in the country.
        </p>
      </div>
    </div>
  </div>
</section><!-- End About Us Section -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Developed by <a href="https://bootstrapmade.com/">Virgil Jovita.A</a>
      </div>
    </div>
  </footer><!-- End Footer -->

  <!-- Template Main JS File -->
  <script src="./js/main.js"></script>
</body>
</html>
```
## OUTPUT:
### Home Page:
![home1](./bprdwebsite/static/img/out/home.png)
![home2](./bprdwebsite/static/img/out/home2.png)
![home3](./bprdwebsite/static/img/out/home3.png)
### About Us Page:
![menu](./bprdwebsite/static/img/out/about.png)
### SPC Page:
![Training](./bprdwebsite/static/img/out/training.png)

## Result:
Thus a website is designed using bootstrap framework.