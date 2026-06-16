<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ヴィパッサナー瞑想</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@300;400;500&family=Shippori+Mincho:wght@400;500&display=swap" rel="stylesheet">
<style>
:root {
  --gold: #c9a96e;
  --gold-light: #e8d5b0;
  --cream: #f5f0e8;
  --dark: #1a1410;
  --muted: #8a7560;
  --sitting: #7a9e7e;
  --walking: #6b8cba;
  --level1: #8a7e6e;
  --level2: #7a9e7e;
  --level3: #c9a96e;
}
* { margin: 0; padding: 0; box-sizing: border-box; }
body {
  background: var(--dark);
  color: var(--cream);
  font-family: 'Noto Serif JP', serif;
  min-height: 100vh;
  overflow-x: hidden;
}
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background:
    radial-gradient(ellipse at 20% 50%, rgba(201,169,110,0.08) 0%, transparent 60%),
    radial-gradient(ellipse at 80% 20%, rgba(106,140,186,0.06) 0%, transparent 50%),
    radial-gradient(ellipse at 60% 80%, rgba(122,158,126,0.06) 0%, transparent 50%);
  pointer-events: none;
  z-index: 0;
}
.app { position:relative; z-index:1; max-width:480px; margin:0 auto; padding:0 0 100px; }

.header { text-align:center; padding:36px 20px 20px; border-bottom:1px solid rgba(201,169,110,0.2); }
.header h1 { font-family:'Shippori Mincho',serif; font-size:1.5rem; font-weight:400; color:var(--gold); letter-spacing:0.3em; margin-bottom:4px; }
.header p { font-size:0.68rem; color:var(--muted); letter-spacing:0.2em; }

.nav { display:flex; border-bottom:1px solid rgba(201,169,110,0.15); background:rgba(26,20,16,0.9); position:sticky; top:0; z-index:100; backdrop-filter:blur(10px); }
.nav-btn { flex:1; padding:13px 6px; background:none; border:none; color:var(--muted); font-family:'Noto Serif JP',serif; font-size:0.7rem; letter-spacing:0.08em; cursor:pointer; transition:all 0.3s; border-bottom:2px solid transparent; }
.nav-btn.active { color:var(--gold); border-bottom-color:var(--gold); }

.section { display:none; padding:22px 20px; }
.section.active { display:block; }

/* ── LEVEL SELECTOR ── */
.level-section { margin-bottom:22px; }
.level-header { display:flex; align-items:center; justify-content:space-between; margin-bottom:10px; }
.level-title { font-size:0.65rem; letter-spacing:0.2em; color:var(--gold); }
.level-cards { display:flex; flex-direction:column; gap:8px; }
.level-card {
  border:1px solid rgba(201,169,110,0.18);
  border-radius:12px;
  padding:14px 16px;
  cursor:pointer;
  transition:all 0.3s;
  background:rgba(255,255,255,0.02);
  display:flex;
  align-items:center;
  gap:14px;
  position:relative;
  overflow:hidden;
}
.level-card.active { border-color:var(--gold); background:rgba(201,169,110,0.08); }
.level-card.locked { opacity:0.38; cursor:not-allowed; }
.level-card.locked::after { content:'🔒'; position:absolute; right:14px; top:50%; transform:translateY(-50%); font-size:0.9rem; }
.level-num {
  font-family:'Shippori Mincho',serif;
  font-size:1.5rem;
  color:rgba(201,169,110,0.35);
  line-height:1;
  flex-shrink:0;
  width:28px;
  text-align:center;
}
.level-card.active .level-num { color:var(--gold); }
.level-info { flex:1; }
.level-name { font-size:0.78rem; letter-spacing:0.1em; color:var(--gold-light); margin-bottom:3px; }
.level-desc { font-size:0.64rem; color:var(--muted); line-height:1.5; }
.level-badges { display:flex; gap:5px; margin-top:5px; flex-wrap:wrap; }
.level-badge { font-size:0.56rem; padding:2px 8px; border-radius:10px; background:rgba(201,169,110,0.1); color:var(--muted); border:1px solid rgba(201,169,110,0.15); letter-spacing:0.05em; }

.level-unlock-btn {
  margin-top:8px;
  width:100%;
  padding:10px;
  background:rgba(201,169,110,0.06);
  border:1px solid rgba(201,169,110,0.25);
  border-radius:8px;
  color:var(--muted);
  font-family:'Noto Serif JP',serif;
  font-size:0.7rem;
  letter-spacing:0.15em;
  cursor:pointer;
  transition:all 0.3s;
  display:none;
}
.level-unlock-btn:hover { background:rgba(201,169,110,0.12); color:var(--gold); }
.level-unlock-btn.visible { display:block; }

.level-progress-note { font-size:0.62rem; color:var(--muted); text-align:center; margin-top:10px; letter-spacing:0.08em; line-height:1.7; }

/* ── DURATION ── */
.duration-row { display:flex; gap:7px; margin-bottom:18px; flex-wrap:wrap; justify-content:center; }
.dur-btn { padding:6px 13px; border:1px solid rgba(201,169,110,0.25); border-radius:18px; background:none; color:var(--muted); font-family:'Noto Serif JP',serif; font-size:0.7rem; letter-spacing:0.08em; cursor:pointer; transition:all 0.3s; }
.dur-btn.active { border-color:var(--gold); color:var(--gold); background:rgba(201,169,110,0.08); }

/* ── TIMER ── */
.timer-wrap { display:flex; flex-direction:column; align-items:center; margin:16px 0 18px; }
.timer-circle-container { position:relative; width:200px; height:200px; }
.timer-svg { width:200px; height:200px; transform:rotate(-90deg); }
.timer-bg { fill:none; stroke:rgba(201,169,110,0.1); stroke-width:3; }
.timer-progress { fill:none; stroke-width:3; stroke-linecap:round; transition:stroke-dashoffset 1s linear,stroke 0.5s; stroke-dasharray:565; stroke-dashoffset:0; }
.timer-display { position:absolute; top:50%; left:50%; transform:translate(-50%,-50%); text-align:center; }
.timer-time { font-family:'Shippori Mincho',serif; font-size:2.4rem; font-weight:400; color:var(--cream); letter-spacing:0.05em; line-height:1; }
.timer-label { font-size:0.58rem; color:var(--muted); letter-spacing:0.18em; margin-top:6px; }

