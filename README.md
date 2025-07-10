<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PHYCHEMMABIO</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <!-- AOS (Animate on Scroll) CSS -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    /* Reset and basic styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom, #0a1d56, #000000);
      color: #ffffff;
      overflow-x: hidden;
    }

    header {
      padding: 30px;
      text-align: center;
      background: rgba(0, 0, 0, 0.4);
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }

    section {
      padding: 80px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    section p {
      max-width: 700px;
      margin: 0 auto;
      font-size: 1.1rem;
      line-height: 1.7;
      color: #dcdcdc;
    }

    .floating-img {
      width: 200px;
      animation: float 4s ease-in-out infinite;
      margin: 40px auto;
      display: block;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
    }

    footer {
      text-align: center;
      padding: 30px;
      background: rgba(0, 0, 0, 0.3);
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1 data-aos="zoom-in">PHYCHEMMABIO</h1>
    <p data-aos="fade-up" data-aos-delay="300">Explore Physics, Chemistry, and Biology in Motion</p>
  </header>

  <!-- Hero Section -->
  <section>
    <img src="https://cdn-icons-png.flaticon.com/512/3197/3197964.png" alt="atom" class="floating-img" data-aos="fade-up" />
    <h2 data-aos="fade-right">Physics</h2>
    <p data-aos="fade-left" data-aos-delay="200">
      Discover the laws that govern motion, energy, and matter. Experience Newton's brilliance in action.
    </p>
  </section>

  <section>
    <img src="https://cdn-icons-png.flaticon.com/512/1037/1037760.png" alt="chemistry" class="floating-img" data-aos="fade-up" />
    <h2 data-aos="fade-right">Chemistry</h2>
    <p data-aos="fade-left



