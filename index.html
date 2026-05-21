<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Notion OS — Beginner to Master Template</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400&family=DM+Mono:wght@300;400;500&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet"/>
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --card: #16161f;
    --border: #2a2a3a;
    --accent: #c8ff4a;
    --accent2: #ff6b35;
    --accent3: #7b6cff;
    --text: #f0f0f5;
    --muted: #8888a0;
    --glow: rgba(200,255,74,0.15);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Syne', sans-serif;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    width: 12px; height: 12px;
    background: var(--accent);
    border-radius: 50%;
    position: fixed;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.1s ease;
    mix-blend-mode: difference;
  }
  .cursor-ring {
    width: 36px; height: 36px;
    border: 1px solid var(--accent);
    border-radius: 50%;
    position: fixed;
    pointer-events: none;
    z-index: 9998;
    transition: all 0.18s ease;
    opacity: 0.5;
  }

  /* Noise overlay */
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 1000;
    opacity: 0.4;
  }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: grid;
    grid-template-rows: auto 1fr auto;
    padding: 2rem 3rem;
    position: relative;
    overflow: hidden;
  }

  .hero-bg {
    position: absolute; inset: 0;
    background:
      radial-gradient(ellipse 80% 60% at 10% 20%, rgba(123,108,255,0.18) 0%, transparent 60%),
      radial-gradient(ellipse 60% 80% at 90% 80%, rgba(200,255,74,0.1) 0%, transparent 55%),
      radial-gradient(ellipse 40% 40% at 50% 50%, rgba(255,107,53,0.06) 0%, transparent 60%);
    z-index: 0;
  }

  /* grid lines */
  .hero-bg::after {
    content: '';
    position: absolute; inset: 0;
    background-image:
      linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
    background-size: 60px 60px;
  }

  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative; z-index: 2;
  }

  .logo {
    font-family: 'DM Mono', monospace;
    font-size: 0.85rem;
    color: var(--accent);
    letter-spacing: 0.2em;
    text-transform: uppercase;
  }

  .nav-badge {
    background: rgba(200,255,74,0.12);
    border: 1px solid rgba(200,255,74,0.3);
    color: var(--accent);
    font-family: 'DM Mono', monospace;
    font-size: 0.72rem;
    padding: 0.35rem 0.9rem;
    border-radius: 2px;
    letter-spacing: 0.1em;
  }

  .hero-center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    position: relative; z-index: 2;
    padding: 4rem 0 2rem;
  }

  .hero-eyebrow {
    font-family: 'DM Mono', monospace;
    font-size: 0.75rem;
    color: var(--muted);
    letter-spacing: 0.25em;
    text-transform: uppercase;
    margin-bottom: 2rem;
    display: flex; align-items: center; gap: 0.8rem;
  }
  .hero-eyebrow::before {
    content: '';
    width: 32px; height: 1px;
    background: var(--muted);
  }

  h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(3.5rem, 9vw, 8rem);
    font-weight: 900;
    line-height: 0.95;
    margin-bottom: 1.5rem;
  }

  h1 .line1 { display: block; color: var(--text); }
  h1 .line2 {
    display: block;
    color: transparent;
    -webkit-text-stroke: 1.5px var(--accent);
    font-style: italic;
  }
  h1 .line3 { display: block; color: var(--text); }

  .hero-sub {
    max-width: 500px;
    color: var(--muted);
    font-size: 1rem;
    line-height: 1.7;
    margin-bottom: 3rem;
    font-weight: 400;
  }

  .hero-cta-row {
    display: flex; gap: 1rem; align-items: center; flex-wrap: wrap;
  }

  .btn-primary {
    background: var(--accent);
    color: #0a0a0f;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.9rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    padding: 1rem 2.2rem;
    border: none;
    cursor: none;
    position: relative;
    overflow: hidden;
    transition: transform 0.2s;
  }
  .btn-primary::after {
    content: '→';
    margin-left: 0.6rem;
  }
  .btn-primary:hover { transform: translateY(-2px); }

  .btn-ghost {
    border: 1px solid var(--border);
    color: var(--muted);
    font-family: 'DM Mono', monospace;
    font-size: 0.8rem;
    letter-spacing: 0.1em;
    padding: 1rem 1.8rem;
    background: transparent;
    cursor: none;
    transition: all 0.2s;
  }
  .btn-ghost:hover { border-color: var(--accent); color: var(--accent); }

  .hero-stats {
    display: flex; gap: 3rem; position: relative; z-index: 2;
    border-top: 1px solid var(--border);
    padding-top: 1.5rem;
  }

  .stat { display: flex; flex-direction: column; gap: 0.2rem; }
  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    font-weight: 700;
    color: var(--accent);
  }
  .stat-label {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.15em;
    text-transform: uppercase;
  }

  /* floating badge */
  .float-tag {
    position: absolute;
    right: 3rem; top: 50%;
    transform: translateY(-50%);
    width: 160px; height: 160px;
    border: 1px solid var(--border);
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    color: var(--accent);
    letter-spacing: 0.15em;
    text-align: center;
    text-transform: uppercase;
    animation: spin 20s linear infinite;
    background: rgba(200,255,74,0.03);
    z-index: 2;
    line-height: 1.6;
  }
  @keyframes spin { to { transform: translateY(-50%) rotate(360deg); } }

  /* ── MARQUEE ── */
  .marquee-wrap {
    background: var(--accent);
    overflow: hidden;
    padding: 0.8rem 0;
  }
  .marquee-track {
    display: flex; gap: 0;
    animation: marquee 18s linear infinite;
    white-space: nowrap;
  }
  .marquee-item {
    font-family: 'DM Mono', monospace;
    font-size: 0.75rem;
    font-weight: 500;
    color: #0a0a0f;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 0 2rem;
  }
  .marquee-dot { color: rgba(10,10,15,0.4); }
  @keyframes marquee { from { transform: translateX(0); } to { transform: translateX(-50%); } }

  /* ── SECTION BASE ── */
  section { padding: 6rem 3rem; position: relative; }

  .section-label {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--accent);
    letter-spacing: 0.3em;
    text-transform: uppercase;
    margin-bottom: 1rem;
    display: flex; align-items: center; gap: 0.7rem;
  }
  .section-label::after { content: ''; flex: 1; max-width: 40px; height: 1px; background: var(--accent); opacity: 0.5; }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2rem, 5vw, 4rem);
    font-weight: 700;
    line-height: 1.1;
    margin-bottom: 1rem;
  }

  /* ── WHAT'S INSIDE ── */
  .modules-section { background: var(--surface); }

  .modules-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5px;
    margin-top: 4rem;
    background: var(--border);
  }

  .module-card {
    background: var(--card);
    padding: 2.5rem;
    position: relative;
    overflow: hidden;
    transition: background 0.3s;
  }
  .module-card:hover { background: #1c1c28; }

  .module-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--accent3), var(--accent));
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.4s ease;
  }
  .module-card:hover::before { transform: scaleX(1); }

  .module-num {
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    color: var(--muted);
    letter-spacing: 0.2em;
    margin-bottom: 1.5rem;
  }

  .module-icon {
    font-size: 2rem;
    margin-bottom: 1.2rem;
    display: block;
  }

  .module-title {
    font-family: 'Syne', sans-serif;
    font-size: 1.15rem;
    font-weight: 700;
    margin-bottom: 0.8rem;
    color: var(--text);
  }

  .module-desc {
    font-size: 0.875rem;
    color: var(--muted);
    line-height: 1.65;
  }

  .module-tags {
    display: flex; flex-wrap: wrap; gap: 0.5rem;
    margin-top: 1.5rem;
  }
  .tag {
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    color: var(--accent3);
    border: 1px solid rgba(123,108,255,0.3);
    padding: 0.25rem 0.6rem;
    border-radius: 2px;
    letter-spacing: 0.08em;
  }

  /* ── FEATURES ── */
  .features-section { background: var(--bg); }

  .features-layout {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 5rem;
    margin-top: 4rem;
    align-items: center;
  }

  .feature-list { display: flex; flex-direction: column; gap: 0; }

  .feature-item {
    border-bottom: 1px solid var(--border);
    padding: 1.8rem 0;
    display: flex; gap: 1.5rem; align-items: flex-start;
    cursor: none;
    transition: all 0.2s;
  }
  .feature-item:hover .feature-arrow { color: var(--accent); transform: translateX(4px); }

  .feature-num {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--accent);
    opacity: 0.6;
    margin-top: 0.2rem;
    min-width: 28px;
  }

  .feature-body { flex: 1; }
  .feature-name {
    font-size: 1rem;
    font-weight: 600;
    margin-bottom: 0.3rem;
  }
  .feature-text { font-size: 0.85rem; color: var(--muted); line-height: 1.6; }
  .feature-arrow {
    font-size: 1.2rem;
    color: var(--muted);
    transition: all 0.2s;
    margin-top: 0.1rem;
  }

  /* Mock Notion UI */
  .notion-mock {
    background: #1a1a24;
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    box-shadow: 0 40px 80px rgba(0,0,0,0.5), 0 0 0 1px rgba(255,255,255,0.05);
  }

  .notion-topbar {
    background: #141420;
    padding: 0.8rem 1rem;
    display: flex; align-items: center; gap: 0.5rem;
    border-bottom: 1px solid var(--border);
  }
  .dot { width: 10px; height: 10px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #ffbd2e; }
  .dot-g { background: #28c940; }
  .notion-url {
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    color: var(--muted);
    margin-left: 0.8rem;
  }

  .notion-sidebar {
    display: flex; height: 360px;
  }
  .sidebar-nav {
    width: 180px;
    background: #111118;
    border-right: 1px solid var(--border);
    padding: 1rem 0;
    flex-shrink: 0;
  }
  .sidebar-item {
    padding: 0.4rem 1rem;
    font-family: 'DM Mono', monospace;
    font-size: 0.68rem;
    color: var(--muted);
    display: flex; align-items: center; gap: 0.5rem;
    transition: background 0.2s;
  }
  .sidebar-item.active {
    background: rgba(200,255,74,0.08);
    color: var(--accent);
  }
  .sidebar-item:hover:not(.active) { background: rgba(255,255,255,0.04); }

  .notion-content {
    flex: 1;
    padding: 1.5rem;
    overflow: hidden;
  }
  .notion-page-title {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    font-weight: 700;
    margin-bottom: 1.2rem;
    color: var(--text);
  }

  .notion-db {
    display: grid;
    grid-template-columns: 1.5fr 1fr 1fr;
    gap: 0;
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    border: 1px solid var(--border);
  }
  .db-header {
    background: #0f0f18;
    padding: 0.5rem 0.8rem;
    color: var(--muted);
    border-bottom: 1px solid var(--border);
    border-right: 1px solid var(--border);
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }
  .db-cell {
    padding: 0.5rem 0.8rem;
    color: var(--text);
    border-bottom: 1px solid rgba(255,255,255,0.04);
    border-right: 1px solid rgba(255,255,255,0.04);
    font-size: 0.63rem;
  }
  .db-badge {
    display: inline-block;
    padding: 0.1rem 0.5rem;
    border-radius: 2px;
    font-size: 0.6rem;
  }
  .badge-done { background: rgba(200,255,74,0.15); color: var(--accent); }
  .badge-prog { background: rgba(123,108,255,0.15); color: var(--accent3); }
  .badge-todo { background: rgba(255,107,53,0.15); color: var(--accent2); }

  .notion-progress {
    margin-top: 1rem;
    background: var(--border);
    height: 4px;
    border-radius: 2px;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--accent3), var(--accent));
    width: 65%;
    animation: grow 2s ease-out forwards;
  }
  @keyframes grow { from { width: 0%; } to { width: 65%; } }

  /* ── PRICING ── */
  .pricing-section { background: var(--surface); }

  .pricing-grid {
    display: grid;
    grid-template-columns: 1fr 1.1fr 1fr;
    gap: 1.5px;
    background: var(--border);
    margin-top: 4rem;
  }

  .price-card {
    background: var(--card);
    padding: 2.5rem 2rem;
    position: relative;
    overflow: hidden;
    transition: transform 0.3s;
  }
  .price-card.featured {
    background: #1a1a28;
  }
  .price-card.featured::before {
    content: 'BEST VALUE';
    position: absolute;
    top: 1.2rem; right: -2rem;
    background: var(--accent);
    color: #0a0a0f;
    font-family: 'DM Mono', monospace;
    font-size: 0.6rem;
    font-weight: 500;
    letter-spacing: 0.15em;
    padding: 0.3rem 3rem;
    transform: rotate(45deg);
    transform-origin: center;
  }

  .price-tier {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.2em;
    text-transform: uppercase;
    margin-bottom: 1rem;
  }

  .price-amount {
    font-family: 'Playfair Display', serif;
    font-size: 3rem;
    font-weight: 900;
    color: var(--text);
    line-height: 1;
    margin-bottom: 0.3rem;
  }
  .price-amount span {
    font-size: 1rem;
    font-family: 'Syne', sans-serif;
    font-weight: 400;
    color: var(--muted);
  }

  .price-desc {
    font-size: 0.8rem;
    color: var(--muted);
    margin-bottom: 2rem;
    line-height: 1.6;
  }

  .price-features { list-style: none; display: flex; flex-direction: column; gap: 0.7rem; margin-bottom: 2.5rem; }
  .price-features li {
    font-size: 0.82rem;
    color: var(--text);
    display: flex; gap: 0.7rem; align-items: flex-start;
  }
  .price-features li::before {
    content: '✓';
    color: var(--accent);
    font-family: 'DM Mono', monospace;
    font-size: 0.75rem;
    margin-top: 0.1rem;
    flex-shrink: 0;
  }
  .price-features li.muted { color: var(--muted); }
  .price-features li.muted::before { content: '—'; color: var(--border); }

  .btn-buy {
    width: 100%;
    padding: 0.9rem;
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 0.85rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    cursor: none;
    transition: all 0.2s;
    border: 1px solid var(--border);
    background: transparent;
    color: var(--text);
  }
  .btn-buy:hover { border-color: var(--accent); color: var(--accent); }
  .btn-buy.primary { background: var(--accent); color: #0a0a0f; border-color: var(--accent); }
  .btn-buy.primary:hover { background: #b8ef3a; }

  /* ── TESTIMONIALS ── */
  .testimonials-section { background: var(--bg); }

  .testimonials-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5px;
    background: var(--border);
    margin-top: 4rem;
  }

  .testi-card {
    background: var(--card);
    padding: 2.5rem;
  }

  .testi-quote {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    color: var(--accent);
    opacity: 0.4;
    line-height: 1;
    margin-bottom: 1rem;
  }

  .testi-text {
    font-size: 0.9rem;
    color: var(--muted);
    line-height: 1.7;
    margin-bottom: 1.5rem;
  }

  .testi-author {
    display: flex; align-items: center; gap: 0.8rem;
  }
  .testi-avatar {
    width: 36px; height: 36px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--accent3), var(--accent));
    display: flex; align-items: center; justify-content: center;
    font-family: 'DM Mono', monospace;
    font-size: 0.75rem;
    color: #0a0a0f;
    font-weight: 500;
  }
  .testi-name {
    font-size: 0.85rem;
    font-weight: 600;
  }
  .testi-role {
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    color: var(--muted);
    letter-spacing: 0.1em;
  }

  /* ── FAQ ── */
  .faq-section { background: var(--surface); }

  .faq-list { margin-top: 4rem; display: flex; flex-direction: column; gap: 0; }

  .faq-item {
    border-bottom: 1px solid var(--border);
    overflow: hidden;
  }

  .faq-q {
    padding: 1.5rem 0;
    display: flex; justify-content: space-between; align-items: center;
    cursor: none;
    font-size: 1rem;
    font-weight: 600;
  }

  .faq-toggle {
    width: 28px; height: 28px;
    border: 1px solid var(--border);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.2rem;
    color: var(--accent);
    transition: all 0.3s;
    flex-shrink: 0;
  }
  .faq-item.open .faq-toggle { transform: rotate(45deg); border-color: var(--accent); }

  .faq-a {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s ease, padding 0.3s;
    font-size: 0.88rem;
    color: var(--muted);
    line-height: 1.7;
  }
  .faq-item.open .faq-a {
    max-height: 200px;
    padding-bottom: 1.5rem;
  }

  /* ── FOOTER CTA ── */
  .cta-section {
    background: var(--bg);
    text-align: center;
    padding: 8rem 3rem;
    position: relative;
    overflow: hidden;
  }
  .cta-section::before {
    content: '';
    position: absolute;
    left: 50%; top: 50%;
    transform: translate(-50%, -50%);
    width: 600px; height: 600px;
    background: radial-gradient(circle, rgba(200,255,74,0.07) 0%, transparent 70%);
    pointer-events: none;
  }

  .cta-section h2 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.5rem, 7vw, 6rem);
    font-weight: 900;
    line-height: 1;
    margin-bottom: 1.5rem;
    position: relative; z-index: 1;
  }
  .cta-section h2 em { font-style: italic; color: var(--accent); }

  .cta-sub {
    color: var(--muted);
    font-size: 1rem;
    margin-bottom: 3rem;
    position: relative; z-index: 1;
  }

  footer {
    background: var(--surface);
    border-top: 1px solid var(--border);
    padding: 2rem 3rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .footer-copy {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.1em;
  }
  .footer-links {
    display: flex; gap: 2rem;
  }
  .footer-links a {
    font-family: 'DM Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    text-decoration: none;
    letter-spacing: 0.1em;
    transition: color 0.2s;
  }
  .footer-links a:hover { color: var(--accent); }

  /* Animations */
  .fade-up {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .fade-up.visible {
    opacity: 1;
    transform: translateY(0);
  }

  @media (max-width: 768px) {
    .hero { padding: 1.5rem; }
    section { padding: 4rem 1.5rem; }
    .features-layout { grid-template-columns: 1fr; }
    .pricing-grid { grid-template-columns: 1fr; }
    .testimonials-grid { grid-template-columns: 1fr; }
    .float-tag { display: none; }
    .hero-stats { gap: 2rem; flex-wrap: wrap; }
    footer { flex-direction: column; gap: 1rem; text-align: center; }
  }
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <nav>
    <div class="logo">Notion OS™</div>
    <div class="nav-badge">v2.0 — 2026 Edition</div>
  </nav>

  <div class="hero-center">
    <div class="hero-eyebrow">The Ultimate Productivity Template</div>
    <h1>
      <span class="line1">Master</span>
      <span class="line2">Notion</span>
      <span class="line3">From Zero.</span>
    </h1>
    <p class="hero-sub">A complete operating system for your life and work — built inside Notion. From your first page to advanced automations, this template grows with you.</p>
    <div class="hero-cta-row">
      <button class="btn-primary">Get Instant Access</button>
      <button class="btn-ghost">Preview Template</button>
    </div>
  </div>

  <div class="hero-stats">
    <div class="stat">
      <span class="stat-num">12+</span>
      <span class="stat-label">Core Modules</span>
    </div>
    <div class="stat">
      <span class="stat-num">80+</span>
      <span class="stat-label">Premade Pages</span>
    </div>
    <div class="stat">
      <span class="stat-num">4.9★</span>
      <span class="stat-label">Avg Rating</span>
    </div>
    <div class="stat">
      <span class="stat-num">2,400+</span>
      <span class="stat-label">Users</span>
    </div>
  </div>

  <div class="float-tag">The Only<br/>Notion Template<br/>You'll Ever Need</div>
</section>

<!-- MARQUEE -->
<div class="marquee-wrap">
  <div class="marquee-track">
    <span class="marquee-item">Task Manager <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Second Brain <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Project Hub <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Content Calendar <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">CRM System <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Habit Tracker <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Finance Manager <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Goal Planner <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Reading List <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Notion AI Guide <span class="marquee-dot">◆</span></span>
    <!-- duplicate for seamless loop -->
    <span class="marquee-item">Task Manager <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Second Brain <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Project Hub <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Content Calendar <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">CRM System <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Habit Tracker <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Finance Manager <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Goal Planner <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Reading List <span class="marquee-dot">◆</span></span>
    <span class="marquee-item">Notion AI Guide <span class="marquee-dot">◆</span></span>
  </div>
</div>

<!-- MODULES -->
<section class="modules-section fade-up">
  <div class="section-label">What's Inside</div>
  <h2 class="section-title">12 Modules.<br/>One Workspace.</h2>

  <div class="modules-grid">
    <div class="module-card">
      <div class="module-num">01 — FOUNDATION</div>
      <span class="module-icon">🏗️</span>
      <div class="module-title">Notion Fundamentals</div>
      <div class="module-desc">Master pages, blocks, properties and linking. The complete beginner's foundation — no fluff, just what actually matters.</div>
      <div class="module-tags"><span class="tag">Blocks</span><span class="tag">Properties</span><span class="tag">Navigation</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">02 — DATABASES</div>
      <span class="module-icon">🗄️</span>
      <div class="module-title">Database Mastery</div>
      <div class="module-desc">Tables, boards, calendars, galleries. Build your first relational database system and understand rollups & relations.</div>
      <div class="module-tags"><span class="tag">Relations</span><span class="tag">Rollups</span><span class="tag">Filters</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">03 — TASKS</div>
      <span class="module-icon">✅</span>
      <div class="module-title">Task & Project Hub</div>
      <div class="module-desc">A full GTD-style task system. Inbox, Today, Projects, Areas — all connected and automated. Never drop a ball again.</div>
      <div class="module-tags"><span class="tag">GTD</span><span class="tag">Projects</span><span class="tag">Priorities</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">04 — SECOND BRAIN</div>
      <span class="module-icon">🧠</span>
      <div class="module-title">Knowledge Management</div>
      <div class="module-desc">Capture, organize and retrieve any idea instantly. Built on the PARA method — the world's most used PKM framework.</div>
      <div class="module-tags"><span class="tag">PARA</span><span class="tag">Notes</span><span class="tag">Resources</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">05 — CONTENT</div>
      <span class="module-icon">📅</span>
      <div class="module-title">Content Calendar</div>
      <div class="module-desc">Plan, draft, publish and track your content across every platform. Status pipelines, ideas vault, and analytics tracker.</div>
      <div class="module-tags"><span class="tag">Calendar</span><span class="tag">Pipeline</span><span class="tag">Ideas</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">06 — FORMULAS</div>
      <span class="module-icon">⚡</span>
      <div class="module-title">Formulas & Automations</div>
      <div class="module-desc">Level up from basic to advanced Notion formulas. Includes 30+ copy-paste formula templates for real-world use cases.</div>
      <div class="module-tags"><span class="tag">Formulas</span><span class="tag">Buttons</span><span class="tag">Automations</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">07 — FINANCE</div>
      <span class="module-icon">💰</span>
      <div class="module-title">Finance Tracker</div>
      <div class="module-desc">Monthly budgets, expense categories, income tracking, net worth dashboard. All inside Notion with live formula calculations.</div>
      <div class="module-tags"><span class="tag">Budget</span><span class="tag">Expenses</span><span class="tag">Net Worth</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">08 — HABITS</div>
      <span class="module-icon">🔥</span>
      <div class="module-title">Habit & Goal Tracker</div>
      <div class="module-desc">Daily, weekly and monthly habit streaks. Set goals with milestones, track progress with visual completion charts.</div>
      <div class="module-tags"><span class="tag">Streaks</span><span class="tag">Goals</span><span class="tag">Progress</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">09 — CRM</div>
      <span class="module-icon">🤝</span>
      <div class="module-title">Personal CRM</div>
      <div class="module-desc">Track contacts, follow-ups, meetings and relationship notes. Perfect for freelancers, networkers and solopreneurs.</div>
      <div class="module-tags"><span class="tag">Contacts</span><span class="tag">Follow-ups</span><span class="tag">Deals</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">10 — READING</div>
      <span class="module-icon">📚</span>
      <div class="module-title">Reading & Learning Hub</div>
      <div class="module-desc">Book tracker, course notes, YouTube saves. Extract highlights, write summaries and link ideas to your Second Brain.</div>
      <div class="module-tags"><span class="tag">Books</span><span class="tag">Courses</span><span class="tag">Highlights</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">11 — AI</div>
      <span class="module-icon">🤖</span>
      <div class="module-title">Notion AI Integration</div>
      <div class="module-desc">Use Notion AI to generate, summarize, translate and automate. Includes 20+ AI prompt templates optimized for Notion.</div>
      <div class="module-tags"><span class="tag">AI Prompts</span><span class="tag">Summarize</span><span class="tag">Generate</span></div>
    </div>
    <div class="module-card">
      <div class="module-num">12 — BONUS</div>
      <span class="module-icon">🎁</span>
      <div class="module-title">Bonus: Travel + Journal</div>
      <div class="module-desc">Trip planner, packing lists, daily journal and reflection templates. Your complete personal life OS — fully connected.</div>
      <div class="module-tags"><span class="tag">Travel</span><span class="tag">Journal</span><span class="tag">Reflection</span></div>
    </div>
  </div>
</section>

<!-- FEATURES -->
<section class="features-section fade-up">
  <div class="section-label">Why This Template</div>
  <h2 class="section-title">Built Different.<br/>Actually Works.</h2>

  <div class="features-layout">
    <div class="feature-list">
      <div class="feature-item">
        <div class="feature-num">01</div>
        <div class="feature-body">
          <div class="feature-name">Fully Interconnected System</div>
          <div class="feature-text">Every database talks to each other. Add a task and it reflects in your project, habits, and daily dashboard automatically.</div>
        </div>
        <div class="feature-arrow">→</div>
      </div>
      <div class="feature-item">
        <div class="feature-num">02</div>
        <div class="feature-body">
          <div class="feature-name">Beginner-Friendly Setup Guide</div>
          <div class="feature-text">Includes a step-by-step onboarding page that teaches you how each part works as you set it up. Learn by doing.</div>
        </div>
        <div class="feature-arrow">→</div>
      </div>
      <div class="feature-item">
        <div class="feature-num">03</div>
        <div class="feature-body">
          <div class="feature-name">30+ Formula Library Included</div>
          <div class="feature-text">Copy-paste Notion formulas for dates, status, progress bars, scores and calculations. Never Google a formula again.</div>
        </div>
        <div class="feature-arrow">→</div>
      </div>
      <div class="feature-item">
        <div class="feature-num">04</div>
        <div class="feature-body">
          <div class="feature-name">Mobile Optimized Views</div>
          <div class="feature-text">Every module has a dedicated mobile view. Quick capture, daily check-ins, and habit logging all work perfectly on phone.</div>
        </div>
        <div class="feature-arrow">→</div>
      </div>
      <div class="feature-item">
        <div class="feature-num">05</div>
        <div class="feature-body">
          <div class="feature-name">Lifetime Free Updates</div>
          <div class="feature-text">Buy once, get every future version free. As Notion releases new features, this template gets updated to use them.</div>
        </div>
        <div class="feature-arrow">→</div>
      </div>
    </div>

    <!-- Mock Notion UI -->
    <div class="notion-mock">
      <div class="notion-topbar">
        <div class="dot dot-r"></div>
        <div class="dot dot-y"></div>
        <div class="dot dot-g"></div>
        <div class="notion-url">notion.so/notion-os-master</div>
      </div>
      <div class="notion-sidebar">
        <div class="sidebar-nav">
          <div class="sidebar-item">🏠 Home</div>
          <div class="sidebar-item active">✅ Tasks</div>
          <div class="sidebar-item">🧠 Second Brain</div>
          <div class="sidebar-item">📅 Content</div>
          <div class="sidebar-item">💰 Finance</div>
          <div class="sidebar-item">🔥 Habits</div>
          <div class="sidebar-item">🤝 CRM</div>
          <div class="sidebar-item">📚 Reading</div>
          <div class="sidebar-item">🤖 Notion AI</div>
          <div class="sidebar-item">⚡ Formulas</div>
        </div>
        <div class="notion-content">
          <div class="notion-page-title">✅ Task Dashboard</div>
          <div class="notion-db">
            <div class="db-header">Task</div>
            <div class="db-header">Project</div>
            <div class="db-header">Status</div>
            <div class="db-cell">Design landing page</div>
            <div class="db-cell">Client Work</div>
            <div class="db-cell"><span class="db-badge badge-done">Done</span></div>
            <div class="db-cell">Write newsletter</div>
            <div class="db-cell">Content</div>
            <div class="db-cell"><span class="db-badge badge-prog">In Progress</span></div>
            <div class="db-cell">Review proposals</div>
            <div class="db-cell">Business</div>
            <div class="db-cell"><span class="db-badge badge-todo">To Do</span></div>
            <div class="db-cell">Update portfolio</div>
            <div class="db-cell">Personal</div>
            <div class="db-cell"><span class="db-badge badge-prog">In Progress</span></div>
          </div>
          <div style="margin-top:1rem; font-family:'DM Mono',monospace; font-size:0.65rem; color:var(--muted);">Weekly Progress</div>
          <div class="notion-progress"><div class="progress-fill"></div></div>
          <div style="font-family:'DM Mono',monospace; font-size:0.6rem; color:var(--accent); margin-top:0.4rem;">65% complete — 13 of 20 tasks done</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section class="pricing-section fade-up">
  <div class="section-label">Pricing</div>
  <h2 class="section-title">One-time.<br/>Yours Forever.</h2>

  <div class="pricing-grid">
    <div class="price-card">
      <div class="price-tier">Starter</div>
      <div class="price-amount">$17<span> / once</span></div>
      <div class="price-desc">Perfect if you're just starting out and want the core system.</div>
      <ul class="price-features">
        <li>Core 6 Modules (Tasks, Notes, Habits, Finance, Reading, Journal)</li>
        <li>Beginner Setup Guide</li>
        <li>Mobile Views Included</li>
        <li class="muted">No Formula Library</li>
        <li class="muted">No Notion AI Module</li>
        <li class="muted">No CRM / Content Cal</li>
      </ul>
      <button class="btn-buy">Buy Starter</button>
    </div>

    <div class="price-card featured">
      <div class="price-tier">Master OS</div>
      <div class="price-amount">$37<span> / once</span></div>
      <div class="price-desc">The complete system. Everything you need to run your entire life in Notion.</div>
      <ul class="price-features">
        <li>All 12 Modules Included</li>
        <li>30+ Formula Library</li>
        <li>Notion AI Integration Guide</li>
        <li>Personal CRM + Content Cal</li>
        <li>Mobile Optimized Views</li>
        <li>Lifetime Free Updates</li>
      </ul>
      <button class="btn-buy primary">Get Master OS</button>
    </div>

    <div class="price-card">
      <div class="price-tier">Team Bundle</div>
      <div class="price-amount">$67<span> / once</span></div>
      <div class="price-desc">For small teams and businesses building their Notion workspace together.</div>
      <ul class="price-features">
        <li>Everything in Master OS</li>
        <li>Team Project Board</li>
        <li>Shared CRM + Pipeline</li>
        <li>Meeting Notes Template</li>
        <li>Up to 5 Workspace Licenses</li>
        <li>Priority Email Support</li>
      </ul>
      <button class="btn-buy">Buy Team Bundle</button>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials-section fade-up">
  <div class="section-label">Social Proof</div>
  <h2 class="section-title">2,400+ People<br/>Can't Be Wrong.</h2>

  <div class="testimonials-grid">
    <div class="testi-card">
      <div class="testi-quote">"</div>
      <div class="testi-text">I've tried 12 different Notion templates. This one finally made everything click. The setup guide alone is worth 10x the price. I'm actually using Notion now instead of just collecting templates.</div>
      <div class="testi-author">
        <div class="testi-avatar">SR</div>
        <div>
          <div class="testi-name">Sarah R.</div>
          <div class="testi-role">Freelance Designer</div>
        </div>
      </div>
    </div>
    <div class="testi-card">
      <div class="testi-quote">"</div>
      <div class="testi-text">The formula library saved me hours of research. I used to Google every single formula — now I just copy from the library and adapt it. Honestly this should be included in Notion itself.</div>
      <div class="testi-author">
        <div class="testi-avatar">MK</div>
        <div>
          <div class="testi-name">Marcus K.</div>
          <div class="testi-role">Product Manager</div>
        </div>
      </div>
    </div>
    <div class="testi-card">
      <div class="testi-quote">"</div>
      <div class="testi-text">Bought it on a Saturday, had my full workspace running by Sunday. The Second Brain + Content Calendar combo has completely transformed how I create. 100% worth it, no question.</div>
      <div class="testi-author">
        <div class="testi-avatar">JL</div>
        <div>
          <div class="testi-name">Jamie L.</div>
          <div class="testi-role">Content Creator</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FAQ -->
<section class="faq-section fade-up">
  <div class="section-label">FAQ</div>
  <h2 class="section-title">Common<br/>Questions.</h2>

  <div class="faq-list">
    <div class="faq-item">
      <div class="faq-q" onclick="toggleFaq(this)">
        Do I need a paid Notion plan to use this?
        <div class="faq-toggle">+</div>
      </div>
      <div class="faq-a">The core template works on Notion's free plan. Some advanced features like Notion AI and unlimited guests require a paid Notion plan, but 90% of the template is fully functional on free.</div>
    </div>
    <div class="faq-item">
      <div class="faq-q" onclick="toggleFaq(this)">
        I'm a complete beginner — is this too advanced?
        <div class="faq-toggle">+</div>
      </div>
      <div class="faq-a">Not at all. The template includes a full beginner onboarding guide that explains every feature as you explore it. If you can use Google Docs, you can use this template.</div>
    </div>
    <div class="faq-item">
      <div class="faq-q" onclick="toggleFaq(this)">
        How do I get the template after purchasing?
        <div class="faq-toggle">+</div>
      </div>
      <div class="faq-a">Immediately after purchase on Gumroad, you'll receive a link to duplicate the Notion template directly into your workspace. It takes less than 30 seconds.</div>
    </div>
    <div class="faq-item">
      <div class="faq-q" onclick="toggleFaq(this)">
        What does "lifetime updates" actually mean?
        <div class="faq-toggle">+</div>
      </div>
      <div class="faq-a">Every time I update the template — whether it's new modules, improved formulas, or Notion feature integrations — you get access to the new version for free. Forever. No subscriptions.</div>
    </div>
    <div class="faq-item">
      <div class="faq-q" onclick="toggleFaq(this)">
        Can I customize the template for my needs?
        <div class="faq-toggle">+</div>
      </div>
      <div class="faq-a">Absolutely. Once you duplicate it into your workspace, it's yours to customize however you like. Delete what you don't need, add what you want. It's built to be flexible.</div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section fade-up">
  <h2>Your Most<br/>Productive Year<br/><em>Starts Today.</em></h2>
  <p class="cta-sub">Join 2,400+ people who upgraded how they work, think and live.</p>
  <button class="btn-primary" style="font-size:1rem; padding:1.2rem 3rem;">Get Notion OS — $37</button>
</section>

<footer>
  <div class="footer-copy">© 2026 Notion OS™ — All rights reserved</div>
  <div class="footer-links">
    <a href="#">Gumroad</a>
    <a href="#">Preview</a>
    <a href="#">Support</a>
    <a href="#">Affiliate</a>
  </div>
</footer>

<script>
  // Cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = mx - 6 + 'px';
    cursor.style.top = my - 6 + 'px';
  });
  function animateRing() {
    rx += (mx - rx - 18) * 0.15;
    ry += (my - ry - 18) * 0.15;
    ring.style.left = rx + 'px';
    ring.style.top = ry + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  // FAQ
  function toggleFaq(el) {
    const item = el.parentElement;
    item.classList.toggle('open');
  }

  // Scroll fade
  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.1 });
  document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));
</script>
</body>
</html>
