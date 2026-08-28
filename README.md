
 # STOCK-MARKET-ANALYSIS 

<div align="center">

📈 Stock Market Analysis & Visualization Dashboard
"Numbers tell stories that words often can't." 🕯️

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Analysis-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Analytics-4C72B0?style=for-the-badge)
![Status](https://img.shields.io/badge/PROJECT-LIVE-00C853?style=for-the-badge)

<br>








<br>






<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00C9A7&center=true&vCenter=true&width=700&lines=Live+Stock+Market+Analysis+%F0%9F%93%88;Tracking+RELIANCE.NS+%F0%9F%92%B9;Trend+%2B+Volatility+%2B+Correlation;Powered+by+Python+%F0%9F%90%8D" alt="Typing SVG" />

<br><br>

</div>

📚 Menu
🧠 About The Project
⚡ Live Market Snapshot
✨ Key Features
🗂️ Project Structure
🛠️ Tech Stack
🚀 Getting Started
⚙️ Configuration
📸 Sample Output
📊 Performance Insights
🗺️ Roadmap
❓ FAQ
💬 Feedback
🤝 Contributing
👩‍💻 Author
⚠️ Disclaimer
📄 License

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00C6FF,100:7B2FFF&height=130&text=🧠%20ABOUT%20THE%20PROJECT&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Learn%20what%20this%20project%20is%20all%20about&descSize=16&descAlignY=68" width="100%" />

</div>

🧠 About The Project
This is an end-to-end stock market analysis tool built in Python that downloads market data through the yfinance API and transforms it into professional-grade, publication-ready visualizations.

It automatically calculates:

📊 SMA 20

📊 SMA 50

📈 EMA 20

📉 Daily Returns

🌊 Rolling Volatility

🔥 Correlation Matrix

The project generates four clean analytical charts:

📈 Price Trend with Moving Averages

📊 Trading Volume

📉 Daily Returns Distribution

🔥 Correlation Heatmap

Whether you're a student learning quantitative finance, a hobbyist tracking stocks, or someone prototyping a larger trading system, this project provides a clean and extensible foundation.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00C853,100:00B8D4&height=130&text=⚡%20LIVE%20MARKET%20SNAPSHOT&fontSize=30&fontColor=FFFFFF&fontAlignY=43&desc=Real-Time%20Stock%20Market%20Analysis&descSize=16&descAlignY=68" width="100%" />

</div>

⚡ Live Market Snapshot
🟢 LIVE DATA

Every time this project runs, it fetches the latest available market data using the yfinance API.

<div align="center">

💹 RELIANCE.NS — LIVE PRICE
<br>

🟢 LIVE • 📡 MARKET DATA • ⚡ AUTO UPDATED

</div>

⚠️ Market prices can change continuously during trading hours. The displayed price depends on the data provided by Yahoo Finance.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF512F,100:DD2476&height=130&text=✨%20KEY%20FEATURES&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Powerful%20Analysis%20and%20Visualization%20Tools&descSize=16&descAlignY=68" width="100%" />

</div>

✨ Key Features
📥 Live Data Fetching
Latest available and historical stock data through yfinance.

📊 Moving Averages
SMA 20, SMA 50 and EMA 20.

📈 Price Trend Visualization
Closing price with moving-average overlays.

📉 Volume Analysis
Trading-volume time series.

🎯 Daily Returns Distribution
Histogram with KDE curve.

🔥 Correlation Heatmap
Correlation matrix for price, volume, returns and moving averages.

🧮 Volatility Tracking
20-day rolling volatility analysis.

🖼️ Auto-Saved Charts
High-resolution PNG outputs.

🧹 Clean Data Pipeline
Missing-value handling and MultiIndex flattening.

🔁 Ticker-Agnostic
Works with any valid Yahoo Finance ticker.

🧾 Quick Statistics
Mean, standard deviation, minimum and maximum values.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:636E72,100:2D3436&height=130&text=🗂️%20PROJECT%20STRUCTURE&fontSize=30&fontColor=FFFFFF&fontAlignY=43&desc=Clean%20and%20Simple%20Project%20Organization&descSize=16&descAlignY=68" width="100%" />

</div>

🗂️ Project Structure
stock-analysis-dashboard/
│
├── 📄 stock_analysis.py
├── 📊 price_trend_with_moving_averages.png
├── 📊 trading_volume.png
├── 📊 daily_returns_distribution.png
├── 📊 correlation_heatmap.png
├── 📄 requirements.txt
├── 📄 README.md
└── 📄 LICENSE
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00CEC9,100:0984E3&height=130&text=🛠️%20TECH%20STACK&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Technologies%20Powering%20the%20Dashboard&descSize=16&descAlignY=68" width="100%" />

</div>

🛠️ Tech Stack
🐍 Python — Core programming language.

📦 yfinance — Stock market data retrieval.

🐼 Pandas — Data manipulation and analysis.

🔢 NumPy — Numerical computation.

🎨 Matplotlib — Base plotting engine.

🌊 Seaborn — Statistical visualization and heatmaps.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FD79A8,100:E84393&height=130&text=🚀%20GETTING%20STARTED&fontSize=30&fontColor=FFFFFF&fontAlignY=43&desc=Run%20Your%20First%20Stock%20Analysis&descSize=16&descAlignY=68" width="100%" />

</div>

🚀 Getting Started
✅ Prerequisites
🐍 Python 3.9+

🌐 Internet connection

📊 A valid Yahoo Finance ticker

1️⃣ Clone the Repository
git clone https://github.com/your-username/stock-analysis-dashboard.git
cd stock-analysis-dashboard
2️⃣ Install Dependencies
pip install -r requirements.txt
Or:

pip install yfinance pandas numpy matplotlib seaborn
3️⃣ Run the Script
python stock_analysis.py
4️⃣ Output
The script automatically generates:

📈 price_trend_with_moving_averages.png

📊 trading_volume.png

📉 daily_returns_distribution.png

🔥 correlation_heatmap.png

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FDCB6E,100:FE8C00&height=130&text=⚙️%20CONFIGURATION&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Customize%20Your%20Stock%20Analysis&descSize=16&descAlignY=68" width="100%" />

</div>

⚙️ Configuration
Change these values at the top of stock_analysis.py:

TICKER = "RELIANCE.NS"
START_DATE = "2020-01-01"
END_DATE = "2024-12-31"
🌍 Exchange Examples
🇮🇳 NSE India → RELIANCE.NS

🇮🇳 BSE India → RELIANCE.BO

🇺🇸 USA → AAPL

🇺🇸 Tesla → TSLA

🇬🇧 London → HSBA.L

💡 Always use the correct Yahoo Finance ticker symbol for the exchange you want to analyze.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:A29BFE,100:6C5CE7&height=130&text=📸%20SAMPLE%20OUTPUT&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Publication-Ready%20Financial%20Visualizations&descSize=16&descAlignY=68" width="100%" />

</div>

📸 Sample Output
📈 Price Trend
SMA / EMA Overlay

📊 Volume Analysis
Trading Volume

📉 Returns Distribution
Histogram + KDE

🔥 Correlation Heatmap
Correlation Matrix

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:11998E,100:38EF7D&height=130&text=📊%20PERFORMANCE%20INSIGHTS&fontSize=31&fontColor=FFFFFF&fontAlignY=43&desc=Understand%20Market%20Trends%20and%20Volatility&descSize=16&descAlignY=68" width="100%" />
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>RELIANCE.NS · Stock Market Analysis Dashboard</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#0a0e18;
    --panel:#111726;
    --panel-2:#161d30;
    --line: rgba(232,176,75,0.14);
    --gold:#e8b04b;
    --gold-soft: rgba(232,176,75,0.35);
    --gain:#35d07f;
    --loss:#ff5c6a;
    --text:#e9edf6;
    --muted:#8b93a7;
    --mono: 'JetBrains Mono', monospace;
    --disp: 'Space Grotesk', sans-serif;
    --body: 'Inter', sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--ink);
    color:var(--text);
    font-family:var(--body);
    overflow-x:hidden;
    -webkit-font-smoothing:antialiased;
  }
  a{color:inherit;}

  /* ---------- background molecule/particle canvas ---------- */
  #bg-canvas{
    position:fixed; inset:0; width:100%; height:100%;
    z-index:0; opacity:0.55;
    pointer-events:none;
  }
  .grain{
    position:fixed; inset:0; z-index:1; pointer-events:none;
    background-image:radial-gradient(circle at 20% 20%, rgba(232,176,75,0.05), transparent 45%),
                      radial-gradient(circle at 80% 70%, rgba(53,208,127,0.05), transparent 45%);
  }

  .wrap{ position:relative; z-index:2; max-width:1120px; margin:0 auto; padding:0 28px; }

  /* ---------- nav ---------- */
  nav{
    position:sticky; top:0; z-index:20;
    backdrop-filter: blur(10px);
    background:rgba(10,14,24,0.7);
    border-bottom:1px solid var(--line);
  }
  nav .wrap{ display:flex; align-items:center; justify-content:space-between; padding:16px 28px; max-width:1120px; }
  .brand{ display:flex; align-items:center; gap:10px; font-family:var(--disp); font-weight:600; letter-spacing:0.02em; }
  .brand .dot{ width:9px; height:9px; border-radius:50%; background:var(--gain); box-shadow:0 0 10px var(--gain); animation:blink 1.6s infinite; }
  @keyframes blink{ 0%,100%{opacity:1;} 50%{opacity:0.25;} }
  .brand small{ color:var(--muted); font-family:var(--mono); font-size:11px; font-weight:400; letter-spacing:0.08em; }
  .nav-links{ display:flex; gap:26px; font-size:13px; color:var(--muted); }
  .nav-links a:hover{ color:var(--gold); }

  /* ---------- ticker tape ---------- */
  .ticker{
    position:relative; z-index:5;
    border-bottom:1px solid var(--line);
    background:linear-gradient(90deg, rgba(232,176,75,0.06), rgba(53,208,127,0.04));
    overflow:hidden; white-space:nowrap;
  }
  .ticker-track{
    display:inline-flex; gap:48px; padding:9px 0;
    animation:scroll-left 34s linear infinite;
    font-family:var(--mono); font-size:12.5px;
  }
  .ticker:hover .ticker-track{ animation-play-state:paused; }
  @keyframes scroll-left{ from{ transform:translateX(0); } to{ transform:translateX(-50%); } }
  .tk{ color:var(--muted); }
  .tk b{ color:var(--text); font-weight:500; margin:0 6px; }
  .up{ color:var(--gain); } .down{ color:var(--loss); }

  /* ---------- hero ---------- */
  header.hero{ position:relative; padding:96px 0 60px; }
  .eyebrow{
    display:inline-flex; align-items:center; gap:8px;
    font-family:var(--mono); font-size:11.5px; letter-spacing:0.16em; text-transform:uppercase;
    color:var(--gold); border:1px solid var(--gold-soft); padding:6px 12px; border-radius:100px;
    background:rgba(232,176,75,0.06);
  }
  h1.headline{
    font-family:var(--disp); font-weight:700;
    font-size:clamp(34px, 5.4vw, 60px); line-height:1.06;
    margin:22px 0 20px; max-width:820px; letter-spacing:-0.01em;
  }
  h1.headline .accent{ color:var(--gold); font-style:italic; font-weight:500; }
  .sub{ color:var(--muted); font-size:16.5px; max-width:560px; line-height:1.65; margin-bottom:34px; }
  .cta-row{ display:flex; gap:14px; flex-wrap:wrap; }
  .btn{
    font-family:var(--body); font-weight:600; font-size:14px;
    padding:13px 22px; border-radius:9px; text-decoration:none;
    display:inline-flex; align-items:center; gap:8px; transition:transform .15s ease, box-shadow .15s ease;
  }
  .btn-gold{ background:var(--gold); color:#151004; box-shadow:0 6px 24px rgba(232,176,75,0.25); }
  .btn-gold:hover{ transform:translateY(-2px); box-shadow:0 10px 28px rgba(232,176,75,0.35); }
  .btn-ghost{ border:1px solid rgba(255,255,255,0.14); color:var(--text); }
  .btn-ghost:hover{ border-color:var(--gold-soft); color:var(--gold); }

  /* ---------- live pulse panel ---------- */
  section.pulse{ padding:20px 0 70px; }
  .pulse-card{
    border:1px solid var(--line); border-radius:18px;
    background:linear-gradient(160deg, var(--panel), var(--panel-2));
    padding:30px 32px; display:grid; grid-template-columns:1.15fr 1fr; gap:28px; align-items:center;
    position:relative; overflow:hidden;
  }
  .pulse-card::before{
    content:""; position:absolute; top:-40%; right:-10%; width:280px; height:280px; border-radius:50%;
    background:radial-gradient(circle, rgba(232,176,75,0.10), transparent 70%);
  }
  .pulse-left .label{ font-family:var(--mono); font-size:12px; color:var(--muted); letter-spacing:0.08em; text-transform:uppercase; display:flex; gap:8px; align-items:center; margin-bottom:8px;}
  .live-chip{ background:rgba(53,208,127,0.12); color:var(--gain); border:1px solid rgba(53,208,127,0.35); font-size:10.5px; padding:2px 8px; border-radius:100px; letter-spacing:0.1em; }
  .price-row{ display:flex; align-items:baseline; gap:14px; flex-wrap:wrap; }
  #price{ font-family:var(--mono); font-size:46px; font-weight:700; transition:color .25s ease; }
  #delta{ font-family:var(--mono); font-size:16px; font-weight:500; }
  .stat-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:14px 26px; margin-top:22px; }
  .stat{ }
  .stat .k{ font-family:var(--mono); font-size:11px; color:var(--muted); text-transform:uppercase; letter-spacing:0.08em; }
  .stat .v{ font-family:var(--mono); font-size:17px; margin-top:3px; }
  canvas#spark{ width:100%; height:150px; display:block; }
  .pulse-right{ border-left:1px solid var(--line); padding-left:26px; }
  .pulse-right .cap{ font-size:11.5px; color:var(--muted); font-family:var(--mono); margin-top:10px; letter-spacing:0.04em; }

  /* ---------- features ---------- */
  section.features{ padding:20px 0 80px; }
  .section-head{ margin-bottom:34px; }
  .section-head .eyebrow{ margin-bottom:14px; }
  .section-head h2{ font-family:var(--disp); font-size:clamp(24px,3vw,32px); font-weight:600; }
  .section-head p{ color:var(--muted); margin-top:10px; max-width:520px; font-size:14.5px; }
  .grid{ display:grid; grid-template-columns:repeat(3, 1fr); gap:18px; }
  .card{
    border:1px solid var(--line); border-radius:14px; padding:24px 22px;
    background:rgba(255,255,255,0.015); transition:border-color .2s ease, transform .2s ease;
    position:relative;
  }
  .card:hover{ border-color:var(--gold-soft); transform:translateY(-3px); }
  .card .glyph{ width:34px; height:34px; border-radius:9px; display:flex; align-items:center; justify-content:center; font-size:16px; margin-bottom:16px; }
  .card h3{ font-family:var(--disp); font-size:16.5px; font-weight:600; margin-bottom:8px; }
  .card p{ color:var(--muted); font-size:13.5px; line-height:1.55; }
  .g-gold{ background:rgba(232,176,75,0.12); color:var(--gold); }
  .g-gain{ background:rgba(53,208,127,0.12); color:var(--gain); }
  .g-loss{ background:rgba(255,92,106,0.12); color:var(--loss); }

  /* ---------- stack ---------- */
  section.stack{ padding:10px 0 80px; text-align:center; }
  .chips{ display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin-top:22px; }
  .chip{
    font-family:var(--mono); font-size:12.5px; padding:9px 16px; border-radius:100px;
    border:1px solid var(--line); color:var(--muted); background:rgba(255,255,255,0.02);
  }

  /* ---------- footer ---------- */
  footer{ border-top:1px solid var(--line); padding:40px 0 50px; }
  footer .wrap{ display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:16px; }
  .author{ display:flex; align-items:center; gap:12px; }
  .avatar{
    width:38px; height:38px; border-radius:50%; background:conic-gradient(from 180deg, var(--gold), var(--gain), var(--gold));
    display:flex; align-items:center; justify-content:center; font-family:var(--disp); font-weight:700; font-size:14px; color:#151004;
  }
  .author .name{ font-family:var(--disp); font-weight:600; font-size:14.5px; }
  .author .role{ color:var(--muted); font-size:12px; }
  footer .disclaimer{ color:var(--muted); font-size:11.5px; max-width:420px; line-height:1.6; }

  @media (max-width: 860px){
    .pulse-card{ grid-template-columns:1fr; }
    .pulse-right{ border-left:none; border-top:1px solid var(--line); padding-left:0; padding-top:22px; }
    .grid{ grid-template-columns:1fr 1fr; }
  }
  @media (max-width: 560px){
    .grid{ grid-template-columns:1fr; }
    .stat-grid{ grid-template-columns:1fr 1fr; }
    nav .nav-links{ display:none; }
  }

  @media (prefers-reduced-motion: reduce){
    .ticker-track{ animation:none; }
    .brand .dot{ animation:none; }
  }
