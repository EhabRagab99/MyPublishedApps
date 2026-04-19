<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Ehab Ragab — Published Production Apps</title>
<meta name="description" content="25+ production mobile apps shipped to Google Play and App Store across 8 industry domains. Senior Flutter Developer · Mobile Team Lead · CTO.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">

<style>
/* ══════════════════════════════════════════════════
   RESET & TOKENS
══════════════════════════════════════════════════ */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth;font-size:16px}
:root{
  --bg:       #080C18;
  --bg2:      #0D1122;
  --bg3:      #111827;
  --card:     #131B2E;
  --card2:    #1A2340;
  --border:   rgba(255,255,255,.07);
  --border2:  rgba(255,255,255,.13);

  --cyan:     #00D9FF;
  --cyan-d:   rgba(0,217,255,.1);
  --cyan-glow:rgba(0,217,255,.2);
  --violet:   #7C3AED;
  --violet-d: rgba(124,58,237,.12);
  --amber:    #F59E0B;
  --amber-d:  rgba(245,158,11,.1);
  --green:    #10B981;
  --green-d:  rgba(16,185,129,.1);
  --rose:     #F43F5E;
  --rose-d:   rgba(244,63,94,.1);
  --blue:     #3B82F6;
  --blue-d:   rgba(59,130,246,.1);
  --orange:   #F97316;
  --orange-d: rgba(249,115,22,.1);
  --gold:     #D4AF37;
  --gold-d:   rgba(212,175,55,.1);

  --t1:#F1F5FF;
  --t2:#8896B0;
  --t3:#3D4A65;

  --fn:'Inter',system-ui,sans-serif;
  --fm:'JetBrains Mono',monospace;
  --r: 14px;
  --rl:20px;
  --rp:100px;
}

body{font-family:var(--fn);background:var(--bg);color:var(--t1);line-height:1.6;overflow-x:hidden}

/* ── SCROLLBAR ── */
::-webkit-scrollbar{width:4px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--card2);border-radius:100px}

/* ── NOISE OVERLAY ── */
body::before{
  content:'';position:fixed;inset:0;z-index:0;pointer-events:none;
  background:
    radial-gradient(ellipse 70% 50% at 80% 0%,rgba(0,217,255,.06),transparent),
    radial-gradient(ellipse 60% 40% at 20% 100%,rgba(124,58,237,.05),transparent);
}
body::after{
  content:'';position:fixed;inset:0;z-index:0;pointer-events:none;
  background-image:radial-gradient(circle,rgba(255,255,255,.025) 1px,transparent 1px);
  background-size:32px 32px;
}

/* ── LAYOUT ── */
section,.w{position:relative;z-index:1}
.w{max-width:1200px;margin:0 auto;padding:0 clamp(20px,5vw,64px)}

/* ══════════════════════════════════════════════════
   NAV
══════════════════════════════════════════════════ */
nav{
  position:sticky;top:0;z-index:100;
  backdrop-filter:blur(24px);
  background:rgba(8,12,24,.82);
  border-bottom:1px solid var(--border);
}
.nav-inner{
  max-width:1200px;margin:0 auto;
  padding:14px clamp(20px,5vw,64px);
  display:flex;align-items:center;justify-content:space-between;gap:20px;
}
.nav-logo{
  font-family:var(--fm);font-size:.75rem;font-weight:600;
  color:var(--cyan);letter-spacing:2px;text-decoration:none;
  display:flex;align-items:center;gap:8px;
}
.nav-logo::before{
  content:'';width:8px;height:8px;border-radius:50%;
  background:var(--cyan);box-shadow:0 0 8px var(--cyan);
  animation:pulse 2s infinite;
}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.6;transform:scale(.85)}}
.nav-links{display:flex;gap:4px;align-items:center;flex-wrap:wrap}
.nav-link{
  font-size:.78rem;color:var(--t2);text-decoration:none;
  padding:5px 12px;border-radius:var(--rp);
  transition:.15s;border:1px solid transparent;
}
.nav-link:hover{color:var(--t1);background:rgba(255,255,255,.05);border-color:var(--border)}
.nav-cta{
  font-size:.78rem;font-weight:600;font-family:var(--fm);
  color:var(--bg);background:var(--cyan);
  padding:6px 16px;border-radius:var(--rp);
  text-decoration:none;transition:.15s;letter-spacing:.3px;white-space:nowrap;
}
.nav-cta:hover{filter:brightness(1.12);transform:translateY(-1px)}

/* ══════════════════════════════════════════════════
   HERO
══════════════════════════════════════════════════ */
#hero{padding:80px 0 64px;text-align:center}
.hero-pill{
  display:inline-flex;align-items:center;gap:8px;
  font-family:var(--fm);font-size:.65rem;letter-spacing:2px;text-transform:uppercase;
  color:var(--cyan);background:var(--cyan-d);
  border:1px solid rgba(0,217,255,.2);border-radius:var(--rp);
  padding:6px 16px;margin-bottom:28px;
}
.hero-title{
  font-size:clamp(2rem,5.5vw,4rem);
  font-weight:900;letter-spacing:-1.5px;line-height:1.07;
  margin-bottom:16px;
}
.hero-title em{
  font-style:normal;
  background:linear-gradient(135deg,var(--cyan) 0%,var(--violet) 100%);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
}
.hero-sub{
  font-size:1.05rem;color:var(--t2);max-width:600px;margin:0 auto 40px;line-height:1.75;
}
/* Stats strip */
.stats{
  display:inline-flex;align-items:stretch;gap:0;
  background:var(--card);border:1px solid var(--border2);
  border-radius:var(--rl);overflow:hidden;margin-bottom:40px;
}
.stat{
  padding:18px 28px;text-align:center;
  border-right:1px solid var(--border);
}
.stat:last-child{border-right:none}
.stat-n{
  font-size:1.7rem;font-weight:800;letter-spacing:-1px;
  background:linear-gradient(135deg,var(--cyan),var(--violet));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  line-height:1;margin-bottom:4px;
}
.stat-l{font-size:.68rem;color:var(--t2);text-transform:uppercase;letter-spacing:.8px}

