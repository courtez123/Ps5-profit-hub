# Ps5-profit-hub
PS5 Profit Hub — All-in-one toolkit for UK gamers to earn real money &amp; PSN credit from their console. 8 proven methods, tournament listings, UK deals tracker &amp; scam safety guide. Works on PS5, phone &amp; PC — 100% free, no installs needed! 🎮💰
# 🎮 PS5 Profit Hub
### All-in-one toolkit for UK gamers — earn real money & PSN credit from your console!

---

## 📌 What Is It?
A **free, standalone web app** packed with every legitimate way to earn cash, PSN credit & rewards from your PS5 — all in one place. No fluff, no scams, just real methods for UK players. 🇬🇧

---

## ✨ Features
- 💰 **8 Money Methods** — sell games, tournaments, streaming, coaching & more
- 🏆 **UK Tournament Finder** — Fortnite, FIFA & CoD events with direct links
- 📉 **Gaming Deals Tracker** — PSN discounts, trade-in values, sale calendar
- 🛡️ **Safety Centre** — scam warnings + 2FA account security guide
- 📊 **Progress Checklist** — auto-saves your goals as you go
- 📱 **Works Everywhere** — PS5 browser, phone, laptop, tablet
- 🎨 **Dark PlayStation Theme** — looks clean & professional
- 💾 **No Installs • No Sign-ups • 100% Free Forever** 🚀

---

## 🚀 How to Use
1. **Download** index.html
2. **Open it** in any web browser
3. **That's it!** — no setup, no accounts, no fees

---

## ⚠️ Important
- All methods are **UK-focused** & fully legitimate
- **Never** share your PSN login — stay safe!
- This is a **free community project** — no hidden costs