/* ── CONTROLS ── */
.controls { display:flex; align-items:center; justify-content:center; gap:18px; margin-bottom:18px; }
.ctrl-btn { width:50px; height:50px; border-radius:50%; border:1px solid rgba(201,169,110,0.3); background:none; color:var(--gold-light); font-size:1.1rem; cursor:pointer; display:flex; align-items:center; justify-content:center; transition:all 0.3s; }
.ctrl-btn:hover { border-color:var(--gold); background:rgba(201,169,110,0.08); }
.ctrl-btn.primary { width:66px; height:66px; font-size:1.5rem; border-color:var(--gold); background:rgba(201,169,110,0.1); }
.ctrl-btn.primary:hover { background:rgba(201,169,110,0.2); }

/* ── GUIDANCE BOX ── */
.guidance-box { background:rgba(255,255,255,0.03); border:1px solid rgba(201,169,110,0.15); border-radius:12px; padding:18px 20px; margin-bottom:14px; min-height:90px; transition:all 0.6s; position:relative; }
.guidance-phase { font-size:0.62rem; color:var(--gold); letter-spacing:0.25em; margin-bottom:8px; }
.guidance-text { font-size:0.82rem; line-height:1.9; color:var(--cream); opacity:0.9; }
.speaking-indicator { position:absolute; top:14px; right:14px; display:flex; gap:3px; align-items:flex-end; height:16px; opacity:0; transition:opacity 0.3s; }
.speaking-indicator.active { opacity:1; }
.speaking-bar { width:3px; background:var(--gold); border-radius:2px; animation:speakBar 0.8s ease-in-out infinite alternate; }
.speaking-bar:nth-child(1){height:6px;animation-delay:0s}
.speaking-bar:nth-child(2){height:12px;animation-delay:0.15s}
.speaking-bar:nth-child(3){height:8px;animation-delay:0.3s}
.speaking-bar:nth-child(4){height:14px;animation-delay:0.1s}
@keyframes speakBar { from{transform:scaleY(0.4);opacity:0.5} to{transform:scaleY(1);opacity:1} }

.progress-detail { font-size:0.63rem; color:var(--muted); text-align:center; letter-spacing:0.12em; margin-bottom:14px; }

/* ── CURRENT LEVEL DISPLAY ── */
.current-level-bar {
  display:flex;
  align-items:center;
  gap:10px;
  padding:10px 14px;
  background:rgba(201,169,110,0.06);
  border:1px solid rgba(201,169,110,0.2);
  border-radius:10px;
  margin-bottom:16px;
}
.clb-label { font-size:0.62rem; color:var(--muted); letter-spacing:0.12em; }
.clb-name { font-size:0.75rem; color:var(--gold-light); letter-spacing:0.1em; flex:1; }
.clb-sessions { font-size:0.6rem; color:var(--muted); }

/* ── VOICE BANNER ── */
.voice-banner { background:rgba(201,169,110,0.08); border:1px solid rgba(201,169,110,0.3); border-radius:10px; padding:12px 16px; margin-bottom:20px; display:flex; align-items:center; gap:10px; }
.voice-banner span { font-size:0.74rem; color:var(--gold-light); line-height:1.6; flex:1; }
.voice-test-btn { padding:6px 14px; border:1px solid rgba(201,169,110,0.4); border-radius:16px; background:none; color:var(--gold); font-size:0.68rem; font-family:'Noto Serif JP',serif; cursor:pointer; white-space:nowrap; transition:all 0.3s; }
.voice-test-btn:hover { background:rgba(201,169,110,0.1); }

/* ── GUIDANCE REFERENCE ── */
.ref-box { background:rgba(255,255,255,0.02); border:1px solid rgba(201,169,110,0.12); border-radius:12px; padding:15px 17px; margin-bottom:11px; }
.ref-phase { font-size:0.62rem; color:var(--gold); letter-spacing:0.2em; margin-bottom:6px; }
.ref-text { font-size:0.78rem; line-height:1.85; color:var(--cream); opacity:0.8; }
.section-divider { display:flex; align-items:center; gap:10px; margin:20px 0 14px; }
.section-divider::before,.section-divider::after { content:''; flex:1; height:1px; background:rgba(201,169,110,0.18); }
.section-divider span { font-size:0.62rem; color:var(--muted); letter-spacing:0.18em; }

/* ── JOURNAL ── */
.journal-entry { margin-bottom:13px; }
.journal-entry label { display:block; font-size:0.68rem; color:var(--gold); letter-spacing:0.18em; margin-bottom:6px; }
.journal-entry textarea,.journal-entry input,.journal-entry select { width:100%; background:rgba(255,255,255,0.03); border:1px solid rgba(201,169,110,0.2); border-radius:10px; padding:11px 13px; color:var(--cream); font-family:'Noto Serif JP',serif; font-size:0.8rem; outline:none; transition:border-color 0.3s; resize:none; }
.journal-entry textarea:focus,.journal-entry input:focus { border-color:rgba(201,169,110,0.45); }
.journal-entry textarea::placeholder,.journal-entry input::placeholder { color:var(--muted); }
.journal-entry select { cursor:pointer; }
.save-btn { width:100%; padding:13px; background:rgba(201,169,110,0.1); border:1px solid rgba(201,169,110,0.4); border-radius:10px; color:var(--gold); font-family:'Noto Serif JP',serif; font-size:0.8rem; letter-spacing:0.2em; cursor:pointer; transition:all 0.3s; }
.save-btn:hover { background:rgba(201,169,110,0.18); }

