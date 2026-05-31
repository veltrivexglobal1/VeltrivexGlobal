<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Veltrivex Global - Learn & Earn Certificates</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; background-color: #0e1a2b; color: #fff; }
    header { background-color: #1c2b4a; padding: 15px 30px; display: flex; justify-content: space-between; align-items: center; }
    header img { height: 60px; }
    nav a { color: #fff; margin: 0 10px; text-decoration: none; font-weight: 500; }
    .hero { text-align: center; padding: 60px 20px; background: linear-gradient(180deg, #1c2b4a, #0e1a2b); }
    .hero img { height: 100px; }
    .hero h2 { color: #f5b700; font-size: 32px; }
    .hero p { font-size: 18px; color: #ccc; }
    .courses { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; padding: 40px; }
    .course-card { background-color: #16233b; border-radius: 10px; padding: 20px; box-shadow: 0 0 10px rgba(0,0,0,0.3); }
    .course-card h3 { color: #f5b700; }
    .btn { display: inline-block; margin-top: 10px; padding: 10px 15px; border-radius: 5px; text-decoration: none; font-weight: bold; }
    .btn-blue { background-color: #007bff; color: #fff; }
    .btn-gold { background-color: #f5b700; color: #000; }
    .certificate-section, .quiz-section, .auth-section, .about-section { background-color: #1c2b4a; padding: 40px; text-align: center; }
    input, button { padding: 10px; margin: 5px; border-radius: 5px; border: none; }
    footer { background-color: #1c2b4a; text-align: center; padding: 20px; font-size: 14px; color: #ccc; }
    footer img { height: 40px; }
    .badge { margin-top: 20px; font-size: 18px; color: #f5b700; font-weight: bold; }
  </style>
</head>
<body>
  <header>
    <img src="veltrivex-logo.png" alt="Veltrivex Global Logo">
    <nav>
      <a href="#">Home</a>
      <a href="#courses">Courses</a>
      <a href="#certificate">Certificates</a>
      <a href="#quiz">Quizzes</a>
      <a href="#auth">Register/Login</a>
      <a href="#about">About Us</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <img src="veltrivex-logo.png" alt="Veltrivex Global Logo">
    <h2>Empowering Your Learning Journey</h2>
    <p>Professional courses and certifications by <strong>Abubakar Muhammad</strong> & <strong>Ahmad Suleiman Bello</strong>.</p>
    <a href="#courses" class="btn btn-blue">Browse Courses</a>
    <a href="#certificate" class="btn btn-gold">Subscribe to Certify</a>
  </section>

  <section id="courses" class="courses">
    <div class="course-card">
      <h3>AI Fundamentals</h3>
      <p>Instructor: Abubakar Muhammad</p>
      <p>₦10,000 | 4.5★</p>
      <a href="#" class="btn btn-blue">View PDF</a>
      <a href="#quiz" class="btn btn-gold">Start Quizzes</a>
    </div>
    <div class="course-card">
      <h3>Python Programming (Hausa & English)</h3>
      <p>Instructor: Ahmad Suleiman Bello</p>
      <p>₦10,000 | 5.0★</p>
      <a href="#" class="btn btn-blue">View PDF</a>
      <a href="#quiz" class="btn btn-gold">Start Quizzes</a>
    </div>
    <div class="course-card">
      <h3>Frontend Development</h3>
      <p>Instructor: Veltrivex Global Team</p>
      <p>₦6,200 | New</p>
      <a href="#" class="btn btn-blue">View PDF</a>
      <a href="#quiz" class="btn btn-gold">Start Quizzes</a>
    </div>
  </section>

  <section id="quiz" class="quiz-section">
    <h2>Course Quizzes</h2>
    <p>Answer 10 quizzes to earn your badge!</p>
    <button onclick="takeQuiz()" class="btn btn-blue">Take Quiz</button>
    <p id="quizResult"></p>
    <p id="badge" class="badge"></p>
  </section>

  <section id="certificate" class="certificate-section">
    <img src="veltrivex-logo.png" alt="Veltrivex Global Logo" style="height:80px;">
    <h2>Certificate Verification</h2>
    <p>Subscribe to our YouTube channel to earn free course certificates!</p>
    <form id="verifyForm">
      <input type="email" id="email" placeholder="Enter your email" required>
      <input type="text" id="screenshot" placeholder="Paste YouTube screenshot link" required>
      <button type="submit" class="btn btn-blue">Verify Subscription</button>
    </form>
    <p id="result"></p>
  </section>

  <section id="auth" class="auth-section">
    <h2>Register / Login</h2>
    <div>
      <h3>Create Account</h3>
      <form id="registerForm">
        <input type="text" id="regName" placeholder="Full Name" required>
        <input type="email" id="regEmail" placeholder="Email" required>
        <input type="password" id="regPass" placeholder="Password" required>
        <button type="submit" class="btn btn-blue">Register</button>
      </form>
    </div>
    <div>
      <h3>Login</h3>
      <form id="loginForm">
        <input type="email" id="logEmail" placeholder="Email" required>
        <input type="password" id="logPass" placeholder="Password" required>
        <button type="submit" class="btn btn-gold">Login</button>
      </form>
    </div>
    <p id="authResult"></p>
  </section>

  <section id="about" class="about-section">
    <h2>About Us</h2>
    <p><strong>Abubakar Muhammad</strong> – CEO & Founder</p>
    <p>Email: veltrivexglobal@gmail.com | Phone: +234 704 336 7956</p>
    <p><strong>Ahmad Suleiman Bello</strong> – Co-Founder</p>
    <p>Email: ahmadthecyberian@gmail.com | Phone: +234 816 292 2267</p>
    <p>Veltrivex Global is dedicated to empowering learners with professional courses, badges, and certificates through innovative digital education.</p>
  </section>

  <footer id="contact">
    <img src="veltrivex-logo.png" alt="Veltrivex Global Logo">
    <p>Contact: +234 704 336 7956 | +234 816 292 2267 | veltrivexglobal@gmail.com</p>
    <p>© 2026 Veltrivex Global. All rights reserved.</p>
  </footer>

  <script>
    let quizCount = 0;
    function takeQuiz() {
      quizCount++;
      const quizResult = document.getElementById('quizResult');
      quizResult.innerHTML = `✅ Quiz ${quizCount} completed successfully!`;
      if (quizCount >= 10) {
        document.getElementById('badge').innerHTML = "🎉 Congratulations! You earned a Badge. Download now!";
      }
    }

    document.getElementById('
