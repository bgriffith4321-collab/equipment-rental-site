# equipment-rental-site
/index.html
/style.css
/script.js
/equipment/
    excavator.html
    skid-steer.html
    dump-trailer.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Equipment Rental Co.</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

  <header>
    <h1>Equipment Rental Co.</h1>
    <p>Fast, affordable heavy equipment rentals</p>
  </header>

  <section class="equipment-grid">

    <a class="card" href="equipment/excavator.html">
      <h2>Excavator</h2>
      <p>$450 / day</p>
    </a>

    <a class="card" href="equipment/skid-steer.html">
      <h2>Skid Steer</h2>
      <p>$250 / day</p>
    </a>

    <a class="card" href="equipment/dump-trailer.html">
      <h2>Dump Trailer</h2>
      <p>$120 / day</p>
    </a>

  </section>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f4f4;
  color: #222;
}

header {
  background: #111;
  color: white;
  padding: 30px;
  text-align: center;
}

.equipment-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 20px;
}

.card {
  background: white;
  padding: 20px;
  text-decoration: none;
  color: black;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: 0.2s;
}

.card:hover {
  transform: scale(1.03);
}
<!DOCTYPE html>
<html>
<head>
  <title>Excavator Rental</title>
  <link rel="stylesheet" href="../style.css"/>
</head>
<body>

  <header>
    <h1>Excavator</h1>
    <p>$450 / day</p>
  </header>

  <div style="padding: 20px;">
    <h2>Details</h2>
    <p>Powerful excavator for digging, grading, and construction work.</p>

    <h2>Book This Equipment</h2>

    <form>
      <label>Name</label><br/>
      <input type="text" required><br/><br/>

      <label>Rental Days</label><br/>
      <input type="number" min="1" required><br/><br/>

      <button type="submit">Request Booking</button>
    </form>

    <br/>
    <a href="../index.html">← Back to Home</a>
  </div>

</body>
</html>