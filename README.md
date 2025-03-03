<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Navod Kiriwaththuduwa - Engineering Professional | NPI Engineer">
    <meta name="keywords" content="NPI Engineer, Engineering, Professional CV, Electronics Manufacturing, SMT, GPV Lanka">
    <title>Navod Kiriwaththuduwa - Interactive CV</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
        }
        /* Fix the profile image positioning */
        .profile-container {
            position: relative;
            text-align: center;
            margin-top: -75px; /* Pulls the image over the banner */
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid white;
            position: relative;
            z-index: 10; /* Ensures it's in front */
        }
        .carousel {
            position: relative;
            z-index: 1; /* Keeps banner in the background */
        }
        .section-title {
            color: #001f5f;
            text-transform: uppercase;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .nav-tabs .nav-link {
            color: #001f5f;
            font-weight: bold;
        }
        .nav-tabs .nav-link.active {
            background-color: #001f5f;
            color: white;
        }
        .tab-content {
            padding-top: 20px;
        }
        .btn-custom {
            background-color: #001f5f;
            color: white;
            border: none;
        }
        .btn-custom:hover {
            background-color: #003080;
        }
        .contact-icons a {
            margin: 10px;
            font-size: 24px;
            color: #001f5f;
            transition: 0.3s;
        }
        .contact-icons a:hover {
            color: #003080;
            transform: scale(1.2);
        }
        @media (max-width: 768px) {
            .profile-img {
                width: 100px;
                height: 100px;
            }
            h1 {
                font-size: 22px;
            }
            h5 {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <!-- Banner with Slideshow -->
    <div id="bannerCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="banner1.jpg" class="d-block w-100" alt="Banner 1">
            </div>
            <div class="carousel-item">
                <img src="banner2.jpg" class="d-block w-100" alt="Banner 2">
            </div>
            <div class="carousel-item">
                <img src="banner3.jpg" class="d-block w-100" alt="Banner 3">
            </div>
        </div>

        <!-- Previous Button -->
        <button class="carousel-control-prev" type="button" data-bs-target="#bannerCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>

        <!-- Next Button -->
        <button class="carousel-control-next" type="button" data-bs-target="#bannerCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <div class="container text-center">
        <div class="profile-container">
            <img src="FB_IMG_1739336827040.jpg" alt="Navod Kiriwaththuduwa" class="profile-img">
        </div>
        <h1 class="custom-text">Navod Kiriwaththuduwa</h1>
        <h5>Engineering Professional | NPI Engineer</h5>
        <p class="mt-2"><i class="fas fa-phone"></i> +94 77 172 3911</p>
        <div class="contact-icons mt-3">
            <a href="mailto:navodkiri@gmail.com"><i class="fas fa-envelope"></i></a>
            <a href="https://linkedin.com/in/navod-kiriwaththuduwa" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.facebook.com/navod.kiriwaththuduwa" target="_blank"><i class="fab fa-facebook"></i></a>
        </div>
        <a href="CV_Navod.pdf" class="btn btn-custom mt-3" download>Download CV</a>
    </div>

    <div class="container mt-5">
        <ul class="nav nav-tabs" id="cvTabs" role="tablist">
            <li class="nav-item"><a class="nav-link active" id="education-tab" data-bs-toggle="tab" href="#education" role="tab">Education</a></li>
            <li class="nav-item"><a class="nav-link" id="experience-tab" data-bs-toggle="tab" href="#experience" role="tab">Professional Experience</a></li>
            <li class="nav-item"><a class="nav-link" id="projects-tab" data-bs-toggle="tab" href="#projects" role="tab">Major Projects Completed</a></li>
            <li class="nav-item"><a class="nav-link" id="leadership-tab" data-bs-toggle="tab" href="#leadership" role="tab">Leadership</a></li>
            <li class="nav-item"><a class="nav-link" id="achievements-tab" data-bs-toggle="tab" href="#achievements" role="tab">Achievements</a></li>
            <li class="nav-item"><a class="nav-link" id="technical-tab" data-bs-toggle="tab" href="#technical" role="tab">Technical Knowledge</a></li>
            <li class="nav-item"><a class="nav-link" id="skills-tab" data-bs-toggle="tab" href="#skills" role="tab">Skills</a></li>
           <li class="nav-item"><a class="nav-link" id="reports-tab" data-bs-toggle="tab" href="#reports" role="tab">View Reports</a></li>
        </ul>
        
        <div class="tab-content mt-4">

<div class="tab-pane fade show active" id="education">
    <ul class="list-group">
        <li class="list-group-item d-flex align-items-center">
            <img src="UOK.png" alt="University of Kelaniya" width="40" height="40" class="me-3">
            <div>
                <h5>Master of Business Administration (Reading)</h5>
                <p><strong><a href="https://www.kln.ac.lk/" target="_blank">University of Kelaniya, Sri Lanka</a></strong> | 2023 - Present</p>
            </div>
        </li>
        <li class="list-group-item d-flex align-items-center">
            <img src="SLTC.png" alt="Sri Lanka Technological Campus" width="40" height="40" class="me-3">
            <div>
                <h5>B.Sc (Hons) in Engineering in Electronics and Power Systems</h5>
                <p><strong><a href="https://www.sltc.ac.lk/" target="_blank">Sri Lanka Technological Campus</a></strong> | 2016 - 2020</p>
                <p><em>Best Final Year Project Award (2019) | University Gold Medalist</em></p>
            </div>
        </li>
        <li class="list-group-item d-flex align-items-center">
            <img src="Esoft.png" alt="Esoft Metro Campus" width="40" height="40" class="me-3">
            <div>
                <h5>Diploma in Information Technology with E-Commerce</h5>
                <p><strong><a href="https://www.esoft.lk/" target="_blank">Esoft Metro Campus</a></strong> | 2016</p>
            </div>
        </li>
        <li class="list-group-item d-flex align-items-center">
            <img src="Kegalu Vidyalaya.png" alt="Kegalu Vidyalaya" width="40" height="40" class="me-3">
            <div>
                <h5>GCE Advanced Level (A/L) – Physical Science Stream</h5>
                <p><strong><a href="https://www.kegaluvidyalaya.lk/" target="_blank">Kegalu Vidyalaya</a></strong> | 2015</p>
                <p><em>Presidential Scholarship Awardee – Kegalle District</em></p>
            </div>
        </li>
        <li class="list-group-item d-flex align-items-center">
            <img src="Kegalu Vidyalaya.png" alt="Kegalu Vidyalaya" width="40" height="40" class="me-3">
            <div>
                <h5>GCE Ordinary Level (O/L)</h5>
                <p><strong><a href="https://www.kegaluvidyalaya.lk/" target="_blank">Kegalu Vidyalaya</a></strong> | 2011</p>
            </div>
        </li>
        <li class="list-group-item d-flex align-items-center">
            <img src="CALSA.png" alt="Colombo Academy of Language Skills and Dramatic Art" width="40" height="40" class="me-3">
            <div>
                <h5>Spoken and Written English Graded Examinations</h5>
                <p><strong><a href="https://www.calsda.org/" target="_blank">Colombo Academy of Language Skills and Dramatic Art</a></strong> | 2005 - 2010</p>
            </div>
        </li>
    </ul>
</div>


               <div class="tab-pane fade" id="experience">
    <ul class="list-group">
        <li class="list-group-item d-flex align-items-center">
            <img src="GPV.png" alt="GPV Lanka" width="50" height="50" class="me-3">
            <div>
                <h5>NPI Engineer</h5>
                <p><strong><a href="https://www.gpv-group.com/" target="_blank">GPV Lanka (Private) Ltd</a></strong> | Mar 2024 - Present</p>
                <ul>
                    <li>Providing Technical documentation and SOPs to the production floor for manufacturing new products according to customer requirements.</li>
                    <li>Handling engineering changes of existing products.</li>
		    <li>Process Failure Mode and Effects Analysis.</li>
                    <li>Fulfilling stencil requirements for the SMT process.</li>
                    <li>Creating supporting tools for the manufacturing process.</li>
                    <li>Analyzing existing designs and technologies, conducting experiments to optimize manufacturing.</li>
                    <li>Executing product-related experiments requested by customers.</li>
                    <li>Introducing Manufacturing Execution Systems (FactoryLogix) to production.</li>
                </ul>
            </div>
        </li>

        <li class="list-group-item d-flex align-items-center">
            <img src="GPV.png" alt="GPV Lanka" width="50" height="50" class="me-3">
            <div>
                <h5>Junior NPI Engineer</h5>
                <p><strong><a href="https://www.gpv-group.com/" target="_blank">GPV Lanka (Private) Ltd</a></strong> | Feb 2021 - Mar 2024</p>
            </div>
        </li>

        <li class="list-group-item d-flex align-items-center">
            <img src="CEB.png" alt="Ceylon Electricity Board" width="50" height="50" class="me-3">
            <div>
                <h5>Trainee Engineer</h5>
                <p><strong><a href="https://www.ceb.lk/" target="_blank">Broadlands Hydro Power Project, Ceylon Electricity Board</a></strong> | Mar 2019 - Sep 2019</p>
                <ul>
                    <li>Covered feasibility designing, construction, health and safety inspections, arrival inspections, distribution, and commissioning.</li>
                    <li>Finalized 3 major projects.</li>
                </ul>
            </div>
        </li>
    </ul>
</div>



 		<div class="tab-pane fade" id="projects">
    		<h5><strong>Reducing Transformer Scrap at Visual Inspection Line</strong> (GPV Lanka (Private) Ltd)</h5>
    		<ul>
        		<li>Awarded Gold Award at National Convention on Quality and Productivity 2023.</li>
    		</ul>

    		<h5><strong>Home Automation and Control using Power Line Communication</strong></h5>
    		<ul>
        		<li>Received Best Final Year Project Student Research Award 2019.</li>
    		</ul>

    		<h5><strong>Micro Hydro Power Plant Designs</strong> (Broadlands Hydro Power Project, CEB)</h5>
    		<ul>
        	<li>Designed two micro hydro power plants (11kW and 23kW).</li>
    		</ul>

    		<h5><strong>Design for Digital Power Meter</strong></h5>
		</div>

		<div class="tab-pane fade" id="technical">
   			<ul>
        		<li>New Product Introduction processes</li>
       			<li>Engineering change management</li>
        		<li>Manufacturing Execution Systems (FactoryLogix)</li>
        		<li>Process improvement and lean manufacturing</li>
        		<li>Root Cause Analysis and corrective actions</li>
        		<li>PCB assembly and troubleshooting</li>
        		
   			</ul>
		</div>

 		<div class="tab-pane fade" id="skills">
    			<ul>
        		<li>Team Leadership</li>
        		<li>Collaboration and Teamwork</li>
        		<li>Communication skills – Sinhala and English</li>
        		<li>Project management</li>
        		<li>Critical thinking</li>
        		<li>Negotiation and conflict management</li>
        		<li>Ability to work under pressure</li>
        		<li>Effective public relations</li>
        		<li>High ethical standards</li>
    			</ul>
		</div>

        
		<div class="tab-pane fade" id="leadership">
    
    <!-- Leo Movement -->
    <h5><img src="Leo.png" alt="Leo Club" width="70" height="70" class="me-2"> <strong>Leo Movement</strong></h5>
    <ul class="timeline">
        <li><strong>2024</strong> - <a href="https://www.leomd306.org/" target="_blank">Multiple District President – Leo Multiple District 306 Sri Lanka & Maldives</a></li>
        <li><strong>2021</strong> - <a href="https://www.leodistrict306a2.org/" target="_blank">District President – Leo District 306 A2</a></li>
        <li><strong>2020</strong> - District Vice President – Leo District 306 A2, Director – Leo Multiple District 306 Sri Lanka</li>
        <li><strong>2019</strong> - Chairman – Orientation Committee, Chairman – Jeewana Yathra (Multi-Service Mega Project)</li>
        <li><strong>2018</strong> - Region Director – Leo District 306 A2</li>
        <li><strong>2017</strong> - Youth Director – Leo District 306 A2</li>
        <li><strong>2016</strong> - <a href="https://www.lionsclubs.org/en"target="_blank">Volunteer – Lions ISSAME Forum</a></li>
    </ul>

    <!-- Sri Lanka Technological Campus -->
    <h5><img src="SLTC.png" alt="Sri Lanka Technological Campus" width="50" height="50" class="me-2"> <strong>Sri Lanka Technological Campus</strong></h5>
    <ul class="timeline">
        <li><strong>2020</strong> - Class Representative (Class of 2019), Chapter Advisor – IEEE Computer Society</li>
        <li><strong>2019</strong> - Event Coordinator – IEEE Student Branch, Treasurer – Model United Nations</li>
        <li><strong>2018</strong> - Lead Operations – University Students’ Enterprise</li>
        <li><strong>2017</strong> - Logistics Team Member – INSYS 2017 (International Symposium on Industrial Systems)</li>
        <li><strong>2016</strong> - Charter President – Leo Club of Sri Lanka Technological Campus, Vice President – Student Interactive Society</li>
    </ul>

    <!-- School (Kegalu Vidyalaya) -->
    <h5><img src="Kegalu Vidyalaya.png" alt="Kegalu Vidyalaya" width="50" height="50" class="me-2"> <strong>School (Kegalu Vidyalaya)</strong></h5>
    <ul class="timeline">
        <li><strong>2014</strong> - <strong>School Head Prefect</strong>, Chairman – Walk with Vidyalions (First-ever parade & walk), Student Mentor – Science Society, Committee Member – Buddhist Association</li>
        <li><strong>2013</strong> - <a href="https://thecommonwealth.org/chogm"target="_blank">Volunteer – Commonwealth Heads of Government Meeting (CHOGM)</a>, President – Drama & Theatre Society</li>
        <li><strong>2012</strong> - Chairman – Ranga Bihi Dora (First-ever drama & theatre show), Secretary – Non-Alcoholic Society</li>
    </ul>

    <!-- IEEE & Other Memberships -->
    <h5><img src="IEEE.png" alt="IEEE" width="50" height="50" class="me-2"> <strong>IEEE & Other Memberships</strong></h5>
    <ul class="timeline">
        <li><strong>2020</strong> - Logistics Lead – <a href="https://www.ieee.org/" target="_blank">IEEE Young Professionals</a>, Member – IEEE Computer Society & IEEE Power and Energy Society</li>
        <li><strong>2019</strong> - Treasurer – IEEE Student, Young Professionals & Women in Engineering Conference</li>
        <li><strong>2018</strong> - Logistics Team Member – IEEE Conference</li>
        <li><strong>2010</strong> - Representative – <a href="https://slmun.org/" target="_blank">National Youth Model United Nations</a></li>
        <li><strong>2008</strong> - Member – <a href="https://www.redcross.lk/" target="_blank">Red Cross Sri Lanka</a></li>
        <li><strong>2007</strong> - Member – Colombo Academy of Language Skills & Dramatic Art</li>
    </ul>
</div>


            <div class="tab-pane fade" id="achievements">
    <h5><strong>GPV Lanka (Private) Ltd</strong></h5>
    <ul>
        <li><strong>2023</strong> – Gold Award – National Convention on Quality and Productivity</li>
    </ul>

    <h5><strong>Sri Lanka Technological Campus</strong></h5>
    <ul>
        <li><strong>2020</strong> – Eng. Ranjith Rubasinghe University Award for <strong>Overall Excellence</strong></li>
        <li><strong>2020</strong> – Gold Medal for outstanding contribution to university life</li>
        <li><strong>2019</strong> – Best Final Year Project Student Research Award</li>
        <li><strong>2017</strong> – Winner – EL Mistico Debate Competition</li>
        <li><strong>2016</strong> – Presidential Scholarship – Kegalle District</li>
    </ul>

    <h5><strong>School Achievements</strong></h5>
    <ul>
        <li><strong>2013</strong> – Golden Award – Head Prefect, <strong>Best Actor</strong> – Ranga Bihi Dora</li>
        <li><strong>2012</strong> – Winner – National Science Foundation Drama Competition</li>
        <li><strong>2010</strong> – Winner – Inter-School Weight Lifting</li>
    </ul>

    <h5><strong>Other Achievements</strong></h5>
    <ul>
        <li><strong>2020</strong> – <strong>Leo of the Year</strong> – Leo District 306 A2 Conference</li>
        <li><strong>2019</strong> – Winner – Most Outstanding Service Project – Jeewana Yathra (Leo Multiple Awards)</li>
        <li><strong>2018</strong> – Best Camper Male – Leo Youth Camp, Leo District 306 A2</li>
        <li><strong>2017</strong> – 1st Runner-up – Best New Leo (Leo Multiple Awards, Sri Lanka)</li>
        <li><strong>2017</strong> – Winner – Most Outstanding New Club President (Leo District 306 A2)</li>
    </ul>
</div>

<div class="tab-pane fade" id="reports">
    <ul class="list-group">
        
	<li class="list-group-item">
            <a href="01.Project Report for National Convention on Quality and Productivity - 2022.pdf" target="_blank">
                <i class="fas fa-file-pdf"></i> National Convention on Quality and Productivity - Project Report (2022)
            </a>
        </li>
	<li class="list-group-item">
            <a href="02.Annual Report - Leo District 306 A2.pdf" target="_blank">
                <i class="fas fa-file-pdf"></i> Annual Report - Leo District 306 A2
            </a>
        </li>
	<li class="list-group-item">
            <a href="03.Final Year Project - Final Report - SLTC - 2020.pdf" target="_blank">
                <i class="fas fa-file-pdf"></i> Final Year Project - SLTC (2020)
            </a>
        </li>
	<li class="list-group-item">
            <a href="04.Leo of the Year - Leo District 306 A2 - 2019_20.pdf" target="_blank">
                <i class="fas fa-file-pdf"></i> Leo of the Year Report - Leo District 306 A2 (2019/2020)
		</a>
        </li>
	  
        
    </ul>
</div>


    </div>
 </div>

<div id="bottomBannerCarousel" class="carousel slide mt-5" data-bs-ride="carousel">
    <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="banner1.jpg" class="d-block w-100" alt="Banner 1">
        </div>
        <div class="carousel-item">
            <img src="banner2.jpg" class="d-block w-100" alt="Banner 2">
        </div>
        <div class="carousel-item">
            <img src="banner3.jpg" class="d-block w-100" alt="Banner 3">
        </div>
    </div>

    <!-- Previous Button -->
    <button class="carousel-control-prev" type="button" data-bs-target="#bottomBannerCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>

    <!-- Next Button -->
    <button class="carousel-control-next" type="button" data-bs-target="#bottomBannerCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
    </button>
</div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