</style>
</head>
<body>

<canvas id="bg-canvas"></canvas>
<div class="grain"></div>

<nav>
  <div class="wrap">
    <div class="brand"><span class="dot"></span>RELIANCE.NS <small>STOCK ANALYSIS DASHBOARD</small></div>
    <div class="nav-links">
      <a href="#pulse">Live Pulse</a>
      <a href="#features">Features</a>
      <a href="#stack">Stack</a>
      <a href="#author">Author</a>
    </div>
  </div>
</nav>

<div class="ticker">
  <div class="ticker-track" id="ticker-track"></div>
</div>

<header class="hero">
  <div class="wrap">
    <span class="eyebrow">◆ Python · Quant Analysis Toolkit</span>
    <h1 class="headline">Numbers tell stories<br>that words often <span class="accent">can't.</span></h1>
    <p class="sub">An end-to-end market analysis engine — trend, volatility, and correlation
      pulled apart and put back together as clean, publication-ready charts. Built on
      yfinance, pandas, and a healthy respect for what the data actually says.</p>
    <div class="cta-row">
      <a class="btn btn-gold" href="#pulse">▸ View Live Pulse</a>
      <a class="btn btn-ghost" href="#features">See Features</a>
    </div>
  </div>
</header>

<section class="pulse" id="pulse">
  <div class="wrap">
    <div class="pulse-card">
      <div class="pulse-left">
        <div class="label"><span class="live-chip">● LIVE SIM</span> RELIANCE.NS</div>
        <div class="price-row">
          <span id="price">₹4,204.41</span>
          <span id="delta" class="up">+0.14%</span>
        </div>
        <div class="stat-grid">
          <div class="stat"><div class="k">Ann. Volatility</div><div class="v">28.29%</div></div>
          <div class="stat"><div class="k">Mean Daily Return</div><div class="v">0.135%</div></div>
          <div class="stat"><div class="k">Return Std Dev</div><div class="v">1.783</div></div>
          <div class="stat"><div class="k">Sample Size</div><div class="v">1,305d</div></div>
          <div class="stat"><div class="k">52w-style Low</div><div class="v">₹1,817.52</div></div>
          <div class="stat"><div class="k">52w-style High</div><div class="v">₹10,738.74</div></div>
        </div>
      </div>
      <div class="pulse-right">
        <canvas id="spark"></canvas>
        <div class="cap">Simulated tick stream — SMA/EMA-driven random walk, refreshed every 1.5s client-side.</div>
      </div>
    </div>
  </div>