/* Quick nav chips */
.quick-nav{display:flex;flex-wrap:wrap;justify-content:center;gap:8px}
.qn{
  font-family:var(--fm);font-size:.68rem;
  padding:7px 16px;border-radius:var(--rp);
  border:1px solid var(--border);color:var(--t2);
  text-decoration:none;transition:.15s;letter-spacing:.3px;
  background:transparent;cursor:pointer;
}
.qn:hover,.qn.act{color:var(--cyan);border-color:rgba(0,217,255,.35);background:var(--cyan-d)}

/* ══════════════════════════════════════════════════
   SECTION HEADERS
══════════════════════════════════════════════════ */
.sec-label{
  display:inline-flex;align-items:center;gap:8px;
  font-family:var(--fm);font-size:.62rem;letter-spacing:2px;text-transform:uppercase;
  color:var(--t2);margin-bottom:10px;
}
.sec-label::before{
  content:'';display:block;width:20px;height:2px;border-radius:1px;
  background:linear-gradient(90deg,var(--cyan),var(--violet));
}
.sec-title{
  font-size:clamp(1.6rem,3vw,2.2rem);
  font-weight:800;letter-spacing:-.4px;margin-bottom:6px;
}
.sec-sub{font-size:.9rem;color:var(--t2);line-height:1.7;max-width:560px}

/* ══════════════════════════════════════════════════
   FEATURED SECTION
══════════════════════════════════════════════════ */
#featured{padding:56px 0 48px}
.feat-head{
  display:flex;align-items:flex-end;justify-content:space-between;
  flex-wrap:wrap;gap:16px;margin-bottom:28px;
}
.feat-grid{
  display:grid;
  grid-template-columns:1.4fr 1fr 1fr;
  gap:14px;
}
/* Featured card */
.fc{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--rl);overflow:hidden;
  display:flex;flex-direction:column;
  transition:.22s;position:relative;
}
.fc:hover{
  border-color:var(--border2);
  transform:translateY(-4px);
  box-shadow:0 20px 48px rgba(0,0,0,.45);
}
.fc-top-bar{height:3px;width:100%}
.fc-body{padding:22px;flex:1;display:flex;flex-direction:column;gap:0}
.fc-meta{display:flex;align-items:center;gap:10px;margin-bottom:14px}
.fc-logo{
  width:48px;height:48px;border-radius:12px;
  object-fit:cover;flex-shrink:0;
  background:var(--card2);border:1px solid var(--border);
}
.fc-logo-ph{
  width:48px;height:48px;border-radius:12px;
  background:var(--card2);border:1px solid var(--border);
  display:flex;align-items:center;justify-content:center;
  font-size:1.2rem;flex-shrink:0;font-weight:800;
  font-family:var(--fm);color:var(--t2);
}
.fc-cat{
  font-family:var(--fm);font-size:.58rem;letter-spacing:1.5px;text-transform:uppercase;
  margin-bottom:3px;
}
.fc-name{font-size:1rem;font-weight:700;line-height:1.2}
.fc-desc{font-size:.82rem;color:var(--t2);line-height:1.7;flex:1;margin-bottom:14px}
.fc-foot{
  display:flex;align-items:center;gap:7px;
  flex-wrap:wrap;
  padding-top:14px;
  border-top:1px solid var(--border);
  margin-top:auto;
}
/* First featured card extra emphasis */
.fc-hero{
  grid-row:span 2;
  border-color:rgba(0,217,255,.18);
  background:linear-gradient(160deg,#0F1D38 0%,var(--card) 60%);
}
.fc-hero:hover{border-color:rgba(0,217,255,.35)}
.fc-hero .fc-body{padding:28px}
.fc-hero .fc-logo,.fc-hero .fc-logo-ph{width:64px;height:64px;border-radius:16px;font-size:1.4rem}
.fc-hero .fc-name{font-size:1.3rem}
.fc-hero .fc-desc{font-size:.88rem}
.fc-hero .fc-desc-long{display:block}
.fc-desc-long{display:none}

/* ══════════════════════════════════════════════════
   ALL PROJECTS SECTION
══════════════════════════════════════════════════ */
#projects{padding:48px 0 80px}
.proj-head{
  display:flex;align-items:flex-end;justify-content:space-between;
  flex-wrap:wrap;gap:16px;margin-bottom:20px;
}
/* Category filter tabs */
.cat-tabs{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:28px}
.cat-tab{
  font-family:var(--fm);font-size:.67rem;padding:6px 15px;
  border-radius:var(--rp);border:1px solid var(--border);
  color:var(--t2);background:transparent;cursor:pointer;
  transition:.15s;letter-spacing:.3px;
}
.cat-tab:hover,.cat-tab.on{
  color:var(--cyan);border-color:rgba(0,217,255,.35);background:var(--cyan-d);
}

/* Project grid */
.proj-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:14px}
/* Project card */
.pc{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--r);overflow:hidden;
  display:flex;flex-direction:column;
  transition:.22s;cursor:default;
}
.pc:hover{
  border-color:var(--border2);
  transform:translateY(-3px);
  box-shadow:0 14px 36px rgba(0,0,0,.4);
}
.pc-bar{height:2.5px;width:100%}
.pc-body{padding:18px;flex:1;display:flex;flex-direction:column}
.pc-meta{display:flex;align-items:center;gap:11px;margin-bottom:12px}
.pc-icon{
  width:44px;height:44px;border-radius:11px;
  background:var(--card2);border:1px solid var(--border);
  display:flex;align-items:center;justify-content:center;
  font-family:var(--fm);font-size:.8rem;font-weight:700;
  color:var(--t2);flex-shrink:0;
}
.pc-icon img{width:44px;height:44px;border-radius:11px;object-fit:cover}
.pc-cat{font-family:var(--fm);font-size:.57rem;letter-spacing:1px;text-transform:uppercase;margin-bottom:2px}
.pc-name{font-size:.94rem;font-weight:700;line-height:1.2}
.pc-desc{font-size:.79rem;color:var(--t2);line-height:1.68;flex:1;margin-bottom:12px}
.pc-foot{
  display:flex;align-items:center;gap:6px;flex-wrap:wrap;
  padding-top:11px;border-top:1px solid var(--border);
  margin-top:auto;
}