/* ── RECORDS ── */
.stats-row { display:grid; grid-template-columns:repeat(3,1fr); gap:10px; margin-bottom:18px; }
.stat-card { background:rgba(255,255,255,0.03); border:1px solid rgba(201,169,110,0.15); border-radius:10px; padding:13px 10px; text-align:center; }
.stat-val { font-family:'Shippori Mincho',serif; font-size:1.4rem; color:var(--gold); display:block; }
.stat-lbl { font-size:0.58rem; color:var(--muted); letter-spacing:0.1em; margin-top:3px; }
.record-card { background:rgba(255,255,255,0.03); border:1px solid rgba(201,169,110,0.15); border-radius:12px; padding:14px 16px; margin-bottom:10px; }
.record-header { display:flex; justify-content:space-between; align-items:center; margin-bottom:6px; }
.record-date { font-size:0.64rem; color:var(--muted); }
.record-badge { font-size:0.6rem; padding:3px 9px; border-radius:10px; }
.record-badge.lv1 { background:rgba(138,126,110,0.15); color:var(--level1); border:1px solid rgba(138,126,110,0.3); }
.record-badge.lv2 { background:rgba(122,158,126,0.15); color:var(--sitting); border:1px solid rgba(122,158,126,0.3); }
.record-badge.lv3 { background:rgba(201,169,110,0.1); color:var(--gold); border:1px solid rgba(201,169,110,0.3); }
.record-duration { font-family:'Shippori Mincho',serif; font-size:1.05rem; color:var(--gold-light); margin-bottom:5px; }
.record-note { font-size:0.72rem; color:var(--muted); line-height:1.6; }
.empty-state { text-align:center; padding:40px 20px; color:var(--muted); font-size:0.78rem; line-height:2.2; }

.toast { position:fixed; bottom:110px; left:50%; transform:translateX(-50%) translateY(20px); background:rgba(201,169,110,0.15); border:1px solid rgba(201,169,110,0.4); border-radius:20px; padding:9px 22px; font-size:0.72rem; color:var(--gold); letter-spacing:0.12em; opacity:0; transition:all 0.4s; white-space:nowrap; backdrop-filter:blur(10px); z-index:200; }
.toast.show { opacity:1; transform:translateX(-50%) translateY(0); }

/* ── LEVEL UP MODAL ── */
.modal-overlay { position:fixed; inset:0; background:rgba(0,0,0,0.7); z-index:300; display:flex; align-items:center; justify-content:center; opacity:0; pointer-events:none; transition:opacity 0.4s; backdrop-filter:blur(4px); }
.modal-overlay.show { opacity:1; pointer-events:all; }
.modal-box { background:var(--dark); border:1px solid rgba(201,169,110,0.35); border-radius:20px; padding:32px 28px; max-width:340px; width:90%; text-align:center; }
.modal-icon { font-size:2.5rem; margin-bottom:14px; }
.modal-title { font-family:'Shippori Mincho',serif; font-size:1.1rem; color:var(--gold); letter-spacing:0.15em; margin-bottom:10px; }
.modal-desc { font-size:0.78rem; line-height:1.9; color:var(--cream); opacity:0.8; margin-bottom:24px; }
.modal-btns { display:flex; gap:10px; }
.modal-btn { flex:1; padding:11px; border-radius:10px; font-family:'Noto Serif JP',serif; font-size:0.75rem; letter-spacing:0.1em; cursor:pointer; transition:all 0.3s; }
.modal-btn.primary { background:rgba(201,169,110,0.15); border:1px solid var(--gold); color:var(--gold); }
.modal-btn.primary:hover { background:rgba(201,169,110,0.25); }
.modal-btn.secondary { background:none; border:1px solid rgba(201,169,110,0.25); color:var(--muted); }
.modal-btn.secondary:hover { border-color:var(--gold); color:var(--gold-light); }
</style>
</head>
<body>
<div class="app">
  <div class="header">
    <h1>ヴィパッサナー</h1>
    <p>VIPASSANĀ MEDITATION</p>
  </div>

  <nav class="nav">
    <button class="nav-btn active" onclick="showSection('timer',this)">瞑想</button>
    <button class="nav-btn" onclick="showSection('guidance',this)">ガイダンス</button>
    <button class="nav-btn" onclick="showSection('journal',this)">日記</button>
    <button class="nav-btn" onclick="showSection('records',this)">記録</button>
  </nav>

  <!-- Timer -->
  <div class="section active" id="timer">
    <div class="voice-banner">
      <span>🔊 音声でガイドします。<br>音量をご確認ください。</span>
      <button class="voice-test-btn" onclick="testVoice()">音声テスト</button>
    </div>

    <!-- Level Selector -->
    <div class="level-section">
      <div class="level-header">
        <span class="level-title">　実践の段階を選ぶ</span>
      </div>
      <div class="level-cards" id="levelCards">
        <!-- JS で生成 -->
      </div>
      <button class="level-unlock-btn" id="unlockBtn" onclick="showUnlockModal()">
        次の段階へ進む →
      </button>
      <p class="level-progress-note" id="levelProgressNote"></p>
    </div>

    <!-- Duration -->
    <div class="duration-row" id="durationRow">
      <!-- JS で生成 -->
    </div>

    <!-- Current level display -->
    <div class="current-level-bar" id="currentLevelBar">
      <span class="clb-label">段階</span>
      <span class="clb-name" id="clbName">—</span>
      <span class="clb-sessions" id="clbSessions"></span>
    </div>

    <div class="timer-wrap">
      <div class="timer-circle-container">
        <svg class="timer-svg" viewBox="0 0 200 200">
          <circle class="timer-bg" cx="100" cy="100" r="90"/>
          <circle class="timer-progress" id="progressCircle" cx="100" cy="100" r="90"
            stroke="#c9a96e" stroke-dasharray="565" stroke-dashoffset="0"/>
        </svg>
        <div class="timer-display">
          <div class="timer-time" id="timerDisplay">20:00</div>
          <div class="timer-label" id="timerLabel">準備ができたら開始</div>
        </div>
      </div>
    </div>

    <div class="progress-detail" id="progressDetail"></div>

    <div class="controls">
      <button class="ctrl-btn" onclick="resetTimer()" title="リセット">↺</button>
      <button class="ctrl-btn primary" id="playBtn" onclick="toggleTimer()">▶</button>
      <button class="ctrl-btn" style="opacity:0.3;cursor:default" title="セットは固定です">—</button>
    </div>
    <button id="breakEndBtn" onclick="endBreak(false)" style="display:none;width:100%;margin-bottom:14px;padding:13px;background:rgba(122,158,126,0.12);border:1px solid rgba(122,158,126,0.4);border-radius:10px;color:#7a9e7e;font-family:'Noto Serif JP',serif;font-size:0.8rem;letter-spacing:0.2em;cursor:pointer;">
      休憩を終える →
    </button>

    <div class="guidance-box" id="mainGuidance">
      <div class="speaking-indicator" id="speakingIndicator">
        <div class="speaking-bar"></div><div class="speaking-bar"></div>
        <div class="speaking-bar"></div><div class="speaking-bar"></div>
      </div>
      <div class="guidance-phase" id="guidancePhase">今この瞬間</div>
      <div class="guidance-text" id="guidanceText">段階を選んで、開始ボタンを押してください。音声でガイドします。</div>
    </div>
  </div>

  <!-- Guidance Reference -->
  <div class="section" id="guidance">
    <div id="guidanceRef"><!-- JS で生成 --></div>
  </div>

  <!-- Journal -->
  <div class="section" id="journal">
    <div class="journal-entry">
      <label>今日の段階</label>
      <select id="journalLevel" style="background:#1a1410">
        <option value="1">段階 1 — はじめの気づき</option>
        <option value="2">段階 2 — より明確な観察</option>
        <option value="3">段階 3 — 細かい気づき</option>
      </select>
    </div>
    <div class="journal-entry">
      <label>瞑想の時間</label>
      <input type="text" id="journalDuration" placeholder="例：20分">
    </div>
    <div class="journal-entry">
      <label>今日の気づき・感覚</label>
      <textarea id="journalObs" rows="4" placeholder="身体に感じた感覚、心に浮かんだこと…"></textarea>
    </div>
    <div class="journal-entry">
      <label>難しかったこと</label>
      <textarea id="journalChal" rows="3" placeholder="集中が切れた、音が気になった…"></textarea>
    </div>
    <div class="journal-entry">
      <label>今日の一言</label>
      <textarea id="journalWord" rows="2" placeholder="瞑想後の今、一言で表すと…"></textarea>
    </div>
    <button class="save-btn" onclick="saveJournal()">記録を保存する</button>
  </div>

  <!-- Records -->
  <div class="section" id="records">
    <div class="stats-row">
      <div class="stat-card"><span class="stat-val" id="statTotal">0</span><span class="stat-lbl">記録数</span></div>
      <div class="stat-card"><span class="stat-val" id="statMinutes">0</span><span class="stat-lbl">合計分数</span></div>
      <div class="stat-card"><span class="stat-val" id="statStreak">0</span><span class="stat-lbl">連続日数</span></div>
    </div>
    <div id="recordsList">
      <div class="empty-state">まだ記録がありません<br><br>瞑想日記を書いて<br>記録を積み重ねましょう</div>
    </div>
  </div>