</section>

<section class="features" id="features">
  <div class="wrap">
    <div class="section-head">
      <span class="eyebrow">◆ Under the hood</span>
      <h2>Six lenses on the same price series</h2>
      <p>Every chart answers a different question: where is it going, how rough is the ride, and what's actually driving it.</p>
    </div>
    <div class="grid">
      <div class="card"><div class="glyph g-gold">◐</div><h3>SMA 20 / SMA 50</h3><p>Short vs. medium-term trend, smoothed to cut through daily noise.</p></div>
      <div class="card"><div class="glyph g-gain">◑</div><h3>EMA 20</h3><p>A trend line that reacts faster — weights recent sessions more heavily.</p></div>
      <div class="card"><div class="glyph g-loss">◒</div><h3>Rolling Volatility</h3><p>20-day rolling std. of returns — a live read on market nervousness.</p></div>
      <div class="card"><div class="glyph g-gold">◍</div><h3>Daily Returns</h3><p>Histogram + KDE curve showing the real shape of day-to-day moves.</p></div>
      <div class="card"><div class="glyph g-gain">◔</div><h3>Correlation Heatmap</h3><p>Price, volume, returns, and moving averages — how they move together.</p></div>
      <div class="card"><div class="glyph g-loss">◕</div><h3>Volume Analysis</h3><p>Conviction behind the move — volume time series alongside price.</p></div>
    </div>
  </div>
