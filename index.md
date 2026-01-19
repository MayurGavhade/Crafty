---
layout: default
title: Crafty – AI Writing Chrome Extension
---

<style>
:root {
  --bg: radial-gradient(circle at top, #0f172a, #020617);
  --glass: rgba(255, 255, 255, 0.08);
  --border: rgba(255, 255, 255, 0.15);
  --text: #e5e7eb;
  --muted: #9ca3af;
  --accent: #38bdf8;
  --glow: 0 0 25px rgba(56, 189, 248, 0.35);
}

body {
  background: var(--bg);
  color: var(--text);
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
               Roboto, Ubuntu, Cantarell;
}

.main-content {
  max-width: 1100px;
}

.hero {
  text-align: center;
  padding: 4.5rem 1rem 3rem;
}

.hero h1 {
  font-size: 3.2rem;
  letter-spacing: -0.03em;
}

.hero p {
  font-size: 1.2rem;
  color: var(--muted);
  margin-top: 0.5rem;
}

.btn-download {
  display: inline-block;
  margin-top: 2rem;
  padding: 0.9rem 1.6rem;
  background: linear-gradient(135deg, #38bdf8, #0ea5e9);
  color: #020617;
  border-radius: 14px;
  font-weight: 700;
  text-decoration: none;
  box-shadow: var(--glow);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.btn-download:hover {
  transform: translateY(-4px) scale(1.02);
  box-shadow: 0 0 35px rgba(56, 189, 248, 0.6);
}

.section {
  margin-top: 4.5rem;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 1.2rem;
}

.card {
  background: var(--glass);
  border: 1px solid var(--border);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
  padding: 1.4rem;
  border-radius: 18px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-6px) scale(1.02);
  box-shadow: var(--glow);
}

.steps li {
  margin-bottom: 0.7rem;
  color: var(--muted);
}

.footer {
  margin-top: 5rem;
  text-align: center;
  color: var(--muted);
  font-size: 0.9rem;
}

.footer a {
  color: var(--accent);
  text-decoration: none;
}
</style>

<div class="hero">
  <h1>✨ Crafty</h1>
  <p>AI-powered long-form writing, right inside your Chrome sidebar</p>

  <a class="btn-download" href="/Crafty/crafty.zip">
  ⬇ Download Crafty Extension
  </a>
</div>

<div class="section">
  <h2>🚀 Why Crafty?</h2>

  <div class="cards">
    <div class="card">
      <h3>✍ Long Writing</h3>
      <p>Generate rich paragraphs and descriptions in seconds.</p>
    </div>

    <div class="card">
      <h3>🎚 Tone Selector</h3>
      <p>Professional, casual, creative, or technical output.</p>
    </div>

    <div class="card">
      <h3>🌙 Dark Mode</h3>
      <p>Automatically matches your system theme.</p>
    </div>

    <div class="card">
      <h3>🔐 Privacy First</h3>
      <p>Your API key never leaves your browser.</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>📦 Installation Guide</h2>

  <ol class="steps">
    <li>Download <strong>crafty.zip</strong></li>
    <li>Extract the ZIP file</li>
    <li>Open <code>chrome://extensions</code></li>
    <li>Enable <strong>Developer Mode</strong></li>
    <li>Click <strong>Load unpacked</strong></li>
    <li>Select the extracted Crafty folder</li>
  </ol>
</div>

<div class="section">
  <h2>👤 About the Developer</h2>

  <div class="card">
    <h3>Mayur (Mayur Dev)</h3>
    <p>Student developer building AI-powered
