# My-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
  <title>My Portfolio</title>
  <style>
    /* ==== Global Styles ==== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      max-width: 100%;
      display: block;
    }

    /* ==== Header ==== */
    header {
      background: #222;
      color: #fff;
      padding: 1.5rem 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: 0 auto;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav h1 {
      font-size: 1.5rem;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      gap: 1.5rem;
      list-style: none;
    }

    nav ul li a {
      color: #fff;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #00bcd4;
    }
    /* ==== CONTACT SECTION ==== */
#say-hello {
  background: linear-gradient(to right, #007991, #78ffd6);
  color: #004b5a;
  padding: 60px 0;
  font-family: "Poppins", sans-serif;
}

/* Columns */
#say-hello .col-lg-6 {
  padding: 40px;
}

/* ===== HEADINGS ===== */
#say-hello h2 {
  font-size: 2rem;
  font-weight: 800;
  letter-spacing: 1px;
  margin-bottom: 25px;
  text-transform: uppercase;
  color: #ffffff; /* White headings */
}

/* ===== PARAGRAPHS ===== */
#say-hello p,
#say-hello ul li {
  font-size: 1.05rem;
  color: #f5fdfd;
}

/* ===== FORM FIELDS ===== */
#say-hello .form-control {
  border: none;
  border-radius: 8px;
  background: linear-gradient(to right, #e0ffff, #c2f5eb); /* soft gradient */
  color: #004b5a;
  padding: 12px 15px;
  font-size: 1rem;
  transition: all 0.3s ease;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

#say-hello .form-control:focus {
  background: linear-gradient(to right, #78ffd6, #007991);
  color: #fff;
  box-shadow: 0 0 8px rgba(0, 121, 145, 0.5);
  border: none;
}

#say-hello .form-control::placeholder {
  color: #007991;
  opacity: 0.8;
}

/* ===== SUBMIT BUTTON ===== */
#say-hello button[type="submit"] {
  background: #fff;
  color: #007991;
  font-weight: 700;
  border: none;
  border-radius: 30px;
  padding: 12px 35px;
  transition: all 0.3s ease;
  text-transform: uppercase;
  box-shadow: 0 4px 12px rgba(0, 121, 145, 0.3);
}

#say-hello button[type="submit"]:hover {
  background: linear-gradient(to right, #007991, #78ffd6);
  color: #fff;
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0, 121, 145, 0.4);
}

/* ===== RIGHT COLUMN (EMAIL INFO) ===== */
#say-hello .bg-dark {
  background: rgba(255, 255, 255, 0.15);
  border-radius: 10px;
  color: #ffffff;
}

#say-hello ul {
  list-style: none;
  padding-left: 0;
}

#say-hello ul li strong {
  color: #ffffff;
}

/* ===== LINKS ===== */
#say-hello a {
  color: #ffffff;
  font-weight: 600;
  text-decoration: underline;
  transition: all 0.3s ease;
}

#say-hello a:hover {
  color: #004b5a;
  text-decoration: none;
}

/* ===== SOCIAL BUTTONS ===== */
#say-hello .btn-outline-light {
  border-color: #fff;
  color: #fff;
  transition: all 0.3s ease;
}