</section>

<section class="stack" id="stack">
  <div class="wrap">
    <span class="eyebrow">◆ Built with</span>
    <div class="chips">
      <span class="chip">Python 3.x</span>
      <span class="chip">yfinance</span>
      <span class="chip">pandas</span>
      <span class="chip">NumPy</span>
      <span class="chip">Matplotlib</span>
      <span class="chip">Seaborn</span>
    </div>
  </div>
</section>

<footer id="author">
  <div class="wrap">
    <div class="author">
      <div class="avatar">KK</div>
      <div>
        <div class="name">Kavita Khushalani</div>
        <div class="role">Python · Data Analysis · Stock Market Visualization</div>
      </div>
    </div>
    <div class="disclaimer">Educational project only — not investment advice. Data via Yahoo Finance / yfinance. Markets move fast; do your own research.</div>
  </div>
</footer>

<script>
// ---------------- ticker tape content ----------------
const symbols = [
  {s:"RELIANCE.NS", c: 1},{s:"TCS.NS", c:-1},{s:"INFY.NS", c:1},
  {s:"HDFCBANK.NS", c:1},{s:"AAPL", c:-1},{s:"TSLA", c:1},
  {s:"RELIANCE.BO", c:-1},{s:"HSBA.L", c:1}
];
function renderTicker(){
  const track = document.getElementById('ticker-track');
  let html = '';
  for(let rep=0; rep<2; rep++){
    symbols.forEach(o=>{
      const pct = (Math.random()*2.6*o.c).toFixed(2);
      const cls = pct >= 0 ? 'up' : 'down';
      const arrow = pct >= 0 ? '▲' : '▼';
      html += `<span class="tk">${o.s}<b>₹${(1800+Math.random()*9000).toFixed(2)}</b><span class="${cls}">${arrow} ${Math.abs(pct)}%</span></span>`;
    });
  }
  track.innerHTML = html;
}
renderTicker();

