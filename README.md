
/recruitment-website
  ├── index.html
  ├── style.css
  ├── script.js
  ├── images/ (store your images here)
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Study Abroad Recruitment Agency</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <div class="logo">
        <h1>StudyLink Tanzania</h1>
      </div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#testimonials">Testimonials</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <h2>Your Gateway to Global Education</h2>
      <p>We help Tanzanian students achieve their dreams of studying abroad.</p>
      <a href="#contact" class="btn">Get Started</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-list">
        <div class="service-item">
          <i class="fas fa-university"></i>
          <h3>University Admissions</h3>
          <p>Assistance with applications to top universities worldwide.</p>
        </div>
        <div class="service-item">
          <i class="fas fa-passport"></i>
          <h3>Visa Processing</h3>
          <p>Expert guidance for student visa applications.</p>
        </div>
        <div class="service-item">
          <i class="fas fa-book-open"></i>
          <h3>Scholarship Guidance</h3>
          <p>Help in finding and applying for scholarships.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="about">
    <div class="container">
      <h2>About Us</h2>
      <p>StudyLink Tanzania is a leading recruitment agency dedicated to helping students from Tanzania pursue their educational dreams abroad. With years of experience, we provide personalized guidance and support throughout the entire process.</p>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="testimonials">
    <div class="container">
      <h2>What Our Clients Say</h2>
      <div class="testimonial-list">
        <div class="testimonial-item">
          <p>"StudyLink helped me secure admission to my dream university in the UK. Their support was invaluable!"</p>
          <h3>- Jane Doe</h3>
        </div>
        <div class="testimonial-item">
          <p>"The visa process was seamless thanks to StudyLink. Highly recommend their services!"</p>
          <h3>- John Smith</h3>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <form id="contact-form">
        <input type="text" id="name" placeholder="Your Name" required>
        <input type="email" id="email" placeholder="Your Email" required>
        <textarea id="message" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2023 StudyLink Tanzania. All rights reserved.</p>
      <div class="social-links">
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
}

/* Header */
header {
  background: #333;
  color: #fff;
  padding: 20px 0;
}

header .logo h1 {
  margin: 0;
  font-size: 24px;
}

header nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: flex-end;
}

header nav ul li {
  margin-left: 20px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

/* Hero Section */
.hero {
  background: url('images/hero-bg.jpg') no-repeat center center/cover;
  color: #fff;
  padding: 100px 0;
  text-align: center;
}

.hero h2 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 20px;
  margin-bottom: 30px;
}

.hero .btn {
  background: #007BFF;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

/* Services Section */
.services {
  padding: 60px 0;
  text-align: center;
}

.services h2 {
  margin-bottom: 40px;
}

.service-list {
  display: flex;
  justify-content: space-between;
}

.service-item {
  flex: 1;
  margin: 0 10px;
  padding: 20px;
  background: #f4f4f4;
  border-radius: 5px;
}

.service-item i {
  font-size: 40px;
  margin-bottom: 20px;
}

/* About Us Section */
.about {
  padding: 60px 0;
  text-align: center;
  background: #f4f4f4;
}

/* Testimonials Section */
.testimonials {
  padding: 60px 0;
  text-align: center;
}

.testimonial-list {
  display: flex;
  justify-content: space-between;
}

.testimonial-item {
  flex: 1;
  margin: 0 10px;
  padding: 20px;
  background: #f4f4f4;
  border-radius: 5px;
}

/* Contact Section */
.contact {
  padding: 60px 0;
  text-align: center;
}

.contact form {
  max-width: 600px;
  margin: 0 auto;
}

.contact input, .contact textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.contact .btn {
  background: #007BFF;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

/* Footer */
footer {
  background: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

footer .social-links a {
  color: #fff;
  margin: 0 10px;
  font-size: 20px;
}
// Simple form submission handling
document.getElementById('contact-form').addEventListener('submit', function (e) {
  e.preventDefault();
  alert('Thank you for contacting us! We will get back to you soon.');
  document.getElementById('contact-form').reset();
});
