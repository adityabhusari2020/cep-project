<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Helping Platform</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background: #3b82f6;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      background: #1e40af;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      background: white;
      margin: 2rem auto;
      padding: 2rem;
      border-radius: 8px;
      width: 90%;
      max-width: 500px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #1e3a8a;
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      margin-bottom: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #2563eb;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #1d4ed8;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #1e3a8a;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Helping Platform</h1>
    <p>Connecting people for a better community</p>
  </header>

  <nav>
    <a href="#login">Login</a>
    <a href="#signup">Sign Up</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <!-- Login Section -->
  <section id="login">
    <h2>Login</h2>
    <form>
      <label>Email</label>
      <input type="email" placeholder="Enter your email" required />

      <label>Password</label>
      <input type="password" placeholder="Enter your password" required />

      <label><input type="checkbox" /> Remember me</label><br><br>

      <button type="submit">Login</button>
    </form>
  </section>

  <!-- Sign Up Section -->
  <section id="signup">
    <h2>Create Account</h2>
    <form>
      <label>Full Name</label>
      <input type="text" placeholder="Your full name" required />

      <label>Email</label>
      <input type="email" placeholder="Enter your email" required />

      <label>Password</label>
      <input type="password" placeholder="Create a password" required />

      <button type="submit">Sign Up</button>
    </form>
  </section>

  <!-- About Us Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>Our platform helps students find safe and affordable homes while allowing owners to list their properties. We aim to bridge the gap between people in need and people who can help.</p>
  </section>

  <!-- Contact Us Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <label>Your Name</label>
      <input type="text" placeholder="Your name" required />

      <label>Email</label>
      <input type="email" placeholder="Your email" required />

      <label>Subject</label>
      <select required>
        <option value="">Select a subject</option>
        <option>General Query</option>
        <option>Technical Support</option>
        <option>Report an Issue</option>
      </select>

      <label>Message</label>
      <textarea rows="4" placeholder="Write your message here..." required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Helping Platform. All rights reserved...
  </footer>

</body>
</html>
