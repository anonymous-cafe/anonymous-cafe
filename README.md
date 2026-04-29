<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>anonymous-cafe | Ecommerce Growth</title>

<style>
body {
  margin: 0;
  font-family: 'Courier New', monospace;
  background: #0a0a0a;
  color: #eaeaea;
  overflow-x: hidden;
}

/* Glow effect */
.glow {
  color: #d4af37;
  text-shadow: 0 0 5px #d4af37, 0 0 10px #d4af37;
}

/* Hero */
.hero {
  text-align: center;
  padding: 120px 20px;
}

/* Typing animation */
.typing {
  font-size: 28px;
  border-right: 2px solid #d4af37;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  animation: typing 4s steps(40, end) forwards, blink 1s infinite;
}

@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink {
  50% { border-color: transparent }
}

/* Button */
.btn {
  display: inline-block;
  margin-top: 30px;
  padding: 12px 30px;
  border: 1px solid #d4af37;
  color: #d4af37;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  background: #d4af37;
  color: #000;
  box-shadow: 0 0 15px #d4af37;
}

/* Sections */
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 60px 0;
}

.section {
  margin-top: 80px;
}

/* Cards */
.card {
  background: #111;
  padding: 25px;
  margin-top: 20px;
  border-left: 3px solid #d4af37;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 15px rgba(212,175,55,0.3);
}

/* Fade animation */
.fade {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeIn 1s forwards;
}

.fade:nth-child(1) { animation-delay: 0.3s; }
.fade:nth-child(2) { animation-delay: 0.6s; }
.fade:nth-child(3) { animation-delay: 0.9s; }

@keyframes fadeIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Footer */
.footer {
  text-align: center;
  margin: 80px 0;
  color: #666;
}
</style>
</head>

<body>

<div class="hero">
  <h1 class="glow">anonymous-cafe</h1>

  <div class="typing glow">
    Scaling Ecommerce Brands Profitably...
  </div>

  <a href="#" class="btn">Book a Call</a>
</div>

<div class="container">

  <div class="section fade">
    <h2 class="glow">About</h2>
    <p>
      I build high-performance ad systems with precise tracking.
      No guesswork. Only data-driven scaling.
    </p>
  </div>

  <div class="section fade">
    <h2 class="glow">Results</h2>

    <div class="card">
      ROAS: 4.8x <br>
      Revenue: +140% <br>
      CPA: -38%
    </div>

    <div class="card">
      Lead Cost: -48% <br>
      Conversion Rate: +67%
    </div>

  </div>

  <div class="section fade">
    <h2 class="glow">System</h2>
    <p>
      Tracking → Data → Testing → Scaling → Profit
    </p>
  </div>

  <div class="section fade">
    <h2 class="glow">Contact</h2>
    <p>Email: your@email.com</p>
    <p>Calendly: your-link</p>
  </div>

</div>

<div class="footer">
  █▓▒░ SYSTEM READY ░▒▓█
</div>

</body>
</html>