</div>

<!-- Level Up Modal -->
<div class="modal-overlay" id="unlockModal">
  <div class="modal-box">
    <div class="modal-icon">🌸</div>
    <div class="modal-title" id="modalTitle">次の段階へ</div>
    <div class="modal-desc" id="modalDesc"></div>
    <div class="modal-btns">
      <button class="modal-btn secondary" onclick="closeModal()">もう少し続ける</button>
      <button class="modal-btn primary" onclick="confirmUnlock()">次の段階へ進む</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
// =====================
// LEVELS DEFINITION
// =====================
const LEVELS = [
  {
    id: 1,
    name: 'はじめの気づき',
    desc: 'シンプルなラベリングで、動きと呼吸に気づく',
    durations: [10, 20, 30, 45, 60],
    defaultDuration: 10,
    walking: {
      steps: ['上げる', '動かす', '下げる'],
      phases: [
        {
          title: '立つ・準備',
          intro: '静かな場所に立ちましょう。目を半眼にして、足元の少し前を見ます。全身の重さが、足の裏から伝わっているのを感じてください。「立っている」と心の中で静かに気づきましょう。',
          reminder: '立っている感覚をただ感じています。',
        },
        {
          title: '歩く・上げる、動かす、下げる',
          intro: 'ゆっくりと歩き始めましょう。一歩ごとに、「上げる・動かす・下げる」の三つに気づきながら歩きます。ラベルは声に出さず、心の中で静かに。急がなくていいです。一歩一歩、丁寧に。もし頭に何か浮かんできたら、「考えている」と気づいて、また歩みに戻ります。音が気になったら、「聞こえている」と気づいて、また戻ります。',
          reminder: '上げる、動かす、下げる。一歩ずつ、丁寧に歩いています。',
        },
      ],
    },
    sitting: {
      steps: ['膨らむ', '縮む'],
      phases: [
        {
          title: '座る・落ち着く',
          intro: '静かに座りましょう。背筋をゆっくりと伸ばします。目を閉じてください。坐骨が床に触れる感覚を感じます。手が膝に置かれている重さに気づいてください。今ここにいます。',
          reminder: '座っている。今ここにいます。',
        },
        {
          title: '呼吸・膨らむ、縮む',
          intro: '意識をお腹に向けます。息を吸うとき、お腹が「膨らむ」のを感じてください。息を吐くとき、「縮む」のを感じます。「膨らむ、縮む」とただ気づいていきましょう。うまくやろうとしなくて大丈夫です。何か思いが浮かんだら、「考えている」と気づいて、またお腹に戻ります。音が気になったら、「聞こえている」と気づいて、また戻ります。',
          reminder: '膨らむ、縮む。ただお腹の動きを感じています。',
        },
      ],
    },
  },
  {
    id: 2,
    name: 'より明確な観察',
    desc: '動作を細かく分け、より明確に気づく',
    durations: [10, 20, 30, 45, 60],
    defaultDuration: 20,
    walking: {
      steps: ['上げる', '動かす', '下ろす', '触れる'],
      phases: [
        {
          title: '立つ・準備',
          intro: '静かな場所に立ちましょう。目を半眼にして足元を見ます。足の裏全体が床に触れている感覚に気づいてください。体重の分布、熱さや冷たさ、圧力を感じましょう。「立っている」と静かに気づきます。',
          reminder: '足の裏の感覚。立っている。',
        },
        {
          title: '歩く・上げる、動かす、下ろす、触れる',
          intro: 'ゆっくりと歩き始めます。今回は四つの動作に気づきます。「上げる・動かす・下ろす・触れる」。足が床を離れる感触、空中を動く感触、床に下ろす感触、触れる瞬間の感触。一つひとつを丁寧に感じましょう。思考や音が来たら、ラベルをつけて気づき、また歩みに戻ります。',
          reminder: '上げる、動かす、下ろす、触れる。感触を丁寧に。',
        },
      ],
    },
    sitting: {
      steps: ['膨らむ', '縮む', '座っている'],
      phases: [
        {
          title: '座る・落ち着く',
          intro: '静かに座りましょう。背筋を伸ばし、目を閉じます。全身の存在感を感じてください。坐骨、背中、手、足。今ここに座っている自分に気づきます。',
          reminder: '今ここに座っています。',
        },
        {
          title: '呼吸と存在感',
          intro: 'お腹に意識を向けます。「膨らむ・縮む」に気づきながら、同時に「座っている」という全身の感覚も保ちましょう。呼吸とともに、座っているという存在感を感じています。思考が来たら「考えている」、音が来たら「聞こえている」、体の感覚が来たら「感じている」と気づいて、また戻ります。',
          reminder: '膨らむ、縮む、座っている。呼吸と存在感を感じています。',
        },
      ],
    },
  },
  {
    id: 3,
    name: '細かい気づき',
    desc: 'より精細な動作と感覚の流れを観察する',
    durations: [10, 20, 30, 45, 60],
    defaultDuration: 30,
    walking: {
      steps: ['かかと上げる', 'つま先上げる', '動かす', '下ろす', '触れる', '重みを移す'],
      phases: [
        {
          title: '立つ・全身の気づき',
          intro: '静かな場所に立ちます。目を半眼にして、足元の少し前を見ましょう。今日は、足の裏から始まり、体全体の感覚に気づいていきます。体重の分布、体の微細な揺れ、体温。全身が今ここにあることを感じます。「立っている」と静かに気づきましょう。',
          reminder: '全身の重さ、微細な感覚を感じています。',
        },
        {
          title: '歩く・六つの動作',
          intro: 'ゆっくりと歩き始めます。今回は六つの動作です。「かかとが上がる・つま先が上がる・前へ動かす・下ろす・触れる・体重を移す」。一つひとつの瞬間に、精細に気づきます。焦らず、丁寧に。思考、音、感覚が来たら、それぞれ「考えている」「聞こえている」「感じている」と気づき、また歩みへ。',
          reminder: 'かかと、つま先、動かす、下ろす、触れる、移す。精細に感じています。',
        },
      ],
    },
    sitting: {
      steps: ['膨らむ', '縮む', '感覚が生じる', '感覚が消える'],
      phases: [
        {
          title: '座る・深い落ち着き',
          intro: '静かに座ります。背筋を伸ばし、目を閉じましょう。全身をゆっくりと感じます。体に触れている感覚、温度、重さ。今ここに座っているという確かな感覚を保ちましょう。',
          reminder: '今ここに座っています。全身を感じています。',
        },
        {
          title: '呼吸と感覚の流れ',
          intro: '「膨らむ・縮む」を感じながら、全身にも意識を開いていきましょう。感覚が生じてきます。それを「感じている」と気づいて、消えていくのを見守ります。すべての感覚は生じて、変化して、消えていきます。思考も同じです。ただ、流れを見守りましょう。',
          reminder: '感覚が生じて、消えていく。ただ見守っています。',
        },
      ],
    },
  },
];

