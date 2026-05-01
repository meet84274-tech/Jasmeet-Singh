<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me - Jasmeet</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e1e2f, #2b5876);
      color: white;
      text-align: center;
    }

    header {
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5rem;
    }

    p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    .card {
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 20px;
      margin: 20px auto;
      width: 80%;
      max-width: 600px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    button {
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      background: #00c6ff;
      color: black;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #0072ff;
      color: white;
    }

    .hidden {
      display: none;
    }

    footer {
      margin-top: 30px;
      padding: 20px;
      font-size: 0.9rem;
      opacity: 0.7;
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I'm Jasmeet 👋</h1>
    <p>A passionate developer exploring AI, ML, and creative coding.</p>
  </header>

  <div class="card">
    <h2>🚀 Skills</h2>
    <p>Python | Machine Learning | OpenCV | SQL | HTML</p>
  </div>

  <div class="card">
    <h2>📊 Current Project</h2>
    <p>Emotion-based Content Recommendation System</p>
  </div>

  <div class="card">
    <h2>🎯 Fun Fact</h2>
    <button onclick="showFact()">Click to Reveal</button>
    <p id="fact" class="hidden">I love combining AI with real-world applications 🤖</p>
  </div>

  <div class="card">
    <h2>📫 Contact</h2>
    <p>Email: your-email@example.com</p>
    <p>
      <a href="https://github.com/yourusername" target="_blank" style="color:#00c6ff;">GitHub</a>
    </p>
  </div>

  <footer>
    Made with ❤️ by Jasmeet
  </footer>

  <script>
    function showFact() {
      document.getElementById("fact").classList.toggle("hidden");
    }
  </script>

</body>
</html>