// ---------------- live price pulse ----------------
let price = 4204.41;
const priceEl = document.getElementById('price');
const deltaEl = document.getElementById('delta');
const history = Array.from({length:60}, ()=> price);

function tick(){
  const change = (Math.random()-0.48) * 14;
  price = Math.max(50, price + change);
  history.push(price);
  history.shift();
  const pct = (change/price*100).toFixed(2);
  priceEl.textContent = '₹' + price.toLocaleString('en-IN', {minimumFractionDigits:2, maximumFractionDigits:2});
  priceEl.style.color = change >= 0 ? 'var(--gain)' : 'var(--loss)';
  deltaEl.textContent = (change>=0? '+':'') + pct + '%';
  deltaEl.className = change>=0 ? 'up' : 'down';
  drawSpark();
}
setInterval(tick, 1500);

// ---------------- sparkline ----------------
const spark = document.getElementById('spark');
const sctx = spark.getContext('2d');
function sizeSpark(){
  spark.width = spark.clientWidth * devicePixelRatio;
  spark.height = spark.clientHeight * devicePixelRatio;
}
function drawSpark(){
  sizeSpark();
  const w = spark.width, h = spark.height;
  sctx.clearRect(0,0,w,h);
  const min = Math.min(...history), max = Math.max(...history);
  const range = (max - min) || 1;
  sctx.beginPath();
  history.forEach((v,i)=>{
    const x = (i/(history.length-1)) * w;
    const y = h - ((v-min)/range) * (h*0.8) - h*0.1;
    if(i===0) sctx.moveTo(x,y); else sctx.lineTo(x,y);
  });
  const rising = history[history.length-1] >= history[0];
  sctx.strokeStyle = rising ? '#35d07f' : '#ff5c6a';
  sctx.lineWidth = 2*devicePixelRatio;
  sctx.lineJoin = 'round';
  sctx.stroke();
  // fill
  sctx.lineTo(w,h); sctx.lineTo(0,h); sctx.closePath();
  const grad = sctx.createLinearGradient(0,0,0,h);
  grad.addColorStop(0, rising ? 'rgba(53,208,127,0.18)' : 'rgba(255,92,106,0.18)');
  grad.addColorStop(1, 'rgba(0,0,0,0)');
  sctx.fillStyle = grad;
  sctx.fill();
}
window.addEventListener('resize', drawSpark);
drawSpark();

