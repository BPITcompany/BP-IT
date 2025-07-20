<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BP Technology’s | IT Services</title>
  <style>
    :root {
      --primary-color: #008080;
      --dark-color: #111;
      --light-bg: #f9f9f9;
      --text-light: #fff;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--light-bg);
      color: var(--dark-color);
      line-height: 1.6;
    }

    header {
      background-color: var(--dark-color);
      color: var(--text-light);
      text-align: center;
      padding: 50px 20px;
      animation: fadeIn 1s ease-in-out;
    }

    header h1 {
      font-size: 2.4rem;
      margin-bottom: 10px;
    }

    nav {
      background-color: var(--primary-color);
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 12px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 8px 15px;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ddd;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 30px 20px;
    }

    h2 {
      color: var(--primary-color);
      font-size: 1.8rem;
      margin-bottom: 15px;
    }

    section {
      margin-bottom: 40px;
    }

    ul {
      padding-left: 20px;
    }

    form {
      background-color: white;
      padding: 25px;
      border-radius: 6px;
      box-shadow: 0 2px 15px rgba(0,0,0,0.05);
      max-width: 600px;
      animation: fadeInUp 1s ease-in-out;
    }

    input, textarea {
      width: 100%;
      padding: 12px;
      margin: 8px 0 16px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }

    button {
      background-color: var(--primary-color);
      color: white;
      border: none;
      padding: 12px 20px;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #006666;
    }

    footer {
      background-color: var(--dark-color);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    /* Animations */
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      nav a {
        margin: 6px 10px;
        font-size: 0.95rem;
      }

      h2 {
        font-size: 1.5rem;
      }

      form {
        padding: 20px;
      }
    }

    @media (max-width: 480px) {
      header {
        padding: 40px 10px;
      }

      header h1 {
        font-size: 1.8rem;
      }

      button {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>BP Technology’s</h1>
    <p>Your Trusted IT Partner</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#technologies">Technologies</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Website Design & Development</li>
        <li>App Design & UI/UX Consulting</li>
        <li>App Troubleshooting & Maintenance</li>
        <li>Custom Software Solutions</li>
      </ul>
    </section>

    <section id="technologies">
      <h2>Technologies We Work With</h2>
      <ul>
        <li>C++</li>
        <li>HTML & HTML5</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Python</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: info@bptechnologys.com</p>
      <p>Phone: +1 (555) 123-4567</p>

      <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email Address</label>
        <input type="email" id="email" name="_replyto" required />

        <label for="message">Your Message</label>
        <textarea id="message" name="message" rows="6" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 BP Technology’s. All rights reserved.</p>
  </footer>

</body>
</html>