/* ══════════════════════════════════════════════════
   STORE BUTTONS
══════════════════════════════════════════════════ */
.sb{
  display:inline-flex;align-items:center;gap:5px;
  font-family:var(--fm);font-size:.62rem;font-weight:500;letter-spacing:.2px;
  padding:5px 12px;border-radius:7px;
  text-decoration:none;transition:.15s;border:1px solid;
  white-space:nowrap;
}
.sb-play{color:#4ADE80;border-color:rgba(74,222,128,.28);background:rgba(74,222,128,.07)}
.sb-play:hover{background:rgba(74,222,128,.14);transform:translateY(-1px)}
.sb-ios{color:#C8C2E0;border-color:rgba(200,194,224,.22);background:rgba(200,194,224,.05)}
.sb-ios:hover{background:rgba(200,194,224,.1);transform:translateY(-1px)}
.sb-web{color:var(--cyan);border-color:rgba(0,217,255,.22);background:var(--cyan-d)}
.sb-web:hover{background:rgba(0,217,255,.15);transform:translateY(-1px)}
.sb svg{width:12px;height:12px;flex-shrink:0}

/* ══════════════════════════════════════════════════
   CHIPS / TAGS
══════════════════════════════════════════════════ */
.chip{
  display:inline-flex;align-items:center;
  font-family:var(--fm);font-size:.58rem;
  padding:3px 8px;border-radius:5px;border:1px solid;white-space:nowrap;
}
.chip-c{color:var(--cyan);border-color:rgba(0,217,255,.22);background:var(--cyan-d)}
.chip-v{color:#A78BFA;border-color:rgba(167,139,250,.22);background:var(--violet-d)}
.chip-a{color:var(--amber);border-color:rgba(245,158,11,.22);background:var(--amber-d)}
.chip-g{color:var(--green);border-color:rgba(16,185,129,.22);background:var(--green-d)}
.chip-r{color:var(--rose);border-color:rgba(244,63,94,.22);background:var(--rose-d)}
.chip-b{color:#93C5FD;border-color:rgba(147,197,253,.22);background:var(--blue-d)}
.chip-o{color:var(--orange);border-color:rgba(249,115,22,.22);background:var(--orange-d)}
.chip-gold{color:var(--gold);border-color:rgba(212,175,55,.22);background:var(--gold-d)}
.chip-n{color:var(--t3);border-color:var(--border);background:var(--card2)}

/* ══════════════════════════════════════════════════
   CATEGORY DIVIDERS
══════════════════════════════════════════════════ */
.cat-section{margin-bottom:40px}
.cat-section-head{
  display:flex;align-items:center;gap:14px;
  margin-bottom:14px;
  font-family:var(--fm);font-size:.65rem;letter-spacing:2px;text-transform:uppercase;
  color:var(--t2);
}
.cat-section-head::after{content:'';flex:1;height:1px;background:var(--border)}

/* ══════════════════════════════════════════════════
   FOOTER
══════════════════════════════════════════════════ */
footer{
  border-top:1px solid var(--border);
  background:var(--bg2);
  padding:32px 0;text-align:center;
  position:relative;z-index:1;
}
.footer-name{
  font-size:.88rem;font-weight:600;color:var(--t1);margin-bottom:5px;
}
.footer-sub{font-size:.78rem;color:var(--t2);margin-bottom:16px}
.footer-links{display:flex;justify-content:center;gap:16px;flex-wrap:wrap}
.footer-link{
  font-family:var(--fm);font-size:.68rem;color:var(--t2);
  text-decoration:none;transition:.15s;
}
.footer-link:hover{color:var(--cyan)}

/* ══════════════════════════════════════════════════
   REVEAL ANIMATION
══════════════════════════════════════════════════ */
.r0{opacity:0;transform:translateY(20px);transition:opacity .55s ease,transform .55s ease}
.r0.in{opacity:1;transform:none}
.d1{transition-delay:.06s}.d2{transition-delay:.12s}.d3{transition-delay:.18s}
.d4{transition-delay:.24s}.d5{transition-delay:.30s}.d6{transition-delay:.36s}

/* ══════════════════════════════════════════════════
   RESPONSIVE
══════════════════════════════════════════════════ */
@media(max-width:1024px){
  .feat-grid{grid-template-columns:1fr 1fr}
  .fc-hero{grid-row:span 1}
  .fc-desc-long{display:none}
}
@media(max-width:720px){
  .feat-grid{grid-template-columns:1fr}
  .proj-grid{grid-template-columns:1fr}
  .stats{flex-wrap:wrap}
  .stat{flex:1;min-width:120px}
  .nav-links{display:none}
}
</style>
</head>
<body>

<!-- ════════════════════════ NAV ════════════════════════ -->
<nav>
  <div class="nav-inner">
    <a href="#" class="nav-logo">Ehab Ragab</a>
    <div class="nav-links">
      <a class="nav-link" href="#featured">Featured</a>
      <a class="nav-link" href="#gov-sec">Gov</a>
      <a class="nav-link" href="#hr-sec">HR Tech</a>
      <a class="nav-link" href="#prop-sec">PropTech</a>
      <a class="nav-link" href="#ec-sec">E-Commerce</a>
      <a class="nav-link" href="#fin-sec">FinTech</a>
      <a class="nav-link" href="#social-sec">Social</a>
    </div>
    <a class="nav-cta" href="mailto:ehabragab96@gmail.com">Hire Me</a>
  </div>
</nav>

<!-- ════════════════════════ HERO ════════════════════════ -->
<section id="hero">
  <div class="w" style="text-align:center">
    <div class="hero-pill">Published Production Apps</div>
    <h1 class="hero-title">25+ Apps.<br>8 Industries.<em><br>Real Impact.</em></h1>
    <p class="hero-sub">Senior Flutter Developer · Mobile Team Lead · CTO — building production-grade apps from architecture through App Store delivery since 2019.</p>
    <div class="stats" style="margin:0 auto 40px">
      <div class="stat"><div class="stat-n">25+</div><div class="stat-l">Apps Shipped</div></div>
      <div class="stat"><div class="stat-n">8</div><div class="stat-l">Industries</div></div>
      <div class="stat"><div class="stat-n">6+</div><div class="stat-l">Years Flutter</div></div>
      <div class="stat"><div class="stat-n">2</div><div class="stat-l">Platforms</div></div>
    </div>
    <!-- Quick navigation -->
    <div class="quick-nav">
      <a class="qn" href="#gov-sec">🏛 Government</a>
      <a class="qn" href="#hr-sec">👥 HR Tech</a>
      <a class="qn" href="#prop-sec">🏠 PropTech</a>
      <a class="qn" href="#ec-sec">🛒 E-Commerce</a>
      <a class="qn" href="#ride-sec">🚖 Ride Hailing</a>
      <a class="qn" href="#food-sec">🍔 Food</a>
      <a class="qn" href="#fin-sec">💡 FinTech</a>
      <a class="qn" href="#home-sec">🔧 Home Services</a>
      <a class="qn" href="#social-sec">⭐ Social</a>
    </div>
  </div>
</section>

<!-- ════════════════════════ FEATURED ════════════════════════ -->
<section id="featured" style="padding:56px 0 48px;position:relative;z-index:1">
  <div class="w">
    <div class="feat-head r0">
      <div>
        <div class="sec-label">Featured Work</div>
        <h2 class="sec-title">Flagship Projects</h2>
        <p class="sec-sub">High-impact apps across enterprise and government domains.</p>
      </div>
    </div>
    <div class="feat-grid r0">

      <!-- ★ NAJIZ — HERO CARD ★ -->
      <div class="fc fc-hero">
        <div class="fc-top-bar" style="background:linear-gradient(90deg,var(--gold),var(--amber))"></div>
        <div class="fc-body">
          <div class="fc-meta">
            <div class="fc-logo-ph" style="background:linear-gradient(135deg,#1A1400,#3D2E00);color:var(--gold);border-color:rgba(212,175,55,.3)">ن</div>
            <div>
              <div class="fc-cat" style="color:var(--gold)">Ministry of Justice · KSA</div>
              <div class="fc-name">Najiz | ناجز</div>
            </div>
          </div>
          <p class="fc-desc">Official digital services platform for the Ministry of Justice, Kingdom of Saudi Arabia. Enables citizens to access court services, case tracking, legal document management, and judicial appointments — built to serve millions of users across the country.</p>
          <p class="fc-desc fc-desc-long" style="margin-top:8px">Architected for enterprise scale with Clean Architecture, Bloc state management, offline capability, RTL support, and full Arabic localization.</p>
          <div class="fc-foot">
            <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.moj.najiz&hl=ar" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play
            </a>
            <a class="sb sb-ios" href="https://apps.apple.com/us/app/najiz/id1524792474" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store
            </a>
            <span class="chip chip-gold">Government</span>
            <span class="chip chip-c">Flutter</span>
          </div>
        </div>
      </div>

      <!-- HR LINK — FEATURED -->
      <div class="fc">
        <div class="fc-top-bar" style="background:linear-gradient(90deg,var(--cyan),var(--violet))"></div>
        <div class="fc-body">
          <div class="fc-meta">
            <div class="fc-logo-ph" style="background:linear-gradient(135deg,#0C2040,#1A3A6B);color:var(--cyan);border-color:rgba(0,217,255,.25)">HR</div>
            <div>
              <div class="fc-cat" style="color:var(--cyan)">Enterprise HR</div>
              <div class="fc-name">HR Link</div>
            </div>
          </div>
          <p class="fc-desc">Full-featured HR platform — employee self-service, recruitment pipelines, payroll management, and automated workflow approvals. Serving enterprise clients with a production-ready scalable system.</p>
          <div class="fc-foot">
            <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.multitech.link" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play
            </a>
            <a class="sb sb-ios" href="https://apps.apple.com/us/app/hr-link/id6476208994" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store
            </a>
            <span class="chip chip-c">Flutter</span>
          </div>
        </div>
      </div>

      <!-- TURNKII — FEATURED -->
      <div class="fc">
        <div class="fc-top-bar" style="background:linear-gradient(90deg,var(--green),#0EA472)"></div>
        <div class="fc-body">
          <div class="fc-meta">
            <div class="fc-logo-ph" style="background:linear-gradient(135deg,#012818,#0B5E3A);color:var(--green);border-color:rgba(16,185,129,.25)">TK</div>
            <div>
              <div class="fc-cat" style="color:var(--green)">PropTech</div>
              <div class="fc-name">TurnKii</div>
            </div>
          </div>
          <p class="fc-desc">Multi-sided property platform for owners, tenants, and service providers — with integrated financing tools, project management, and payment solutions to simplify the property lifecycle.</p>
          <div class="fc-foot">
            <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.turnkii.turnkiiapp" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play
            </a>
            <a class="sb sb-ios" href="https://apps.apple.com/eg/app/turnkii-app/id6742509535" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store
            </a>
            <span class="chip chip-g">Flutter</span>
          </div>
        </div>
      </div>

      <!-- IMPLOY — FEATURED -->
      <div class="fc">
        <div class="fc-top-bar" style="background:linear-gradient(90deg,#7C3AED,#A855F7)"></div>
        <div class="fc-body">
          <div class="fc-meta">
            <div class="fc-logo-ph" style="background:linear-gradient(135deg,#1A0533,#3D1A7A);color:#A78BFA;border-color:rgba(167,139,250,.25)">Im</div>
            <div>
              <div class="fc-cat" style="color:#A78BFA">Recruitment Platform</div>
              <div class="fc-name">Imploy</div>
            </div>
          </div>
          <p class="fc-desc">Two-sided recruitment platform where professionals build profiles and CVs while recruiters search using advanced multi-dimensional filters. Published on both stores.</p>
          <div class="fc-foot">
            <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=watan.imploy_app" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play
            </a>
            <a class="sb sb-ios" href="https://apps.apple.com/us/app/imploy/id1659274612" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store
            </a>
            <span class="chip chip-v">Flutter</span>
          </div>
        </div>
      </div>

    </div><!-- /feat-grid -->
  </div>
</section>

<!-- ════════════════════════ ALL PROJECTS ════════════════════════ -->
<section id="projects" style="padding:48px 0 80px;position:relative;z-index:1">
  <div class="w">
    <div class="proj-head r0">
      <div>
        <div class="sec-label">Full Portfolio</div>
        <h2 class="sec-title">All Published Apps</h2>
        <p class="sec-sub">Every app shipped to production — real users, real stores, real impact.</p>
      </div>
    </div>

    <!-- ── GOV / SECURITY ── -->
    <div class="cat-section r0" id="gov-sec">
      <div class="cat-section-head">🏛 &nbsp;Government &amp; Security</div>
      <div class="proj-grid">

        <!-- Najiz -->
        <div class="pc" data-cat="gov">
          <div class="pc-bar" style="background:linear-gradient(90deg,var(--gold),var(--amber))"></div>
          <div class="pc-body">
            <div class="pc-meta">
              <div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--gold);font-size:.75rem">ن</span></div>
              <div>
                <div class="pc-cat" style="color:var(--gold)">Ministry of Justice · KSA</div>
                <div class="pc-name">Najiz | ناجز</div>
              </div>
            </div>
            <p class="pc-desc">Official platform for Ministry of Justice digital services — court access, case tracking, legal documents, and judicial appointments for citizens across Saudi Arabia.</p>
            <div class="pc-foot">
              <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.moj.najiz&hl=ar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a>
              <a class="sb sb-ios" href="https://apps.apple.com/us/app/najiz/id1524792474" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a>
            </div>
          </div>
        </div>

        <!-- Amnco -->
        <div class="pc" data-cat="gov">
          <div class="pc-bar" style="background:linear-gradient(90deg,var(--gold),#9B8600)"></div>
          <div class="pc-body">
            <div class="pc-meta">
              <div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--gold)">A</span></div>
              <div>
                <div class="pc-cat" style="color:var(--gold)">Gov · Security · KSA</div>
                <div class="pc-name">Amnco</div>
              </div>
            </div>
            <p class="pc-desc">Comprehensive civil security services platform for government and private agencies across Saudi Arabia — built for reliability at national scale.</p>
            <div class="pc-foot">
              <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=sa.com.amnco" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a>
              <a class="sb sb-ios" href="https://apps.apple.com/us/app/amnco-op/id6504042795" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a>
            </div>
          </div>
        </div>

        <!-- Thaki -->
        <div class="pc" data-cat="gov">
          <div class="pc-bar" style="background:linear-gradient(90deg,var(--blue),var(--cyan))"></div>
          <div class="pc-body">
            <div class="pc-meta">
              <div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--blue)">ث</span></div>
              <div>
                <div class="pc-cat" style="color:var(--blue)">Smart City · Parking · KSA</div>
                <div class="pc-name">Thaki</div>
              </div>
            </div>
            <p class="pc-desc">Smart public road parking for Saudi Arabia — park reservations, violation payments, package subscriptions, and real-time fee management in one app.</p>
            <div class="pc-foot">
              <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.scscsa.thaki" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a>
              <a class="sb sb-ios" href="https://apps.apple.com/sa/app/thaki/id1576005384" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a>
            </div>
          </div>
        </div>

        <!-- International Judicial Conference -->
        <div class="pc" data-cat="gov">
          <div class="pc-bar" style="background:linear-gradient(90deg,var(--gold),var(--violet))"></div>
          <div class="pc-body">
            <div class="pc-meta">
              <div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--gold);font-size:.7rem">ICJ</span></div>
              <div>
                <div class="pc-cat" style="color:var(--gold)">Government · Judicial</div>
                <div class="pc-name">International Judicial Conference</div>
              </div>
            </div>
            <p class="pc-desc">Official app for the Second International Judicial Conference — conference agenda, speaker sessions, and judicial content for delegates and attendees.</p>
            <div class="pc-foot">
              <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.moj.icj&hl=ar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a>
              <a class="sb sb-ios" href="https://apps.apple.com/us/app/id6689517350" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a>
            </div>
          </div>
        </div>

        <!-- Saudi Real Estate Market -->
        <div class="pc" data-cat="gov">
          <div class="pc-bar" style="background:linear-gradient(90deg,var(--green),var(--gold))"></div>
          <div class="pc-body">
            <div class="pc-meta">
              <div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--green);font-size:.7rem">SREM</span></div>
              <div>
                <div class="pc-cat" style="color:var(--green)">PropTech · KSA Gov</div>
                <div class="pc-name">Saudi Real Estate Market</div>
              </div>
            </div>
            <p class="pc-desc">Official Saudi real estate market platform under the Ministry of Justice — property listings, market data, and transaction transparency for the KSA real estate sector.</p>
            <div class="pc-foot">
              <a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.srem.moj&hl=ar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a>
              <a class="sb sb-ios" href="https://apps.apple.com/us/app/saudi-real-estate-market/id6446234209" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- ── HR TECH ── -->
    <div class="cat-section r0" id="hr-sec">
      <div class="cat-section-head">👥 &nbsp;HR Tech &amp; Attendance</div>
      <div class="proj-grid">

        <!-- HR Link -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--cyan),var(--violet))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--cyan);font-size:.7rem">HR</span></div><div><div class="pc-cat" style="color:var(--cyan)">Enterprise HR</div><div class="pc-name">HR Link</div></div></div><p class="pc-desc">Full enterprise HR suite — employee self-service, recruitment, payroll management, benefits administration, and automated workflow approvals.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.multitech.link" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/hr-link/id6476208994" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <!-- Imploy -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,#7C3AED,#A855F7)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:#A78BFA">Im</span></div><div><div class="pc-cat" style="color:#A78BFA">Recruitment</div><div class="pc-name">Imploy</div></div></div><p class="pc-desc">Two-sided recruitment platform — professionals build CVs and profiles, recruiters post jobs and search candidates using advanced multi-dimensional filters.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=watan.imploy_app" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/imploy/id1659274612" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <!-- Digital Office -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--cyan),#38BDF8)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--cyan);font-size:.7rem">DO</span></div><div><div class="pc-cat" style="color:var(--cyan)">Enterprise · Internal HR</div><div class="pc-name">Digital Office</div></div></div><p class="pc-desc">Internal communication and HR request management platform — announcements, approvals, employee directory, and daily operations in one workspace.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=watan.digital.office.watan_digital_office" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/watan-digital-office/id6449026931" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <!-- Mwardi -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--cyan),var(--blue))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--cyan)">M</span></div><div><div class="pc-cat" style="color:var(--cyan)">HR · Attendance</div><div class="pc-name">Mwardi</div></div></div><p class="pc-desc">Smart HR attendance system — geolocation check-in, leave requests, photo reports, and meeting management for employees and managers.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.mwardi.app" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/mwardi/id6444159801" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <!-- Real Come -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,#7C3AED,var(--cyan))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:#A78BFA;font-size:.7rem">RC</span></div><div><div class="pc-cat" style="color:#A78BFA">Attendance</div><div class="pc-name">Real Come</div></div></div><p class="pc-desc">Precision attendance tracking — geolocation check-in, business card scanning, per-employee reports, leave management, and permissions in one place.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.arabbadia.attendance_app" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/real-come/id1599098078" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <!-- JTC -->
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--gold),var(--green))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--gold);font-size:.75rem">JTC</span></div><div><div class="pc-cat" style="color:var(--gold)">Training · Corporate</div><div class="pc-name">JTC</div></div></div><p class="pc-desc">Corporate training and development platform — structured learning paths, progress tracking, and certification management for professional development programs.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.classera.leadxera.jtc&hl=ar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/jtc/id6478453619" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

      </div>
    </div>

    <!-- ── PROPTECH ── -->
    <div class="cat-section r0" id="prop-sec">
      <div class="cat-section-head">🏠 &nbsp;PropTech</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--green),#0EA472)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--green);font-size:.7rem">TK</span></div><div><div class="pc-cat" style="color:var(--green)">PropTech</div><div class="pc-name">TurnKii</div></div></div><p class="pc-desc">Unified property platform for owners, tenants, and service providers — financing options, project management tools, and payment solutions in one seamless ecosystem.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.turnkii.turnkiiapp" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/turnkii-app/id6742509535" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>
      </div>
    </div>

    <!-- ── E-COMMERCE ── -->
    <div class="cat-section r0" id="ec-sec">
      <div class="cat-section-head">🛒 &nbsp;E-Commerce &amp; Marketplace</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--orange),#FB923C)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--orange)">T</span></div><div><div class="pc-cat" style="color:var(--orange)">E-Commerce</div><div class="pc-name">Tshtri تشتري</div></div></div><p class="pc-desc">Online marketplace for buying and selling — instantly upload, list, and sell anything. Real-time listings with in-app messaging and secure transactions.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.tshtri.tshtri" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/tshtri/id1602869931" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--orange),var(--amber))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--orange)">Ma</span></div><div><div class="pc-cat" style="color:var(--orange)">E-Commerce</div><div class="pc-name">Maojod</div></div></div><p class="pc-desc">Multi-category marketplace with products from top brands — electronics, fashion, health, beauty, groceries, and more. Your go-to shopping destination.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.maojod.maojod_app" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a></div></div></div>
      </div>
    </div>

    <!-- ── RIDE & FOOD ── -->
    <div class="cat-section r0" id="ride-sec">
      <div class="cat-section-head">🚖 &nbsp;Ride Hailing &amp; Food Delivery</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--amber),#FCD34D)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--amber);font-size:.7rem">GT</span></div><div><div class="pc-cat" style="color:var(--amber)">Ride Hailing</div><div class="pc-name">Go Taxi</div></div></div><p class="pc-desc">On-demand ride booking with real-time driver tracking, seamless payment integration, and a state-machine powered ride lifecycle — reliable wherever you go.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.gotaxi.user" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/go-taxi/id1287483414" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc" id="food-sec"><div class="pc-bar" style="background:linear-gradient(90deg,var(--rose),#FB7185)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--rose);font-size:.7rem">GL</span></div><div><div class="pc-cat" style="color:var(--rose)">Food Delivery</div><div class="pc-name">Go Talabat</div></div></div><p class="pc-desc">Restaurant food ordering — browse menus, add to cart, and track your order from preparation through delivery in real time.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.app.go_talabat" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/go-talabat/id1587119217" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--rose),var(--orange))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--orange)">Al</span></div><div><div class="pc-cat" style="color:var(--orange)">Food & Restaurants</div><div class="pc-name">Alyassirah</div></div></div><p class="pc-desc">Al-Yassirah restaurant ordering app — Turkish cuisine, Ottoman grills, kofta, and kebab. Browse the menu and order with ease.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=alyassirah.company.com" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/alyassirah/id1512178854" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>
      </div>
    </div>

    <!-- ── FINTECH ── -->
    <div class="cat-section r0" id="fin-sec">
      <div class="cat-section-head">💡 &nbsp;FinTech &amp; Investment</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,#7C3AED,#A855F7)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:#A78BFA">Af</span></div><div><div class="pc-cat" style="color:#A78BFA">Investment</div><div class="pc-name">Afkar</div></div></div><p class="pc-desc">Investment platform connecting entrepreneurs with project ideas to potential investors — pitch your idea, discover funding opportunities, and communicate securely.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.afkar" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/eg/app/afkar/id1525581075" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--green),#34D399)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--green);font-size:.7rem">EF</span></div><div><div class="pc-cat" style="color:var(--green)">FinTech · Invoicing · KSA</div><div class="pc-name">E Fatora Tec</div></div></div><p class="pc-desc">Secure cloud-based electronic invoicing system authorized by Saudi Arabia's Zakat, Tax and Customs Authority — generate, manage, and share e-invoices instantly.</p><div class="pc-foot"><a class="sb sb-web" href="http://www.fatora-tec.com/" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>Visit Website</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--green),var(--cyan))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--green);font-size:.7rem">IS</span></div><div><div class="pc-cat" style="color:var(--green)">InsurTech · Consulting</div><div class="pc-name">InSure</div></div></div><p class="pc-desc">On-demand consulting platform — request expert advice across multiple professional disciplines simultaneously, with a flexible multi-offer system.</p><div class="pc-foot"><a class="sb sb-ios" href="https://apps.apple.com/eg/app/insure/id1553904022" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>
      </div>
    </div>

    <!-- ── HOME SERVICES & AUTOMOTIVE ── -->
    <div class="cat-section r0" id="home-sec">
      <div class="cat-section-head">🔧 &nbsp;Home Services &amp; Automotive</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--orange),#FB923C)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--orange);font-size:.7rem">MP</span></div><div><div class="pc-cat" style="color:var(--orange)">Home Services</div><div class="pc-name">Main Pro</div></div></div><p class="pc-desc">All-in-one maintenance marketplace — car, home, and electronics repair services. Find verified providers, compare quotes, and track your technician in real time.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.Musllaha" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/main-pro/id1582292480" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,#FB923C,var(--amber))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:#FB923C;font-size:.65rem">MP+</span></div><div><div class="pc-cat" style="color:#FB923C">Home Services · B2B</div><div class="pc-name">Main Pro Partner</div></div></div><p class="pc-desc">Provider portal for the Main Pro ecosystem — join as a maintenance professional, manage service requests, and grow your client base across Saudi Arabia.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.musllah.musullahservice" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/main-pro-partner/id1576702076" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--rose),#FB7185)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--rose)">W</span></div><div><div class="pc-cat" style="color:var(--rose)">Automotive</div><div class="pc-name">Warshati</div></div></div><p class="pc-desc">Car maintenance marketplace — get instant repair cost estimates from authorized workshops with detailed, transparent pricing for any type of damage.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=app.warshati" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/warshati-app/id1610405764" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>
      </div>
    </div>

    <!-- ── EDUCATION ── -->
    <div class="cat-section r0">
      <div class="cat-section-head">📚 &nbsp;Education</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,#818CF8,#A78BFA)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:#818CF8">G</span></div><div><div class="pc-cat" style="color:#818CF8">Education</div><div class="pc-name">Guidlle</div></div></div><p class="pc-desc">Educational resource platform offering structured content from primary school through career entry — learning pathways for every stage of academic and professional growth.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.daleeldev.guidlle" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a></div></div></div>
      </div>
    </div>

    <!-- ── SOCIAL & LIFESTYLE ── -->
    <div class="cat-section r0" id="social-sec">
      <div class="cat-section-head">⭐ &nbsp;Social, Lifestyle &amp; Creator</div>
      <div class="proj-grid">
        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--rose),#F472B6)"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--rose);font-size:.7rem">iF</span></div><div><div class="pc-cat" style="color:var(--rose)">Social · Creator</div><div class="pc-name">I Famous</div></div></div><p class="pc-desc">Celebrity interaction and content creation platform — connect with public figures directly, build your following, and provide services to your audience.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=com.Badia.Mr.Mashhur" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a><a class="sb sb-ios" href="https://apps.apple.com/us/app/ifamous/id1644139054" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.8-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>App Store</a></div></div></div>

        <div class="pc"><div class="pc-bar" style="background:linear-gradient(90deg,var(--amber),var(--rose))"></div><div class="pc-body"><div class="pc-meta"><div class="pc-icon"><span style="font-family:var(--fm);font-weight:700;color:var(--amber);font-size:.7rem">TM</span></div><div><div class="pc-cat" style="color:var(--amber)">Lifestyle · Loyalty · KSA</div><div class="pc-name">Altamayuz</div></div></div><p class="pc-desc">Membership and loyalty card platform providing daily-need services and exclusive discounts — designed in alignment with the Saudi Vision 2030 initiative.</p><div class="pc-foot"><a class="sb sb-play" href="https://play.google.com/store/apps/details?id=tamayouzapp.tamayouz" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M3 20.5v-17l17.5 8.5L3 20.5z"/></svg>Google Play</a></div></div></div>
      </div>
    </div>

  </div><!-- /w -->
