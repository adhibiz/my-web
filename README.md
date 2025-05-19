<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Home Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em 0;
      text-align: center;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      padding: 0.5em 0;
    }
    nav a {
      color: white;
      margin: 0 1em;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background-color: #f4f4f4;
      text-align: center;
      padding: 4em 1em;
    }
    .hero h1 {
      margin: 0;
    }
    .content {
      padding: 2em;
      text-align: center;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em 0;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h1>Your Catchy Tagline Here</h1>
    <p>Start building your awesome website today.</p>
  </section>

  <section class="content" id="about">
    <h2>About Us</h2>
    <p>This is a simple home page example created with HTML and CSS.</p>
  </section>

  <footer>
    &copy; 2025 Your Website Name
  </footer>
</body>
</html>
