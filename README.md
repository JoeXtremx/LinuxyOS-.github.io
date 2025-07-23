<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Water Wise, Future Bright</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }

    body {
      background: linear-gradient(to bottom, #e0f7fa, #ffffff);
      overflow-x: hidden;
      color: #003366;
      position: relative;
    }

    .animated-bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      overflow: hidden;
    }

    .wave {
      position: absolute;
      width: 200%;
      height: 200px;
      background: rgba(0, 183, 255, 0.2);
      border-radius: 43%;
      animation: waveAnim 10s infinite linear;
    }

    .wave:nth-child(2) {
      animation-delay: -5s;
      background: rgba(0, 183, 255, 0.15);
    }

    @keyframes waveAnim {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    header {
      background: #0077b6;
      color: white;
      padding: 30px 20px;
      text-align: center;
      animation: fadeInDown 1s ease-out;
    }

    header img {
      width: 120px;
      animation: bounce 2s infinite;
    }

    header h1 {
      font-size: 2.8rem;
      margin-top: 15px;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      background: #00a6c9;
      padding: 10px;
    }

    nav button {
      background: white;
      border: none;
      padding: 10px 20px;
      font-weight: bold;
      border-radius: 8px;
      color: #0077b6;
      cursor: pointer;
      transition: background 0.3s;
    }

    nav button:hover {
      background: #cceeff;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeInUp 1s ease-in;
    }

    h2 {
      font-size: 2rem;
      color: #004d66;
      margin-bottom: 15px;
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.8s ease-in-out;
    }

    p, ul, .cta, .more-buttons {
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.8s ease-in-out;
    }

    .show { opacity: 1 !important; transform: translateY(0) !important; }

    ul {
      margin-bottom: 20px;
      padding-left: 20px;
    }

    .highlight {
      background: #d0f0ff;
      padding: 10px;
      border-left: 4px solid #0077b6;
      margin-bottom: 30px;
    }

    .cta {
      background: #00b4d8;
      color: white;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      font-size: 1.3rem;
      margin: 30px 0;
      animation: pulse 2s infinite;
    }

    .more-buttons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-top: 30px;
    }

    .more-buttons button {
      background: #0077b6;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
    }

    .more-buttons button:hover {
      background: #005f8e;
    }

    .back-to-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #0077b6;
      color: white;
      border: none;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      font-size: 24px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    footer {
      background: #0077b6;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <div class="animated-bg">
    <div class="wave"></div>
    <div class="wave"></div>
  </div>

  <header>
    <img src="logopng" alt="Water Wise Logo" />
    <h1>Water Wise, Future Bright</h1>
  </header>

  <nav>
    <button onclick="scrollToSection('why')">Why Save Water?</button>
    <button onclick="scrollToSection('action')">Take Action</button>
    <button onclick="scrollToSection('join')">Join Us</button>
    <button onclick="scrollToSection('tips')">Tips</button>
    <button onclick="scrollToSection('danger')">Dangers</button>
    <button onclick="scrollToSection('schools')">For Schools</button>
    <button onclick="scrollToSection('global')">Global Stats</button>
    <button onclick="scrollToSection('success')">Success Stories</button>
  </nav>

  <section>
    <div class="highlight">
      <h2>💧 Campaign Mission</h2>
      <p>Water isn’t just a resource – it’s life, it’s survival, it’s love. When we waste it, we erase futures. When we protect it, we preserve humanity. Every drop you save is a heartbeat for our planet.</p>
    </div>

    <h2 id="why">🌍 Why Save Water?</h2>
    <p>Freshwater is only 2.5% of the total water on Earth. Much of it is frozen or unreachable. Wasting water today means facing scarcity tomorrow. It affects food, health, nature, and survival.</p>

    <h2 id="danger">⚠️ Dangers of Water Scarcity</h2>
    <ul>
      <li>Increased disease and health issues</li>
      <li>Food insecurity due to droughts</li>
      <li>Economic damage and poverty</li>
      <li>Conflict over resources</li>
    </ul>

    <h2 id="action">🔧 Take Action Now</h2>
    <ul>
      <li>Fix leaks in pipes and taps immediately</li>
      <li>Switch to drip irrigation in agriculture</li>
      <li>Reduce water use in industrial processes</li>
      <li>Advocate for water protection policies</li>
    </ul>

    <div class="cta">🌊 Join the #WaterWise Movement – Your Future Deserves It</div>

    <h2 id="join">🤝 Join the Movement</h2>
    <p>Get involved by signing up for campaigns, participating in clean-up events, or donating to clean water charities. Everyone has a role to play, no matter where you are.</p>

    <div class="more-buttons">
      <button>💌 Subscribe</button>
      <button>📅 Attend Events</button>
      <button>🎁 Donate</button>
      <button>📲 Share</button>
      <button>🧠 Learn</button>
      <button>🙋 Volunteer</button>
      <button>🌐 Become Ambassador</button>
      <button>📖 Read Stories</button>
    </div>

    <h2 id="tips">💡 Smart Tips to Save Water</h2>
    <ul>
      <li>Turn off the tap while brushing your teeth</li>
      <li>Install low-flow showerheads</li>
      <li>Water plants in the early morning</li>
      <li>Harvest rainwater for gardening</li>
      <li>Use a broom instead of hose for cleaning driveways</li>
    </ul>

    <h2 id="schools">🏫 Schools & Youth</h2>
    <p>Teachers and students can run water audits, launch school campaigns, and start garden irrigation projects using greywater. Youth voices are powerful – speak up!</p>

    <h2 id="global">🌐 Global Water Facts</h2>
    <ul>
      <li>1 in 3 people lack safe drinking water</li>
      <li>By 2025, half the world’s population will live in water-stressed areas</li>
      <li>Women and girls spend 200 million hours daily collecting water</li>
    </ul>

    <h2 id="success">🎉 Real Success Stories</h2>
    <p>Kenya’s community wells, India’s rainwater revival, and U.S. cities reducing consumption by 30% prove change is possible. Be part of the success.</p>
  </section>

  <button class="back-to-top" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });">↑</button>

  <footer>
    © 2025 Water Wise Campaign | Designed with 💧 by Earth for Earth
  </footer>

  <script>
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        }
      });
    }, { threshold: 0.2 });

    document.querySelectorAll('h2, p, ul, .cta, .more-buttons').forEach(el => {
      observer.observe(el);
    });

    function scrollToSection(id) {
      const el = document.getElementById(id);
      if (el) {
        el.scrollIntoView({ behavior: 'smooth' });
      }
    }
  </script>
</body>
</html>