---
courtez123.github.io
### 🎮 Start earning from your PS5 today!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PS5 Profit Hub | Make Money Gaming 🎮</title>
    <style>
        *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',Roboto,sans-serif}
        :root{--ps-blue:#0066CC;--ps-dark:#0D1117;--ps-card:#161B22;--neon:#00D9FF;--gold:#FFD700;--success:#00C851;--danger:#FF4444;--text:#E6EDF3}
        body{background:var(--ps-dark);color:var(--text);min-height:100vh;padding-bottom:80px}
        header{background:linear-gradient(135deg,var(--ps-blue),#004C99);padding:20px;text-align:center;box-shadow:0 4px 20px rgba(0,102,204,.4);position:sticky;top:0;z-index:100}
        header h1{font-size:28px;font-weight:900;letter-spacing:1px}
        header p{opacity:.8;font-size:14px;margin-top:5px}
        .tabs{display:flex;background:var(--ps-card);position:sticky;top:85px;z-index:99;overflow-x:auto;scrollbar-width:none}
        .tabs::-webkit-scrollbar{display:none}
        .tab{flex:1;min-width:90px;padding:14px 10px;text-align:center;font-size:13px;font-weight:600;cursor:pointer;border-bottom:3px solid transparent;transition:all .2s}
        .tab.active{border-bottom-color:var(--neon);color:var(--neon);background:rgba(0,217,255,.05)}
        .tab:hover{background:rgba(255,255,255,.05)}
        .content{padding:15px;max-width:500px;margin:0 auto}
        .tab-page{display:none;animation:fadeIn .3s ease}
        .tab-page.active{display:block}
        @keyframes fadeIn{from{opacity:0;transform:translateY(5px)}to{opacity:1;transform:translateY(0)}}
        .card{background:var(--ps-card);border-radius:12px;padding:16px;margin-bottom:14px;border:1px solid rgba(255,255,255,.08);transition:transform .2s,border-color .2s}
        .card:hover{transform:translateY(-2px);border-color:var(--ps-blue)}
        .card h3{font-size:17px;margin-bottom:8px;display:flex;align-items:center;gap:8px}
        .tag{display:inline-block;padding:3px 10px;border-radius:20px;font-size:11px;font-weight:700;margin-right:6px;margin-bottom:10px}
        .tag.fast{background:rgba(0,200,81,.15);color:#00FF6A}
        .tag.medium{background:rgba(255,170,0,.15);color:#FFAA00}
        .tag.long{background:rgba(170,0,255,.15);color:#CC66FF}
        .tag.free{background:rgba(0,217,255,.15);color:var(--neon)}
        .earnings{color:var(--gold);font-weight:700;font-size:15px;margin:8px 0}
        .card p{font-size:14px;line-height:1.6;opacity:.85;margin-bottom:10px}
        .btn{display:inline-block;background:linear-gradient(135deg,var(--ps-blue),#0080FF);color:white;padding:10px 16px;border-radius:8px;text-decoration:none;font-weight:600;font-size:14px;border:none;cursor:pointer;transition:all .2s}
        .btn:hover{transform:scale(1.03);box-shadow:0 4px 15px rgba(0,102,204,.4)}
        .stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:20px}
        .stat-card{background:var(--ps-card);border-radius:12px;padding:15px;text-align:center;border:1px solid rgba(255,255,255,.08)}
        .stat-value{font-size:24px;font-weight:900;color:var(--neon)}
        .stat-label{font-size:12px;opacity:.6;margin-top:4px}
        .warning-box{background:rgba(255,68,68,.1);border-left:4px solid var(--danger);padding:14px;border-radius:8px;margin:15px 0}
        .warning-box h4{color:var(--danger);margin-bottom:5px}
        .check-item{display:flex;align-items:flex-start;gap:10px;padding:8px 0;border-bottom:1px solid rgba(255,255,255,.05)}
        .check-item input{width:18px;height:18px;accent-color:var(--success);margin-top:2px}
        .bottom-nav{position:fixed;bottom:0;left:0;right:0;background:var(--ps-card);display:flex;justify-content:space-around;padding:10px 0;border-top:1px solid rgba(255,255,255,.1);z-index:200}
        .nav-item{text-align:center;font-size:11px;opacity:.6;cursor:pointer}
        .nav-item.active{opacity:1;color:var(--neon)}
        .nav-icon{font-size:20px;margin-bottom:3px}
        .progress-bar{height:8px;background:rgba(255,255,255,.1);border-radius:10px;overflow:hidden;margin-top:8px}
        .progress-fill{height:100%;background:linear-gradient(90deg,var(--ps-blue),var(--neon));border-radius:10px;width:0%;transition:width .5s ease}
        ul{margin-left:20px;margin-bottom:10px;line-height:1.8}
    </style>
</head>
<body>
<header><h1>🎮 PS5 PROFIT HUB</h1><p>Make money playing — UK • 2026</p></header>
<nav class="tabs"><div class="tab active" data-page="home">🏠 Home</div><div class="tab" data-page="methods">💰 Methods</div><div class="tab" data-page="tourneys">🏆 Tourneys</div><div class="tab" data-page="deals">📉 Deals</div><div class="tab" data-page="safe">🛡️ Safety</div></nav>
<main class="content">
<section class="tab-page active" id="home">
    <div class="stats-grid"><div class="stat-card"><div class="stat-value">8</div><div class="stat-label">Money Methods</div></div><div class="stat-card"><div class="stat-value">£0-500+</div><div class="stat-label">Monthly Potential</div></div></div>
    <div class="card"><h3>👋 Welcome, Gamer!</h3><p>Everything you need to earn real money & PSN credit from your PS5 — all in one place. No scams, just real methods.</p><button class="btn" onclick="switchTab('methods')">Start Earning →</button></div>
    <div class="card"><h3>✅ Quick Start Checklist</h3><div class="check-item"><input type="checkbox" id="c1"><label for="c1">Join PlayStation Stars (free PSN credit)</label></div><div class="check-item"><input type="checkbox" id="c2"><label for="c2">List 1 finished game on eBay/CeX</label></div><div class="check-item"><input type="checkbox" id="c3"><label for="c3">Sign up to 1 tournament platform</label></div><div class="check-item"><input type="checkbox" id="c4"><label for="c4">Turn on PS5 broadcast to Twitch/YouTube</label></div></div>
    <div class="card"><h3>📊 Your Progress</h3><p id="progress-text">0/4 completed</p><div class="progress-bar"><div class="progress-fill" id="progress-bar"></div></div></div>
</section>
<section class="tab-page" id="methods">
    <h2 style="margin:10px 0 20px;font-size:22px">💰 Money Methods</h2>
    <div class="card"><span class="tag fast">⚡ FAST</span><span class="tag free">🆓 FREE</span><h3>1. Sell Physical Games</h3><div class="earnings">💷 £5–£30 per game</div><p>Beat a physical game? Sell it on <strong>CeX, eBay, or Facebook Marketplace</strong>. Fastest real cash — money in 24–48hrs.</p><strong>Where to sell:</strong> CeX (instant cash), eBay (highest price), FB Marketplace (no fees, local pickup)</div>
    <div class="card"><span class="tag fast">⚡ FAST</span><span class="tag free">🆓 FREE</span><h3>2. PlayStation Stars</h3><div class="earnings">💷 Free PSN Credit (£5+ monthly)</div><p>Earn points by playing games, earning trophies & completing campaigns. <strong>1,250 pts = £5 PSN credit</strong>. Completely free!</p><strong>How:</strong> PS5 → PlayStation Stars app → Join Free → Complete campaigns</div>
    <div class="card"><span class="tag medium">⏱️ MEDIUM</span><h3>3. Tournaments & 1v1s</h3><div class="earnings">💷 £10–£500+ per win</div><p>Fortnite, FIFA, CoD cash tournaments. Skill = profit.</p><strong>Top platforms (UK):</strong> GamerSaloon, Battlefy, ESports.gg, Twitch Rivals<br><br><em>⚠️ Some need entry fees — only play what you can lose!</em></div>
    <div class="card"><span class="tag medium">⏱️ MEDIUM</span><h3>4. Coaching & Boosting</h3><div class="earnings">💷 £10–£30 per hour</div><p>Good at the game? Offer coaching on <strong>Fiverr, Upwork, or socials</strong>. Safe & legitimate.</p><em>⚠️ Account boosting = ban risk. Coaching = safe.</em></div>
    <div class="card"><span class="tag long">🚀 LONG</span><h3>5. Stream & Content Creation</h3><div class="earnings">💷 £0–£1,000+ monthly</div><p>PS5 has built-in streaming to <strong>Twitch & YouTube</strong> — ONE BUTTON start. Monetise via subs, ads, donations, affiliates.</p><strong>Tip:</strong> Clip your best plays → TikTok/YouTube Shorts → fastest growth!</div>
    <div class="card"><span class="tag long">🚀 LONG</span><h3>6. Affiliate Marketing</h3><div class="earnings">💷 £50–£500+ monthly (passive)</div><p>Share Amazon, gaming gear, PSN card links. Earn % when people buy through you.</p><strong>Programs:</strong> Amazon Associates, UK affiliate programs</div>
    <div class="card"><span class="tag medium">⏱️ MEDIUM</span><h3>7. Game Testing & Beta Programs</h3><div class="earnings">💷 Free games + sometimes paid</div><p>Sign up for PlayStation Insider & official beta programs. Early access + free rewards.</p></div>
    <div class="card"><span class="tag long">🚀 LONG</span><h3>8. Rent Your PS5</h3><div class="earnings">💷 £20–£50 per day</div><p>List on <strong>Fat Llama (UK)</strong> — earn when you're not gaming.</p><em>⚠️ Risk: damage/theft. Always factory reset & log out first!</em></div>
</section>
<section class="tab-page" id="tourneys">
    <h2 style="margin:10px 0 20px;font-size:22px">🏆 UK Tournaments</h2>
    <div class="card"><h3>🎯 Fortnite Tourneys</h3><p><strong>Best platforms for PS5 players:</strong></p><ul><li><strong>Battlefy</strong> — Free & paid events, daily</li><li><strong>GamerSaloon</strong> — 1v1 & tourneys, real cash prizes</li><li><strong>Epic Games Official</strong> — In-game cash cups (free entry!)</li><li><strong>ESL</strong> — Pro level, big prizes</li></ul><a href="https://battlefy.com" target="_blank" class="btn">Open Battlefy</a></div>
    <div class="card"><h3>⚽ FIFA / EA FC</h3><p>Official EA Sports tournaments + GamerSaloon 1v1s. Highest consistent prize pools.</p><div class="earnings">Top prize: £500–£10,000+</div></div>
    <div class="card"><h3>🎮 Call of Duty / Warzone</h3><p>CoD League qualifiers + community tourneys. Warzone 1v1s very popular.</p></div>
    <div class="warning-box"><h4>⚠️ BEFORE JOINING</h4><p>• Check region = EU/London for lowest ping<br>• Never pay "entry fee" via PayPal Friends & Family<br>• Use official platforms only — no random Discord links!</p></div>
</section>
<section class="tab-page" id="deals">
    <h2 style="margin:10px 0 20px;font-size:22px">📉 UK Gaming Deals</h2>
    <div class="card"><h3>💰 PSN Credit Deals</h3><p>Best places to buy cheaper PSN cards (UK):</p><ul><li><strong>CDKeys</strong> — often 5–15% off</li><li><strong>ShopTo</strong> — reliable UK retailer</li><li><strong>Amazon UK</strong> — occasional discount</li></ul></div>
    <div class="card"><h3>🎮 Trade-In Values</h3><p>Check <strong>CeX</strong> & <strong>MusicMagpie</strong> for best prices before selling.</p><strong>Tip:</strong> Physical games hold value better than digital!</div>
    <div class="card"><h3>📅 PS Store Sales Calendar</h3><p>Major sales to watch:</p><ul><li>⚡ January — Winter Sale</li><li>🎮 March — Spring Sale</li><li>🎂 June — Days of Play</li><li>🔥 July — Summer Sale</li><li>🎄 December — Christmas/Black Friday</li></ul></div>
</section>
<section class="tab-page" id="safe">
    <h2 style="margin:10px 0 20px;font-size:22px">🛡️ Stay Safe Online</h2>
    <div class="warning-box"><h4>🚫 THE BIG 3 SCAMS — AVOID THESE!</h4><p>• <strong>"Free PSN Codes" generators</strong> = 100% SCAM<br>• <strong>Account boosting services</strong> = BAN risk<br>• <strong>"Send me your PSN login"</strong> = HACK attempt</p></div>
    <div class="card"><h3>✅ Safe Rules</h3><ul><li>Never share your PSN password — ever</li><li>Enable 2FA on your account (CRITICAL!)</li><li>Only use official platforms for tournaments</li><li>If it sounds too good to be true — it is</li><li>Never click links from strangers in DMs</li><li>Use a separate email for gaming accounts</li></ul></div>
    <div class="card"><h3>🔐 Enable 2FA on PS5</h3><p>Settings → Users & Accounts → Security → 2-Step Verification → Turn ON</p><strong>Do this today — it protects ALL your purchases!</strong></div>
    <div class="card"><h3>📞 Report a Scam</h3><p>UK gamers: Report scams to <strong>ActionFraud</strong> (0300 123 2040) or via PlayStation Support.</p></div>
</section>
</main>
<nav class="bottom-nav"><div class="nav-item active" data-page="home"><div class="nav-icon">🏠</div>Home</div><div class="nav-item" data-page="methods"><div class="nav-icon">💰</div>Methods</div><div class="nav-item" data-page="tourneys"><div class="nav-icon">🏆</div>Events</div><div class="nav-item" data-page="deals"><div class="nav-icon">📉</div>Deals</div><div class="nav-item" data-page="safe"><div class="nav-icon">🛡️</div>Safe</div></nav>
<script>
const allTabs = document.querySelectorAll('.tab'), allNavItems = document.querySelectorAll('.nav-item'), allPages = document.querySelectorAll('.tab-page');
function switchTab(pageName){allPages.forEach(p=>p.classList.remove('active'));allTabs.forEach(t=>t.classList.remove('active'));allNavItems.forEach(n=>n.classList.remove('active'));document.getElementById(pageName).classList.add('active');allTabs.forEach(t=>t.dataset.page===pageName&&t.classList.add('active'));allNavItems.forEach(n=>n.dataset.page===pageName&&n.classList.add('active'));window.scrollTo(0,0)}
allTabs.forEach(t=>t.addEventListener('click',()=>switchTab(t.dataset.page)));
allNavItems.forEach(n=>n.addEventListener('click',()=>switchTab(n.dataset.page)));
const checkboxes = document.querySelectorAll('.check-item input'), progressBar = document.getElementById('progress-bar'), progressText = document.getElementById('progress-text');
function updateProgress(){const total=checkboxes.length,checked=document.querySelectorAll('.check-item input:checked').length,percent=(checked/total)*100;progressBar.style.width=percent+'%';progressText.textContent=`${checked}/${total} completed`;localStorage.setItem('profitHubProgress',checked)}
function loadProgress(){const saved=localStorage.getItem('profitHubProgress');if(saved){const n=parseInt(saved);checkboxes.forEach((b,i)=>b.checked=i<n);updateProgress()}}
checkboxes.forEach(b=>b.addEventListener('change',updateProgress));
loadProgress();
</script>
</body>
</html>