// ---------------- molecule / particle network background ----------------
const canvas = document.getElementById('bg-canvas');
const ctx = canvas.getContext('2d');
let W, H, nodes = [];
const palette = ['#e8b04b', '#35d07f', '#ff5c6a', '#8b93a7'];
const reduceMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

function resize(){
  W = canvas.width = window.innerWidth;
  H = canvas.height = window.innerHeight;
}
function initNodes(){
  const count = Math.max(26, Math.min(60, Math.floor(W/28)));
  nodes = Array.from({length:count}, ()=>({
    x:Math.random()*W, y:Math.random()*H,
    vx:(Math.random()-0.5)*0.28, vy:(Math.random()-0.5)*0.28,
    r: Math.random()*1.8+1.4,
    color: palette[Math.floor(Math.random()*palette.length)]
  }));
}
function step(){
  ctx.clearRect(0,0,W,H);
  nodes.forEach(n=>{
    n.x += n.vx; n.y += n.vy;
    if(n.x<0||n.x>W) n.vx*=-1;
    if(n.y<0||n.y>H) n.vy*=-1;
  });
  for(let i=0;i<nodes.length;i++){
    for(let j=i+1;j<nodes.length;j++){
      const a=nodes[i], b=nodes[j];
      const dx=a.x-b.x, dy=a.y-b.y;
      const dist=Math.sqrt(dx*dx+dy*dy);
      if(dist<130){
        ctx.strokeStyle = `rgba(232,176,75,${(1-dist/130)*0.16})`;
        ctx.lineWidth=1;
        ctx.beginPath(); ctx.moveTo(a.x,a.y); ctx.lineTo(b.x,b.y); ctx.stroke();
      }
    }
  }
  nodes.forEach(n=>{
    ctx.beginPath();
    ctx.fillStyle = n.color;
    ctx.globalAlpha = 0.85;
    ctx.arc(n.x,n.y,n.r,0,Math.PI*2);
    ctx.fill();
    ctx.globalAlpha = 1;
  });
  if(!reduceMotion) requestAnimationFrame(step);
}
resize(); initNodes();
requestAnimationFrame(step);
window.addEventListener('resize', ()=>{ resize(); initNodes(); });
</script>

