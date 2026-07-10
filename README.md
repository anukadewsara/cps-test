<html lang="en">
<head>
<title>Clean CPS Test - Free Click Speed Test</title>
<meta name="description" content="Test your clicking speed with Clean CPS Test. A fast, accurate, and responsive Clicks Per Second tester.">
<meta name="keywords" content="CPS Test, Click Speed Test, Click Test, Clicks Per Second">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>BlecnoTade's CPS Test — 1440×900</title>
<style>
  /* ---------- Fixed app size ---------- */
  :root{
    --app-w:1440px;
    --app-h:900px;
    --ui-radius:14px;
    --shadow:0 28px 90px rgba(0,0,0,0.45);
    --ripple: rgba(0,212,255,0.12);

    /* default theme variables (Neon Night) */
    --accent: #4f46e5;
    --accent-2: #00d4ff;
    --muted: #9fbfe6;
    --text: #e6f6ff;
    --panel: linear-gradient(180deg,#071026,#071a2a);
    --glass: rgba(255,255,255,0.04);
    --banner-border: rgba(255,255,255,0.04);
    --banner-bg: linear-gradient(180deg, rgba(6,12,20,0.96), rgba(8,16,28,0.96));
    --banner-text: var(--text);

    /* menu background and text forced to be clear */
    --menu-bg: #ffffff;
    --menu-text: #000000;
    --menu-border: rgba(0,0,0,0.08);
  }

  /* ---------- Theme presets (applied via body class) ---------- */
  .theme-a { --panel: linear-gradient(180deg,#071026,#071a2a); --accent:#4f46e5; --accent-2:#00d4ff; --muted:#9fbfe6; --text:#e6f6ff; --banner-bg: linear-gradient(180deg, rgba(6,12,20,0.96), rgba(8,16,28,0.96)); --banner-text: #e6f6ff; --ripple: rgba(0,212,255,0.12); }
  .theme-b { --panel: linear-gradient(180deg,#07121a,#082826); --accent:#00c853; --accent-2:#00e5ff; --muted:#bfead0; --text:#eafff4; --banner-bg: linear-gradient(180deg, rgba(2,18,14,0.96), rgba(4,28,24,0.96)); --banner-text:#eafff4; --ripple: rgba(0,255,170,0.14); }
  .theme-c { --panel: linear-gradient(180deg,#050505,#0b0b0b); --accent:#00ff9e; --accent-2:#00d4ff; --muted:#9aa4b2; --text:#eafaf1; --banner-bg: linear-gradient(180deg, rgba(2,2,2,0.96), rgba(8,8,8,0.96)); --banner-text:#eafaf1; --ripple: rgba(0,255,150,0.12); }
  .theme-d { --panel: linear-gradient(180deg,#fff6f4,#fff0ee); --accent:#ff7a7a; --accent-2:#ffb86b; --muted:#6b4f4f; --text:#2b1f1f; --banner-bg: linear-gradient(180deg,#fff6f4,#fff0ee); --banner-text:#2b1f1f; --ripple: rgba(255,140,120,0.12); }
  .theme-e { --panel: linear-gradient(180deg,#02121a,#052b2b); --accent:#7c5cff; --accent-2:#00ffd5; --muted:#bfeef0; --text:#dffcf7; --banner-bg: linear-gradient(90deg, rgba(6,12,20,0.96), rgba(4,22,28,0.96)); --banner-text:#dffcf7; --ripple: rgba(0,255,210,0.12); }

  /* ---------- Base layout ---------- */
  html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}
  body{display:flex;align-items:center;justify-content:center;padding:18px;background:var(--panel);color:var(--text)}
  body.theme-a, body.theme-b, body.theme-c, body.theme-d, body.theme-e { /* variables applied via class */ }

  /* ---------- App container (fixed size) ---------- */
  .app {
    width: var(--app-w);
    height: var(--app-h);
    border-radius: var(--ui-radius);
    background: var(--panel);
    box-shadow: var(--shadow);
    overflow: hidden;
    position: relative;
    display:flex;
    flex-direction:column;
  }

  /* ---------- Very noticeable close button (very top-right corner) ---------- */
  .close-app{
    position:fixed;
    right:8px; top:6px;
    width:64px;height:64px;border-radius:14px;border:0;
    background: linear-gradient(135deg,#ff4d4f,#ff7a7a);
    color:white;font-weight:900;font-size:22px;cursor:pointer;z-index:99999;
    box-shadow:0 18px 60px rgba(255,80,80,0.28);
    display:flex;align-items:center;justify-content:center;
  }
  .close-app:active{transform:scale(.98)}
  .close-app[aria-hidden="true"]{display:none}

  header{display:flex;align-items:center;justify-content:space-between;padding:18px 24px;border-bottom:1px solid rgba(255,255,255,0.03);z-index:10}
  .brand{display:flex;gap:12px;align-items:center}
  .logo{
    width:56px;height:56px;border-radius:12px;display:flex;align-items:center;justify-content:center;
    font-size:32px;line-height:1;background:linear-gradient(135deg,var(--accent),var(--accent-2));color:white;user-select:none;
  }
  h1{font-size:20px;margin:0}
  p.lead{margin:0;color:var(--muted);font-size:13px}

  /* modern select / inputs (clear in every theme) */
  .modern-select, .modern-input {
    -webkit-appearance:none; -moz-appearance:none; appearance:none;
    background: var(--menu-bg);
    border: 1px solid var(--menu-border);
    color: var(--menu-text);
    padding:10px 12px;
    border-radius:10px;
    font-weight:700;
    min-width:140px;
    box-shadow: inset 0 -6px 18px rgba(0,0,0,0.03);
  }
  .modern-select:focus, .modern-input:focus { outline: 2px solid rgba(0,0,0,0.06); outline-offset:2px; }

  .controls{display:flex;gap:12px;align-items:center}
  .controls .card{padding:8px 10px;border-radius:10px;background:transparent;border:1px solid rgba(255,255,255,0.03);display:flex;gap:8px;align-items:center}

  main{display:flex;gap:18px;padding:18px;align-items:stretch;flex:1}
  .left{flex:1;display:flex;flex-direction:column;gap:12px}
  .right{width:360px;display:flex;flex-direction:column;gap:12px}

  /* big target - default size set to Large (260px) */
  .big-target{flex:1;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;cursor:pointer}
  .target-btn{width:260px;height:260px;border-radius:999px;background:linear-gradient(180deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:white;font-weight:900;font-size:28px;box-shadow:0 18px 50px rgba(0,0,0,0.12);transition:transform .06s ease}
  .target-btn.small{width:200px;height:200px;font-size:22px}
  .target-btn:active{transform:scale(.96)}

  /* overlay banner that covers the big button and blocks clicks */
  .overlay-banner{
    position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);min-width:320px;max-width:86%;border-radius:14px;padding:18px 20px;display:none;z-index:80;
    box-shadow:0 24px 80px rgba(0,0,0,0.45);border:1px solid var(--banner-border);background:var(--banner-bg);color:var(--banner-text);text-align:center;pointer-events:auto;
    -webkit-backdrop-filter: blur(6px);backdrop-filter: blur(6px);
  }
  .overlay-banner[aria-hidden="false"]{display:block}
  .overlay-banner .close-banner{position:absolute;right:10px;top:10px;width:36px;height:36px;border-radius:10px;border:0;background:transparent;color:var(--muted);cursor:pointer;font-weight:800}
  .overlay-banner .emoji{font-size:40px;margin-bottom:8px}
  .overlay-banner .title{font-weight:900;font-size:20px;margin:0}
  .overlay-banner .desc{color:var(--muted);font-size:14px;margin-top:8px}

  /* stats and controls */
  .stats{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
  .stat{flex:1;min-width:140px;padding:12px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);text-align:center}
  .stat .label{font-size:12px;color:var(--muted)}
  .stat .num{font-weight:900;font-size:18px;margin-top:6px}

  .actions{display:flex;gap:10px;margin-top:12px}
  button.btn{padding:12px 14px;border-radius:12px;border:0;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;font-weight:800;cursor:pointer}
  /* make Stop and Reset more noticeable */
  button.stop-btn{padding:12px 16px;border-radius:12px;border:0;background:linear-gradient(90deg,#ff6b6b,#ff3b3b);color:white;font-weight:900;cursor:pointer;box-shadow:0 12px 40px rgba(255,80,80,0.18)}
  button.reset-btn{padding:12px 16px;border-radius:12px;border:0;background:linear-gradient(90deg,#ffb86b,#ff7a7a);color:white;font-weight:900;cursor:pointer;box-shadow:0 12px 40px rgba(255,140,80,0.12)}

  .progress-wrap{height:10px;background:linear-gradient(180deg,rgba(0,0,0,0.02),transparent);border-radius:999px;overflow:hidden;margin-top:12px}
  .progress{height:100%;background:linear-gradient(90deg,var(--accent),var(--accent-2));width:0%;transition:width .12s linear}

  .card{background:transparent;padding:12px;border-radius:10px}
  .history{max-height:420px;overflow:auto;margin-top:8px}
  .history-item{display:flex;justify-content:space-between;padding:8px;border-radius:8px;margin-bottom:8px;background:linear-gradient(90deg,rgba(0,0,0,0.02),transparent);font-size:13px}

  /* right panel tabs */
  .tabs{display:flex;gap:6px;border-radius:10px;overflow:hidden}
  .tab{flex:1;padding:8px 10px;text-align:center;cursor:pointer;border:1px solid rgba(255,255,255,0.03);background:transparent;color:var(--muted);border-radius:8px}
  .tab.active{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;font-weight:800}

  /* ripple */
  .ripple{position:absolute;border-radius:999px;transform:translate(-50%,-50%);pointer-events:none;opacity:.9;mix-blend-mode:screen}

  /* target size menu styling */
  .size-select { display:flex; gap:8px; flex-wrap:wrap; align-items:center; }
  .size-select button { padding:8px 10px; border-radius:10px; border:1px solid rgba(0,0,0,0.06); background:var(--menu-bg); color:var(--menu-text); cursor:pointer; font-weight:800; }
  .size-select button.active { background:linear-gradient(90deg,var(--accent),var(--accent-2)); color:white; box-shadow:0 12px 40px rgba(0,0,0,0.12); }

  /* modern clear history button */
  .clear-modern {
    padding:10px 12px;border-radius:10px;border:0;background:linear-gradient(90deg,#7c5cff,#00d4ff);color:white;font-weight:800;cursor:pointer;box-shadow:0 12px 40px rgba(0,0,0,0.12)
  }

  /* responsive fallback */
  @media (max-width:1500px){
    .app{width:calc(100vw - 40px);height:calc(100vh - 40px);border-radius:10px}
  }
  @media (max-width:920px){
    main{flex-direction:column}
    .right{width:100%}
    .overlay-banner{left:50%;top:40%}
  }
</style>
</head>
<body class="theme-a">
  <!-- close button remains; no opening banner/button -->
  <button id="closeApp" class="close-app" title="Close app" aria-hidden="false">✕</button>

  <div class="app" id="app" role="application" aria-label="BlecnoTade CPS Test (1440×900)">
    <header>
      <div class="brand">
        <!-- middle-finger logo -->
        <div class="logo" role="img" aria-label="middle finger logo" title="logo">🖕</div>
        <div>
          <h1>BlecnoTade's CPS Test</h1>
          <p class="lead" id="leadText">Aim, click, improve — 1440×900</p>
        </div>
      </div>

      <!-- header intentionally minimal; all options moved to Settings tab -->
      <div class="controls" aria-hidden="true" style="opacity:0;pointer-events:none"></div>
    </header>

    <main>
      <div class="left">
        <div class="big-target" id="target" tabindex="0" role="button" aria-pressed="false" aria-label="Click target">
          <div class="target-btn" id="targetBtn">Start</div>

          <!-- overlay banner that covers the big button and blocks clicks -->
          <div class="overlay-banner" id="overlayBanner" aria-hidden="true" role="dialog" aria-live="polite">
            <button class="close-banner" id="overlayClose" title="Close">✕</button>
            <div class="emoji" id="overlayEmoji">🐢</div>
            <div class="title" id="overlayTitle">Turtle — 0.00 CPS</div>
            <div class="desc" id="overlayDesc">Take it easy — Turtle pace.</div>
            <div style="margin-top:12px;font-size:13px;color:var(--muted)">Close this banner to continue</div>
          </div>
        </div>

        <div class="stats">
          <div class="stat">
            <div class="label">Time</div>
            <div class="num" id="timeDisplay">0.00s</div>
          </div>
          <div class="stat">
            <div class="label">Clicks (L / R / Total)</div>
            <div class="num" id="clickCount">0 / 0 / 0</div>
          </div>
          <div class="stat">
            <div class="label">CPS (L / R / Total)</div>
            <div class="num" id="cpsDisplay">0.00 / 0.00 / 0.00</div>
          </div>
        </div>

        <div class="actions">
          <button id="startBtn" class="btn">Start</button>
          <button id="stopBtn" class="stop-btn">Stop</button>
          <button id="resetBtn" class="reset-btn">Reset</button>
          <div style="margin-left:auto;color:var(--muted)" id="statusText">Ready</div>
        </div>

        <div class="card" style="margin-top:12px">
          <div style="display:flex;gap:12px;flex-wrap:wrap;align-items:center">
            <div style="flex:1;min-width:140px">
              <label>Duration (s)</label>
              <input id="duration" class="modern-input" type="number" min="1" max="120" value="5">
            </div>

            <div style="flex:1;min-width:140px">
              <label>Target Size</label>
              <div class="size-select" id="sizeSelect">
                <button data-size="140">Big</button>
                <button data-size="200" class="active">Large</button>
                <button data-size="260">Giant</button>
                <button data-size="340">Yuthmi</button>
              </div>
            </div>
          </div>

          <div style="display:flex;gap:8px;align-items:center;margin-top:10px">
            <label class="muted" style="margin:0">Countdown</label>
            <select id="countdown" class="modern-select" style="min-width:80px;padding:8px;border-radius:8px">
              <option value="0" selected>Off</option>
              <option value="3">3s</option>
              <option value="5">5s</option>
            </select>

            <label class="muted" style="margin-left:12px">Sound</label>
            <input id="soundToggle" type="checkbox" checked>

            <label class="muted" style="margin-left:12px">Vibrate</label>
            <input id="vibrateToggle" type="checkbox">
          </div>

          <div class="progress-wrap" style="margin-top:12px">
            <div class="progress" id="progressBar"></div>
          </div>
        </div>
      </div>

      <aside class="right">
        <div class="card">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div style="display:flex;gap:8px;align-items:center">
              <div class="tabs" role="tablist" aria-label="Right panel tabs">
                <div class="tab active" id="tabSettings" role="tab" tabindex="0">Settings</div>
                <div class="tab" id="tabHistory" role="tab" tabindex="0">History</div>
              </div>
            </div>
            <div id="bestText" style="color:var(--muted)">Best CPS: 0.00</div>
          </div>

          <!-- Settings tab contains all options (no header menus) -->
          <div id="settingsPanel" style="margin-top:12px">
            <div style="margin-bottom:10px">
              <label style="display:block;color:var(--muted)">Click Type</label>
              <select id="clickType2" class="modern-select"><option value="left">Left</option><option value="right">Right</option><option value="both">Both</option></select>
            </div>

            <div style="margin-bottom:10px">
              <label style="display:block;color:var(--muted)">Theme</label>
              <select id="themeSelect2" class="modern-select">
                <option value="theme-a">Neon Night</option>
                <option value="theme-b">Forest Glow</option>
                <option value="theme-c">Midnight Black</option>
                <option value="theme-d">Sunset Light</option>
                <option value="theme-e">Aurora</option>
              </select>
            </div>

            <div style="margin-bottom:10px">
              <label style="display:block;color:var(--muted)">Fullscreen on start</label>
              <input id="fullscreenToggle" type="checkbox" checked>
            </div>

            <div style="margin-top:8px;color:var(--muted);font-size:13px">Settings are saved locally. Keyboard: <span class="kbd">Space</span> start/click, <span class="kbd">R</span> reset.</div>
          </div>

          <div id="historyPanel" style="display:none;margin-top:12px">
            <div class="history" id="historyList" aria-live="polite"></div>
            <div style="display:flex;gap:8px;margin-top:8px">
              <button id="clearHistory" class="clear-modern">Clear History</button>
            </div>
          </div>
        </div>
      </aside>
    </main>
  </div>

<script>
/* Final adjustments requested:
   - Removed opening banner/button entirely
   - Default target size set to Large (260px)
   - Removed header click menu (click type moved to Settings)
   - Menu texts forced to black and clear across themes
   - Replaced "giant" with "Youthmi" (button label "Youthmi")
   - Clear History button modernized
   - Countdown default is Off
*/

(() => {
  const body = document.body;
  const app = document.getElementById('app');

  const clickType2 = document.getElementById('clickType2');
  const themeSelect2 = document.getElementById('themeSelect2');
  const fullscreenToggle = document.getElementById('fullscreenToggle');

  const target = document.getElementById('target');
  const targetBtn = document.getElementById('targetBtn');
  const overlayBanner = document.getElementById('overlayBanner');
  const overlayClose = document.getElementById('overlayClose');
  const overlayEmoji = document.getElementById('overlayEmoji');
  const overlayTitle = document.getElementById('overlayTitle');
  const overlayDesc = document.getElementById('overlayDesc');

  const timeDisplay = document.getElementById('timeDisplay');
  const clickCountEl = document.getElementById('clickCount');
  const cpsDisplay = document.getElementById('cpsDisplay');
  const progressBar = document.getElementById('progressBar');
  const statusText = document.getElementById('statusText');
  const bestText = document.getElementById('bestText');
  const historyList = document.getElementById('historyList');

  const startBtn = document.getElementById('startBtn');
  const stopBtn = document.getElementById('stopBtn');
  const resetBtn = document.getElementById('resetBtn');

  const durationEl = document.getElementById('duration');
  const sizeSelect = document.getElementById('sizeSelect');
  const countdownEl = document.getElementById('countdown');
  const soundToggle = document.getElementById('soundToggle');
  const vibrateToggle = document.getElementById('vibrateToggle');

  const tabSettings = document.getElementById('tabSettings');
  const tabHistory = document.getElementById('tabHistory');
  const settingsPanel = document.getElementById('settingsPanel');
  const historyPanel = document.getElementById('historyPanel');

  const clearHistory = document.getElementById('clearHistory');
  const leadText = document.getElementById('leadText');
  const closeApp = document.getElementById('closeApp');

  // State
  let running = false;
  let startTime = 0;
  let raf = null;
  let duration = parseFloat(durationEl.value) || 5;
  let bestCps = 0;
  let history = [];
  let streak = 0;

  let leftClicks = 0, rightClicks = 0, totalClicks = 0;
  let audioCtx = null;

  const themes = ['theme-a','theme-b','theme-c','theme-d','theme-e'];

  // Helpers
  function setTargetSize(px){
    targetBtn.style.width = px + 'px';
    targetBtn.style.height = px + 'px';
  }

  function beep(freq = 880, time = 0.08, vol = 0.06){
    if(!soundToggle.checked) return;
    try {
      if(!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
      const o = audioCtx.createOscillator();
      const g = audioCtx.createGain();
      o.type = 'sine';
      o.frequency.value = freq;
      g.gain.value = vol;
      o.connect(g); g.connect(audioCtx.destination);
      o.start();
      setTimeout(()=> { o.stop(); o.disconnect(); g.disconnect(); }, time*1000);
    } catch(e){}
  }

  function formatTime(t){ return t.toFixed(2) + 's'; }

  function persist(){
    try {
      localStorage.setItem('blec_cps_history_final', JSON.stringify(history));
      localStorage.setItem('blec_cps_best_final', String(bestCps));
      const currentTheme = themes.find(t => document.body.classList.contains(t)) || 'theme-a';
      localStorage.setItem('blec_cps_theme_final', currentTheme);
      localStorage.setItem('blec_cps_click_final', clickType2.value);
      localStorage.setItem('blec_cps_fullscreen_final', String(fullscreenToggle.checked));
      const sizePx = parseInt(getComputedStyle(targetBtn).width,10) || 260;
      localStorage.setItem('blec_cps_size_final', String(sizePx));
      localStorage.setItem('blec_cps_streak_final', String(streak));
    } catch(e){}
  }

  // load persisted
  try {
    const raw = localStorage.getItem('blec_cps_history_final');
    if(raw) history = JSON.parse(raw);
    const best = localStorage.getItem('blec_cps_best_final');
    if(best) bestCps = parseFloat(best) || 0;
    const theme = localStorage.getItem('blec_cps_theme_final');
    if(theme && themes.includes(theme)) {
      body.classList.remove(...themes);
      body.classList.add(theme);
      themeSelect2.value = theme;
    }
    const savedClick = localStorage.getItem('blec_cps_click_final');
    if(savedClick){ clickType2.value = savedClick; }
    const savedFullscreen = localStorage.getItem('blec_cps_fullscreen_final');
    if(savedFullscreen) fullscreenToggle.checked = savedFullscreen === 'true';
    const savedSize = localStorage.getItem('blec_cps_size_final');
    if(savedSize) setTargetSize(parseInt(savedSize,10));
    const savedStreak = localStorage.getItem('blec_cps_streak_final');
    if(savedStreak) streak = parseInt(savedStreak,10) || 0;
  } catch(e){}

  // UI updates
  function updateUI(){
    const now = running ? (performance.now() - startTime)/1000 : 0;
    const displayTime = running ? Math.min(now, duration) : 0;
    timeDisplay.textContent = formatTime(displayTime);
    clickCountEl.textContent = `${leftClicks} / ${rightClicks} / ${totalClicks}`;
    const leftCps = displayTime > 0 ? leftClicks / displayTime : 0;
    const rightCps = displayTime > 0 ? rightClicks / displayTime : 0;
    const totalCps = displayTime > 0 ? totalClicks / displayTime : 0;
    cpsDisplay.textContent = `${leftCps.toFixed(2)} / ${rightCps.toFixed(2)} / ${totalCps.toFixed(2)}`;
    progressBar.style.width = Math.min(100, (displayTime / duration) * 100) + '%';
    statusText.textContent = running ? 'Running' : 'Idle';
    bestText.textContent = 'Best CPS: ' + bestCps.toFixed(2);
    targetBtn.textContent = running ? 'Click' : 'Start';
    leadText.style.color = getComputedStyle(body).getPropertyValue('--muted') || '#9fbfe6';
  }

  function tick(){
    updateUI();
    if(!running) return;
    const now = (performance.now() - startTime)/1000;
    if(now >= duration){
      endTest();
      return;
    }
    raf = requestAnimationFrame(tick);
  }

  function tryEnterFullscreen(){
    if(!fullscreenToggle.checked) return;
    try {
      const el = document.documentElement;
      if(el.requestFullscreen) el.requestFullscreen().catch(()=>{});
      else if(el.webkitRequestFullscreen) el.webkitRequestFullscreen();
    } catch(e){}
  }

  // Countdown logic (blocks clicks during countdown)
  async function startTest(autoFocus = true){
    if(running) return;
    const cd = Math.max(0, parseInt(countdownEl.value || '0', 10));
    if(cd > 0){
      target.style.pointerEvents = 'none';
      for(let i = cd; i > 0; i--){
        targetBtn.textContent = String(i);
        beep(600, 0.06, 0.06);
        await new Promise(r => setTimeout(r, 1000));
      }
      targetBtn.textContent = 'Go';
      beep(900, 0.08, 0.08);
      await new Promise(r => setTimeout(r, 220));
      target.style.pointerEvents = 'auto';
    }

    duration = Math.max(1, parseFloat(durationEl.value) || 5);
    leftClicks = rightClicks = totalClicks = 0;
    running = true;
    startTime = performance.now();
    target.setAttribute('aria-pressed','true');
    startBtn.disabled = true; stopBtn.disabled = false; resetBtn.disabled = true;
    tryEnterFullscreen();
    raf = requestAnimationFrame(tick);
    if(autoFocus) target.focus();
    updateUI();
  }

  function endTest(){
    if(!running) return;
    running = false;
    cancelAnimationFrame(raf);
    const elapsed = Math.min(duration, (performance.now() - startTime)/1000);
    const totalCps = elapsed > 0 ? totalClicks / elapsed : 0;
    if(totalCps > bestCps) bestCps = totalCps;
    if(totalCps >= 5) streak++; else streak = 0;
    const avgCps = history.length ? (history.reduce((s,h)=>s+parseFloat(h.cps),0)/history.length) : totalCps;
    const record = {
      time: new Date().toLocaleString(),
      duration: elapsed.toFixed(2),
      left: leftClicks,
      right: rightClicks,
      total: totalClicks,
      cps: totalCps.toFixed(2),
      streak: streak,
      avgCps: avgCps.toFixed(2)
    };
    history.unshift(record);
    if(history.length > 300) history.length = 300;
    persist();
    updateUI();
    renderHistory();
    startBtn.disabled = false; stopBtn.disabled = true; resetBtn.disabled = false;
    target.setAttribute('aria-pressed','false');
    statusText.textContent = 'Finished';
    beep(880, 0.12, 0.12);
    if(vibrateToggle.checked && navigator.vibrate) navigator.vibrate(120);
    showOverlay(totalCps, record);
  }

  function stopTest(){ if(running) endTest(); }

  function resetTest(){
    running = false; leftClicks = rightClicks = totalClicks = 0; startTime = 0;
    updateUI(); progressBar.style.width = '0%'; statusText.textContent = 'Ready';
    hideOverlay();
  }

  // click handling
  function handlePointerDown(e){
    if(overlayBanner.getAttribute('aria-hidden') === 'false') return;
    const rect = target.getBoundingClientRect();
    const x = (e.clientX || (rect.left + rect.width/2)) - rect.left;
    const y = (e.clientY || (rect.top + rect.height/2)) - rect.top;
    const btn = (typeof e.button === 'number') ? e.button : 0;
    const mode = clickType2.value;
    const isLeft = (btn === 0), isRight = (btn === 2);
    const shouldCount = (mode === 'both') || (mode === 'left' && isLeft) || (mode === 'right' && isRight);

    if(!running && shouldCount){
      startTest(false);
    }

    if(running && shouldCount){
      if(isLeft) leftClicks++;
      if(isRight) rightClicks++;
      totalClicks++;
      targetBtn.style.transform = 'scale(0.96)';
      setTimeout(()=> targetBtn.style.transform = '', 80);
      createRipple(x,y);
      if(soundToggle.checked) beep(1200, 0.02, 0.02);
      if(vibrateToggle.checked && navigator.vibrate) navigator.vibrate(8);
      updateUI();
    }
  }

  target.addEventListener('contextmenu', (e) => e.preventDefault());
  target.addEventListener('pointerdown', (e) => { e.preventDefault(); handlePointerDown(e); });
  targetBtn.addEventListener('pointerdown', (e) => { e.preventDefault(); handlePointerDown(e); });

  // keyboard
  window.addEventListener('keydown', (e) => {
    if(e.code === 'Space' || e.code === 'Enter'){
      e.preventDefault();
      const rect = target.getBoundingClientRect();
      handlePointerDown({button:0, clientX: rect.left + rect.width/2, clientY: rect.top + rect.height/2});
    }
    if(e.key === 's' || e.key === 'S') startTest();
    if(e.key === 'r' || e.key === 'R') resetTest();
  });

  // ripple
  function createRipple(x,y){
    const r = document.createElement('div');
    const size = Math.max(30, Math.min(target.clientWidth, target.clientHeight) * 0.35);
    r.className = 'ripple';
    r.style.width = r.style.height = size + 'px';
    r.style.left = x + 'px'; r.style.top = y + 'px';
    r.style.background = `radial-gradient(circle at center, var(--ripple), rgba(0,0,0,0.02))`;
    r.style.position = 'absolute'; r.style.borderRadius = '999px'; r.style.pointerEvents = 'none';
    r.style.transition = 'opacity .6s ease, transform .6s cubic-bezier(.2,.9,.2,1)';
    target.appendChild(r);
    requestAnimationFrame(()=> { r.style.transform = 'scale(2)'; r.style.opacity = '0'; });
    setTimeout(()=> r.remove(), 700);
  }

  // overlay banner
  function classify(cps){
    if(cps >= 12) return {label:'Bugatti Chiron', emoji:'🏎️', desc:"Insane speed — you're a Bugatti Chiron!"};
    if(cps >= 8) return {label:'Cheetah', emoji:'🐆', desc:'Lightning fast — Cheetah level!'};
    if(cps >= 6) return {label:'Runner', emoji:'🏃', desc:'Great tracking — Runner level!'};
    if(cps >= 5) return {label:'Human', emoji:'🧍', desc:'Solid speed — Human level.'};
    return {label:'Turtle', emoji:'🐢', desc:'Take it easy — Turtle pace.'};
  }

  function showOverlay(cps, record){
    const info = classify(cps);
    overlayEmoji.textContent = info.emoji;
    overlayTitle.textContent = `${info.label} — ${cps.toFixed(2)} CPS`;
    overlayDesc.textContent = `${info.desc} • Streak: ${record.streak} • Avg CPS: ${record.avgCps}`;
    overlayBanner.style.display = 'block';
    overlayBanner.setAttribute('aria-hidden','false');
    overlayBanner.style.pointerEvents = 'auto';
    target.style.pointerEvents = 'none';
    overlayClose.focus();
  }

  function hideOverlay(){
    overlayBanner.style.display = 'none';
    overlayBanner.setAttribute('aria-hidden','true');
    overlayBanner.style.pointerEvents = 'none';
    target.style.pointerEvents = 'auto';
  }

  overlayClose.addEventListener('click', hideOverlay);

  // history
  function renderHistory(){
    historyList.innerHTML = '';
    if(history.length === 0){
      historyList.innerHTML = '<div style="color:var(--muted);padding:8px">No sessions yet</div>';
      return;
    }
    history.forEach(h => {
      const el = document.createElement('div');
      el.className = 'history-item';
      el.innerHTML = `<div style="min-width:160px">${h.time}</div><div style="text-align:right">${h.total} clicks • ${h.cps} CPS • L:${h.left} R:${h.right}</div>`;
      historyList.appendChild(el);
    });
  }

  clearHistory.addEventListener('click', () => {
    history = []; persist(); renderHistory();
    statusText.textContent = 'History cleared';
    setTimeout(()=> statusText.textContent = running ? 'Running' : 'Idle', 1200);
  });

  // tabs switching
  tabSettings.addEventListener('click', () => {
    tabSettings.classList.add('active'); tabHistory.classList.remove('active');
    settingsPanel.style.display='block'; historyPanel.style.display='none';
  });
  tabHistory.addEventListener('click', () => {
    tabHistory.classList.add('active'); tabSettings.classList.remove('active');
    settingsPanel.style.display='none'; historyPanel.style.display='block'; renderHistory();
  });

  // theme selector behavior (applies body class so menus remain clear)
  function applyThemeClass(cls){
    body.classList.remove(...themes);
    if(cls && themes.includes(cls)) body.classList.add(cls);
    persist();
  }
  themeSelect2.addEventListener('change', (e) => { applyThemeClass(e.target.value); });

  // click type saved in settings
  clickType2.addEventListener('change', persist);

  // fullscreen toggle saved
  fullscreenToggle.addEventListener('change', persist);

  // start/stop/reset
  startBtn.addEventListener('click', () => startTest());
  stopBtn.addEventListener('click', () => stopTest());
  resetBtn.addEventListener('click', () => resetTest());

  // close app: hide UI (no open button to reopen)
  closeApp.addEventListener('click', () => {
    try { if(document.exitFullscreen) document.exitFullscreen().catch(()=>{}); } catch(e){}
    app.style.display = 'none';
    // keep close button visible so user can refresh/close browser to reopen
    closeApp.setAttribute('aria-hidden','false');
  });

  // size select behavior
  sizeSelect.addEventListener('click', (ev) => {
    const btn = ev.target.closest('button[data-size]');
    if(!btn) return;
    Array.from(sizeSelect.querySelectorAll('button')).forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    const px = parseInt(btn.getAttribute('data-size'),10) || 260;
    setTargetSize(px);
    persist();
  });

  // settings inputs
  durationEl.addEventListener('change', () => { duration = parseFloat(durationEl.value) || 5; updateUI(); });

  // initial UI: default target size Large (260)
  (function initSize(){
    const currentW = parseInt(getComputedStyle(targetBtn).width,10);
    if(!currentW || currentW === 260){
      const active = sizeSelect.querySelector('button.active');
      if(active) setTargetSize(parseInt(active.getAttribute('data-size'),10));
      else setTargetSize(260);
    }
  })();

  // initial UI
  stopBtn.disabled = true; resetBtn.disabled = false;
  updateUI(); renderHistory();
  // apply initial theme from body class (theme-a by default)
  const initial = Array.from(document.body.classList).find(c => themes.includes(c)) || 'theme-a';
  applyThemeClass(initial);

  // persist periodically
  setInterval(persist, 5000);
  window.addEventListener('beforeunload', persist);

  // service worker registration (best-effort)
  if('serviceWorker' in navigator){
    try {
      const swCode = `
        const CACHE_NAME = 'blec-cps-blecnotade-final';
        const toCache = [location.href];
        self.addEventListener('install', e => { e.waitUntil(caches.open(CACHE_NAME).then(c => c.addAll(toCache)).catch(()=>{})); self.skipWaiting(); });
        self.addEventListener('activate', e => e.waitUntil(self.clients.claim()));
        self.addEventListener('fetch', e => {
          if(e.request.method !== 'GET') return;
          e.respondWith(caches.match(e.request).then(r => r || fetch(e.request).then(resp => {
            try { const url = new URL(e.request.url); if(url.origin === location.origin) caches.open(CACHE_NAME).then(c => c.put(e.request, resp.clone()).catch(()=>{})); } catch(e){}
            return resp.clone();
          }).catch(()=> caches.match(location.href))));
        });
      `;
      const blob = new Blob([swCode], {type:'application/javascript'});
      const swUrl = URL.createObjectURL(blob);
      navigator.serviceWorker.register(swUrl).catch(()=>{});
    } catch(e){}
  }
})();
</script>
</body>
</html>
