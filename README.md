<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Isaac's Garbage Cleaning</title>
  <link href="https://fonts.googleapis.com/css2?family=Staatliches&family=Rubik+Glitch&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Staatliches', sans-serif;
      background: #111;
      color: #fff;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 100px 20px 40px;
      background: url('https://images.unsplash.com/photo-1600573476271-ef0c2367f4c2?auto=format&fit=crop&w=1400&q=80') no-repeat center center/cover;
      position: relative;
    }

    header::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.7);
    }

    header h1 {
      font-family: 'Rubik Glitch', cursive;
      font-size: 4em;
      z-index: 1;
      position: relative;
      color: #00ffae;
      text-shadow: 2px 2px #ff0055;
    }

    .section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    .spray-text {
      font-size: 2em;
      color: #ff0055;
      text-shadow: 0 0 10px #00ffae;
    }

    .contact {
      background: #222;
      padding: 40px 20px;
      border-top: 5px dashed #00ffae;
    }

    .contact a {
      color: #00ffae;
      text-decoration: none;
      font-size: 1.2em;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #999;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.5em;
      }

      .spray-text {
        font-size: 1.5em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>ISAAC'S CLEAN CREW</h1>
  </header>

  <div class="section">
    <p class="spray-text">We clean up so you don't have to.</p>
    <p>
      Servicing <strong>Albuquerque</strong>, <strong>Bernalillo</strong>, and <strong>Rio Rancho</strong> — fast, affordable, no BS.
    </p>
    <p>
      Garbage removal, cleanouts, hauling, and more.  
      Residential and commercial — same day available.
    </p>
  </div>

  <div class="contact">
    <h2>📞 Contact Isaac</h2>
    <p>Phone: <a href="tel:+15053474869">(505) 347-4869</a></p>
    <p>Email: <a href="mailto:isaac.mv05@gmail.com">isaac.mv05@gmail.com</a></p>
  </div>

  <footer>
    &copy; 2025 Isaac's Clean Crew. Built with pride.
  </footer>

</body>
</html>