// =====================
// STATE
// =====================
let currentLevel = 1;
let unlockedLevels = JSON.parse(localStorage.getItem('vp_unlocked') || '[1]');
let sessionCounts = JSON.parse(localStorage.getItem('vp_sessions') || '{"1":0,"2":0,"3":0}');
let records = JSON.parse(localStorage.getItem('vp_records') || '[]');

let perSideMins = 10;
let duration = 10 * 60;
let remaining = 10 * 60;
let isRunning = false;
let mainInterval = null;
let sessionPhases = [];
let currentPhaseIndex = 0;
let phaseElapsed = 0;
let totalElapsed = 0;
let reminderCounter = 0;
const REMINDER_SECS = 80;
let isBreak = false;
let breakRemaining = 0;
let breakInterval = null;

// =====================
// VOICE
// =====================
const synth = window.speechSynthesis;
let japaneseVoice = null;

function initVoice() {
  const load = () => {
    const voices = synth.getVoices();
    japaneseVoice =
      voices.find(v => v.lang === 'ja-JP' && v.localService) ||
      voices.find(v => v.lang === 'ja-JP') ||
      voices.find(v => v.lang.startsWith('ja')) || null;
  };
  if (synth.getVoices().length > 0) load();
  synth.onvoiceschanged = load;
}

function speak(text, onEnd, rate=0.82, pitch=0.95) {
  synth.cancel();
  if (!text) { if (onEnd) onEnd(); return; }
  const utt = new SpeechSynthesisUtterance(text);
  utt.lang = 'ja-JP'; utt.rate = rate; utt.pitch = pitch; utt.volume = 1;
  if (japaneseVoice) utt.voice = japaneseVoice;
  utt.onstart = () => document.getElementById('speakingIndicator').classList.add('active');
  utt.onend = () => { document.getElementById('speakingIndicator').classList.remove('active'); if (onEnd) onEnd(); };
  utt.onerror = () => { document.getElementById('speakingIndicator').classList.remove('active'); if (onEnd) onEnd(); };
  synth.speak(utt);
}

function testVoice() { speak('音声テストです。ヴィパッサナー瞑想へようこそ。'); }

