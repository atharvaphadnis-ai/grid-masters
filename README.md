<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Gridmasters README</title>
  <style>
    body {
      background-color: #0a0a0a;
      color: #eaeaea;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      padding: 20px;
    }
    h1, h2 {
      color: #00f7ff;
    }
    h1 {
      text-align: center;
      font-size: 40px;
      margin-bottom: 10px;
    }
    .subtitle {
      text-align: center;
      color: #ff2e9a;
      margin-bottom: 30px;
    }
    .section {
      margin-bottom: 30px;
      padding: 15px;
      border-radius: 10px;
      background: rgba(255,255,255,0.03);
      box-shadow: 0 0 10px rgba(0,255,255,0.1);
    }
    ul {
      padding-left: 20px;
    }
    code {
      background: #111;
      padding: 3px 6px;
      border-radius: 5px;
      color: #00f7ff;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>
<body>

  <h1>🎮 Gridmasters</h1>
  <p class="subtitle">Tic Tac Toe. Upgraded.</p>

  <div class="section">
    <h2>📌 Overview</h2>
    <p>
      Gridmasters is a modern, neon-themed Tic-Tac-Toe game featuring real-time multiplayer and an advanced AI bot.
      Built for mobile-first gameplay, it delivers smooth performance, responsive controls, and competitive gameplay.
    </p>
  </div>

  <div class="section">
    <h2>✨ Features</h2>
    <ul>
      <li>🌐 Real-time Online Multiplayer (Socket.io)</li>
      <li>🤖 Offline Mode with Minimax AI</li>
      <li>📱 Mobile-first Responsive UI</li>
      <li>🎯 Turn-based gameplay enforcement</li>
      <li>🔢 Room code system for private matches</li>
      <li>🏆 Live score tracking</li>
      <li>🎨 Dark theme with neon accents</li>
    </ul>
  </div>

  <div class="section">
    <h2>🎮 How to Play</h2>
    <ul>
      <li>Select <b>Online Multiplayer</b> or <b>Offline vs Bot</b></li>
      <li>Create or join a room using a code (online mode)</li>
      <li>Take turns placing X or O on the grid</li>
      <li>First to align 3 marks wins</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Tech Stack</h2>
    <ul>
      <li>Frontend: HTML, CSS, JavaScript</li>
      <li>Backend: Node.js, Express</li>
      <li>Realtime: Socket.io</li>
      <li>AI Logic: Minimax Algorithm</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 Setup</h2>
    <p>Run the following commands:</p>
    <pre>
npm install
node server.js
    </pre>
  </div>

  <div class="section">
    <h2>📊 Game Rules</h2>
    <ul>
      <li>3x3 grid</li>
      <li>Players alternate turns</li>
      <li>Win by completing a row, column, or diagonal</li>
      <li>Draw if all cells are filled</li>
    </ul>
  </div>

  <footer>
    Made by Atharva Phadnis
  </footer>

</body>
</html>
