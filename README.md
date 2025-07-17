<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Portfólio - Sobre Mim e Stacks</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 40px;
      background-color: #f5f5f5;
      color: #333;
    }

    h2 {
      margin-top: 40px;
      color: #2c3e50;
    }

    h3 {
      margin-top: 30px;
      color: #34495e;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    li {
      margin: 8px 0;
    }

    .emoji {
      font-size: 1.2em;
      margin-right: 8px;
    }

    .tech-section {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-bottom: 40px;
    }

    .tech-box {
      width: 120px;
      height: 140px;
      text-align: center;
    }

    .progress-circle {
      width: 80px;
      height: 80px;
      margin: 0 auto 10px;
      position: relative;
    }

    .progress-circle svg {
      transform: rotate(-90deg);
    }

    .progress-bg,
    .progress-value {
      fill: none;
      stroke-width: 10;
    }

    .progress-bg {
      stroke: #eee;
    }

    .progress-value {
      stroke: #4caf50;
      stroke-linecap: round;
      stroke-dasharray: 251;
      stroke-dashoffset: 0;
    }

    .progress-text {
      position: absolute;
      top: 25%;
      left: 50%;
      transform: translateX(-50%);
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h2>🧠 Sobre Mim</h2>
  <ul>
    <li><span class="emoji">🎯</span>Focado em resolver problemas reais com soluções limpas e eficientes</li>
    <li><span class="emoji">💡</span>Praticante de boas práticas, código performático e interfaces agradáveis</li>
    <li><span class="emoji">🔭</span>Atualmente estudando Flutter pelo programa Entra21</li>
    <li><span class="emoji">🚀</span>Criador de projetos próprios e apaixonado por aprendizado constante</li>
  </ul>

  <h2>🛠️ Minhas Stacks</h2>

  <h3>Frontend</h3>
  <div class="tech-section">
    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="50"></circle>
        </svg>
        <div class="progress-text">80%</div>
      </div>
      <span>React</span>
    </div>

    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="100"></circle>
        </svg>
        <div class="progress-text">60%</div>
      </div>
      <span>Angular</span>
    </div>

    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="75"></circle>
        </svg>
        <div class="progress-text">70%</div>
      </div>
      <span>Next.js</span>
    </div>
  </div>

  <h3>Backend</h3>
  <div class="tech-section">
    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="40"></circle>
        </svg>
        <div class="progress-text">85%</div>
      </div>
      <span>Node.js</span>
    </div>

    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="80"></circle>
        </svg>
        <div class="progress-text">68%</div>
      </div>
      <span>Java</span>
    </div>
  </div>

  <h3>Mobile</h3>
  <div class="tech-section">
    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="40"></circle>
        </svg>
        <div class="progress-text">85%</div>
      </div>
      <span>Flutter</span>
    </div>

    <div class="tech-box">
      <div class="progress-circle">
        <svg width="80" height="80">
          <circle class="progress-bg" cx="40" cy="40" r="40"></circle>
          <circle class="progress-value" cx="40" cy="40" r="40" stroke-dashoffset="100"></circle>
        </svg>
        <div class="progress-text">60%</div>
      </div>
      <span>Kotlin</span>
    </div>
  </div>

</body>
</html>