#say-hello .btn-outline-light:hover {
  background: linear-gradient(to right, #007991, #78ffd6);
  color: #fff;
  border-color: transparent;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 991px) {
  #say-hello .col-lg-6 {
    padding: 25px;
  }
}


    /* ==== Hero Section ==== */
    .hero {
      background: linear-gradient(to right, #007991, #78ffd6);
      color: #fff;
      text-align: center;
      padding: 6rem 1rem;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      max-width: 600px;
      margin: 0 auto 2rem;
    }

    .btn {
      background: #fff;
      color: #007991;
      padding: 0.75rem 1.5rem;
      border-radius: 25px;
      font-weight: bold;
      transition: 0.3s ease;
      display: inline-block;
    }

    .btn:hover {
      background: #007991;
      color: #fff;
      border: 2px solid #fff;
    }

    /* ==== About Section ==== */
    .about {
      padding: 4rem 0;
      background: #fff;
    }

    .about-content {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      align-items: center;
    }

    .about img {
      flex: 1 1 30px;
      border-radius: 10px;
      width: 45px;
      height: 230px;
    }

    .about-text {
      flex: 2 1 400px;
    }

    .about-text h2 {
      margin-bottom: 1rem;
      color: #007991;
    }

    /* ==== Projects ==== */
    .projects {
      background: #f0f0f0;
      padding: 4rem 0;
    }

    .projects h2 {
      text-align: center;
      margin-bottom: 2rem;
      color: #007991;
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .project {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .project:hover {
      transform: translateY(-5px);
    }

    .project img {
      border-radius: 10px;
      margin-bottom: 1rem;
    }

    .project h3 {
      margin-bottom: 0.5rem;
      color: #007991;
    }

    /* ==== Contact ==== */
    .contact {
      padding: 4rem 0;
      background: #fff;
      text-align: center;
    }

    .contact h2 {
      margin-bottom: 1rem;
      color: #007991;
    }

    .contact p {
      margin-bottom: 1.5rem;
    }

    .contact a.btn {
      background: #007991;
      color: #fff;
    }

    .contact a.btn:hover {
      background: #005f63;
    }

    /* ==== Footer ==== */
    footer {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
      font-size: 0.9rem;
    }

    /* ==== Responsive ==== */
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        text-align: center;
        gap: 1rem;
      }

      .hero h2 {
        font-size: 2rem;
      }

      .about-content {
        flex-direction: column;
        text-align: center;
        width: 50px;
        height: 50px;
      }
    }
  </style>
</head>
<body>

  <!-- ==== Header ==== -->
  <header>
    <div class="container">
      <nav>
        <h1>MyPortfolio</h1>
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- ==== Hero ==== -->
  <section class="hero" id="hero">
    <h2>Hi, I'm roshni prajapati</h2>
    <p>I'm a web developer passionate about creating clean, responsive, and user-friendly websites using modern technologies.</p>
    <a href="#projects" class="btn">View My Work</a>
  </section>

  <!-- ==== About ==== -->
  <section class="about" id="about">
    <div class="container about-content">
      <img src="r1.jpeg" alt="About Me">
      <div class="about-text">
        <h2>About Me</h2>
        <p>Hello! I'm roshni, a front-end developer who loves turning ideas into beautiful digital experiences. I specialize in HTML, CSS, and responsive design. When I’m not coding, I enjoy photography and hiking.</p>
      </div>
    </div>
    <section class="section section-no-border bg-color-light m-0">
					<div class="container">
						<div class="row">
							<div class="col">

								<div
									class="custom-box-details bg-color-light custom-box-shadow-1 col-lg-6 ms-5 mb-5 mb-lg-4 float-end clearfix">
									<h4>Personal Details</h4>
									<div class="row">
										<div class="col-md-6">
											<ul class="custom-list-style-1 p-0 mb-0">
												<li>
													<span class="text-color-dark">Birthday:</span>
													<span class="custom-text-color-2">2005 sep 8</span>
												</li>
												<li>
													<span class="text-color-dark">Marital:</span>
													<span class="custom-text-color-2">Unmarried</span>
												</li>
												<li>
													<span class="text-color-dark">Nationality:</span>
													<span class="custom-text-color-2">Indian</span>
												</li>
											</ul>
										</div>
										<div class="col-md-6">
											<ul class="custom-list-style-1 p-0 mb-0">
												<li>
													<span class="text-color-dark">Skype:</span>
													<span class="custom-text-color-2"><a class="custom-text-color-2"
															href="skype:ptlshubham?chat" target="_blank">Roshni Prajapati</a></span>
												</li>
												<li>
													<span class="text-color-dark">PHONE:</span>
													<span class="custom-text-color-2"><a class="custom-text-color-2"
															href="tel:+91 81419 52604" target="_blank">+91
														83209-72941</a></span>
												</li>
												<li>
													<span class="text-color-dark">EMAIL:</span>
													<span class="custom-text-color-2"><a class="custom-text-color-2"
															href="mailto:ptlshubham@gmail.com"
															target="_blank">roshniprajapati809@gmail.com</a></span>
												</li>
											</ul>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</section>
  </section>

  <!-- ==== Projects ==== -->
  <section class="projects" id="projects">
    <div class="container">
      <h2>My Projects</h2>
      <div class="project-grid">
        <div class="project">
          <img src="https://via.placeholder.com/400x250" alt="Project 1">
          <h3>Portfolio Website</h3>
          <p>A clean and modern personal portfolio website built with HTML and CSS.</p>
        </div>
        <div class="project">
          <img src="https://via.placeholder.com/400x250" alt="Project 2">
          <h3>Landing Page</h3>
          <p>A responsive product landing page layout showcasing features and pricing.</p>
        </div>
        <div class="project">
          <img src="https://via.placeholder.com/400x250" alt="Project 3">
          <h3>Blog Layout</h3>
          <p>A simple blog homepage designed with CSS Grid and Flexbox.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ==== Contact ==== -->
  <section class="contact" id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>If you'd like to work together or just say hi, feel free to reach out!</p>
      <a href="mailto:roshniprajapati809gmail.com" class="btn">Email Me</a>
    </div>
  </section>
  
    <!-- Contact Section -->
<div class="container-fluid py-5 bg-color-primary text-light" id="say-hello">
  <div class="row">
    
    <!-- Left Column - Contact Form -->
    <div class="col-lg-6 p-5">
      <h2 class="text-uppercase font-weight-bold mb-4">Contact Me</h2>
      
      <form id="contactForm" action="php/contact-form.php" method="post" class="contact-form">
        
        <!-- Success & Error Messages -->
        <div class="alert alert-success d-none mt-3" id="contactSuccess">
          <strong>Success!</strong> Your message has been sent.
        </div>
        <div class="alert alert-danger d-none mt-3" id="contactError">
          <strong>Error!</strong> There was an error sending your message.
          <span id="mailErrorMessage"></span>
        </div>

        <!-- Form Fields -->
        <div class="mb-3">
          <input type="text" class="form-control" name="name" id="name" placeholder="Your Name *" required>
        </div>

        <div class="mb-3">
          <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject *" required>
        </div>

        <div class="mb-3">
          <textarea class="form-control" name="message" id="message" rows="6" placeholder="Your Message *" required></textarea>
        </div>

        <div class="text-center">
          <button type="submit" class="btn btn-light text-uppercase fw-bold px-4 py-2">
            Send Message
          </button>
        </div>
      </form>
    </div>

    <!-- Right Column - Email Me -->
    <div class="col-lg-6 bg-dark p-5">
      <h2 class="text-uppercase font-weight-bold mb-4 text-light">Email Me</h2>
      <p class="lead mb-4 text-light">
        Feel free to reach out directly through email or social platforms.
      </p>

      <ul class="list-unstyled text-light">
        <li><strong>Email:</strong> <a href="mailto:roshniprajapati809@example.com" class="text-light text-decoration-underline">roshniprajapati809@gmail.com</a></li>
        <li><strong>Phone:</strong> +91 8320972941</li>
      </ul>

      <div class="mt-4">
        <a href="#" class="btn btn-outline-light btn-sm me-2" style="color:#222">LinkedIn</a>
        <a href="#" class="btn btn-outline-light btn-sm me-2" style="color:#222">Twitter</a>
        <a href="#" class="btn btn-outline-light btn-sm" style="color:#222">GitHub</a>
      </div>
    </div>

  </div>
</div>

 <div class="form-content">
 
  <!-- ==== Footer ==== -->
  <footer>
    <p>&copy; 2025 reserved</p>
  </footer>

</body>
</html>

