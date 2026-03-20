<!DOCTYPE html>
<html>
<head>
  <title>Luxury Hotel Junagadh</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    header {
      background: #1b5e20;
      color: white;
      padding: 15px;
      text-align: center;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
      url('https://images.unsplash.com/photo-1566073771259-6a8506099945');
      height: 90vh;
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .hero h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    .section {
      padding: 50px 20px;
      text-align: center;
    }

    .rooms {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .card {
      width: 280px;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      background: white;
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card h3 {
      margin: 10px 0;
    }

    .card p {
      padding: 0 10px 10px;
    }

    .booking {
      background: #f1f1f1;
      padding: 30px;
      border-radius: 10px;
      max-width: 500px;
      margin: auto;
    }

    input, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    button {
      background: #2e7d32;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background: #1b5e20;
    }

    footer {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    /* MOBILE FRIENDLY */
    @media(max-width: 768px) {
      .hero h1 {
        font-size: 28px;
      }

      .hero {
        height: 70vh;
        text-align: center;
        padding: 20px;
      }
    }

  </style>
</head>

<body>

<header>
  <h2>Fern Leo Resort - Junagadh</h2>
</header>

<div class="hero">
  <h1>Luxury Stay in Junagadh</h1>
  <p>Relax • Enjoy • Experience</p>
</div>

<div class="section">
  <h2>Our Rooms</h2>
  <div class="rooms">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1611892440504-42a792e24d32">
      <h3>Deluxe Room</h3>
      <p>Comfortable and elegant stay</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b">
      <h3>Premium Suite</h3>
      <p>Luxury experience with premium facilities</p>
    </div>

  </div>
</div>

<div class="section">
  <h2>Book Your Stay</h2>

  <div class="booking">
    <input type="text" placeholder="Your Name">
    <input type="email" placeholder="Email">
    <input type="date">
    <input type="date">
    <button onclick="bookNow()">Book Now</button>
  </div>

</div>

<div class="section">
  <h2>Contact</h2>
  <p>📞 +91 99999 99999</p>
  <p>📍 Junagadh, Gujarat</p>
</div>

<footer>
  <p>© 2026 Fern Leo Resort</p>
</footer>

<script>
  function bookNow() {
    alert("Booking request sent!");
  }
</script>

</body>
</html>
