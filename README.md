<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta http-equiv="X-UA-Compatible" content="ie=edge"/>
  <title>Mantas Krutulis Portfolio</title>
  <style>
    body {
      font-family: sans-serif;
      background: #0B132B;
      color: #ffffff;
      margin: 0;
      padding: 0;
    }

    nav {
      background: #1C2541;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .nav-left a.name {
      color: #ffffff;
      font-family: 'Times New Roman', Times, serif;
      font-size: 32px;
      text-decoration: none;
    }

    .nav-left h2 {
      margin: 0;
      font-size: 18px;
      color: #ffffff;
    }

    .nav-right {
      display: flex;
      gap: 1.5rem;
    }

    .nav-right a {
      color: #ffffff;
      font-size: 18px;
      text-decoration: none;
    }

    .nav-right a:hover {
      opacity: 0.7;
    }

    .about {
      padding: 3rem 2rem 1rem;
      text-align: center;
    }

    .about h2 {
      font-size: 36px;
      color: #5BC0BE;
      margin-bottom: 1rem;
    }

    .games-section {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
      padding: 2rem;
    }

    .game-card {
      text-align: center;
      max-width: 320px;
    }

    .game-card img {
      width: 100%;
      height: auto;
      border-radius: 15%;
      transition: transform 0.3s ease;
    }

    .game-card img:hover {
      transform: scale(1.05);
    }

    .game-card a {
      display: block;
      margin-top: 0.5rem;
      font-size: 22px;
      color: #3A506B;
      text-decoration: none;
    }

    .game-card a:hover {
      color: #5BC0BE;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .nav-right {
        margin-top: 1rem;
        flex-direction: column;
        gap: 0.5rem;
      }

      .games-section {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

  <nav>
    <div class="nav-left">
      <a class="name" href="PortFolio.html"><strong>Mantas Krutulis</strong></a>
      <h2>Game Developer</h2>
    </div>
    <div class="nav-right">
      <a href="https://kubas-13.github.io/Portfolio/">HOME</a>
      <a href="https://kubas-13.github.io/Demo/">DEMOS</a>
      <a href="https://kubas-13.github.io/Games/">GAMES</a>
      <a href="[Contact.html]">CONTACT</a>
    </div>
  </nav>

  <section class="about">
    <h2><strong>GAMES</strong></h2>
  </section>

  <section class="games-section">
    <div class="game-card">
      <a href="https://cubeindustry.itch.io/pour" target="_blank">
        <img src="Pour.png" alt="Pour Game">
        <span><strong>Pour</strong></span>
      </a>
    </div>
    <div class="game-card">
      <a href="https://cubeiacon.itch.io/killstinct" target="_blank">
        <img src="Killstict.png" alt="Killstict Game">
        <span><strong>Killstict</strong></span>
      </a>
    </div>
    <div class="game-card">
      <a href="https://cubeiacon.itch.io/homework" target="_blank">
        <img src="Homework.png" alt="Homework Game">
        <span><strong>Homework</strong></span>
      </a>
    </div>
  </section>

</body>
</html>
