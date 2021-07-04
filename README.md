<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Fylo landing page with dark theme and features grid</title>
  		<link rel="stylesheet" href="style.css">

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
 
  }
  
  
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>>
<body class="dark-theme">
  <header>
    <img src="logo.svg" alt="" class="logo">
    <nav>
      <a href="#">Features</a>
      <a href="#">Team</a>
      <a href="#">Sign In</a>
    </nav>
  </header>

  <section class="intro-container">
    <div class="intro">
      <img src="illustration-intro.png" alt="">
      <h1>
        All your files in one secure location, accessible anywhere.
      </h1>
      <p>
        Fylo stores all your most important files in one secure location. Access them wherever
        you need, share and collaborate with friends family, and co-workers.
      </p>
      <button class="get-started" type="button" name="button">
        Get Started
      </button>
    </div>

  </section>

  <section class="feature-grid">
    <div class="feature-square">
      <img src="icon-access-anywhere.svg" alt="">
      <h3>
        Access your files, anywhere
      </h3>
      <p>
        The ability to use a smartphone, tablet, or computer to access your account means your
        files follow you everywhere.
      </p>
    </div>
    <div class="feature-square">
      <img src="icon-security.svg" alt="">
      <h3>Security you can trust</h3>
      <p>
        2-factor authentication and user-controlled encryption are just a couple of the security
        features we allow to help secure your files.
      </p>
    </div>
    <div class="feature-square">
      <img src="icon-collaboration.svg" alt="">
      <h3>Real-time collaboration</h3>
      <p>
        Securely share files and folders with friends, family and colleagues for live collaboration.
        No email attachments required.
      </p>
    </div>
    <div class="feature-square">
      <img src="icon-any-file.svg" alt="">
      <h3>Store any type of file</h3>
      <p>
        Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all
        file types to be securely stored and shared.
      </p>
    </div>

  </section>

  <section class="half-img-half-text">
    <div class="section-image">
      <img src="illustration-stay-productive.png" alt="">
    </div>
    <div class="section-content">
      <h1>Stay productive, wherever you are</h1>
      <p>
        Never let location be an issue when accessing your files. Fylo has you covered for all of your file
        storage needs.
      </p>
      <p>
        Securely share files and folders with friends, family and colleagues for live collaboration. No email
        attachments required.
      </p>
      <a href="#"><span class="link-decor">See how Fylo works <img src="icon-arrow.svg"></span></a>
    </div>

  </section>

  <section class="testimonials">

    <div class="testimonial-square first">
      <p>
        Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
        become a well-oiled collaboration machine.
      </p>
      <div class="testimonial-profile">
        <img src="profile-1.jpg" alt="">
        <div class="author">
          <h4>Satish Patel</h4>
          <p>Founder & CEO, Huddle</p>
        </div>
      </div>
    </div>
    <div class="testimonial-square">
      <p>
        Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
        become a well-oiled collaboration machine.
      </p>
      <div class="testimonial-profile">
        <img src="profile-2.jpg" alt="">
        <div class="author">
          <h4>Bruce McKenzie</h4>
          <p>Founder & CEO, Huddle</p>
        </div>
      </div>
    </div>
    <div class="testimonial-square">
      <p>
        Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has
        become a well-oiled collaboration machine.
      </p>
      <div class="testimonial-profile">
        <img src="profile-3.jpg" alt="">
        <div class="author">
          <h4>Iva Boyd</h4>
          <p>Founder & CEO, Huddle</p>
        </div>
      </div>
    </div>


  </section>

  <section class="call-to-action">
    <div class="section-content">
      <h1>Get early access today</h1>
      <p>
        It only takes a minute to sign up and our free starter tier is extremely generous. If you have any
        questions, our support team would be happy to help you.
      </p>
      <input type="email" name="" value="">
      <button type="button" name="button" class="get-started">Get Started For Free</button>
    </div>
  </section>


  <footer>

    <div class="footer-header">
      <img src="logo.svg" alt="" class="logo">

    </div>
    <div class="col-1">
      <div class="icon-text">
        <img src="icon-location.svg" alt="">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
          dolore magna aliqua
        </p>
      </div>
    </div>
    <div class="col-2">
      <p><img src="icon-phone.svg" alt="">+1-543-123-4567</p>
      <p><img src="icon-email.svg" alt="">example@fylo.com</p>

    </div>
    <div class="col-3">

      <a href="#">About Us</a>
      <a href="#">Jobs</a>
      <a href="#">Press</a>
      <a href="#">Blog</a>

    </div>
    <div class="col-4">
      <a href="#">Contact Us</a>
      <a href="#">Terms</a>
      <a href="#">Privacy</a>

    </div>
    <div class="col-5">
      <p class="social-icons">
        <i class="fab fa-facebook-square fa-2x"></i>
        <i class="fab fa-instagram fa-2x"></i>
        <i class="fab fa-twitter-square fa-2x"></i>
      </p>
    </div>



  </footer>
  <p class="attribution">
    Challenge by <a href="#">Frontend Mentor</a>.
    Coded by <a href="#">Vegher Sunday</a>.
  </p>
</body>
</html>