</body>
</html>

</div>


📊 Performance Insights
📈 Trend Analysis
Identify upward and downward price trends.

📊 Moving Average Analysis
Compare short-term and medium-term trends.

🌊 Volatility Analysis
Track changes in market volatility.

📉 Return Analysis
Study daily return behavior and distribution.

🔥 Correlation Analysis
Understand relationships between market variables.

💹 Volume Analysis
Observe changes in trading activity.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:81ECEC,100:00CEC9&height=130&text=🗺️%20ROADMAP&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=Future%20Improvements%20and%20New%20Features&descSize=16&descAlignY=68" width="100%" />

</div>

🗺️ Roadmap
🔲 Interactive Dashboard

🔲 Multiple Stock Comparison

🔲 Technical Indicators

🔲 RSI & MACD Analysis

🔲 Candlestick Charts

🔲 Portfolio Tracking

🔲 Automated Reports

🔲 Streamlit Web Application

🔲 Real-Time Alerts

🔲 Advanced Risk Analysis

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6A11CB,100:2575FC&height=130&text=❓%20FAQ&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=Frequently%20Asked%20Questions&descSize=16&descAlignY=68" width="100%" />

</div>

❓ FAQ
❓ Can I analyze another stock?
Yes. Change the TICKER value to any valid Yahoo Finance ticker.

❓ Can I use Indian stocks?
Yes. For example:

RELIANCE.NS
TCS.NS
INFY.NS
HDFCBANK.NS
❓ Does the project save the charts?
Yes. All four visualizations are automatically saved as PNG files.

❓ Can I change the analysis period?
Yes. Update the START_DATE and END_DATE values in stock_analysis.py.

❓ Is this project suitable for beginners?
Yes. It is designed as a simple and extensible foundation for learning Python, data analysis, visualization, and basic quantitative finance.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00B09B,100:96C93D&height=130&text=💬%20FEEDBACK&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=Your%20Ideas%20and%20Suggestions%20Matter&descSize=16&descAlignY=68" width="100%" />

</div>

💬 Feedback
💡 Your feedback is always welcome!

📝 Suggestions — Share your ideas for improving the project.

🐛 Bug Reports — Let me know if you find any issues.

✨ Feature Requests — Suggest new analysis or visualization features.

📈 Improvement Ideas — Help make the dashboard better and more useful.

⭐ Support the Project — If you like this project, consider giving it a Star on GitHub.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FC466B,100:3F5EFB&height=130&text=🤝%20CONTRIBUTING&fontSize=32&fontColor=FFFFFF&fontAlignY=43&desc=Help%20Make%20This%20Project%20Better&descSize=16&descAlignY=68" width="100%" />

