# index.html <!DOCTYPE html>
<html>
<head>
  <title>Luxury Hotel Junagadh</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial;
    }

    header {
      background: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1566073771259-6a8506099945');
      height: 400px;
      background-size: cover;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 32px;
      font-weight: bold;
    }

    .section {
      padding: 40px;
      text-align: center;
    }

    .rooms {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      border: 1px solid #ddd;
      padding: 20px;
      width: 250px;
      border-radius: 10px;
    }

    .btn {
      background: #4caf50;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      display: inline-block;
      margin-top: 10px;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>Fern Leo Resort - Junagadh</h1>
</header>

<div class="hero">
  Experience Luxury Stay
</div>

<div class="section">
  <h2>Our Rooms</h2>
  <div class="rooms">
    <div class="card">
      <h3>Deluxe Room</h3>
      <p>Comfortable stay with modern design</p>
    </div>

    <div class="card">
      <h3>Premium Suite</h3>
      <p>Luxury experience with extra space</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>Gallery</h2>
  <p>Beautiful views, pool & nature</p>
</div>

<div class="section">
  <h2>Contact Us</h2>
  <p>Call: +91 99999 99999</p>
  <a href="#" class="btn">Book Now</a>
</div>

<footer>
  <p>© 2026 Hotel Website</p>
</footer>

</body>
</html>
