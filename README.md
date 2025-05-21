  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #2d2d2d;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #2d2d2d;
    }
    footer {
      background-color: #2d2d2d;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .contact-form input, .contact-form textarea {
      display: block;
      width: 100%;
      margin-bottom: 1rem;
      padding: 10px;
      font-size: 1rem;
      box-sizing: border-box; /* Added for better sizing */
    }
  </style>
</head>
<body>
  <header>
    <h1>SMP Consulting</h1>
    <p>Your Partner in Strategic Success</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>SMP Consulting is a sole proprietorship dedicated to helping individuals and businesses achieve their strategic goals. With years of experience in the consulting industry, we offer personalized solutions tailored to your needs.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Business Strategy Consulting</li>
      <li>Operations & Process Improvement</li>
      <li>Market Research & Analysis</li>
      <li>Startup Mentoring & Support</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <strong>smpconsulting@gmail.com</strong></p>
    <p>Phone: (123) 456-7890</p>
    <p>Or use the form below:</p>
    <form class="contact-form" onsubmit="handleSubmit(event)">
      <label for="name">Your Name</label>
      <input id="name" type="text" placeholder="Your Name" required />
      <label for="email">Your Email</label>
      <input id="email" type="email" placeholder="Your Email" required />
      <label for="message">Your Message</label>
      <textarea id="message" rows="5" placeholder="Your Message"></textarea>
      <input type="submit" value="Send Message" />
    </form>
  </section>

  <footer>
    <p>&copy; 2025 SMP Consulting. All rights reserved.</p>
  </footer>
  <script>
    function handleSubmit(e) {
      e.preventDefault();
      alert('Thank you for contacting SMP Consulting!');
    }
  </script>
</body>
</html>