</div>

🤝 Contributing
Contributions are welcome!

1️⃣ Fork the repository.

2️⃣ Create a new branch.

3️⃣ Make your changes.

4️⃣ Commit your changes.

5️⃣ Push your changes.

6️⃣ Open a Pull Request.

Every contribution, suggestion, and improvement is appreciated. ❤️

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7F00FF,100:E100FF&height=130&text=👩%E2%80%8D💻%20AUTHOR&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=Created%20with%20Passion%20for%20Data%20and%20Finance&descSize=16&descAlignY=68" width="100%" />

</div>

👩‍💻 Author
<div align="center">

✨ Kavita ✨
🐍 Python

📊 Data Analysis

📈 Stock Market Visualization

💻 Data Science

🚀 Financial Data Analytics

<br>

Built with ❤️ using Python and Data Visualization.

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF8008,100:FFC837&height=130&text=⚠️%20DISCLAIMER&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=For%20Educational%20and%20Analytical%20Purposes&descSize=16&descAlignY=68" width="100%" />

</div>

⚠️ Disclaimer
📚 Educational Purpose
This project is created for learning, analysis, and educational purposes.

📡 Market Data
Data is obtained through Yahoo Finance using the yfinance library.

⚠️ No Investment Advice
The information and visualizations generated by this project should not be considered financial or investment advice.

📈 Market Risk
Stock prices and market conditions can change rapidly.

💡 Do Your Own Research
Always conduct your own research before making any investment decision.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:232526,100:414345&height=130&text=📄%20LICENSE&fontSize=34&fontColor=FFFFFF&fontAlignY=43&desc=Open%20Source%20Project&descSize=16&descAlignY=68" width="100%" />

</div>

📄 License
This project is available under the MIT License.

You are free to use, modify, and distribute this project according to the terms of the license.

<div align="center">

📈 Stock Market Analysis & Visualization Dashboard
"Numbers tell stories that words often can't." 🕯️
<br>

🐍 Python • 📊 Data Analysis • 📈 Finance • 🎨 Visualization

<br><br>







<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,50:0984E3,100:6C5CE7&height=200&section=header&text=🙏%20THANK%20YOU%20FOR%20VISITING&fontSize=36&fontColor=FFFFFF&fontAlignY=35&desc=Hope%20this%20project%20added%20value%20to%20your%20journey&descSize=18&descAlignY=55&animation=fadeIn" width="100%" />

<br>

![Visitor Badge](https://img.shields.io/badge/📊_MARKET-BULLISH-00C853?style=for-the-badge)
![Made With](https://img.shields.io/badge/MADE_WITH-☕_%2B_🐍-6C5CE7?style=for-the-badge)
![Stars](https://img.shields.io/badge/⭐_STAR_THIS-REPO-FFD700?style=for-the-badge)

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF6B6B,50:C44569,100:6C5CE7&height=150&text=👩‍💻%20AUTHOR%20%3A%20KAVITA%20KHUSHALANI&fontSize=26&fontColor=FFFFFF&fontAlignY=45&desc=Python%20%7C%20Data%20Analysis%20%7C%20Stock%20Market%20Visualization&descSize=15&descAlignY=70" width="100%" />

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=1200&color=FFD700&center=true&vCenter=true&width=650&lines=%22Invest+in+knowledge%2C+it+pays+the+best+interest%22+%F0%9F%92%B0;See+you+at+the+next+market+close+%F0%9F%94%94;Built+with+%E2%9D%A4%EF%B8%8F+by+Kavita+Khushalani" alt="Closing Typing SVG" />

<br><br>

![Profile Views](https://komarev.com/ghpvc/?username=your-username&label=Profile%20Views&color=00C9A7&style=for-the-badge)

</div>
⭐ If you like this project, don't forget to Star it! ⭐

![Made With Python](https://img.shields.io/badge/MADE%20WITH-PYTHON-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Data Driven](https://img.shields.io/badge/DATA-DRIVEN-FF6F00?style=for-the-badge)
![Analytics](https://img.shields.io/badge/ANALYTICS-POWERED-8A2BE2?style=for-the-badge)
![Completed](https://img.shields.io/badge/STATUS-COMPLETED-00C853?style=for-the-badge)
</div>
