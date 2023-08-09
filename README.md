# movie_hub
It is a simple website having a similar homepage to that of Netflix using HTML and CSS.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Movie Hub</title>
<style>
  /* Reset some default styles */
  body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
  }

  /* Set background and font styles */
  body {
    font-family: Arial, sans-serif;
    background-color: #141414;
    color: #fff;
    background-image: url('background1.jpg'); /* Background image */
    background-size: cover;
    background-repeat: no-repeat;
  }

  /* Header styles */
  header {
    background-color: #111;
    padding: 10px 0;
    text-align: center;
  }
  .logo {
    font-size: 24px;
    font-weight: bold;
    text-transform: uppercase;
  }

  /* Main content styles */
  .main-content {
    padding: 40px;
  }
  .main-content h1 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
    text-transform: uppercase;
  }

  /* Movie/Show card styles */
  .movie-card {
    display: inline-block;
    width: 200px;
    margin: 0 10px;
    text-align: center;
  }
  .movie-card img {
    max-width: 90%; /* Decrease image size by 10% */
    border-radius: 8px;
  }
  .movie-card h2 {
    font-size: 20px;
    margin-top: 10px;
  }

  /* Footer styles */
  footer {
    text-align: center;
    padding: 20px 0;
    background-color: #111;
    color: #888;
  }
</style>
</head>
<body>
  <header>
    <div class="logo">Movie Hub</div>
  </header>

  <div class="main-content">
    <h1>Popular Movies</h1>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=9dofjL8eOXs" target="_blank">
        <img src="movie1.jpg" alt="Mr. Perfect">
        <h2>Mr. Perfect</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=G7haVu5g-Qw" target="_blank">
        <img src="movie2.jpg" alt="Magadheera">
        <h2>Magadheera</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=tas_30CdOss" target="_blank">
        <img src="movie3.jpg" alt="Maya Bazaar">
        <h2>Maya Bazaar</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=wCwqqWQvX_o" target="_blank">
        <img src="movie4.jpg" alt="Mahanati">
        <h2>Mahanati</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=d_hNNnOc5Bo" target="_blank">
        <img src="movie5.jpg" alt="Snehitudu">
        <h2>Snehitudu</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=Z3DQ9Xtzd9Y" target="_blank">
        <img src="raja.jpg" alt="Raja">
        <h2>Raja</h2>
      </a>
    </div>

    <div class="movie-card">
      <a href="https://www.youtube.com/watch?v=nVsJLEIMnmE" target="_blank">
        <img src="movie7.jpg" alt="Govindudu Andharivadu">
        <h2>Govindudu Andharivadu</h2>
      </a>
    </div>
  </div>

  <footer>
    <p>&copy; 2023 Movie Hub. All rights reserved.</p>
  </footer>
</body>
</html>