// =====================
// BUILD UI
// =====================
function buildLevelCards() {
  const lv = LEVELS.find(l => l.id === currentLevel);
  const container = document.getElementById('levelCards');
  container.innerHTML = LEVELS.map(l => {
    const locked = !unlockedLevels.includes(l.id);
    const active = l.id === currentLevel;
    return `
      <div class="level-card${active?' active':''}${locked?' locked':''}"
           onclick="${locked ? 'showLockedMsg()' : `selectLevel(${l.id})`}">
        <div class="level-num">${l.id}</div>
        <div class="level-info">
          <div class="level-name">${l.name}</div>
          <div class="level-desc">${l.desc}</div>
          <div class="level-badges">
            <span class="level-badge">🚶 ${l.walking.steps.join('・')}</span>
            <span class="level-badge">🪷 ${l.sitting.steps.join('・')}</span>
          </div>
        </div>
      </div>`;
  }).join('');

  // Unlock button
  const btn = document.getElementById('unlockBtn');
  const maxUnlocked = Math.max(...unlockedLevels);
  if (currentLevel === maxUnlocked && currentLevel < LEVELS.length) {
    btn.classList.add('visible');
  } else {
    btn.classList.remove('visible');
  }

  // Progress note
  const note = document.getElementById('levelProgressNote');
  const cnt = sessionCounts[currentLevel] || 0;
  if (currentLevel < LEVELS.length && !unlockedLevels.includes(currentLevel + 1)) {
    note.textContent = `この段階での実践回数：${cnt} 回　慣れてきたら「次の段階へ進む」ボタンを押してください。`;
  } else {
    note.textContent = `この段階での実践回数：${cnt} 回`;
  }

  // Current level bar
  document.getElementById('clbName').textContent = `段階${lv.id}：${lv.name}`;
  document.getElementById('clbSessions').textContent = `${cnt}回`;
}

function buildDurationBtns() {
  const lv = LEVELS.find(l => l.id === currentLevel);
  const row = document.getElementById('durationRow');
  row.innerHTML = lv.durations.map(d =>
    `<button class="dur-btn${d===lv.defaultDuration?' active':''}" onclick="setDuration(${d})">${d}分</button>`
  ).join('');
  setDuration(lv.defaultDuration, true);
}

function buildGuidanceRef() {
  const container = document.getElementById('guidanceRef');
  let html = '';
  LEVELS.forEach(lv => {
    const locked = !unlockedLevels.includes(lv.id);
    html += `<div class="section-divider"><span>段階 ${lv.id}：${lv.name}${locked?' 🔒':''}</span></div>`;
    if (!locked) {
      html += `
        <div class="ref-box">
          <div class="ref-phase">🚶 歩く瞑想　気づきのポイント：${lv.walking.steps.join('・')}</div>
          <div class="ref-text">${lv.walking.phases.map(p=>`【${p.title}】${p.reminder}`).join('<br>')}</div>
        </div>
        <div class="ref-box">
          <div class="ref-phase">🪷 座る瞑想　気づきのポイント：${lv.sitting.steps.join('・')}</div>
          <div class="ref-text">${lv.sitting.phases.map(p=>`【${p.title}】${p.reminder}`).join('<br>')}</div>
        </div>
        <div class="ref-box" style="background:rgba(201,169,110,0.03)">
          <div class="ref-phase">どの段階でも共通</div>
          <div class="ref-text">何かが浮かんだら「考えている」「聞こえている」「感じている」と気づいて、また元の観察へ戻ります。自然に消えていくまで観察するだけでよいのです。</div>
        </div>`;
    } else {
      html += `<div class="ref-box" style="opacity:0.4"><div class="ref-text" style="text-align:center">段階 ${lv.id-1} を実践してから解放されます</div></div>`;
    }
  });
  container.innerHTML = html;
}

// =====================
// LEVEL SELECT
// =====================
function selectLevel(id) {
  if (!unlockedLevels.includes(id)) return;
  currentLevel = id;
  buildLevelCards();
  buildDurationBtns();
  updateIntroGuidance();
  resetTimer();
}

function showLockedMsg() {
  showToast('前の段階を実践してから解放されます 🙏');
}

// =====================
// DURATION
// =====================
function setDuration(mins, silent=false) {
  if (isRunning) return;
  perSideMins = mins;
  duration = mins * 60;
  remaining = duration;
  document.querySelectorAll('.dur-btn').forEach(b =>
    b.classList.toggle('active', parseInt(b.textContent) === mins));
  updateDisplay();
  updateProgress();
  if (!silent) updateIntroGuidance();
}

function updateIntroGuidance() {
  const lv = LEVELS.find(l => l.id === currentLevel);
  const total = perSideMins * 2;
  setDisplay('今この瞬間',
    `段階${lv.id}「${lv.name}」で実践します。\n\n🚶 歩く瞑想：${perSideMins}分\n　└ 立つ・準備：2分（固定）\n　└ 歩く実践：${perSideMins - 2}分\n↔ 移行：30秒\n🪷 座る瞑想：${perSideMins}分\n　└ 座る・落ち着く：2分（固定）\n　└ 座る実践：${perSideMins - 2}分\n合計：約${total}分30秒\n\n準備ができたら開始ボタンを押してください。`);
}

// =====================
// BUILD SESSION PHASES
// =====================
function buildSessionPhases() {
  const lv = LEVELS.find(l => l.id === currentLevel);
  const walkSecs = perSideMins * 60;
  const sitSecs  = perSideMins * 60;
  const transSecs = 30;
  const introFixed = 2 * 60; // 導入フェーズ固定2分

  const wPhases = lv.walking.phases;
  const sPhases = lv.sitting.phases;

  // 歩く：最初のフェーズ2分固定、残りを後続フェーズで均等に
  const wMainSecs = walkSecs - introFixed;
  const wMainCount = wPhases.length - 1;
  const wpp = wMainCount > 0 ? Math.floor(wMainSecs / wMainCount) : wMainSecs;

  // 座る：最初のフェーズ2分固定、残りを後続フェーズで均等に
  const sMainSecs = sitSecs - introFixed;
  const sMainCount = sPhases.length - 1;
  const spp = sMainCount > 0 ? Math.floor(sMainSecs / sMainCount) : sMainSecs;

  sessionPhases = [
    // 歩く：導入2分固定
    { ...wPhases[0], type: 'walking', secs: introFixed },
    // 歩く：残りフェーズ均等
    ...wPhases.slice(1).map((p, i) => ({
      ...p,
      type: 'walking',
      secs: i < wMainCount - 1 ? wpp : wMainSecs - wpp * (wMainCount - 1),
    })),
    // 移行30秒
    { title: '移行', type: 'transition', secs: transSecs, intro: null, reminder: null },
    // 座る：導入2分固定
    { ...sPhases[0], type: 'sitting', secs: introFixed },
    // 座る：残りフェーズ均等
    ...sPhases.slice(1).map((p, i) => ({
      ...p,
      type: 'sitting',
      secs: i < sMainCount - 1 ? spp : sMainSecs - spp * (sMainCount - 1),
    })),
  ];

  // 合計秒数をdurationに反映（プログレスバー用）
  duration = walkSecs + transSecs + sitSecs;
  remaining = duration;
}