</section>

<!-- ════════════════════════ FOOTER ════════════════════════ -->
<footer>
  <div class="footer-name">Ehab Ragab</div>
  <div class="footer-sub">Senior Flutter Developer · Mobile Team Lead · CTO · Cairo, Egypt</div>
  <div class="footer-links">
    <a class="footer-link" href="mailto:ehabragab96@gmail.com">ehabragab96@gmail.com</a>
    <a class="footer-link" href="https://www.linkedin.com/in/EhabRagab99" target="_blank" rel="noopener">LinkedIn</a>
    <a class="footer-link" href="https://github.com/EhabRagab99/MyPublishedApps/blob/main/projects.md" target="_blank" rel="noopener">GitHub</a>
    <a class="footer-link" href="tel:+201113662310">+20 111 366 2310</a>
  </div>
</footer>

<script>
/* ── REVEAL ON SCROLL ── */
const io = new IntersectionObserver(
  es => es.forEach(e => { if(e.isIntersecting) e.target.classList.add('in') }),
  { threshold:0.07 }
);
document.querySelectorAll('.r0').forEach(el => io.observe(el));

/* ── ACTIVE NAV HIGHLIGHT ── */
const sections = document.querySelectorAll('section[id]');
const navLinks = document.querySelectorAll('.nav-link');
window.addEventListener('scroll', () => {
  let cur = '';
  sections.forEach(s => { if(window.scrollY >= s.offsetTop - 80) cur = s.id; });
  navLinks.forEach(l => {
    l.style.color = l.getAttribute('href') === '#'+cur ? 'var(--t1)' : '';
  });
}, {passive:true});
</script>
</body>
</html>
