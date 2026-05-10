<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lucas Raphael - Profile</title>
  <style>
    :root {
      --bg: #0d1117;
      --surface: #161b22;
      --border: #30363d;
      --text: #c9d1d9;
      --muted: #8b949e;
      --accent: #58a6ff;
      --green: #3fb950;
    }
 
    * { box-sizing: border-box; margin: 0; padding: 0; }
 
    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Courier New', monospace;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      min-height: 100vh;
      padding: 2rem;
    }
 
    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 2rem;
      max-width: 780px;
      width: 100%;
      display: flex;
      gap: 2rem;
      align-items: flex-start;
    }
 
    .ascii-art {
      flex-shrink: 0;
      font-size: 3.2px;
      line-height: 1;
      font-family: monospace;
      white-space: pre;
      color: var(--green);
      opacity: 0.85;
      /* Sem transform: scale() — tamanho controlado via font-size */
    }
 
    .profile {
      display: flex;
      flex-direction: column;
      gap: 1.2rem;
      justify-content: center;
    }
 
    .profile h2 {
      font-size: 1.6rem;
      font-weight: 700;
      color: #ffffff;
      letter-spacing: 0.05em;
      border-left: 3px solid var(--accent);
      padding-left: 0.6rem;
    }
 
    .badge a {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      background: #21262d;
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 0.4rem 0.8rem;
      color: var(--text);
      text-decoration: none;
      font-size: 0.85rem;
      transition: border-color 0.2s, color 0.2s;
    }
 
    .badge a:hover {
      border-color: var(--accent);
      color: var(--accent);
    }
 
    .badge a::before {
      content: '';
      display: inline-block;
      width: 16px;
      height: 16px;
      background: url('https://img.shields.io/badge/-181717?logo=github') no-repeat center;
      background-size: contain;
    }
 
    hr {
      border: none;
      border-top: 1px solid var(--border);
    }
 
    .quote {
      font-style: italic;
      color: var(--muted);
      font-size: 0.9rem;
      line-height: 1.6;
    }
 
    .quote span {
      color: var(--accent);
    }
 
    @media (max-width: 600px) {
      .card {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <div class="card">
 
    <!-- ASCII art: font-size pequeno, sem scale() -->
    <pre class="ascii-art">⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠟⣛⣉⣭⣥⣤⣦⣬⣭⣭⣉⣛⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢟⣡⣴⣿⣿⣿⡿⢛⣻⣿⣉⠻⣿⣿⣿⣿⣦⣌⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⢋⣴⣿⣿⠟⣻⣿⢏⣴⣿⣿⣿⣿⣦⣘⣿⣿⣿⣿⣿⣷⡌⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⡿⢡⣾⣿⡿⣡⣾⣿⢃⣾⣿⣿⣿⣿⣧⢹⣿⣿⣿⣿⣿⡌⢿⣿⡆⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡿⠣⢋⣷⡟⣱⣿⢻⡿⢸⣿⣿⣿⣿⣿⣿⠈⣿⣿⡝⣿⣿⣿⡌⢿⣿⡄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⠇⢄⣾⣿⢠⣿⠃⣾⡇⢾⣿⢻⣿⣿⣿⢸⡇⢻⣿⣧⠸⣿⣿⣿⡄⢿⣿⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡿⢸⣾⣿⣿⣿⠁⠀⢹⡇⠘⠛⡘⣿⣿⣿⠈⠇⠀⠻⣿⡆⢻⠙⣿⣿⢸⣿⡆⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⠇⣾⣿⣿⣿⠇⠀⣦⠈⡇⠀⠀⠁⠹⣿⡇⠀⠐⠀⠀⠈⠣⠀⠃⢻⣿⡆⣿⡇⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⡏⢀⢹⡏⣿⣿⠀⢰⠛⣀⠀⠀⠀⠀⠀⠻⠇⠀⣼⣷⣆⠀⡀⠀⠄⢸⣿⣧⠘⣧⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⠇⠈⢺⡇⣿⣿⠀⠸⠟⠋⠉⠒⠦⣷⣦⣤⣀⣠⣿⠋⠁⠀⠈⠁⠂⠀⣿⡁⣤⠹⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣧⣀⣤⢸⠀⣿⣿⡄⢀⢠⠰⠀⠀⠠⣿⣿⣿⣿⣿⣿⣿⠁⠀⠀⢸⣀⠀⣿⣇⡿⠀⠀⢻⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡄⠀⠘⢿⣇⠘⣿⣧⣀⣀⣼⣿⣿⣿⣿⣿⣿⣿⣷⣴⣤⣿⡏⢀⣿⡏⠀⠀⣰⣴⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⡄⠰⣌⠛⠀⠙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠀⠸⣿⠁⠀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣄⠙⣦⠀⠀⠀⠉⡛⠛⠻⠿⠿⠿⠿⠿⠛⢛⠋⠁⠀⠁⢠⡁⢀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⠦⠈⠀⠀⢾⠿⢿⠀⠀⠀⡙⠋⠁⠀⠀⢸⡿⣿⣆⡀⠀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡟⠀⣒⣒⣒⣒⣒⣒⣒⣒⣐⠈⠒⣂⣀⣙⣚⣐⣂⣀⣀⣐⣀⣀⠀⠈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⠋⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⢰⣆⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡏⢰⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⢸⣯⡄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡈⠁⢿⣿⣿⣿⣿⣿⣿⣿⣿⠋⣁⣀⡀⢹⣿⣿⣿⣿⣿⣿⣿⣿⡇⢈⡛⠁⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡏⢰⠇⢘⣿⣿⣿⣿⣿⣿⣿⣿⡄⠻⠿⠧⠈⣿⣿⣿⣿⣿⣿⣿⣿⡇⢸⢿⠆⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⡟⢃⣤⣤⣄⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣤⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⠀⣤⣄⡙⠿⢿⠿⣿⣿⣿⣿⣿⣿
⣿⣿⠿⠂⠉⢻⡟⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⠘⠛⠻⠛⠑⣀⠀⣬⣭⣛⠻⢿⣿
⣿⠋⠀⠀⠀⠀⠈⠀⠙⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠁⠀⠀⠀⠀⠀⠈⢃⣾⢟⣽⡿⠀⠀⢻
⣿⣷⣄⠀⠀⠀⠀⠄⠀⠀⠀⠀⡀⠀⠀⢤⡤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡇⣿⡿⣡⠂⣸⠀⠀⠀⣿
⣿⣿⡿⠟⣂⣀⠀⠀⠀⢀⣴⣶⣦⡙⢦⡀⠁⠀⠀⠀⠀⠀⠀⣠⡶⢋⣤⣶⣤⠀⠀⠀⠀⠀⠀⢀⣌⡉⠛⠟⠀⠚⢻⠀⣿
⣿⣧⡀⠻⠿⣿⣿⣆⠀⢻⣿⣿⣿⣿⣦⠙⠀⢀⣴⣶⣆⡀⠠⠘⢠⣿⣿⣿⣿⡧⠀⡀⡤⠴⠛⢋⣉⣤⣶⣶⣶⣶⣾
⣿⣿⣿⣷⣶⣶⣦⣤⣤⣤⣍⡛⠿⣿⡟⠀⣐⣛⣛⣛⣛⣛⣀⡀⠘⢿⣿⠟⠋⠀⣤⣴⣶⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣤⣍⣉⣀⣀⣤⣼⣿⣿⣿⣿⣿⣿⣿⣿⣤⣄⣀⣊⣁⣀⣬⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿</pre>
 
    <div class="profile">
      <h2>Lucas Raphael</h2>
 
      <div class="badge">
        <a href="https://github.com/AlgumonL" target="_blank" rel="noopener">
          GitHub — AlgumonL
        </a>
      </div>
 
      <hr />
 
      <p class="quote">
        <span>❝</span> Todo expert já foi um iniciante.<br>
        Cada linha de código é um passo a mais na jornada. 🚀 <span>❞</span>
      </p>
    </div>
 
  </div>
</body>
</html>
 
