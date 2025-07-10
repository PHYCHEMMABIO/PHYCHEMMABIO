<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PHYCHEMMABIO</title>
  <style>
    /* Reset & base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", sans-serif;
      line-height: 1.6;
      background: linear-gradient(to bottom, #0a1d56, #000000);
      color: #f5f5f5;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
    }

    /* Header */
    header {
      background-color: rgba(10, 29, 86, 0.9);
      padding: 20px 0;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      float: left;
      letter-spacing: 1px;
    }

    nav {
      float: right;
    }

    nav a {
      color: #f5f5f5;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #00bfff;
    }

    header::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Main */
    main {
      padding: 60px 0;
    }

    h2 {
      margin-bottom: 15px;
    }

    p {
      max-width: 700px;
    }

    /* Footer */
    footer {
      background-color: rgba(10, 29, 86, 0.9);
      text-align: center;
      padding: 20px 0;
      margin-top: 60px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <h1 class="logo">PHYCHEMMABIO</h1>
      <nav>
        <a href="#">Home</a>
        <a href="#">Physics</a>
        <a href="#">Chemistry</a>
        <a href="#">Biology</a>
        <a href="#">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main class="container">
    <section>
      <h2>Welcome to PHYCHEMMABIO</h2>
      <p>PHYCHEMMABIO is a modern, student-focused educational site. Dive into the worlds of Physics, Chemistry,Maths and Biology — all at one place.</p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; ©2025 PHYCHEMMABIO. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>


