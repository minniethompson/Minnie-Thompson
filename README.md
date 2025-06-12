# Minnie-Thompson
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nomadiq Travel Destinations</title>
  <link href="https://fonts.googleapis.com/css2?family=Lato&family=Montserrat:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Lato', sans-serif;
    }

    header {
      background-color: #0077b6;
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      font-family: 'Montserrat', sans-serif;
      font-size: 1.5rem;
    }

    .nav-toggle {
      font-size: 1.5rem;
      background: none;
      border: none;
      color: white;
      cursor: pointer;
      display: block;
    }

    nav {
      display: none;
      flex-direction: column;
      gap: 1rem;
      width: 100%;
      margin-top: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .show-nav {
      display: flex;
    }

    @media (min-width: 768px) {
      .nav-toggle {
        display: none;
      }

      nav {
        display: flex !important;
        flex-direction: row;
        gap: 2rem;
        margin-top: 0;
        width: auto;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Nomadiq Travel Destinations</div>
    <button class="nav-toggle" onclick="document.querySelector('nav').classList.toggle('show-nav')">☰</button>
    <nav>
      <a href="#">Home</a>
      <a href="#">Destinations</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>
</body>
</html>
