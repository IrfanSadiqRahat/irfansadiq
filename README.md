<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Irfan Sadiq Rahat - Machine Learning Researcher</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="Irfan Sadiq Rahat, Machine Learning, Data Science, AI, Researcher, Portfolio, VIT-AP University, Bangladesh, Research Scientist">
    <meta name="description" content="Explore the portfolio of Irfan Sadiq Rahat, an accomplished researcher in Machine Learning, Data Science, and AI. Discover his work, achievements, and contributions to the field.">
    <link rel="icon" href="img/favicon.ico" type="image/x-icon">
    
    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- CSS Libraries -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
    <link href="lib/animate/animate.min.css" rel="stylesheet">
    <link href="lib/owlcarousel/assets/owl.carousel.min.css" rel="stylesheet">
    <link href="lib/lightbox/css/lightbox.min.css" rel="stylesheet">
    
    <!-- Template Stylesheet -->
    <link href="css/style.css" rel="stylesheet">

    <!-- Custom Styles for the "Topmate-Style" Purple Theme -->
    <style>
    /* ----------------------------
       Global Colors & Typography
       ---------------------------- */
    body {
        font-family: 'Montserrat', sans-serif;
        color: #333;
        background-color: #fff;
    }
    h1, h2, h3, h4, h5, h6 {
        font-weight: 700;
        color: #6C63FF; /* Primary Purple */
    }
    p {
        font-size: 1rem;
        line-height: 1.6;
        color: #555;
    }
    a {
        color: #6C63FF;
        text-decoration: none;
        transition: color 0.3s;
    }
    a:hover {
        color: #4a3bbf;
    }

    /* ----------------------------
       Navbar
       ---------------------------- */
    .navbar {
        background-color: #6C63FF !important; /* Purple Navbar */
    }
    .navbar-brand,
    .navbar-nav .nav-link {
        color: #fff !important; 
    }
    .navbar-brand:hover,
    .navbar-nav .nav-link:hover {
        color: #ffe400 !important; /* Bright accent on hover */
    }
    .navbar-toggler-icon {
        background-image: url("data:image/svg+xml;charset=UTF8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba%288, 8, 8, 0.7%29' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
    }

    /* ----------------------------
       Hero Section
       ---------------------------- */
    .hero {
        min-height: 100vh;
        display: flex;
        align-items: center;
        background-color: #6C63FF; /* Purple Background */
        color: #fff;
        padding: 60px 0;
    }
    .hero-content {
        max-width: 600px;
    }
    .hero-content h1 {
        font-size: 3rem;
        margin-bottom: 15px;
    }
    .typed-text {
        font-size: 1.25rem;
        margin-bottom: 20px;
    }
    .hero-btn .btn {
        margin: 5px;
        font-weight: 600;
    }
    /* Make CTA buttons stand out in white or purple outline */
    .btn-primary {
        background-color: #ffe400;
        border-color: #ffe400;
        color: #333;
    }
    .btn-primary:hover {
        background-color: #ffc107;
        border-color: #ffc107;
        color: #fff;
    }
    .btn-outline-primary {
        border-color: #fff !important;
        color: #fff !important;
    }
    .btn-outline-primary:hover {
        background-color: #fff !important;
        color: #6C63FF !important;
    }

    /* Hero Image */
    .hero-image img {
        width: 400px;
        height: 400px;
        object-fit: cover;
        border-radius: 50%; /* Circular image */
        border: 5px solid #ffe400; /* Accent border */
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    /* Subtle animations for hero text */
    @keyframes fadeInDown {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    /* Initially hidden; then fade in */
    .hero-content h1 {
      opacity: 0;
      transform: translateY(-20px);
      animation: fadeInDown 1s ease-out forwards;
    }
    .typed-text {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1.5s ease-out forwards;
      animation-delay: 0.5s;
    }
    .hero-btn a {
      opacity: 0;
      animation: fadeIn 2s ease-out forwards;
      animation-delay: 1s;
    }
    .footer-social a i {
      animation: zoomIn 1.5s ease-out forwards;
      animation-delay: 1.5s;
      opacity: 0;
    }
    @keyframes zoomIn {
      from {
        transform: scale(0.8);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    /* ----------------------------
       Section Headers
       ---------------------------- */
    .section-header p {
        font-weight: 600;
        color: #6C63FF;
    }
    .section-header h2 {
        color: #6C63FF;
        font-weight: 700;
        margin-bottom: 30px;
    }

    /* ----------------------------
       Common Card / Box Style
       ---------------------------- */
    .bg-white {
        background-color: #fff !important;
    }
    .rounded {
        border-radius: 8px !important;
    }
    .shadow-sm {
        box-shadow: 0 4px 8px rgba(0,0,0,0.05) !important;
    }
    .h-100 {
        height: 100% !important;
    }

    /* ----------------------------
       About Section
       ---------------------------- */
    .about {
        padding: 60px 0;
        background-color: #f9f9f9;
    }
    .about-content h2 {
        color: #6C63FF;
    }
    .about-text {
        background-color: #fff;
        border: 1px solid #ddd;
    }
    .about-img img {
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    /* ----------------------------
       Leadership Section
       ---------------------------- */
    .Leadership {
        padding: 60px 0;
        background-color: #fff; /* Switch to white to create color contrast */
    }
    .Leadership-item {
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .Leadership-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    }
    .Leadership-item h3 {
        color: #6C63FF;
    }

    /* ----------------------------
       Timeline / Experience
       ---------------------------- */
    .timeline-date {
        color: #6C63FF;
        font-weight: 600;
    }
    .timeline-text h2 {
        color: #6C63FF;
    }
    .timeline {
        margin-top: 40px;
        position: relative;
    }
    /* (Keeping your existing timeline design mostly intact) */

    /* ----------------------------
       Resume Banner
       ---------------------------- */
    .banner {
        background: #f9f9f9;
        padding: 40px 0;
    }
    .banner-text .btn {
        background-color: #6C63FF;
        color: #fff;
        margin-top: 10px;
        font-weight: 600;
    }
    .banner-text .btn:hover {
        background-color: #4a3bbf;
        border-color: #4a3bbf;
    }

    /* ----------------------------
       Portfolio
       ---------------------------- */
    .portfolio {
        background-color: #fff;
    }
    .portfolio-text h6, .portfolio-text h3 {
        color: #6C63FF;
    }
    .portfolio-wrap {
        background-color: #fff;
    }

    /* ----------------------------
       Publications
       ---------------------------- */
    .publications {
        background-color: #fff;
    }
    .publication-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    }

    /* ----------------------------
       Contact Section
       ---------------------------- */
    .contact {
        background-color: #f9f9f9;
    }
    .contact-info {
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    /* ----------------------------
       Footer
       ---------------------------- */
    .footer {
        background-color: #6C63FF;
        color: #fff;
        padding: 60px 0;
        margin-top: 40px;
    }
    .footer-info h2, .footer-info h3 {
        color: #fff;
    }
    .footer-menu p {
        color: #fff;
    }
    .icon-container a {
        color: #fff;
    }
    .icon-container a:hover {
        color: #ffe400;
    }
    .copyright a {
        color: #fff;
        text-decoration: underline;
    }
    .copyright a:hover {
        color: #ffe400;
    }
    </style>
</head>
<body data-spy="scroll" data-target=".navbar" data-offset="51">
    <!-- Navbar Start -->
    <nav class="navbar navbar-expand-lg navbar-light sticky-top">
        <div class="container">
            <a href="#home" class="navbar-brand">Irfan Sadiq Rahat</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarCollapse">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a href="#home" class="nav-link active">Home</a></li>
                    <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                    <li class="nav-item"><a href="#Leadership" class="nav-link">Leadership</a></li>
                    <li class="nav-item"><a href="#education" class="nav-link">Education</a></li>
                    <li class="nav-item"><a href="#portfolio" class="nav-link">Portfolio</a></li>
                    <li class="nav-item"><a href="img/My Resume.pdf" class="nav-link">My Resume</a></li>
                    <li class="nav-item"><a href="#publications" class="nav-link">publications</a></li>
                    <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Navbar End -->

    <!-- Hero Start -->
    <div class="hero" id="home">
        <div class="container">
            <div class="row align-items-center">
                <!-- Text Column -->
                <div class="col-md-6">
                    <div class="hero-content">
                        <h1>I'm Irfan Sadiq Rahat</h1>
                        <div class="typed-text">ML Model Developer, Research Scientist, Data Scientist</div>
                        <div class="hero-btn mt-4">
                            <a href="#about" class="btn btn-primary">Know More</a>
                            <a href="#contact" class="btn btn-outline-primary">Contact Me</a>
                        </div>
                        <!-- Social Links -->
                        <div class="footer-social mt-4">
                            <a href="https://scholar.google.com/citations?user=QIhCXGMAAAAJ&hl=en" class="google-scholar"><i class="fas fa-book"></i> Google Scholar</a>
                            <a href="https://www.linkedin.com/in/irfan-sadiq-3a2884218" class="linkedin"><i class="fab fa-linkedin"></i> LinkedIn</a>
                            <a href="https://www.researchgate.net/profile/Irfan-Rahat-2" class="researchgate"><i class="fas fa-file-alt"></i> ResearchGate</a>
                            <a href="https://orcid.org/0009-0003-3254-4846" class="orcid"><i class="fab fa-orcid"></i> ORCID</a>
                            <a href="https://github.com/IrfanSadiqRahat" class="github"><i class="fab fa-github"></i> GitHub</a>
                        </div>
                    </div>
                </div>
                <!-- Image Column -->
                <div class="col-md-6 d-none d-md-block">
                    <div class="hero-image text-center">
                        <img src="img/about.jpg" alt="Hero Image" class="img-fluid">
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Hero End -->


    <!-- About Start -->
    <div class="about wow fadeInUp" data-wow-delay="0.1s" id="about">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="about-img">
                        <img src="img/about.jpg" alt="About Image" class="img-fluid">
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="about-content">
                        <div class="section-header text-left">
                            <p>Learn About Me</p>
                            <h2>2 Years Experience</h2>
                        </div>
                        <div class="about-text">
                            <h2>About Irfan Sadiq</h2>
                            <p>
                                Hello! I’m Irfan Sadiq from Bangladesh, currently an undergraduate in Computer Science at VIT-AP University, India. My journey here has enriched my academic and cultural perspective, fueling my passion for machine learning and artificial intelligence with applications in healthcare and agriculture. I’ve completed over 20 research projects, with publications in respected journals like IEEE Xplore and Computers in Biology and Medicine, and presented my findings at prominent conferences in Slovakia, Germany, Dubai, and India.
                            </p>
                            <p>
                                As President of the Machine Learning Club, I led our growth from a small group to the university’s best technical club, fostering innovation through hackathons and research initiatives. Motivated by a desire to bridge real-world challenges through AI, I am committed to using technology to make a meaningful impact.
                            </p>
                        </div>
                        <a class="btn btn-primary mt-3" href="#resume">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- About End -->
    

    <!-- Leadership Start -->
    <section class="Leadership py-5" id="Leadership">
        <div class="container">
            <div class="section-header text-center">
                <h2 class="font-weight-bold">Leadership</h2>
                <p class="lead">Unique Leadership Identities</p>
            </div>
            <div class="row">
                <!-- Card 1 -->
                <div class="col-lg-6 mb-4">
                    <div class="Leadership-item p-4 h-100">
                        <div class="d-flex align-items-center mb-3">
                            <i class="fa fa-users fa-3x text-primary"></i>
                            <h3 class="ml-3 font-weight-bold">Team Player</h3>
                        </div>
                        <p>
                            When I joined the Machine Learning Club at VIT-AP University, it was a small, almost unknown group with just four members. Out of more than 80 clubs on campus, we were in a challenging position, with limited visibility and impact. However, I saw potential in what we could become.
                        </p>
                        <p>
                            As president, I believed collaboration would be the key to our growth. My first priority was to create an environment where everyone felt valued and motivated to contribute. Through persistent effort, we grew from four members to 160, establishing a reputation as the university’s Best Technical Club.
                        </p>
                    </div>
                </div>
                <!-- Card 2 -->
                <div class="col-lg-6 mb-4">
                    <div class="Leadership-item p-4 h-100">
                        <div class="d-flex align-items-center mb-3">
                            <i class="fa fa-chalkboard-teacher fa-3x text-primary"></i>
                            <h3 class="ml-3 font-weight-bold">Innovator</h3>
                        </div>
                        <p>
                            At the heart of my work is a drive to redefine possibilities through innovation. I focus on developing advanced deep learning models and hybrid approaches that address real-world challenges, constantly pushing the boundaries of machine learning. My commitment to innovation means that I don’t just seek solutions; I seek breakthroughs—ideas and methods that elevate accuracy, efficiency, and applicability.
                        </p>
                        <p>
                            My work combines curiosity and purpose, from creating robust models for medical diagnostics to pioneering AI solutions in agriculture. By merging state-of-the-art architectures with custom techniques, I ensure that my innovations are both impactful and grounded in practical value.
                        </p>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="col-lg-6 mb-4">
                    <div class="Leadership-item p-4 h-100">
                        <div class="d-flex align-items-center mb-3">
                            <i class="fa fa-lightbulb fa-3x text-primary"></i>
                            <h3 class="ml-3 font-weight-bold">“Why” I Do What I Do</h3>
                        </div>
                        <p>
                            At the core of my work is a commitment to innovation that serves a purpose. As an international student from Bangladesh at VIT-AP University, I’ve been driven by a vision: to harness the power of AI and machine learning to tackle real-world issues. Each research project is a step toward building tools that diagnose diseases more accurately, predict environmental shifts, and support farmers in managing crop health.
                        </p>
                    </div>
                </div>
                <!-- Card 4 -->
                <div class="col-lg-6 mb-4">
                    <div class="Leadership-item p-4 h-100">
                        <div class="d-flex align-items-center mb-3">
                            <i class="fa fa-question-circle fa-3x text-primary"></i>
                            <h3 class="ml-3 font-weight-bold">How I Do</h3>
                        </div>
                        <p>
                            My approach to research is rooted in innovation, specifically through the creation of new model architectures and hybrid approaches that address real-world challenges in fields like healthcare and agriculture. I start by identifying critical issues—whether in disease detection for medical imaging or crop disease recognition. 
                        </p>
                        <p>
                            Each project involves meticulous testing, where I employ optimization algorithms to fine-tune models, ensuring they are both accurate and efficient. This commitment to practical, high-impact research is what drives my continuous pursuit of excellence.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Leadership End -->

    
    <!-- Experience / Education Start -->
    <div class="experience" id="education">
        <div class="container">
            <header class="section-header text-center wow zoomIn" data-wow-delay="0.1s">
                <p>My Academic Journey </p>
                <h2>My Educational Qualification</h2>
            </header>
            <div class="timeline">
                <!-- Timeline Item 1 -->
                <div class="timeline-item left wow slideInLeft" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">2021 - Present</div>
                        <h2>B.Tech in Computer Science and Engineering</h2>
                        <h4>Vellore Institute of Technology, Andhra Pradesh, India</h4>
                        <p>
                            Specialization in Artificial Intelligence and Machine Learning, GPA: 7.89.
                        </p>
                    </div>
                </div>
                <!-- Timeline Item 2 -->
                <div class="timeline-item right wow slideInRight" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">2018 - 2020</div>
                        <h2>Higher Secondary Certificate</h2>
                        <h4>BAF Shaheen College, Dhaka</h4>
                        <p>GPA: 5.0 on a scale of 5.0</p>
                    </div>
                </div>
                <!-- Timeline Item 3: Awards & Scholarships -->
                <div class="timeline-item left wow slideInLeft" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">Awards & Scholarships</div>
                        <h2>Various Recognitions</h2>
                        <h4>VIT-AP University and ICISML Conference</h4>
                        <p>
                            ● 2023: Raman Research Award for Publications, VIT-AP University, India.<br>
                            ● 2023: Best Research Paper Award in ICISML Conference.<br>
                            ● 2023-24: Best Technical Club Award.<br>
                            ● 2021: <strong>INTERNATIONAL SCHOLARSHIP FOR EDUCATION & ENRICHMENT (I-SEE)</strong><br>
                            <strong>Date: 13.12.2021</strong>
                        </p>
                        <a href="img/Admission letter.pdf" target="_blank" class="btn btn-primary">View Scholarship Certificate</a>
                    </div>
                </div>
                <!-- Timeline Item 4: Internship 1 -->
                <div class="timeline-item right wow slideInRight" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">November 2022 – November 2023</div>
                        <h2>Internship under Dr. Janjhyam Venkata Naga Ramesh</h2>
                        <h4>Graphic Era Hill University, Dehradun</h4>
                        <p>
                            ● Focused on deep learning applications in medical imaging and agricultural sustainability.<br>
                            ● Projects on Lung Tissue Classification, Cassava Leaf Disease, and Cauliflower Disease Classification.<br>
                            ● Demonstrated strong research skills and innovative problem-solving.
                        </p>
                        <a href="imgc/intern_Janjhyam.pdf" target="_blank" class="btn btn-primary">View Internship Certificate</a>
                    </div>
                </div>
                <!-- Timeline Item 5: Internship 2 -->
                <div class="timeline-item right wow slideInRight" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">September 2023 – February 2024</div>
                        <h2>Internship under Dr. Mohammed Altaf Ahmed</h2>
                        <h4>Prince Sattam Bin Abdulaziz University, Al-Kharj</h4>
                        <p>
                            ● Developed advanced deep learning models for automated haematology.<br>
                            ● Published a research paper on "Deep Learning Models for Blood Cell Detection and Classification."
                        </p>
                        <a href="img/intern_Altaf.pdf" target="_blank" class="btn btn-primary">View Internship Certificate</a>
                    </div>
                </div>
                <!-- Timeline Item 6: Internship 3 -->
                <div class="timeline-item right wow slideInRight" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">April 2023 – April 2024</div>
                        <h2>Internship under Dr. P. Pavan Kumar</h2>
                        <h4>IcfaiTech Faculty of Science & Technology, IFHE, Hyderabad</h4>
                        <p>
                            ● Worked on advanced deep learning models in medical image processing.<br>
                            ● Published three research papers on Tuberculosis, Pneumonia, and Alzheimer's Disease detection.
                        </p>
                        <a href="img/intern.pdf" target="_blank" class="btn btn-primary">View Internship Certificate</a>
                    </div>
                </div>
                <!-- Timeline Item 7: Research and Development -->
                <div class="timeline-item left wow slideInLeft" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">Responsibilities</div>
                        <h2>Research and Development</h2>
                        <p>
                            ● Conducted extensive research under the supervision of Dr. Janjhyam.<br>
                            ● Attended workshops on ML, image processing, computer vision, optimization, and NLP.
                        </p>
                    </div>
                </div>
                <!-- Timeline Item 8: Leadership Identities -->
                <div class="timeline-item right wow slideInRight" data-wow-delay="0.1s">
                    <div class="timeline-text">
                        <div class="timeline-date">Leadership Identities</div>
                        <h2>President of the Machine Learning Club</h2>
                        <h4>VIT-AP University</h4>
                        <p>
                            ● Led the Machine Learning Club (2023-2024), organizing events and competitions.<br>
                            ● Led (Bongojo club, 2022-2023) the technical team.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Experience End -->

    <!-- Resume Start -->
    <div class="banner wow zoomIn" data-wow-delay="0.1s" id="resume">
        <div class="container">
            <div class="section-header text-center">
                <h2>Download My Resume</h2>
            </div>
            <div class="container banner-text text-center">
                <p>
                    Interested in my professional journey? Download my resume to get an in-depth look at my skills, experience, and accomplishments.
                </p>
                <a href="img/My Resume.pdf" class="btn">Download My Resume</a>
            </div>
        </div>
    </div>
    <!-- Resume End -->

   <!-- Portfolio Start -->
<div class="portfolio" id="portfolio">
    <div class="container">
        <div class="section-header text-center wow zoomIn" data-wow-delay="0.1s">
            <p>My Portfolio</p>
            <h2>My Different Works</h2>
        </div>
        <div class="row">
            <div class="col-12">
                <!-- Portfolio Filter -->
                <ul id="portfolio-filter" class="text-center list-unstyled">
                    <li data-filter="*" class="filter-active">All</li>
                    <li data-filter=".filter-1">Extra-Curricular Activities</li>
                    <li data-filter=".filter-2">Data Science & Research Papers</li>
                    <li data-filter=".filter-3">Internships</li>
                </ul>
            </div>
        </div>

        <!-- Portfolio Container -->
        <div class="portfolio-container">
            <!-- =============== 1) EXTRA-CURRICULAR ACTIVITIES (filter-1) =============== -->

            <!-- Item #1: ML Club Best Technical Club -->
            <div class="portfolio-item filter-1 wow fadeInUp" data-wow-delay="0.0s">
                <div class="portfolio-wrap">
                    <!-- Main Image -->
                    <a href="img/DSC_8142(1).JPG" 
                       data-lightbox="ec-1" 
                       data-title="Machine Learning Club Honored as Best Technical Club">
                        <div class="portfolio-img">
                            <img src="img/DSC_8142(1).JPG" 
                                 alt="Machine Learning Club Honored as Best Technical Club">
                        </div>
                        <div class="portfolio-text">
                            <h6>Machine Learning Club Honored as Best Technical Club</h6>
                        </div>
                    </a>
                    <!-- Hidden/Additional Images -->
                    <a href="img/1723069282078(1).JPG" 
                       data-lightbox="ec-1" 
                       data-title="Club Celebration" 
                       style="display: none;"></a>
                    <a href="img/another_image1.jpg" 
                       data-lightbox="ec-1" 
                       data-title="Group Photo" 
                       style="display: none;"></a>
                </div>
            </div>

            <!-- Item #2: ML Club Speech -->
            <div class="portfolio-item filter-1 wow fadeInUp" data-wow-delay="0.2s">
                <div class="portfolio-wrap">
                    <!-- Main Image -->
                    <a href="img/1723068174449(1).jpg" 
                       data-lightbox="ec-2" 
                       data-title="A Message of Motivation: Addressing the ML Club as President">
                        <div class="portfolio-img">
                            <img src="img/1723068174449(1).jpg" 
                                 alt="Addressing the Machine Learning Club as President">
                        </div>
                        <div class="portfolio-text">
                            <h6>A Message of Motivation: Addressing the ML Club as President</h6>
                        </div>
                    </a>
                    <!-- Hidden/Additional Images -->
                    <a href="img/WhatsApp Image 2024-08-08 at 03.46.52.jpeg" 
                       data-lightbox="ec-2" 
                       data-title="Motivational Speech" 
                       style="display: none;"></a>
                    <a href="img/club-speech(1).jpg" 
                       data-lightbox="ec-2" 
                       data-title="Club Speech 2" 
                       style="display: none;"></a>
                </div>
            </div>

            <!-- =============== 2) DATA SCIENCE & RESEARCH PAPERS (filter-2) =============== -->

            <!-- Item #1: Best Research Paper Award -->
            <div class="portfolio-item filter-2 wow fadeInUp" data-wow-delay="0.4s">
                <div class="portfolio-wrap">
                    <!-- Main Image -->
                    <a href="img/Best Research Paper Award.jpeg" 
                       data-lightbox="ds-1" 
                       data-title="Best Research Paper Award">
                        <div class="portfolio-img">
                            <img src="img/Best Research Paper Award.jpeg" alt="Best Research Paper Award">
                        </div>
                        <div class="portfolio-text">
                            <h3>Best Research Paper Award</h3>
                        </div>
                    </a>
                    <!-- Hidden/Additional Images -->
                    <a href="img/Best Research Paper Award-2.jpeg" 
                       data-lightbox="ds-1" 
                       data-title="Award Ceremony" 
                       style="display: none;"></a>
                </div>
            </div>

            <!-- Item #2: Certifications -->
            <div class="portfolio-item filter-2 wow fadeInUp" data-wow-delay="0.4s">
                <div class="portfolio-wrap">
                    <!-- Main Image -->
                    <a href="img/c1.png" 
                       data-lightbox="ds-2" 
                       data-title="Certification 1">
                        <div class="portfolio-img">
                            <img src="img/c1.png" alt="Certification 1">
                        </div>
                        <div class="portfolio-text">
                            <h3>Certifications</h3>
                        </div>
                    </a>
                    <!-- Hidden/Additional Images -->
                    <a href="img/c2.jpeg"  data-lightbox="ds-2" data-title="Certification 2" style="display: none;"></a>
                    <a href="img/c3.png"   data-lightbox="ds-2" data-title="Certification 3" style="display: none;"></a>
                    <a href="img/c4.png"   data-lightbox="ds-2" data-title="Certification 4" style="display: none;"></a>
                    <a href="img/c5.png"   data-lightbox="ds-2" data-title="Certification 5" style="display: none;"></a>
                    <a href="img/c6.png"   data-lightbox="ds-2" data-title="Certification 6" style="display: none;"></a>
                </div>
            </div>

            <!-- =============== 3) INTERNSHIPS (filter-3) =============== -->
            <!-- If you have internship images, create items here like below.
                 Currently no specific internship images are listed, so here is an example placeholder. -->

            <!-- Example Internship Item #1 (Placeholder) -->
            <!--
            <div class="portfolio-item filter-3 wow fadeInUp" data-wow-delay="0.6s">
                <div class="portfolio-wrap">
                    <a href="img/internship1.jpg" data-lightbox="intern-1" data-title="Internship Experience">
                        <div class="portfolio-img">
                            <img src="img/internship1.jpg" alt="Internship Experience">
                        </div>
                        <div class="portfolio-text">
                            <h3>Internship Project</h3>
                        </div>
                    </a>
                    <a href="img/internship1b.jpg" data-lightbox="intern-1" data-title="Internship Presentation" style="display: none;"></a>
                </div>
            </div>
            -->

        </div> <!-- /.portfolio-container -->
    </div> <!-- /.container -->
</div>
<!-- Portfolio End -->


 <!-- Publications Start -->
<div class="publications" id="publications">
  <div class="container">
    <div class="section-header text-center wow zoomIn" data-wow-delay="0.1s">
      <p>Publications</p>
      <h2>Research Papers</h2>
    </div>
    <div class="row">
      <!-- 1. Breast Ultrasound (FIRST) -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="0.1s">
        <div class="publication-text">
          <h2>Advancing Breast Ultrasound Diagnostics Through Hybrid Deep Learning Models</h2>
          <p><strong>Authors:</strong> A. Kiran, J.V.N. Ramesh, I.S. Rahat, M.A.U. Khan, A. Hossain, R. Uddin</p>
          <p><strong>Journal:</strong> Computers in Biology and Medicine, 2024</p>
          <p><strong>DOI:</strong> 
            <a href="https://doi.org/10.1016/j.compbiomed.2024.108962" target="_blank">
              10.1016/j.compbiomed.2024.108962
            </a>
          </p>
          <a href="https://doi.org/10.1016/j.compbiomed.2024.108962" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 2. Water Quality Assessment -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="0.3s">
        <div class="publication-text">
          <h2>Water Quality Assessment Through Predictive Machine Learning</h2>
          <p><strong>Authors:</strong> H. Ghosh, M.A. Tusher, I.S. Rahat, S. Khasim, S.N. Mohanty</p>
          <p><strong>Conference:</strong> Int. Conf. on Intelligent Computing and Networking, 77-88, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.1007/978-981-99-3177-4_6" target="_blank">
              10.1007/978-981-99-3177-4_6
            </a>
          </p>
          <a href="https://doi.org/10.1007/978-981-99-3177-4_6" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 3. ML & DL Techniques for Skin Cancer -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="0.5s">
        <div class="publication-text">
          <h2>A Study on the Application of ML and DL Techniques for Skin Cancer Detection</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, S.N. Mohanty, J.V.R. Ravindra, A. Sobur</p>
          <p><strong>Journal:</strong> International Journal of Computer and Systems Engineering, 18(1), 51-59, 2024</p>
          <!-- If you have a DOI, add it here. Otherwise, leave as-is or add "N/A" -->
          <p><strong>DOI:</strong> N/A</p>
          <!-- Optionally remove the button or link another source if available -->
          <a href="#" target="_blank" class="btn btn-primary disabled" aria-disabled="true">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 4. Automated Haematology -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="0.7s">
        <div class="publication-text">
          <h2>A Step Towards Automated Haematology: DL Models for Blood Cell Detection and Classification</h2>
          <p><strong>Authors:</strong> I.S. Rahat, M.A. Ahmed, D. Rohini, A. Manjula, H. Ghosh, A. Sobur</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5477" target="_blank">
              10.4108/eetpht.10.5477
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5477" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 5. Potato Leaf Disease -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="0.9s">
        <div class="publication-text">
          <h2>Potato Leaf Disease Recognition and Prediction using Convolutional Neural Networks</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, K. Shaik, S. Khasim, M. Yesubabu</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Scalable Information Systems, 10(6), 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetsis.3937" target="_blank">
              10.4108/eetsis.3937
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetsis.3937" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 6. Lung Tissue Classification -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="1.1s">
        <div class="publication-text">
          <h2>Deep Learning in Medical Imaging: A Case Study on Lung Tissue Classification</h2>
          <p><strong>Authors:</strong> S.K. Panda, J.V.N. Ramesh, H. Ghosh, I.S. Rahat, A. Sobur, M.H. Bijoy</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5549" target="_blank">
              10.4108/eetpht.10.5549
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5549" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 7. Corn Leaf Disease (Bangladesh) -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="1.3s">
        <div class="publication-text">
          <h2>Advanced Deep Learning Models for Corn Leaf Disease Classification: A Field Study in Bangladesh</h2>
          <p><strong>Authors:</strong> S.N. Mohanty, H. Ghosh, I.S. Rahat, C.V.R. Reddy</p>
          <p><strong>Journal:</strong> MDPI Engineering Proceedings 59 (1), 69, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.3390/engproc2023059069" target="_blank">
              10.3390/engproc2023059069
            </a>
          </p>
          <a href="https://doi.org/10.3390/engproc2023059069" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 8. Lower-Grade Gliomas -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="1.5s">
        <div class="publication-text">
          <h2>Unraveling the Heterogeneity of Lower-Grade Gliomas: Deep Learning-Assisted Flair Segmentation and Genomic Analysis of Brain MR Images</h2>
          <p><strong>Authors:</strong> I.S. Rahat, H. Ghosh, K. Shaik, S. Khasim, G. Rajaram</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.9.4016" target="_blank">
              10.4108/eetpht.9.4016
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.9.4016" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 9. All-Inclusive ML & DL for Cardiovascular Disease -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="1.7s">
        <div class="publication-text">
          <h2>An All-Inclusive Machine Learning and Deep Learning Method for Forecasting Cardiovascular Disease in Bangladeshi Population</h2>
          <p><strong>Authors:</strong> M. Mandava, S.R. Vinta, H. Ghosh, I.S. Rahat</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.9.4052" target="_blank">
              10.4108/eetpht.9.4052
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.9.4052" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 10. Deciphering Microorganisms -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="1.9s">
        <div class="publication-text">
          <h2>Deciphering Microorganisms Through Intelligent Image Recognition: ML and DL Approaches, Challenges, and Advancements</h2>
          <p><strong>Authors:</strong> S. Khasim, H. Ghosh, I.S. Rahat, K. Shaik, M. Yesubabu</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Internet of Things, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetiot.4484" target="_blank">
              10.4108/eetiot.4484
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetiot.4484" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 11. Yellow Rust in Wheat -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="2.1s">
        <div class="publication-text">
          <h2>Identification and Categorization of Yellow Rust Infection in Wheat Through Deep Learning Techniques</h2>
          <p><strong>Authors:</strong> M. Mandava, S.R. Vinta, H. Ghosh, I.S. Rahat</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Internet of Things, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetiot.4603" target="_blank">
              10.4108/eetiot.4603
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetiot.4603" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 12. Cauliflower Disease Classification -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="2.3s">
        <div class="publication-text">
          <h2>Enhancing Agricultural Sustainability with Deep Learning: A Case Study of Cauliflower Disease Classification</h2>
          <p><strong>Authors:</strong> N.R. Pradhan, H. Ghosh, I.S. Rahat, J.V.N. Ramesh, M. Yesubabu</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Internet of Things, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetiot.4834" target="_blank">
              10.4108/eetiot.4834
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetiot.4834" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 13. Rice-Leaf Diseases in Bangladesh -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="2.5s">
        <div class="publication-text">
          <h2>Using Deep Learning and Machine Learning: Real-Time Discernment and Diagnostics of Rice-Leaf Diseases in Bangladesh</h2>
          <p><strong>Authors:</strong> S. Khasim, I.S. Rahat, H. Ghosh, K. Shaik, S.K. Panda</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Internet of Things, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetiot.4579" target="_blank">
              10.4108/eetiot.4579
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetiot.4579" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 14. Cassava Syndrome Scan -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="2.7s">
        <div class="publication-text">
          <h2>Cassava Syndrome Scan: A Pioneering Deep Learning System for Accurate Cassava Leaf Disease Classification</h2>
          <p><strong>Authors:</strong> I.S. Rahat, H. Ghosh, J.V.N. Ramesh, A. Kiran, P. Verma</p>
          <p><strong>Conference:</strong> Int. Conf. on Applied ML and Data Analytics, 111-123, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.1007/978-3-031-55486-5_9" target="_blank">
              10.1007/978-3-031-55486-5_9
            </a>
          </p>
          <a href="https://doi.org/10.1007/978-3-031-55486-5_9" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 15. Chronic Kidney Disease -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="2.9s">
        <div class="publication-text">
          <h2>A Comparative Analysis of ML and DL Approaches for Prediction of Chronic Kidney Disease Progression</h2>
          <p><strong>Authors:</strong> S. Mandava, S.R. Vinta, H. Ghosh, I.S. Rahat</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Internet of Things, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetiot.5325" target="_blank">
              10.4108/eetiot.5325
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetiot.5325" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 16. Innovative Approaches in Tomato Leaf Disease -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="3.1s">
        <div class="publication-text">
          <h2>Innovative Approaches in Tomato Leaf Disease Recognition using Deep Learning</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, R. Pattanayak, S.N. Mohanty</p>
          <p><strong>Journal:</strong> IEEE Xplore, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.1109/ICRTAC59277.2023.10480762" target="_blank">
              10.1109/ICRTAC59277.2023.10480762
            </a>
          </p>
          <a href="https://doi.org/10.1109/ICRTAC59277.2023.10480762" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 17. Parkinson's Disease -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="3.3s">
        <div class="publication-text">
          <h2>Exploring the Potential of Deep Learning in the Classification and Early Detection of Parkinson's Disease</h2>
          <p><strong>Authors:</strong> V.S. Bakkialakshmi, V. Arulalan, G. Chinnaraju, H. Ghosh, I.S. Rahat, A. Saha</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5568" target="_blank">
              10.4108/eetpht.10.5568
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5568" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 18. Alzheimer's Disease Classification -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="3.5s">
        <div class="publication-text">
          <h2>Exploring Deep Learning Models for Accurate Alzheimer's Disease Classification Based on MRI Imaging</h2>
          <p><strong>Authors:</strong> I.S. Rahat, T. Hossain, H. Ghosh, K.L.K. Reddy, S.K. Palvadi, J.V.R. Ravindra</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5550" target="_blank">
              10.4108/eetpht.10.5550
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5550" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 19. Malaria Diagnosis -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="3.7s">
        <div class="publication-text">
          <h2>Convolutional Neural Networks in Malaria Diagnosis: A Study on Cell Image Classification</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, J.V.R. Ravindra, J. Balajee, M.A.U. Khan, J. Somasekar</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5551" target="_blank">
              10.4108/eetpht.10.5551
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5551" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 20. Tuberculosis (Pixels to Pathology) -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="3.9s">
        <div class="publication-text">
          <h2>From Pixels to Pathology: The Power of CNNs in Detecting Tuberculosis</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, M.D.M.H. Nipu, G.R. Krishna, J.V.R. Ravindra</p>
          <p><strong>Journal:</strong> EAI Endorsed Transactions on Pervasive Health and Technology, 2024</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.4108/eetpht.10.5543" target="_blank">
              10.4108/eetpht.10.5543
            </a>
          </p>
          <a href="https://doi.org/10.4108/eetpht.10.5543" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>

      <!-- 21. Mango Leaf Disease (Benchmarking ML & DL) -->
      <div class="publication-item col-md-6 wow fadeInUp" data-wow-delay="4.1s">
        <div class="publication-text">
          <h2>Benchmarking ML and DL Models for Mango Leaf Disease Detection: A Comparative Analysis</h2>
          <p><strong>Authors:</strong> H. Ghosh, I.S. Rahat, R. Lenka, S.N. Mohanty, D. Chauhan</p>
          <p><strong>Conference:</strong> Int. Conf. on Applied ML and Data Analytics, 111-123, 2023</p>
          <p><strong>DOI:</strong>
            <a href="https://doi.org/10.1007/978-3-031-55486-5_8" target="_blank">
              10.1007/978-3-031-55486-5_8
            </a>
          </p>
          <a href="https://doi.org/10.1007/978-3-031-55486-5_8" target="_blank" class="btn btn-primary">
            Read Full Paper
          </a>
        </div>
      </div>
    </div> <!-- row end -->
  </div> <!-- container end -->
</div>
<!-- Publications End -->


    <!-- Contact Start -->
    <div class="contact wow fadeInUp" data-wow-delay="0.1s" id="contact">
        <div class="container">
            <div class="section-header text-center">
                <h2>Contact Me</h2>
            </div>
            <div class="row justify-content-center">
                <!-- Contact Info -->
                <div class="col-md-6">
                    <div class="contact-info p-4">
                        <h4>Contact Details</h4>
                        <p><strong>Address:</strong> Dhaka Cantonment, East Manikdi, House No. 688, 1216, Dhaka, Bangladesh</p>
                        <p><strong>Phone:</strong> <a href="tel:+916303767012">+91 6303767012</a></p>
                        <p><strong>WhatsApp:</strong> <a href="https://wa.me/8801816991342" target="_blank">+88 01816991342</a></p>
                        <p><strong>Email:</strong> 
                            <a href="mailto:me.rahat2020@gmail.com">me.rahat2020@gmail.com</a>, 
                            <a href="mailto:rahat.21bce9985@vitapstudent.ac.in">rahat.21bce9985@vitapstudent.ac.in</a>
                        </p>
                        <p><strong>LinkedIn:</strong> 
                            <a href="https://www.linkedin.com/in/irfan-sadiq-3a2884218/" target="_blank">Irfan Sadiq Rahat</a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Contact End -->

    <!-- Footer Start -->
    <div class="footer wow fadeIn" data-wow-delay="0.3s">
        <div class="container-fluid">
            <div class="container">
                <div class="footer-info text-center">
                    <h2>Irfan Sadiq Rahat</h2>
                    <h3>VIT-AP University</h3>
                    <div class="footer-menu">
                        <p>+880186199342</p>
                        <p>me.rahat2020@gmail.com</p>
                    </div>
                    <!-- Social Icons and Professional Profiles -->
                    <div class="icon-bar d-flex justify-content-center">
                        <div class="icon-container google-scholar text-center mx-2">
                            <a href="https://scholar.google.com/citations?user=QIhCXGMAAAAJ&hl=en"><i class="fas fa-book"></i></a>
                            <span>Google Scholar</span>
                        </div>
                        <div class="icon-container linkedin text-center mx-2">
                            <a href="https://www.linkedin.com/in/irfan-sadiq-3a2884218"><i class="fab fa-linkedin-in"></i></a>
                            <span>LinkedIn</span>
                        </div>
                        <div class="icon-container researchgate text-center mx-2">
                            <a href="https://www.researchgate.net/profile/Irfan-Rahat-2"><i class="fas fa-file-alt"></i></a>
                            <span>ResearchGate</span>
                        </div>
                        <div class="icon-container orcid text-center mx-2">
                            <a href="https://orcid.org/0009-0003-3254-4846"><i class="fab fa-orcid"></i></a>
                            <span>ORCID</span>
                        </div>
                        <div class="icon-container github text-center mx-2">
                            <a href="https://github.com/IrfanSadiqRahat"><i class="fab fa-github"></i></a>
                            <span>GitHub</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container copyright text-center mt-3">
                <p>&copy; <a href="#">Irfan Sadiq Rahat</a>, All Right Reserved | Designed By <a href="https://htmlcodex.com">HTML Codex</a> | Maintained By <a href="https://irfansadiqrahat.com/#resume">Irfan Sadiq Rahat</a></p>
            </div>
        </div>
    </div>
    <!-- Footer End -->

    <!-- Back to top button -->
    <a href="#" class="btn back-to-top"><i class="fa fa-chevron-up"></i></a>

    <!-- Pre Loader -->
    <div id="loader" class="show">
        <div class="loader"></div>
    </div>

    <!-- JavaScript Libraries -->
    <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"></script>
    <script src="lib/easing/easing.min.js"></script>
    <script src="lib/wow/wow.min.js"></script>
    <script src="lib/waypoints/waypoints.min.js"></script>
    <script src="lib/typed/typed.min.js"></script>
    <script src="lib/owlcarousel/owl.carousel.min.js"></script>
    <script src="lib/isotope/isotope.pkgd.min.js"></script>
    <script src="lib/lightbox/js/lightbox.min.js"></script>

    <!-- Contact Javascript File -->
    <script src="mail/jqBootstrapValidation.min.js"></script>
    <script src="mail/contact.js"></script>

    <!-- Template Javascript -->
    <script src="js/main.js"></script>
</body>
</html>
