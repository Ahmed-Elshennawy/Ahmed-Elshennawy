<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ahmed L. Shennawy | Flutter Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 50px 20px;
      animation: fadeIn 1.5s ease-in-out;
    }
    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      background: linear-gradient(to right, #00f2fe, #4facfe);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      animation: fadeInUp 1.2s ease-in-out;
    }
    h2 {
      color: #4facfe;
      border-bottom: 2px solid #4facfe;
      padding-bottom: 10px;
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 20px;
      box-shadow: 0 0 15px rgba(79, 172, 254, 0.3);
      transition: 0.3s ease-in-out;
    }
    .card:hover {
      transform: scale(1.02);
      box-shadow: 0 0 25px rgba(79, 172, 254, 0.6);
    }
    a {
      color: #00f2fe;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(40px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

  <header>
    <h1>Ahmed L. Shennawy</h1>
    <p>Mobile Application Developer | Flutter | Firebase | UI Lover 🚀</p>
  </header>

  <section>
    <h2>🚀 About Me</h2>
    <div class="card">
      <p>I'm a passionate <strong>Flutter Developer</strong> focused on building smooth, responsive, and user-friendly mobile apps. I care about performance, clean architecture, and great design. I'm currently pursuing my B.Sc. in Computer Science & AI at Damietta University (2021–2025).</p>
    </div>

    <h2>🛠️ Skills & Tools</h2>
    <div class="card">
      <p><strong>Languages:</strong> Dart, Python, Java, SQL</p>
      <p><strong>Mobile:</strong> Flutter, Firebase, Stripe</p>
      <p><strong>Storage:</strong> Hive, Shared Preferences</p>
      <p><strong>State Management:</strong> Cubit, Provider, GetX</p>
      <p><strong>Others:</strong> Git, GitHub, MySQL, Clean Architecture</p>
    </div>

    <h2>📱 Projects</h2>
    <div class="card">
      <p><strong>Medical Appointment App:</strong> Booking, payments via Stripe, dual UI for doctor/patient, Firebase Notifications.</p>
      <p><strong>Chat Module:</strong> WebSocket, text/voice/image messaging, seen & reply, video calls via Zego.</p>
      <p><strong>Restaurant & Grocery Apps:</strong> Admin panel, orders, cart, local API integration.</p>
    </div>

    <h2>🎓 Training & Achievements</h2>
    <div class="card">
      <p><strong>ITI Summer Flutter Training (2024):</strong> Built a complete e-commerce app.</p>
      <p><strong>Digital Egypt Pioneers:</strong> Full mobile track + freelancing + English.</p>
      <p><strong>Athr Internship:</strong> Practical Flutter experience in November 2024.</p>
      <p><strong>ICPC Participant:</strong> Enhanced problem-solving and speed under pressure.</p>
    </div>

    <h2>📬 Contact</h2>
    <div class="card">
      <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
    </div>
  </section>

</body>
</html>
