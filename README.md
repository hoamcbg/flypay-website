# flypay-website
flypay
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FlyPay Download</title>
  <link href="https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', Arial, sans-serif;
      background: linear-gradient(120deg, #fff6cf, #e3e3ff, #c3eaff);
      /* Soft pastel blend, feel free to tweak colors as needed! */
      display: flex;
      justify-content: center;
      padding: 40px 15px;
    }
    .container {
      max-width: 460px;
      background: #ffffff;
      padding: 35px 25px;
      border-radius: 25px;
      box-shadow: 0 18px 35px rgba(0,0,0,0.15);
      text-align: center;
      animation: fadeIn 1s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .logo {
      display: block;
      margin: 0 auto 25px auto;
      width: 220px;
      height: 220px;
      max-width: 95vw;
      box-shadow: 0 10px 30px rgba(0,0,0,0.18);
      border-radius: 50%;
      background: white;
    }
    .logo-text-standout {
      font-family: 'Poppins', Arial, sans-serif;
      font-size: 40px;
      font-weight: bold;
      stroke: #fff;
      stroke-width: 1.1px;
      letter-spacing: 2.5px;
      filter: drop-shadow(0 2px 9px #0050e655);
    }
    h1 {
      font-size: 34px;
      margin: 0 0 12px;
      background: linear-gradient(90deg, #007bff, #0050e6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: 700;
    }
    p {
      font-size: 18px;
      line-height: 1.6;
      color: #444;
      margin-bottom: 25px;
    }
    .highlight {
      font-weight: bold;
      color: #0050e6;
    }
    .download-btn {
      display: inline-block;
      background: linear-gradient(90deg, #007bff, #0050e6);
      color: #fff;
      padding: 16px 28px;
      font-size: 20px;
      border-radius: 14px;
      text-decoration: none;
      transition: .25s;
      font-weight: 600;
      letter-spacing: 0.5px;
      box-shadow: 0 10px 25px rgba(0, 95, 255, 0.35);
    }
    .download-btn:hover {
      transform: scale(1.08);
      box-shadow: 0 14px 28px rgba(0, 95, 255, 0.45);
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Bigger, more vibrant, standout FlyPay logo -->
    <svg class="logo" width="220" height="220" viewBox="0 0 220 220" fill="none" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <radialGradient id="flypay-bg" cx="50%" cy="48%" r="66%">
          <stop offset="0%" stop-color="#63e4ff" />
          <stop offset="50%" stop-color="#007bff" />
          <stop offset="100%" stop-color="#4300c9" />
        </radialGradient>
        <linearGradient id="wing-top" x1="0" y1="0" x2="1" y2="1">
          <stop offset="10%" stop-color="#ffd700"/>
          <stop offset="80%" stop-color="#ff81ad"/>
        </linearGradient>
        <linearGradient id="wing-mid" x1="1" y1="0" x2="0" y2="1">
          <stop offset="20%" stop-color="#56ffe6"/>
          <stop offset="100%" stop-color="#2d82ff"/>
        </linearGradient>
        <linearGradient id="wing-bot" x1="0" y1="1" x2="1" y2="0">
          <stop offset="0%" stop-color="#fff268"/>
          <stop offset="100%" stop-color="#fa6e31"/>
        </linearGradient>
        <filter id="shadow" x="-10%" y="-10%" width="120%" height="120%">
          <feDropShadow dx="0" dy="3" stdDeviation="3" flood-color="#001050" flood-opacity="0.3"/>
        </filter>
        <linearGradient id="text-gradient" x1="0" y1="0" x2="1" y2="0">
          <stop stop-color="#ffb347"/>
          <stop offset="33%" stop-color="#fd1d1d"/>
          <stop offset="66%" stop-color="#007bff"/>
          <stop offset="100%" stop-color="#43e97b"/>
        </linearGradient>
      </defs>
      <circle cx="110" cy="110" r="100" fill="url(#flypay-bg)" filter="url(#shadow)"/>
      <!-- Stylized wings -->
      <path d="M120 70 Q170 55 196 94 Q165 85 155 145" fill="none" stroke="url(#wing-top)" stroke-width="16" stroke-linecap="round" filter="url(#shadow)" />
      <path d="M104 95 Q140 110 180 144 Q130 120 122 180" fill="none" stroke="url(#wing-mid)" stroke-width="14" stroke-linecap="round" filter="url(#shadow)" />
      <path d="M85 115 Q110 170 156 205 Q98 167 50 184" fill="none" stroke="url(#wing-bot)" stroke-width="11" stroke-linecap="round" filter="url(#shadow)" />
      <!-- Payment Arrow -->
      <polygon points="85,160 156,107 165,138 112,184" fill="#fff" filter="url(#shadow)"/>
      <!-- Standout FlyPay text below center (big, drop-shadow, colorful) -->
      <text x="110" y="205" text-anchor="middle"
        class="logo-text-standout"
        font-family="'Poppins', Arial, sans-serif"
        font-size="40"
        font-weight="bold"
        fill="url(#text-gradient)"
        stroke="#fff"
        stroke-width="2"
        paint-order="stroke"
        style="letter-spacing:2.5px;filter:drop-shadow(0 2px 9px #0050e655);">
        FlyPay
      </text>
    </svg>
    <h1>FlyPay App</h1>
    <p>
      🚀 <span class="highlight">Start earning today</span> with simple daily tasks.<br>
      📱 Work anytime, anywhere — full flexibility.<br>
      💸 <span class="highlight">Zero investment</span> – real daily income.
    </p>
    <a class="download-btn"
       href="https://flypay.vip"
       target="_blank">
      DOWNLOAD NOW
    </a>
  </div>
</body>
</html>
