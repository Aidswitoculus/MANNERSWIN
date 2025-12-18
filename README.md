<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CashWave - Online Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #e5e7eb;
      margin: 0;
      padding: 0;
    }
    header {
      background: #020617;
      padding: 25px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
      color: #22c55e;
    }
    header p {
      margin: 5px 0 0 0;
      font-size: 1rem;
      color: #9ca3af;
    }
    main {
      max-width: 900px;
      margin: 20px auto;
      padding: 0 15px;
    }
    .card {
      background: #020617;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 8px 15px rgba(0,0,0,0.3);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-3px);
    }
    .card h2 {
      margin-top: 0;
      font-size: 1.5rem;
    }
    .card p {
      font-size: 1rem;
      margin-bottom: 15px;
    }
    .card button {
      background: #22c55e;
      color: #022c22;
      border: none;
      padding: 12px 20px;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.2s;
    }
    .card button:hover {
      background: #16a34a;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
      color: #9ca3af;
      margin-top: 40px;
      font-size: 0.9rem;
    }
    @media(max-width:600px){
      header h1 {
        font-size: 1.6rem;
      }
      .card h2 {
        font-size: 1.3rem;
      }
      .card button {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>CashWave</h1>
    <p>Your online hub for trending products and instant payments</p>
  </header>

  <main>
    <!-- Affiliate Section -->
    <div class="card">
      <h2>💸 Hot Products</h2>
      <p>Check out these trending products and earn perks.</p>
      <a href="https://www.amazon.com/dp/B09G3HRMVB" target="_blank">
        <button>Buy This Product</button>
      </a>
      <a href="https://www.amazon.com/dp/B08N5WRWNW" target="_blank">
        <button>Buy This Product</button>
      </a>
    </div>

    <!-- Cash App Section -->
    <div class="card">
      <h2>📄 Send Money</h2>
      <p>Support CashWave or purchase products instantly using Cash App.</p>
      <a href="https://cash.app/$IMHIMDEAN" target="_blank">
        <button>Send Money</button>
      </a>
    </div>

    <!-- Ads Section -->
    <div class="card">
      <h2>📢 Sponsored Ads</h2>
      <p>Display ads once your site gets traffic. Replace this link with Google AdSense later.</p>
      <a href="https://www.google.com/" target="_blank">
        <button>Enable Ads</button>
      </a>
    </div>
  </main>

  <footer>
    © 2025 CashWave | Built by IMHIMDEAN
  </footer>
</body>
</html>
