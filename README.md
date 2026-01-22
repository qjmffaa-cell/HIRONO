<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Urban Finds</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
    }

    /* NAVBAR */
    header {
      background-color: #f7b6c2;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 22px;
      color: #392520;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #7a1c2b;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* HERO SECTION */
    .hero {
      display: flex;
      height: 90vh;
    }

    .hero-box {
      flex: 1;
      padding: 40px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      position: relative;
    }

    .hero-box h2 {
      font-size: 48px;
      margin-bottom: 15px;
    }

    .hero-box p {
      font-size: 16px;
      margin-bottom: 25px;
      max-width: 350px;
    }

    .hero-box button {
      width: 140px;
      padding: 12px;
      border: none;
      background-color: #7a1c2b;
      color: white;
      cursor: pointer;
      font-size: 14px;
      border-radius: 5px;
    }

    .hero-box button:hover {
      background-color: #5c1421;
    }

    /* DIFFERENT BACKGROUNDS */
    .left {
      background: url("/Users/jamesmiguelf.faa/Downloads/images.jpeg") center/cover;
      color: white;
    }

    .middle {
      background: #ffffff;
      text-align: center;
    }

    .right {
      background: url("/Users/jamesmiguelf.faa/Downloads/hirono2.webp") center/cover;
      color: white;
    }

    .overlay {
      background-color: rgba(0,0,0,0.5);
      padding: 40px;
      border-radius: 10px;
    }

    /* RESPONSIVE */
    @media (max-width: 900px) {
      .hero {
        flex-direction: column;
        height: auto;
      }

      .hero-box {
        height: 60vh;
      }
    }
  </style>
</head>

<body>

  <!-- NAVIGATION -->
  <header>
    <h1>About Hirono</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Collections</a>
      <a href="#">Order</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <!-- HERO SECTION -->
  <section class="hero">

    <div class="hero-box left">
      <div class="overlay">
        <h2>Hirono Figurines</h2>
        <p>Different Hironos Series</p>
        <button>Shop Now</button>
      </div>
    </div>

    <div class="hero-box middle">
      <h2>Hirono Story</h2>
      <p>Each figurine has a story to tell.</p>
      <button>View Picks</button>
    </div>

    <div class="hero-box right">
      <div class="overlay">
        <h2>About Hirono</h2>
        <p>About artist etc.</p>
        <button>Explore</button>
      </div>
    </div>

  </section>

</body>
</html>