// =====================
// PRAYERS
// =====================
const OPENING_TEXT = 'ナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。\nナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。\nナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。\nワット・プラタート・シー・チョームトーンの伝統に従い、今から瞑想を始めます。';
const OPENING_SPOKEN = 'ナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。ナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。ナモ タッサ バガワトー アラハトー サンマー サンブッダッサ。ワット・プラタート・シー・チョームトーンの伝統に従い、今から瞑想を始めます。';
const CLOSING_TEXT = 'サンマ・アラハン（三唱）\n\nこの実践の功徳を、\n全ての生きとし生けるものへ分かち合います。\n\nサッベー・サッター・スカーニャンツゥ\n（全ての生命が幸福でありますように）';
const CLOSING_SPOKEN = '瞑想が完了しました。サンマ・アラハン。サンマ・アラハン。サンマ・アラハン。この実践の功徳を、全ての生きとし生けるものへ分かち合いましょう。サッベー・サッター・スカーニャンツゥ。全ての生命が幸福でありますように。ゆっくりと目を開けてください。';

// =====================
// TIMER
// =====================
function toggleTimer() {
  if (isBreak) return;
  if (isRunning) pauseTimer(); else startTimer();
}

function startTimer() {
  if (totalElapsed === 0) {
    buildSessionPhases();
    currentPhaseIndex = 0;
    phaseElapsed = 0;
    reminderCounter = 0;
    setDisplay('礼拝 — ナモ タッサ', OPENING_TEXT);
    document.getElementById('timerLabel').textContent = '礼拝中…';
    speak(OPENING_SPOKEN, () => {
      if (isRunning) speakPhaseIntro(0);
    }, 0.75, 0.9);
  }
  isRunning = true;
  document.getElementById('playBtn').textContent = '⏸';
  document.getElementById('timerLabel').textContent = '瞑想中…';

  mainInterval = setInterval(() => {
    if (remaining <= 0) { finishSession(); return; }
    remaining--;
    totalElapsed++;
    phaseElapsed++;
    reminderCounter++;
    updateDisplay();
    updateProgress();

    const ph = sessionPhases[currentPhaseIndex];

    // Phase advance
    if (ph && phaseElapsed >= ph.secs) {
      phaseElapsed = 0;
      currentPhaseIndex++;
      reminderCounter = 0;
      if (currentPhaseIndex < sessionPhases.length) {
        speakPhaseIntro(currentPhaseIndex);
      }
    }

    // Reminder
    if (reminderCounter >= REMINDER_SECS && ph && ph.reminder) {
      reminderCounter = 0;
      if (!synth.speaking) speak(ph.reminder);
    }

    // Progress label
    const cur = sessionPhases[currentPhaseIndex];
    const icon = cur ? (cur.type==='walking'?'🚶':cur.type==='sitting'?'🪷':'↔') : '';
    document.getElementById('progressDetail').textContent =
      cur ? `${icon} ${cur.title}　（${currentPhaseIndex+1}／${sessionPhases.length}）` : '';
  }, 1000);
}

function speakPhaseIntro(idx) {
  const ph = sessionPhases[idx];
  if (!ph) return;
  if (ph.type === 'transition') {
    setDisplay('移行', '歩く瞑想が終わりました。静かに立ち止まり、座る場所へ移動してください。');
    speak('歩く瞑想が終わりました。ゆっくりと立ち止まってください。静かな場所に移動して、座る準備をしましょう。', null, 0.8, 0.92);
    return;
  }
  setDisplay(ph.title, ph.intro || '');
  if (ph.intro) speak(ph.intro, null, 0.82, 0.95);
}

function pauseTimer() {
  isRunning = false;
  clearInterval(mainInterval);
  synth.cancel();
  document.getElementById('playBtn').textContent = '▶';
  document.getElementById('timerLabel').textContent = '一時停止中';
  document.getElementById('speakingIndicator').classList.remove('active');
}

function resetTimer() {
  pauseTimer();
  clearInterval(breakInterval);
  isBreak = false;
  breakRemaining = 0;
  duration = perSideMins * 60;
  remaining = duration;
  totalElapsed = 0;
  phaseElapsed = 0;
  currentPhaseIndex = 0;
  reminderCounter = 0;
  sessionPhases = [];
  document.getElementById('breakEndBtn').style.display = 'none';
  updateDisplay();
  updateProgress();
  document.getElementById('timerLabel').textContent = '準備ができたら開始';
  document.getElementById('progressDetail').textContent = '';
  updateIntroGuidance();
}

function finishSession() {
  clearInterval(mainInterval);
  isRunning = false;
  remaining = 0;
  updateDisplay();
  updateProgress();
  document.getElementById('playBtn').textContent = '▶';
  document.getElementById('timerLabel').textContent = '完了 🙏';
  document.getElementById('progressDetail').textContent = '';
  setDisplay('瞑想の終わり — 回向', CLOSING_TEXT);

  // Increment session count
  sessionCounts[currentLevel] = (sessionCounts[currentLevel] || 0) + 1;
  localStorage.setItem('vp_sessions', JSON.stringify(sessionCounts));
  buildLevelCards();

  // 回向を読み上げてから休憩へ
  speak(CLOSING_SPOKEN, () => {
    startBreak();
  }, 0.75, 0.9);
}

