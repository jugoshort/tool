<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>THE_JUGUNOO</title>

  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(135deg, #e0f7fa, #ffffff);
      color: #2c3e50;
    }

    header {
      background: linear-gradient(135deg, #0d47a1, #1976d2);
      color: #fff;
      text-align: center;
      padding: 40px 0;
      font-size: 3rem;
      font-weight: 700;
      letter-spacing: 2px;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.5);
    }

    .intro {
      text-align: center;
      padding: 60px 20px;
      background: #ffffff;
      margin: 40px auto;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      width: 90%;
      max-width: 1000px;
      opacity: 0;
      transform: translateY(50px);
      transition: all 0.8s ease;
    }

    .intro h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #0d47a1;
      font-weight: 700;
    }

    .intro p {
      font-size: 1.2rem;
      color: #555;
      line-height: 1.6;
    }

    .courses {
      text-align: center;
      margin: 50px 20px;
      opacity: 0;
      transform: translateY(50px);
      transition: all 0.8s ease;
    }

    .courses h2 {
      font-size: 2.3rem;
      margin-bottom: 30px;
      color: #0d47a1;
      font-weight: 700;
    }

    .course-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }

    .course {
      background-color: #ffffff;
      padding: 30px;
      width: 300px;
      border-radius: 18px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      transition: all 0.4s ease;
      cursor: pointer;
      text-align: left;
    }

    .course:hover {
      transform: translateY(-10px);
      background: linear-gradient(135deg, #e3f2fd, #ffffff);
    }

    .course-title {
      font-size: 1.6rem;
      color: #1565c0;
      margin-bottom: 12px;
      font-weight: 600;
    }

    .course-description {
      font-size: 1rem;
      color: #666;
      line-height: 1.5;
    }

    footer {
      background: linear-gradient(135deg, #0d47a1, #1976d2);
      color: white;
      text-align: center;
      padding: 40px 20px;
      margin-top: 50px;
      opacity: 0;
      transform: translateY(50px);
      transition: all 0.8s ease;
      font-size: 1rem;
    }

    footer h3 {
      margin-bottom: 15px;
      font-size: 2rem;
      font-weight: 700;
    }

    footer p {
      margin-top: 8px;
      line-height: 1.8;
    }

    /* Style for the About Button */
    .about-btn {
      display: inline-block;
      background-color: #0d47a1;
      color: #fff;
      padding: 15px 30px;
      margin-top: 30px;
      font-size: 1.2rem;
      font-weight: 600;
      border-radius: 50px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .about-btn:hover {
      background-color: #1976d2;
    }
  </style>
</head>

<body>

<header id="header">
  THE_JUGUNOO
</header>

<main>
  <section class="intro" id="intro">
    <h2>Welcome to THE_JUGUNOO</h2>
    <p>Your one-stop platform to master YouTube, Instagram, and Social Media marketing professionally.</p>
    <!-- About Button -->
    <a href="Desktop/ABOUT.HTML" class="about-btn">About Us</a>
  </section>

  <section class="courses" id="courses">
    <h2>Our Courses</h2>
    <div class="course-list">
      <div class="course">
        <div class="course-title">
          <a href="Desktop/yt.html">YouTube Full Course</a>
        </div>
        <div class="course-description">
          Learn how to create, grow and monetize your YouTube channel from scratch. SEO, Content Creation, Monetization tricks included.
        </div>
      </div>

      <div class="course">
        <div class="course-title">
          <a href="Desktop/ins.html">Instagram Full Course</a>
        </div>
        <div class="course-description">
          Master Instagram growth, reels strategy, algorithm understanding, brand collaborations, and build your influence.
        </div>
      </div>

      <div class="course">
        <div class="course-title">
          <a href="Desktop/sm.html"> Social Media Marketing</a>
        </div>
        <div class="course-description">
          Learn to handle Facebook, Twitter, LinkedIn, Pinterest professionally. Ads setup, organic reach boost & client management included.
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about-section" class="intro">
    <h2>About THE_JUGUNOO</h2>
    <p>THE_JUGUNOO is dedicated to empowering individuals to master social media marketing through hands-on courses and expert-led instruction. Our goal is to help you grow your digital presence, whether you're a beginner or an experienced marketer.</p>
  </section>
</main>

<footer id="footer">
  <h3>Contact Us</h3>
  <p><strong>Email:</strong> THEJUGUNOO046@GMAIL.COM</p>
  <p><strong>Phone:</strong> +91-7388877321</p>
  <p><strong>Address:</strong> Gorakhpur, Uttar Pradesh, India</p>
</footer>

<script>
  window.addEventListener('scroll', () => {
    const intro = document.getElementById('intro');
    const courses = document.getElementById('courses');
    const footer = document.getElementById('footer');

    const introPosition = intro.getBoundingClientRect().top;
    const coursesPosition = courses.getBoundingClientRect().top;
    const footerPosition = footer.getBoundingClientRect().top;
    const screenPosition = window.innerHeight / 1.3;

    if (introPosition < screenPosition) {
      intro.style.opacity = '1';
      intro.style.transform = 'translateY(0px)';
    }

    if (coursesPosition < screenPosition) {
      courses.style.opacity = '1';
      courses.style.transform = 'translateY(0px)';
    }

    if (footerPosition < screenPosition) {
      footer.style.opacity = '1';
      footer.style.transform = 'translateY(0px)';
    }
  });

  document.addEventListener('DOMContentLoaded', () => {
    const intro = document.getElementById('intro');
    const courses = document.getElementById('courses');
    const footer = document.getElementById('footer');

    intro.style.opacity = '0';
    intro.style.transform = 'translateY(50px)';
    courses.style.opacity = '0';
    courses.style.transform = 'translateY(50px)';
    footer.style.opacity = '0';
    footer.style.transform = 'translateY(50px)';
  });
</script>

</body>
</html>
