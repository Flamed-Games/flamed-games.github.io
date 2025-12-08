
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flamed Games</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Courier New', Courier, monospace;
      background-color: #0a0a0a;
      color: #00ff00;
      overflow-x: hidden;
    }

    a {
      color: #00ff00;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    
    header {
      padding: 2rem;
      text-align: center;
      border-bottom: 1px solid #00ff00;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 2px;
    }

    header p {
      margin: 0.5rem 0 0;
      font-size: 1.2rem;
      color: #33ff33;
    }

    
    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }

    .project-card {
      background-color: #111;
      border: 1px solid #00ff00;
      border-radius: 5px;
      padding: 1rem;
      transition: transform 0.2s;
    }

    .project-card:hover {
      transform: scale(1.05);
      border-color: #33ff33;
    }

    .project-card h3 {
      margin-top: 0;
    }

    .project-card p {
      font-size: 0.9rem;
      color: #99ff99;
    }

    .project-card a {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.3rem 0.6rem;
      border: 1px solid #00ff00;
      border-radius: 3px;
      transition: background 0.2s;
    }

    .project-card a:hover {
      background-color: #00ff00;
      color: #000;
    }

  
    footer {
      text-align: center;
      padding: 1rem;
      border-top: 1px solid #00ff00;
      font-size: 0.9rem;
      color: #33ff33;
    }

    @keyframes blink {
      0%, 50%, 100% { opacity: 1; }
      25%, 75% { opacity: 0; }
    }

    .cursor {
      display: inline-block;
      width: 10px;
      background-color: #00ff00;
      margin-left: 2px;
      animation: blink 1s step-start infinite;
    }
  </style>
</head>
<body>
  <header>
    <h1>Flamed Sites</h1>
    <a href="https://discord.gg/8Xx6KptcQS">Discord Server</a>
  </header>

  <main>
    <div class="project-card">
      <h3>Flamed</h3>
      <p>Our first project that has unblocked games playable by anyone, anytime!</p>
      <a href="https://flamed.onrender.com/">Visit Site</a>
    </div>

    <div class="project-card">
      <h3>Flamed Lite</h3>
      <p>Embedable version of Flamed.</p>
      <a href="https://flamed-games.github.io/Flamed-Lite">Visit Site</a>
    </div>

    <div class="project-card">
      <h3>GITHUB ORGANIZATION</h3>
      <p>View the all of Flamed's projects</p>
      <a href="https://github.com/Flamed-Games">Visit</a>
    </div>

  </main>
</body>
</html>
