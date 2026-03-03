<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Abhishek Sharma | Frontend Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
  scroll-behavior: smooth;
}

body {
  background: linear-gradient(135deg, #0f172a, #111827);
  color: #e5e7eb;
}

nav {
  position: fixed;
  width: 100%;
  top: 0;
  background: rgba(15, 23, 42, 0.9);
  backdrop-filter: blur(10px);
  padding: 15px 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 1000;
}

nav h2 {
  color: #38bdf8;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 30px;
}

nav ul li a {
  text-decoration: none;
  color: #e5e7eb;
  font-weight: 500;
  transition: 0.3s;
}

nav ul li a:hover {
  color: #38bdf8;
}

section {
  padding: 120px 80px;
  min-height: 100vh;
}

.hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 15px;
}

.hero h3 {
  color: #38bdf8;
  margin-bottom: 20px;
}

.btn-group a {
  display: inline-block;
  margin-right: 15px;
  padding: 10px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s;
}

.btn-primary {
  background: #38bdf8;
  color: #0f172a;
}

.btn-primary:hover {
  background: #0ea5e9;
}

.btn-outline {
  border: 1px solid #38bdf8;
  color: #38bdf8;
}

.btn-outline:hover {
  background: #38bdf8;
  color: #0f172a;
}

.section-title {
  font-size: 32px;
  margin-bottom: 30px;
  color: #38bdf8;
}

.card {
  background: #1f2937;
  padding: 25px;
  border-radius: 15px;
  margin-bottom: 25px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
  background: #273549;
}

.metrics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 20px;
}

.metric-box {
  background: #1f2937;
  padding: 25px;
  border-radius: 15px;
  text-align: center;
}

.metric-box h2 {
  color: #38bdf8;
  font-size: 28px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #0f172a;
  color: #9ca3af;
}
</style>
</head>

<body>

<nav>
  <h2>Abhishek</h2>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#impact">Impact</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="home" class="hero">
  <h1>Abhishek Sharma</h1>
  <h3>Frontend Engineer | React.js Specialist</h3>
  <p>
    Building scalable digital platforms that eliminate manual workflows and enable
    enterprise-grade operational visibility.
  </p>
  <br/>
  <div class="btn-group">
    <a href="https://portfolio-ten-ashen-10.vercel.app/" class="btn-primary">View Portfolio</a>
    <a href="https://www.linkedin.com/in/abbysharma2002/" class="btn-outline">LinkedIn</a>
  </div>
</section>

<!-- IMPACT -->
<section id="impact">
  <h2 class="section-title">Engineering Impact</h2>

  <div class="metrics">
    <div class="metric-box">
      <h2>25%</h2>
      <p>Paperwork Reduced (BIADA Phase 1)</p>
    </div>

    <div class="metric-box">
      <h2>75%</h2>
      <p>Target Digital Transformation (Phase 2)</p>
    </div>

    <div class="metric-box">
      <h2>40%</h2>
      <p>Frontend Performance Boost</p>
    </div>

    <div class="metric-box">
      <h2>60%</h2>
      <p>Faster Deployment Cycle</p>
    </div>

    <div class="metric-box">
      <h2>1K+</h2>
      <p>Active Users Served</p>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <h2 class="section-title">Projects</h2>

  <div class="card">
    <h3>BIADA Digital Survey Ecosystem</h3>
    <p>
      Architected and developed a full digital survey platform replacing
      paper-based industrial surveys for Bihar Industrial Area Development Authority.
      The system integrates dynamic survey modules, real-time APIs, interactive dashboards,
      and automated Excel reporting.
      Phase 1 reduced paperwork by 25%, with Phase 2 targeting 75% digitization.
    </p>
  </div>

  <div class="card">
    <h3>Enterprise Analytics Dashboards</h3>
    <p>
      Designed high-performance interactive dashboards using modern JavaScript libraries.
      Enabled real-time data visualization and administrative decision-making
      through optimized React component architecture.
    </p>
  </div>

  <div class="card">
    <h3>Wedding Management Platforms (Freelance)</h3>
    <p>
      Built secure backend APIs using Java and integrated them into
      scalable frontend dashboards. Delivered production-ready,
      responsive systems with structured admin monitoring panels.
    </p>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <h2 class="section-title">Core Skills</h2>

  <div class="card">
    <p><strong>Frontend:</strong> HTML, CSS, JavaScript, React.js, Next.js, Tailwind, Bootstrap</p>
    <p><strong>Backend:</strong> Java, REST APIs, Node.js</p>
    <p><strong>Database:</strong> MySQL</p>
    <p><strong>Tools:</strong> Git, GitHub, VS Code</p>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2 class="section-title">Contact</h2>

  <div class="card">
    <p>Email: shabhishek411@gmail.com</p>
    <p>Location: Ghaziabad, India</p>
  </div>
</section>

<footer>
  © 2026 Abhishek Sharma | Frontend Engineer
</footer>

</body>
</html>
