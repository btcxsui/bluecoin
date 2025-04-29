<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bluecoin - The Ultimate Store of Value</title>
  <style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: #F3F4F6;
      color: #1F2937;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background: #1E3A8A;
      color: #FFFFFF;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }
    .nav-links {
      display: flex;
      gap: 1.5rem;
      list-style: none;
    }
    .nav-links a {
      color: #FFFFFF;
      text-decoration: none;
      font-size: 1rem;
    }
    .nav-links a:hover {
      text-decoration: underline;
    }

    /* Hero Section */
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #1E3A8A, #60A5FA);
      color: #FFFFFF;
      text-align: center;
      position: relative;
    }
    .hero-content h1 {
      font-size: 3.5rem;
      margin-bottom: 1rem;
    }
    .hero-content p {
      font-size: 1.3rem;
      margin-bottom: 2rem;
    }
    .cta-buttons .btn {
      padding: 0.8rem 1.5rem;
      border-radius: 5px;
      text-decoration: none;
      margin: 0 0.5rem;
      font-weight: bold;
    }
    .btn.primary {
      background: #FBBF24;
      color: #1F2937;
    }
    .btn.secondary {
      background: transparent;
      border: 1px solid #FFFFFF;
      color: #FFFFFF;
    }
    .btn:hover {
      opacity: 0.9;
      transform: scale(1.05);
      transition: all 0.3s ease;
    }

    /* Coin Animation (Simplified CSS) */
    .coin-animation {
      position: absolute;
      top: 20%;
      left: 50%;
      transform: translateX(-50%);
      width: 100px;
      height: 100px;
      background: radial-gradient(circle, #60A5FA, #1E3A8A);
      border-radius: 50%;
      animation: spin 4s linear infinite;
    }
    @keyframes spin {
      0% { transform: translateX(-50%) rotate(0deg); }
      100% { transform: translateX(-50%) rotate(360deg); }
    }

    /* Features Section */
    .features {
      padding: 4rem 2rem;
      text-align: center;
      background: #FFFFFF;
    }
    .features h2 {
      font-size: 2.5rem;
      margin-bottom: 2rem;
    }
    .feature-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }
    .feature-card {
      background: #F3F4F6;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .feature-card h3 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
      color: #1E3A8A;
    }

    /* Charts Section */
    .charts {
      padding: 4rem 2rem;
      background: #F3F4F6;
      text-align: center;
    }
    .charts h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .chart-container {
      max-width: 100%;
      height: 400px;
      margin: 0 auto;
      border: 1px solid #1E3A8A;
      border-radius: 10px;
      overflow: hidden;
    }

    /* Footer */
    .footer {
      background: #1E3A8A;
      color: #FFFFFF;
      padding: 2rem;
      text-align: center;
    }
    .footer-links {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-bottom: 1rem;
    }
    .footer-links a {
      color: #FFFFFF;
      text-decoration: none;
    }
    .footer-links a:hover {
      text-decoration: underline;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .hero-content h1 {
        font-size: 2rem;
      }
      .hero-content p {
        font-size: 1rem;
      }
      .nav-links {
        flex-direction: column;
        gap: 0.5rem;
      }
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar">
    <div class="logo">Bluecoin</div>
    <ul class="nav-links">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#specs">Specifications</a></li>
      <li><a href="#ecosystem">Ecosystem</a></li>
      <li><a href="#buy">Buy</a></li>
      <li><a href="#community">Community</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="coin-animation"></div>
    <div class="hero-content">
      <h1>Bluecoin: The Ultimate Store of Value</h1>
      <p>Combining Bitcoin’s strength with Sui’s lightning-fast efficiency</p>
      <div class="cta-buttons">
        <a href="https://tinyurl.com/BitcoinxSuix" class="btn primary">Buy Bluecoin</a>
        <a href="#about" class="btn secondary">Learn More</a>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="features">
    <h2>Why Bluecoin?</h2>
    <div class="feature-grid">
      <div class="feature-card">
        <h3>Hybrid Consensus</h3>
        <p>PoW + PoS for unmatched security and efficiency.</p>
      </div>
      <div class="feature-card">
        <h3>150,000 TPS</h3>
        <p>Lightning-fast transactions for DeFi and gaming.</p>
      </div>
      <div class="feature-card">
        <h3>Limited Supply</h3>
        <p>210 billion coins with deflationary burning.</p>
      </div>
    </div>
  </section>

  <!-- Charts Section -->
  <section id="charts" class="charts">
    <h2>Track Bluecoin</h2>
    <div class="chart-container">
      <iframe src="https://dexscreener.com/sui/0x7c3c96ced34b6bb02677467a9b305335a4681ca744cfadaa516884748fcbbad8" width="100%" height="100%" frameborder="0"></iframe>
    </div>
    <p style="font-size: 0.9rem; margin-top: 1rem;">Price data provided by Dexscreener.</p>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="footer-links">
      <a href="https://t.me/BitcoinxSui">Telegram</a>
      <a href="https://x.com/BitcoinxSui">X</a>
      <a href="https://t.me/joshhtg">Contact Dev</a>
    </div>
    <p>© 2025 Bluecoin. All rights reserved.</p>
  </footer>

  <script>
    // Smooth scroll for nav links
    document.querySelectorAll('.nav-links a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        target.scrollIntoView({ behavior: 'smooth' });
      });
    });
  </script>
</body>
</html>
