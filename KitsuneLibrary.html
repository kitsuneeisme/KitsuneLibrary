<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UILibrary — Modern Roblox UI Kit</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#101014;
    --panel:#1a1a20;
    --panel-2:#212128;
    --element:#26262e;
    --element-hover:#2e2e38;
    --stroke:#32323c;
    --text:#eaeaef;
    --sub:#8c8c98;
    --accent:#7c6cff;
    --accent-2:#9c8fff;
    --fox:#ff7a45;
    --success:#5ec88a;
    --error:#eb5a5a;
    --warning:#ebb446;
    --info:#5f96eb;
    --gold:#e6bc5a;
    --silver:#bec3cd;
    --bronze:#c48454;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:'Inter',sans-serif;
    line-height:1.6;
    overflow-x:hidden;
  }
  h1,h2,h3,.display{font-family:'Space Grotesk',sans-serif;}
  code, .mono{font-family:'JetBrains Mono',monospace;}
  a{color:inherit;text-decoration:none;}

  .noise-bg{
    position:fixed; inset:0; z-index:-2;
    background:
      radial-gradient(circle at 15% 10%, rgba(124,108,255,0.08), transparent 45%),
      radial-gradient(circle at 85% 30%, rgba(255,122,69,0.06), transparent 40%),
      var(--bg);
  }
  .grid-overlay{
    position:fixed; inset:0; z-index:-1; opacity:0.4;
    background-image:
      linear-gradient(rgba(255,255,255,0.02) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.02) 1px, transparent 1px);
    background-size:48px 48px;
    mask-image: radial-gradient(ellipse 80% 50% at 50% 0%, black 40%, transparent 100%);
  }

  nav{
    position:sticky; top:0; z-index:50;
    display:flex; align-items:center; justify-content:space-between;
    padding:18px 48px;
    background:rgba(16,16,20,0.75);
    backdrop-filter:blur(14px);
    border-bottom:1px solid rgba(255,255,255,0.06);
  }
  .brand{display:flex; align-items:center; gap:10px; font-weight:700; font-size:17px;}
  .brand .glyph{
    width:30px; height:30px; border-radius:9px;
    background:linear-gradient(145deg, var(--accent), var(--fox));
    display:flex; align-items:center; justify-content:center;
    font-size:15px;
  }
  .nav-links{display:flex; gap:28px; font-size:14px; color:var(--sub);}
  .nav-links a:hover{color:var(--text);}
  .nav-cta{
    padding:9px 18px; border-radius:8px; font-size:13px; font-weight:600;
    background:var(--element); border:1px solid var(--stroke);
    transition:all .15s;
  }
  .nav-cta:hover{background:var(--element-hover); border-color:var(--accent);}

  .hero{
    padding:96px 48px 64px;
    display:grid; grid-template-columns:1.1fr 1fr; gap:56px;
    align-items:center; max-width:1280px; margin:0 auto;
  }
  .eyebrow{
    display:inline-flex; align-items:center; gap:8px;
    font-size:12px; color:var(--fox); font-weight:600;
    letter-spacing:0.04em; text-transform:uppercase;
    margin-bottom:20px;
  }
  .eyebrow::before{content:"●"; font-size:8px;}
  .hero h1{
    font-size:50px; line-height:1.08; font-weight:700; letter-spacing:-0.01em;
    margin-bottom:20px;
  }
  .hero h1 .accent-text{
    background:linear-gradient(90deg, var(--accent-2), var(--fox));
    -webkit-background-clip:text; background-clip:text; color:transparent;
  }
  .hero p{font-size:16px; color:var(--sub); max-width:480px; margin-bottom:32px;}
  .hero-buttons{display:flex; gap:14px; flex-wrap:wrap;}
  .btn{
    padding:13px 24px; border-radius:9px; font-size:14px; font-weight:600;
    display:inline-flex; align-items:center; gap:8px; cursor:pointer;
    transition:all .15s; border:1px solid transparent;
  }
  .btn-primary{background:var(--accent); color:#fff;}
  .btn-primary:hover{background:var(--accent-2); transform:translateY(-1px);}
  .btn-secondary{background:transparent; border-color:var(--stroke); color:var(--text);}
  .btn-secondary:hover{background:var(--element);}

  .hero-stats{display:flex; gap:28px; margin-top:36px; flex-wrap:wrap;}
  .stat-num{font-size:22px; font-weight:700; font-family:'Space Grotesk';}
  .stat-label{font-size:12px; color:var(--sub);}

  .mockup-wrap{display:flex; justify-content:center; perspective:1200px;}
  .mockup{
    width:420px; border-radius:14px; overflow:hidden;
    background:var(--panel);
    border:1px solid var(--stroke);
    box-shadow:0 30px 80px -20px rgba(0,0,0,0.6), 0 0 0 1px rgba(255,255,255,0.02);
    transform:rotateY(-6deg) rotateX(2deg);
    transition:transform .4s ease;
  }
  .mockup-wrap:hover .mockup{transform:rotateY(0deg) rotateX(0deg);}
  .mockup-top{
    background:var(--panel-2); padding:12px 16px;
    display:flex; align-items:center; justify-content:space-between;
    border-bottom:1px solid var(--stroke);
  }
  .mockup-title{font-size:12px; font-weight:600;}
  .mockup-sub{font-size:10px; color:var(--sub); margin-top:1px;}
  .mockup-controls{display:flex; gap:10px; align-items:center;}
  .mockup-controls .ctrl{width:11px; height:11px; cursor:pointer; position:relative;}
  .mockup-controls .ctrl.min::after{content:""; position:absolute; left:1px; top:5px; width:9px; height:1.6px; background:var(--sub); border-radius:1px;}
  .mockup-controls .ctrl.close::before,.mockup-controls .ctrl.close::after{content:""; position:absolute; left:1px; top:5px; width:9px; height:1.6px; background:var(--sub); border-radius:1px;}
  .mockup-controls .ctrl.close::before{transform:rotate(45deg);}
  .mockup-controls .ctrl.close::after{transform:rotate(-45deg);}
  .mockup-controls .ctrl:hover::after,.mockup-controls .ctrl:hover::before{background:var(--text);}
  .mockup-body{display:flex; min-height:280px;}
  .mockup-sidebar{
    width:110px; background:var(--panel-2); padding:10px 8px;
    display:flex; flex-direction:column; gap:4px;
    border-right:1px solid var(--stroke);
  }
  .mockup-tab{
    padding:8px 10px; border-radius:6px; font-size:11px; color:var(--sub);
    cursor:pointer; transition:all .15s; user-select:none;
    display:flex; align-items:center; gap:7px;
  }
  .mockup-tab .dot{width:6px; height:6px; border-radius:50%; background:var(--sub); flex-shrink:0;}
  .mockup-tab.active{background:var(--element); color:var(--text);}
  .mockup-tab.active .dot{background:var(--accent-2);}
  .mockup-content{flex:1; padding:16px; display:flex; flex-direction:column; gap:10px;}
  .mock-row{
    background:var(--element); border:1px solid var(--stroke); border-radius:8px;
    padding:9px 12px; font-size:11px; display:flex; align-items:center; justify-content:space-between;
  }
  .mock-switch{width:30px; height:16px; border-radius:8px; background:var(--accent); position:relative; cursor:pointer;}
  .mock-switch::after{content:""; position:absolute; right:2px; top:2px; width:12px; height:12px; border-radius:50%; background:#fff;}
  .mock-switch.off{background:var(--stroke);}
  .mock-switch.off::after{left:2px; right:auto;}
  .mock-slider-track{width:90px; height:5px; background:var(--stroke); border-radius:3px; position:relative;}
  .mock-slider-fill{position:absolute; left:0; top:0; height:100%; width:60%; background:var(--accent); border-radius:3px;}
  .mock-notify{
    position:absolute; bottom:14px; right:14px; width:170px;
    background:var(--panel-2); border:1px solid var(--stroke); border-radius:8px;
    padding:9px 10px; font-size:9.5px; display:flex; gap:7px;
    box-shadow:0 10px 30px -10px rgba(0,0,0,0.5);
    animation:floatIn 0.6s ease 1.2s both, floatPulse 3s ease 2s infinite;
  }
  @keyframes floatIn{from{opacity:0; transform:translateY(10px);} to{opacity:1; transform:translateY(0);}}
  @keyframes floatPulse{0%,100%{transform:translateY(0);} 50%{transform:translateY(-3px);}}
  .mock-notify .bar{width:3px; border-radius:2px; background:var(--success); flex-shrink:0;}
  .mock-notify .txt b{display:block; color:var(--text); font-weight:600; margin-bottom:1px;}
  .mock-notify .txt span{color:var(--sub);}

  section{max-width:1280px; margin:0 auto; padding:80px 48px;}
  .section-head{max-width:560px; margin-bottom:48px;}
  .section-eyebrow{font-size:12px; color:var(--accent-2); font-weight:600; letter-spacing:0.04em; text-transform:uppercase; margin-bottom:10px;}
  .section-head h2{font-size:32px; font-weight:700; margin-bottom:12px; letter-spacing:-0.01em;}
  .section-head p{color:var(--sub); font-size:15px;}

  .comp-grid{display:grid; grid-template-columns:repeat(auto-fit, minmax(220px, 1fr)); gap:14px;}
  .comp-card{
    background:var(--panel); border:1px solid var(--stroke); border-radius:12px;
    padding:20px; transition:all .2s;
  }
  .comp-card:hover{border-color:var(--accent); transform:translateY(-2px);}
  .comp-icon{
    width:34px; height:34px; border-radius:8px; background:var(--element);
    display:flex; align-items:center; justify-content:center; margin-bottom:14px;
    font-size:15px; color:var(--accent-2);
  }
  .comp-card h3{font-size:15px; margin-bottom:6px;}
  .comp-card p{font-size:12.5px; color:var(--sub);}
  .new-badge{
    display:inline-block; font-size:9.5px; font-weight:700; letter-spacing:0.04em;
    background:var(--fox); color:#1a0f08; padding:2px 7px; border-radius:20px;
    margin-left:6px; vertical-align:middle; text-transform:uppercase;
  }

  .steps{display:flex; flex-direction:column; gap:0;}
  .step{display:grid; grid-template-columns:48px 1fr; gap:20px; padding:24px 0; border-bottom:1px solid rgba(255,255,255,0.06);}
  .step:last-child{border-bottom:none;}
  .step-num{
    width:32px; height:32px; border-radius:50%; background:var(--element);
    border:1px solid var(--stroke); display:flex; align-items:center; justify-content:center;
    font-size:13px; font-weight:700; color:var(--accent-2); font-family:'Space Grotesk';
  }
  .step h3{font-size:16px; margin-bottom:8px;}
  .step p{color:var(--sub); font-size:14px; margin-bottom:10px;}

  pre{
    background:#0b0b0e; border:1px solid var(--stroke); border-radius:10px;
    padding:18px 20px; overflow-x:auto; font-size:13px; line-height:1.65;
    color:#d8d8e2;
  }
  pre .c1{color:#8b8b96;}
  pre .c2{color:var(--accent-2);}
  pre .c3{color:#e3b873;}
  pre .c4{color:#7fd8a4;}
  pre .c5{color:#ff9d7a;}
  code.inline{background:var(--element); padding:2px 6px; border-radius:5px; font-size:0.9em;}

  .docs-layout{display:grid; grid-template-columns:220px 1fr; gap:48px; align-items:start;}
  .docs-nav{
    position:sticky; top:90px;
    display:flex; flex-direction:column; gap:2px;
    max-height:calc(100vh - 110px); overflow-y:auto;
  }
  .docs-nav-label{font-size:11px; color:var(--sub); text-transform:uppercase; letter-spacing:0.05em; margin:14px 0 6px;}
  .docs-nav a{
    font-size:13.5px; color:var(--sub); padding:7px 10px; border-radius:6px;
    transition:all .15s;
  }
  .docs-nav a:hover{color:var(--text); background:var(--element);}

  .doc-block{
    border:1px solid var(--stroke); border-radius:14px; background:var(--panel);
    margin-bottom:24px; overflow:hidden;
  }
  .doc-block-head{
    padding:20px 24px; border-bottom:1px solid var(--stroke);
    display:flex; align-items:center; gap:12px;
  }
  .doc-block-head h3{font-size:18px; font-family:'Space Grotesk'; flex:1;}
  .doc-tag{
    font-size:11px; padding:3px 9px; border-radius:20px; background:var(--element);
    color:var(--sub); font-family:'JetBrains Mono';
  }
  .doc-block-body{padding:24px;}
  .doc-block-body p{color:var(--sub); font-size:14px; margin-bottom:16px;}

  table.params{width:100%; border-collapse:collapse; margin-bottom:20px; font-size:13px;}
  table.params th{
    text-align:left; padding:9px 12px; color:var(--sub); font-weight:600;
    border-bottom:1px solid var(--stroke); font-size:11.5px; text-transform:uppercase; letter-spacing:0.03em;
  }
  table.params td{padding:10px 12px; border-bottom:1px solid rgba(255,255,255,0.05);}
  table.params td:first-child{font-family:'JetBrains Mono'; color:var(--accent-2); font-size:12.5px;}
  table.params td:nth-child(2){color:var(--fox); font-size:12px; font-family:'JetBrains Mono';}

  .notify-demo-grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:12px; margin-bottom:20px;}
  .notify-demo{
    display:flex; gap:10px; padding:12px 14px; border-radius:10px;
    background:var(--element); border:1px solid var(--stroke);
  }
  .notify-demo .bar{width:3px; border-radius:2px;}
  .notify-demo b{display:block; font-size:13px; margin-bottom:2px;}
  .notify-demo span{font-size:12px; color:var(--sub);}

  /* Theme swatches grid */
  .theme-grid{display:grid; grid-template-columns:repeat(auto-fill, minmax(150px, 1fr)); gap:10px; margin-bottom:8px;}
  .theme-swatch{
    border:1px solid var(--stroke); border-radius:10px; overflow:hidden;
    cursor:default; transition:all .15s;
  }
  .theme-swatch:hover{border-color:var(--accent); transform:translateY(-1px);}
  .theme-swatch-bar{height:34px; display:flex;}
  .theme-swatch-bar span{flex:1;}
  .theme-swatch-name{padding:8px 10px; font-size:12px; font-weight:600; background:var(--panel);}

  /* Tier cards */
  .tier-grid{display:grid; grid-template-columns:repeat(auto-fit, minmax(200px,1fr)); gap:14px; margin-bottom:24px;}
  .tier-card{border:1px solid var(--stroke); border-radius:12px; padding:18px; background:var(--panel); position:relative; overflow:hidden;}
  .tier-card::before{content:""; position:absolute; left:0; top:0; bottom:0; width:4px;}
  .tier-card.bronze::before{background:var(--bronze);}
  .tier-card.silver::before{background:var(--silver);}
  .tier-card.gold::before{background:var(--gold);}
  .tier-card h4{font-size:15px; margin-bottom:4px; padding-left:8px;}
  .tier-card p{font-size:12px; color:var(--sub); padding-left:8px;}

  footer{
    border-top:1px solid rgba(255,255,255,0.06); padding:40px 48px;
    display:flex; justify-content:space-between; align-items:center;
    max-width:1280px; margin:0 auto; color:var(--sub); font-size:13px; flex-wrap:wrap; gap:12px;
  }

  @media (max-width: 900px){
    .hero{grid-template-columns:1fr; padding:64px 24px;}
    .hero h1{font-size:36px;}
    .mockup{width:100%; max-width:380px;}
    section{padding:56px 24px;}
    .docs-layout{grid-template-columns:1fr;}
    .docs-nav{position:relative; top:0; flex-direction:row; flex-wrap:wrap; margin-bottom:24px; max-height:none;}
    nav{padding:16px 20px;}
    .nav-links{display:none;}
  }

  @media (prefers-reduced-motion: reduce){
    *{animation:none !important; transition:none !important;}
  }
</style>
</head>
<body>

<div class="noise-bg"></div>
<div class="grid-overlay"></div>

<nav>
  <div class="brand">
    <div class="glyph">🦊</div>
    UILibrary
  </div>
  <div class="nav-links">
    <a href="#components">Komponen</a>
    <a href="#themes">Tema</a>
    <a href="#install">Instalasi</a>
    <a href="#docs">Dokumentasi</a>
    <a href="#notify">Notify</a>
  </div>
  <a href="#install" class="nav-cta">Mulai Pakai →</a>
</nav>

<!-- HERO -->
<div class="hero">
  <div>
    <div class="eyebrow">Modern Roblox UI Kit</div>
    <h1>Bangun menu in-game yang <span class="accent-text">terasa premium</span>, bukan generik.</h1>
    <p>Satu ModuleScript Lua untuk window, tab, dan 12 komponen siap pakai — lengkap dengan notifikasi, 20 tema warna, support icon custom, dan tier GamePass.</p>
    <div class="hero-buttons">
      <a href="#install" class="btn btn-primary">Lihat cara instalasi</a>
      <a href="#docs" class="btn btn-secondary">Baca dokumentasi</a>
    </div>
    <div class="hero-stats">
      <div><div class="stat-num">12</div><div class="stat-label">Komponen UI</div></div>
      <div><div class="stat-num">20</div><div class="stat-label">Tema Warna</div></div>
      <div><div class="stat-num">1</div><div class="stat-label">File ModuleScript</div></div>
    </div>
  </div>

  <div class="mockup-wrap">
    <div class="mockup">
      <div class="mockup-top">
        <div>
          <div class="mockup-title">Game Settings</div>
          <div class="mockup-sub">by YourName</div>
        </div>
        <div class="mockup-controls">
          <div class="ctrl min"></div>
          <div class="ctrl close"></div>
        </div>
      </div>
      <div class="mockup-body" style="position:relative;">
        <div class="mockup-sidebar">
          <div class="mockup-tab active"><span class="dot"></span>Main</div>
          <div class="mockup-tab"><span class="dot"></span>Appearance</div>
          <div class="mockup-tab"><span class="dot"></span>Premium</div>
        </div>
        <div class="mockup-content">
          <div class="mock-row"><span>Enable Music</span><div class="mock-switch"></div></div>
          <div class="mock-row"><span>Auto Sprint</span><div class="mock-switch off"></div></div>
          <div class="mock-row"><span>Volume</span><div class="mock-slider-track"><div class="mock-slider-fill"></div></div></div>
          <div class="mock-row"><span>Difficulty</span><span style="color:var(--sub)">Normal</span></div>
        </div>
        <div class="mock-notify">
          <div class="bar"></div>
          <div class="txt"><b>Saved!</b><span>Settings updated.</span></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- COMPONENTS OVERVIEW -->
<section id="components">
  <div class="section-head">
    <div class="section-eyebrow">Yang tersedia</div>
    <h2>Dua belas komponen, satu library</h2>
    <p>Semua dibangun dari Instance.new murni — tidak ada aset eksternal wajib, tidak ada dependency lain selain file ini. Setiap komponen mendukung icon custom lewat rbxassetid.</p>
  </div>
  <div class="comp-grid">
    <div class="comp-card"><div class="comp-icon">▣</div><h3>Button</h3><p>Tombol klik dengan feedback warna saat ditekan.</p></div>
    <div class="comp-card"><div class="comp-icon">⏼</div><h3>Toggle</h3><p>Switch on/off dengan animasi knob bergeser.</p></div>
    <div class="comp-card"><div class="comp-icon">═</div><h3>Slider</h3><p>Drag untuk atur nilai numerik dengan increment custom.</p></div>
    <div class="comp-card"><div class="comp-icon">▾</div><h3>Dropdown</h3><p>Pilih satu opsi dari daftar, dengan chevron vektor murni.</p></div>
    <div class="comp-card"><div class="comp-icon">▭</div><h3>Input</h3><p>Textbox dengan placeholder dan callback saat selesai diisi.</p></div>
    <div class="comp-card"><div class="comp-icon">◍</div><h3>Color Picker</h3><p>Atur warna lewat slider R/G/B dengan preview swatch.</p></div>
    <div class="comp-card"><div class="comp-icon">⌨</div><h3>Keybind</h3><p>Klik lalu tekan tombol apa pun untuk mem-bind aksi.</p></div>
    <div class="comp-card"><div class="comp-icon">—</div><h3>Section</h3><p>Divider berlabel untuk mengelompokkan elemen di satu tab.</p></div>
    <div class="comp-card"><div class="comp-icon">i</div><h3>Label</h3><p>Blok teks info, sekarang bisa disertai icon.</p></div>
    <div class="comp-card" style="border-color:rgba(230,188,90,0.3);"><div class="comp-icon" style="color:var(--gold);">★</div><h3>GamepassTier</h3><p>Baris premium Bronze/Silver/Gold terhubung ke MarketplaceService.</p></div>
    <div class="comp-card"><div class="comp-icon">▶</div><h3>SocialButton<span class="new-badge">New</span></h3><p>Tombol yang membuka link eksternal (YouTube, Discord, dll).</p></div>
    <div class="comp-card"><div class="comp-icon">◐</div><h3>ThemePicker<span class="new-badge">New</span></h3><p>Dropdown 20 tema siap pakai, langsung dari dalam UI.</p></div>
  </div>
</section>

<!-- THEMES -->
<section id="themes">
  <div class="section-head">
    <div class="section-eyebrow">Personalisasi</div>
    <h2>20 tema warna siap pakai</h2>
    <p>Ganti tampilan seluruh UI cuma dengan satu baris kode. Tema default proyek ini adalah <strong>Kitsune</strong>.</p>
  </div>
  <div class="theme-grid">
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0f0f11"></span><span style="background:#787882"></span><span style="background:#1a1a1e"></span></div><div class="theme-swatch-name">Black</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#f6f6f8"></span><span style="background:#5a50e6"></span><span style="background:#e6e6eb"></span></div><div class="theme-swatch-name">White</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#101014"></span><span style="background:#ff7a45"></span><span style="background:#1e1c22"></span></div><div class="theme-swatch-name">Kitsune</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0d0d0f"></span><span style="background:#c4a65a"></span><span style="background:#161512"></span></div><div class="theme-swatch-name">BlackElegan</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0a0c14"></span><span style="background:#5078ff"></span><span style="background:#121c34"></span></div><div class="theme-swatch-name">Midnight</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#120c0d"></span><span style="background:#dc3c46"></span><span style="background:#1e1011"></span></div><div class="theme-swatch-name">Crimson</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0a1216"></span><span style="background:#2db4c8"></span><span style="background:#12181d"></span></div><div class="theme-swatch-name">Ocean</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0d120e"></span><span style="background:#5fb464"></span><span style="background:#121810"></span></div><div class="theme-swatch-name">Forest</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#140e10"></span><span style="background:#f58250"></span><span style="background:#1a1213"></span></div><div class="theme-swatch-name">Sunset</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#121016"></span><span style="background:#aa8ceb"></span><span style="background:#181520"></span></div><div class="theme-swatch-name">Lavender</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#08080e"></span><span style="background:#ff28a0"></span><span style="background:#0e0e1a"></span></div><div class="theme-swatch-name">Cyberpunk</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#140e11"></span><span style="background:#eb5f96"></span><span style="background:#1b1216"></span></div><div class="theme-swatch-name">Rose</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#110f0a"></span><span style="background:#e6bc5a"></span><span style="background:#171410"></span></div><div class="theme-swatch-name">Gold</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#e8eef4"></span><span style="background:#328cd2"></span><span style="background:#dee6ee"></span></div><div class="theme-swatch-name">Arctic</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0e0a0c"></span><span style="background:#a01e32"></span><span style="background:#130e10"></span></div><div class="theme-swatch-name">Vampire</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0e1312"></span><span style="background:#50d7b4"></span><span style="background:#131918"></span></div><div class="theme-swatch-name">Mint</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0c0c16"></span><span style="background:#8264eb"></span><span style="background:#11111e"></span></div><div class="theme-swatch-name">Royal</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#140f0f"></span><span style="background:#ff6e5f"></span><span style="background:#1b1413"></span></div><div class="theme-swatch-name">Coral</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#141619"></span><span style="background:#6e8ca5"></span><span style="background:#1a1c20"></span></div><div class="theme-swatch-name">Slate</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#0f120c"></span><span style="background:#aae146"></span><span style="background:#141f15"></span></div><div class="theme-swatch-name">Lime</div></div>
    <div class="theme-swatch"><div class="theme-swatch-bar"><span style="background:#09090b"></span><span style="background:#46c8d2"></span><span style="background:#0e0e10"></span></div><div class="theme-swatch-name">Obsidian</div></div>
  </div>
  <pre><span class="c1">-- Ganti tema sebelum CreateWindow</span>
UILibrary:SetTheme(<span class="c4">"Cyberpunk"</span>)

<span class="c2">local</span> Window = UILibrary:CreateWindow({ Title = <span class="c4">"Game Settings"</span> })</pre>
</section>

<!-- INSTALL -->
<section id="install">
  <div class="section-head">
    <div class="section-eyebrow">Mulai dalam 3 langkah</div>
    <h2>Instalasi</h2>
    <p>Tidak perlu plugin tambahan. Cukup satu ModuleScript dan kamu siap.</p>
  </div>
  <div class="steps">
    <div class="step">
      <div class="step-num">1</div>
      <div>
        <h3>Tambahkan ModuleScript</h3>
        <p>Buat ModuleScript baru di <code class="inline">ReplicatedStorage</code>, beri nama <code class="inline">UILibrary</code>, lalu isi dengan kode dari file <code class="inline">UILibrary.lua</code>.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div>
        <h3>Require dari LocalScript</h3>
        <p>Panggil library dari LocalScript mana pun — biasanya di <code class="inline">StarterPlayerScripts</code>.</p>
        <pre><span class="c1">-- LocalScript</span>
<span class="c2">local</span> UILibrary = require(game.ReplicatedStorage.UILibrary)</pre>
      </div>
    </div>
    <div class="step">
      <div class="step-num">3</div>
      <div>
        <h3>Buat window pertamamu</h3>
        <p>Window dan tab pertama akan otomatis terlihat begitu dibuat.</p>
        <pre><span class="c2">local</span> Window = UILibrary:CreateWindow({
  Title = <span class="c4">"Game Settings"</span>,
  SubTitle = <span class="c4">"by YourName"</span>,
})

<span class="c2">local</span> Tab = Window:CreateTab(<span class="c4">"Main"</span>)</pre>
      </div>
    </div>
  </div>
</section>

<!-- DOCS -->
<section id="docs">
  <div class="section-head">
    <div class="section-eyebrow">Referensi API</div>
    <h2>Dokumentasi komponen</h2>
    <p>Setiap komponen menerima tabel konfigurasi dan mengembalikan handle untuk diubah nilainya secara programatik. Parameter <code class="inline">Icon</code> tersedia di hampir semua komponen.</p>
  </div>

  <div class="docs-layout">
    <div class="docs-nav">
      <div class="docs-nav-label">Struktur</div>
      <a href="#doc-window">Window</a>
      <a href="#doc-tab">Tab</a>
      <div class="docs-nav-label">Komponen</div>
      <a href="#doc-button">Button</a>
      <a href="#doc-toggle">Toggle</a>
      <a href="#doc-slider">Slider</a>
      <a href="#doc-dropdown">Dropdown</a>
      <a href="#doc-input">Input</a>
      <a href="#doc-colorpicker">ColorPicker</a>
      <a href="#doc-keybind">Keybind</a>
      <a href="#doc-section">Section</a>
      <a href="#doc-label">Label</a>
      <div class="docs-nav-label">Premium &amp; Lainnya</div>
      <a href="#doc-gamepasstier">GamepassTier</a>
      <a href="#doc-socialbutton">SocialButton</a>
      <a href="#doc-themepicker">ThemePicker</a>
    </div>

    <div>
      <div class="doc-block" id="doc-window">
        <div class="doc-block-head"><h3>CreateWindow</h3><span class="doc-tag">UILibrary:CreateWindow(config)</span></div>
        <div class="doc-block-body">
          <p>Membuat jendela utama, lengkap dengan tombol Minimize dan Close di top bar. Hanya bisa ada satu window aktif — memanggil ulang akan mengganti window lama.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Default</th><th>Keterangan</th></tr>
            <tr><td>Title</td><td>string</td><td>"UI Library"</td><td>Judul di top bar</td></tr>
            <tr><td>SubTitle</td><td>string</td><td>""</td><td>Teks kecil di bawah judul</td></tr>
            <tr><td>Size</td><td>UDim2</td><td>620×420</td><td>Ukuran window</td></tr>
            <tr><td>ToggleKey</td><td>Enum.KeyCode</td><td>RightShift</td><td>Tombol show/hide window</td></tr>
          </table>
          <pre><span class="c2">local</span> Window = UILibrary:CreateWindow({
  Title = <span class="c4">"Admin Panel"</span>,
  SubTitle = <span class="c4">"v1.0"</span>,
  Size = UDim2.fromOffset(<span class="c5">620</span>, <span class="c5">420</span>),
  ToggleKey = Enum.KeyCode.F1,
})

<span class="c1">-- Kontrol manual:</span>
Window:SetVisible(<span class="c5">false</span>)
Window:SetMinimized(<span class="c5">true</span>)</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-tab">
        <div class="doc-block-head"><h3>CreateTab</h3><span class="doc-tag">Window:CreateTab(name, icon)</span></div>
        <div class="doc-block-body">
          <p>Menambah tab baru ke sidebar. Tab pertama yang dibuat otomatis aktif. Parameter <code class="inline">icon</code> opsional, menerima rbxassetid.</p>
          <pre><span class="c2">local</span> Tab = Window:CreateTab(<span class="c4">"Main"</span>, <span class="c4">"rbxassetid://10709790948"</span>)</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-button">
        <div class="doc-block-head"><h3>Button</h3><span class="doc-tag">Tab:CreateButton(config)</span></div>
        <div class="doc-block-body">
          <p>Tombol sekali klik. Cocok untuk aksi langsung seperti respawn atau reset.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label tombol</td></tr>
            <tr><td>Icon</td><td>rbxassetid</td><td>Icon opsional di kiri label</td></tr>
            <tr><td>Callback</td><td>function</td><td>Dipanggil saat tombol diklik</td></tr>
          </table>
          <pre>Tab:CreateButton({
  Name = <span class="c4">"Respawn"</span>,
  Icon = <span class="c4">"rbxassetid://10734952000"</span>,
  Callback = <span class="c2">function</span>()
    print(<span class="c4">"Respawn ditekan"</span>)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-toggle">
        <div class="doc-block-head"><h3>Toggle</h3><span class="doc-tag">Tab:CreateToggle(config)</span></div>
        <div class="doc-block-body">
          <p>Switch dua kondisi. Mengembalikan handle dengan method <code class="inline">.Set(bool)</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label toggle</td></tr>
            <tr><td>Icon</td><td>rbxassetid</td><td>Icon opsional</td></tr>
            <tr><td>CurrentValue</td><td>boolean</td><td>Nilai awal</td></tr>
            <tr><td>Callback</td><td>function(value)</td><td>Dipanggil setiap kali berubah</td></tr>
          </table>
          <pre><span class="c2">local</span> musicToggle = Tab:CreateToggle({
  Name = <span class="c4">"Enable Music"</span>,
  CurrentValue = <span class="c5">true</span>,
  Callback = <span class="c2">function</span>(value)
    print(<span class="c4">"Music:"</span>, value)
  <span class="c2">end</span>
})

musicToggle.Set(<span class="c5">false</span>)</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-slider">
        <div class="doc-block-head"><h3>Slider</h3><span class="doc-tag">Tab:CreateSlider(config)</span></div>
        <div class="doc-block-body">
          <p>Input numerik lewat drag. Mengembalikan handle dengan method <code class="inline">.Set(number)</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label slider</td></tr>
            <tr><td>Range</td><td>{min, max}</td><td>Batas nilai</td></tr>
            <tr><td>Increment</td><td>number</td><td>Kelipatan langkah nilai</td></tr>
            <tr><td>CurrentValue</td><td>number</td><td>Nilai awal</td></tr>
            <tr><td>Callback</td><td>function(value)</td><td>Dipanggil setiap nilai berubah</td></tr>
          </table>
          <pre>Tab:CreateSlider({
  Name = <span class="c4">"Volume"</span>,
  Range = {<span class="c5">0</span>, <span class="c5">100</span>},
  Increment = <span class="c5">1</span>,
  CurrentValue = <span class="c5">50</span>,
  Callback = <span class="c2">function</span>(value)
    print(<span class="c4">"Volume:"</span>, value)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-dropdown">
        <div class="doc-block-head"><h3>Dropdown</h3><span class="doc-tag">Tab:CreateDropdown(config)</span></div>
        <div class="doc-block-body">
          <p>Memilih satu opsi dari daftar. Chevron panahnya dibentuk dari shape vektor murni (bukan karakter font), jadi tampil konsisten di semua platform. Mengembalikan handle dengan <code class="inline">.Set(string)</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label dropdown</td></tr>
            <tr><td>Options</td><td>{string}</td><td>Daftar pilihan</td></tr>
            <tr><td>CurrentOption</td><td>string</td><td>Opsi terpilih awal</td></tr>
            <tr><td>Callback</td><td>function(option)</td><td>Dipanggil saat opsi dipilih</td></tr>
          </table>
          <pre>Tab:CreateDropdown({
  Name = <span class="c4">"Difficulty"</span>,
  Options = {<span class="c4">"Easy"</span>, <span class="c4">"Normal"</span>, <span class="c4">"Hard"</span>},
  CurrentOption = <span class="c4">"Normal"</span>,
  Callback = <span class="c2">function</span>(option)
    print(<span class="c4">"Difficulty:"</span>, option)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-input">
        <div class="doc-block-head"><h3>Input</h3><span class="doc-tag">Tab:CreateInput(config)</span></div>
        <div class="doc-block-body">
          <p>Kotak teks bebas. Mengembalikan handle dengan <code class="inline">.Set(text)</code> dan <code class="inline">.Get()</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label input</td></tr>
            <tr><td>PlaceholderText</td><td>string</td><td>Teks placeholder</td></tr>
            <tr><td>Callback</td><td>function(text, enterPressed)</td><td>Dipanggil saat fokus hilang</td></tr>
          </table>
          <pre>Tab:CreateInput({
  Name = <span class="c4">"Username"</span>,
  PlaceholderText = <span class="c4">"Type here..."</span>,
  Callback = <span class="c2">function</span>(text)
    print(<span class="c4">"Input:"</span>, text)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-colorpicker">
        <div class="doc-block-head"><h3>ColorPicker</h3><span class="doc-tag">Tab:CreateColorPicker(config)</span></div>
        <div class="doc-block-body">
          <p>Pemilih warna lewat tiga slider R/G/B. Mengembalikan handle dengan <code class="inline">.Set(Color3)</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label color picker</td></tr>
            <tr><td>CurrentColor</td><td>Color3</td><td>Warna awal</td></tr>
            <tr><td>Callback</td><td>function(color)</td><td>Dipanggil setiap warna berubah</td></tr>
          </table>
          <pre>Tab:CreateColorPicker({
  Name = <span class="c4">"Accent Color"</span>,
  CurrentColor = Color3.fromRGB(<span class="c5">105</span>, <span class="c5">92</span>, <span class="c5">255</span>),
  Callback = <span class="c2">function</span>(color)
    print(color)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-keybind">
        <div class="doc-block-head"><h3>Keybind</h3><span class="doc-tag">Tab:CreateKeybind(config)</span></div>
        <div class="doc-block-body">
          <p>Klik lalu tekan tombol apa pun untuk merekam keybind baru. Mengembalikan handle dengan <code class="inline">.Set(keyName)</code>.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label keybind</td></tr>
            <tr><td>CurrentKeybind</td><td>string</td><td>Nama tombol awal</td></tr>
            <tr><td>Callback</td><td>function(key)</td><td>Dipanggil saat tombol baru direkam</td></tr>
          </table>
          <pre>Tab:CreateKeybind({
  Name = <span class="c4">"Open Menu"</span>,
  CurrentKeybind = <span class="c4">"RightShift"</span>,
  Callback = <span class="c2">function</span>(key)
    print(<span class="c4">"Bound to:"</span>, key)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-section">
        <div class="doc-block-head"><h3>Section</h3><span class="doc-tag">Tab:CreateSection(name)</span></div>
        <div class="doc-block-body">
          <p>Header berlabel dengan garis pembatas, untuk mengelompokkan elemen secara visual dalam satu tab.</p>
          <pre>Tab:CreateSection(<span class="c4">"Player Options"</span>)</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-label">
        <div class="doc-block-head"><h3>Label</h3><span class="doc-tag">Tab:CreateLabel(text | config)</span></div>
        <div class="doc-block-body">
          <p>Blok teks statis. Bisa dipanggil dengan string biasa, atau tabel kalau ingin menambahkan icon.</p>
          <pre>Tab:CreateLabel(<span class="c4">"Tekan RightShift untuk buka/tutup menu ini."</span>)

<span class="c1">-- dengan icon:</span>
Tab:CreateLabel({
  Text = <span class="c4">"Info penting"</span>,
  Icon = <span class="c4">"rbxassetid://10734959000"</span>,
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-gamepasstier">
        <div class="doc-block-head"><h3>GamepassTier</h3><span class="doc-tag">Tab:CreateGamepassTier(config)</span></div>
        <div class="doc-block-body">
          <p>Baris premium yang terhubung langsung ke <code class="inline">MarketplaceService</code> resmi Roblox — tanpa loadstring eksternal apa pun. Mengecek kepemilikan otomatis dan memunculkan dialog beli native saat diklik.</p>
          <div class="tier-grid">
            <div class="tier-card bronze"><h4>Bronze</h4><p>Tier dasar, harga termurah</p></div>
            <div class="tier-card silver"><h4>Silver</h4><p>Tier menengah</p></div>
            <div class="tier-card gold"><h4>Gold</h4><p>Tier tertinggi, semua fitur</p></div>
          </div>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Nama pass</td></tr>
            <tr><td>Tier</td><td>"Bronze"|"Silver"|"Gold"</td><td>Menentukan warna aksen</td></tr>
            <tr><td>GamepassId</td><td>number</td><td>ID GamePass dari Developer Console</td></tr>
            <tr><td>Price</td><td>number</td><td>Opsional, untuk label harga</td></tr>
            <tr><td>OnUnlocked</td><td>function</td><td>Dipanggil saat pemain memiliki pass</td></tr>
          </table>
          <pre>Tab:CreateGamepassTier({
  Name = <span class="c4">"Gold Pass"</span>,
  Tier = <span class="c4">"Gold"</span>,
  GamepassId = <span class="c5">000000003</span>,
  Price = <span class="c5">199</span>,
  OnUnlocked = <span class="c2">function</span>()
    print(<span class="c4">"Gold Pass aktif!"</span>)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-socialbutton">
        <div class="doc-block-head"><h3>SocialButton</h3><span class="doc-tag">Tab:CreateSocialButton(config)</span></div>
        <div class="doc-block-body">
          <p>Tombol yang membuka URL eksternal lewat browser bawaan Roblox (<code class="inline">GuiService:OpenBrowserWindowAsync</code>). Hanya berfungsi saat game dimainkan lewat aplikasi Roblox sungguhan — tidak berjalan di Studio Play Mode.</p>
          <table class="params">
            <tr><th>Parameter</th><th>Tipe</th><th>Keterangan</th></tr>
            <tr><td>Name</td><td>string</td><td>Label tombol</td></tr>
            <tr><td>URL</td><td>string</td><td>Link tujuan, harus diawali https://</td></tr>
            <tr><td>Icon</td><td>emoji atau rbxassetid</td><td>Icon di kiri label</td></tr>
          </table>
          <pre>Tab:CreateSocialButton({
  Name = <span class="c4">"Subscribe YouTube"</span>,
  URL = <span class="c4">"https://youtube.com/@KitsuneeIsMe"</span>,
})</pre>
        </div>
      </div>

      <div class="doc-block" id="doc-themepicker">
        <div class="doc-block-head"><h3>ThemePicker</h3><span class="doc-tag">Tab:CreateThemePicker(config)</span></div>
        <div class="doc-block-body">
          <p>Dropdown berisi 20 tema yang tersedia. Memanggil <code class="inline">UILibrary:SetTheme()</code> di balik layar saat pemain memilih opsi.</p>
          <pre>Tab:CreateThemePicker({
  Name = <span class="c4">"UI Theme"</span>,
  OnChange = <span class="c2">function</span>(themeName)
    print(<span class="c4">"Tema diganti ke:"</span>, themeName)
  <span class="c2">end</span>
})</pre>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- NOTIFY -->
<section id="notify">
  <div class="section-head">
    <div class="section-eyebrow">Sistem terpisah</div>
    <h2>Notify</h2>
    <p>Tidak terikat ke window manapun — bisa dipanggil dari script apa saja, kapan saja, untuk memberi feedback singkat ke pemain.</p>
  </div>

  <div class="notify-demo-grid">
    <div class="notify-demo"><div class="bar" style="background:var(--success)"></div><div><b>Success</b><span>Aksi berhasil dilakukan.</span></div></div>
    <div class="notify-demo"><div class="bar" style="background:var(--error)"></div><div><b>Error</b><span>Sesuatu gagal diproses.</span></div></div>
    <div class="notify-demo"><div class="bar" style="background:var(--warning)"></div><div><b>Warning</b><span>Perlu perhatian pemain.</span></div></div>
    <div class="notify-demo"><div class="bar" style="background:var(--info)"></div><div><b>Info</b><span>Informasi umum atau tips.</span></div></div>
  </div>

  <pre>UILibrary:Notify({
  Title = <span class="c4">"Saved!"</span>,
  Content = <span class="c4">"Your settings have been saved."</span>,
  Duration = <span class="c5">4</span>,
  Type = <span class="c4">"Success"</span>, <span class="c1">-- Success | Error | Warning | Info</span>
})</pre>
</section>

<footer>
  <div>🦊 UILibrary — dibuat untuk dipasang di game Roblox-mu sendiri.</div>
  <div>Tidak ada dependency eksternal. Tidak ada loadstring tersembunyi.</div>
</footer>

<script>
  document.querySelectorAll('.mockup-tab').forEach(tab => {
    tab.addEventListener('click', () => {
      document.querySelectorAll('.mockup-tab').forEach(t => t.classList.remove('active'));
      tab.classList.add('active');
    });
  });

  document.querySelectorAll('.mock-switch').forEach(sw => {
    sw.style.cursor = 'pointer';
    sw.addEventListener('click', () => sw.classList.toggle('off'));
  });
</script>

</body>
</html>