function startBreak() {
  isBreak = true;
  const breakMins = 15 + Math.floor(Math.random() * 6); // 15〜20分
  breakRemaining = breakMins * 60;

  setDisplay('休憩 ☕', `ワンセットお疲れ様でした。\n${breakMins}分間休憩しましょう。\n\n体をほぐしたり、水を飲んだり、\n静かに過ごしてください。\n\n準備ができたら「休憩を終える」ボタンを押してください。`);
  document.getElementById('timerLabel').textContent = '休憩中…';
  document.getElementById('playBtn').textContent = '—';
  document.getElementById('progressDetail').textContent = '休憩タイム';

  // 休憩終了ボタンを表示
  document.getElementById('breakEndBtn').style.display = 'block';

  speak(`ワンセットお疲れ様でした。${breakMins}分間、ゆっくり休憩してください。`, null, 0.8, 0.92);

  breakInterval = setInterval(() => {
    breakRemaining--;
    const m = Math.floor(breakRemaining / 60);
    const s = breakRemaining % 60;
    document.getElementById('timerDisplay').textContent =
      String(m).padStart(2,'0') + ':' + String(s).padStart(2,'0');

    if (breakRemaining <= 0) {
      endBreak(true);
    }
  }, 1000);
}

function endBreak(auto=false) {
  clearInterval(breakInterval);
  isBreak = false;
  document.getElementById('breakEndBtn').style.display = 'none';
  document.getElementById('timerLabel').textContent = '休憩終了';
  document.getElementById('progressDetail').textContent = '';
  showToast('休憩終了。また始める準備ができたらどうぞ 🙏');
  if (auto) {
    speak('休憩時間が終わりました。また始める準備ができたら開始ボタンを押してください。', null, 0.8, 0.92);
  } else {
    speak('休憩を終えました。また始める準備ができたら開始ボタンを押してください。', null, 0.8, 0.92);
  }
  // リセット準備
  setTimeout(() => resetTimer(), 3000);
}

function setDisplay(phase, text) {
  document.getElementById('guidancePhase').textContent = phase;
  document.getElementById('guidanceText').textContent = text;
}
function updateDisplay() {
  const m = Math.floor(remaining/60), s = remaining%60;
  document.getElementById('timerDisplay').textContent = String(m).padStart(2,'0')+':'+String(s).padStart(2,'0');
}
function updateProgress() {
  const d = duration > 0 ? duration : 1;
  document.getElementById('progressCircle').style.strokeDashoffset = 565*(1-remaining/d);
}

// =====================
// LEVEL UNLOCK
// =====================
function showUnlockModal() {
  const nextId = currentLevel + 1;
  const next = LEVELS.find(l => l.id === nextId);
  if (!next) return;
  const cnt = sessionCounts[currentLevel] || 0;
  document.getElementById('modalTitle').textContent = `段階 ${nextId}「${next.name}」へ`;
  document.getElementById('modalDesc').textContent =
    `段階 ${currentLevel} での実践回数：${cnt} 回\n\n次の段階では、${next.desc}。\n\nいつでも前の段階に戻ることができます。自分のペースで進みましょう。`;
  document.getElementById('unlockModal').classList.add('show');
}

function closeModal() {
  document.getElementById('unlockModal').classList.remove('show');
}

function confirmUnlock() {
  const nextId = currentLevel + 1;
  if (!unlockedLevels.includes(nextId)) {
    unlockedLevels.push(nextId);
    localStorage.setItem('vp_unlocked', JSON.stringify(unlockedLevels));
  }
  closeModal();
  selectLevel(nextId);
  showToast(`段階 ${nextId} が解放されました 🌸`);
  buildGuidanceRef();
}

// =====================
// NAV
// =====================
function showSection(id, btn) {
  document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  btn.classList.add('active');
  if (id === 'records') renderRecords();
}

// =====================
// JOURNAL
// =====================
function saveJournal() {
  const lv = document.getElementById('journalLevel').value;
  const dur = document.getElementById('journalDuration').value || '不明';
  const obs = document.getElementById('journalObs').value;
  const chal = document.getElementById('journalChal').value;
  const word = document.getElementById('journalWord').value;
  if (!obs && !word) { showToast('気づきか一言を入力してください'); return; }
  const now = new Date();
  records.unshift({
    date: now.toLocaleDateString('ja-JP',{year:'numeric',month:'long',day:'numeric',weekday:'short'}),
    level: parseInt(lv), dur, obs, chal, word
  });
  localStorage.setItem('vp_records', JSON.stringify(records));
  ['journalObs','journalChal','journalWord','journalDuration'].forEach(id => document.getElementById(id).value='');
  showToast('記録を保存しました ✨');
}

// =====================
// RECORDS
// =====================
function renderRecords() {
  document.getElementById('statTotal').textContent = records.length;
  let totalMins = 0;
  records.forEach(r => { const m=parseInt(r.dur); if(!isNaN(m)) totalMins+=m; });
  document.getElementById('statMinutes').textContent = totalMins;
  document.getElementById('statStreak').textContent = Math.min(records.length, 7);
  const el = document.getElementById('recordsList');
  if (!records.length) {
    el.innerHTML = '<div class="empty-state">まだ記録がありません<br><br>瞑想日記を書いて<br>記録を積み重ねましょう</div>';
    return;
  }
  el.innerHTML = records.map(r => `
    <div class="record-card">
      <div class="record-header">
        <span class="record-date">${r.date}</span>
        <span class="record-badge lv${r.level||1}">段階 ${r.level||1}</span>
      </div>
      <div class="record-duration">${r.dur}</div>
      ${r.obs?`<div class="record-note">${r.obs}</div>`:''}
      ${r.word?`<div class="record-note" style="color:var(--gold-light);margin-top:5px;font-style:italic">「${r.word}」</div>`:''}
    </div>
  `).join('');
}

function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 2800);
}

// =====================
// INIT
// =====================
initVoice();
buildLevelCards();
buildDurationBtns();
buildGuidanceRef();
updateDisplay();
updateProgress();
updateIntroGuidance();
</script>
</body>
</html>
