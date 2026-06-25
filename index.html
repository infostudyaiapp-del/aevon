<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AEVON</title>
<script src="https://js.puter.com/v2/"></script>
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #1a1a1a; color: #ececec; height: 100vh; display: flex; overflow: hidden; }
#sidebar { width: 260px; min-width: 260px; background: #111111; display: flex; flex-direction: column; padding: 12px; border-right: 1px solid #2a2a2a; }
.logo { display: flex; align-items: center; gap: 10px; padding: 10px 8px 16px; border-bottom: 1px solid #2a2a2a; margin-bottom: 8px; }
.logo-mark { width: 32px; height: 32px; background: #ececec; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 16px; color: #111; font-weight: 800; flex-shrink: 0; }
.logo-name { font-size: 17px; font-weight: 700; color: #ececec; letter-spacing: 1.5px; }
.logo-sub { font-size: 10px; color: #555; letter-spacing: 0.5px; }
.new-chat-btn { display: flex; align-items: center; gap: 8px; padding: 10px 12px; border: 1px solid #2a2a2a; border-radius: 8px; background: transparent; color: #ececec; font-size: 14px; cursor: pointer; width: 100%; margin-bottom: 16px; transition: background 0.15s; font-family: inherit; }
.new-chat-btn:hover { background: #222; }
.sidebar-section { font-size: 11px; color: #444; padding: 4px 8px 8px; letter-spacing: 0.5px; text-transform: uppercase; }
.nav-btn { display: flex; align-items: center; gap: 10px; padding: 9px 12px; border-radius: 8px; border: none; background: transparent; color: #999; font-size: 14px; cursor: pointer; width: 100%; text-align: left; transition: all 0.15s; font-family: inherit; }
.nav-btn:hover { background: #1e1e1e; color: #ececec; }
.nav-btn.active { background: #252525; color: #ececec; }
.nav-btn .icon { font-size: 15px; width: 20px; text-align: center; }
.sidebar-bottom { margin-top: auto; padding-top: 12px; border-top: 1px solid #2a2a2a; }
.model-badge { display: flex; align-items: center; gap: 8px; padding: 8px 12px; background: #1a1a1a; border-radius: 8px; font-size: 12px; color: #666; }
.dot-live { width: 6px; height: 6px; background: #4caf50; border-radius: 50%; animation: blink 2s infinite; }
@keyframes blink { 0%,100% { opacity:1; } 50% { opacity:0.3; } }
#main { flex: 1; display: flex; flex-direction: column; overflow: hidden; background: #1a1a1a; }
.panel { display: none; flex: 1; flex-direction: column; overflow: hidden; }
.panel.active { display: flex; }
#messages { flex: 1; overflow-y: auto; padding: 0; scroll-behavior: smooth; }
#messages::-webkit-scrollbar { width: 6px; }
#messages::-webkit-scrollbar-track { background: transparent; }
#messages::-webkit-scrollbar-thumb { background: #2a2a2a; border-radius: 3px; }
.welcome { display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100%; gap: 20px; padding: 40px 24px; text-align: center; }
.welcome-icon { width: 56px; height: 56px; background: #ececec; border-radius: 14px; display: flex; align-items: center; justify-content: center; font-size: 26px; color: #111; font-weight: 800; }
.welcome h1 { font-size: 28px; font-weight: 700; color: #ececec; letter-spacing: 1px; }
.welcome p { font-size: 15px; color: #666; max-width: 400px; line-height: 1.6; }
.suggestions { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; max-width: 520px; margin-top: 4px; }
.sugg-btn { padding: 9px 16px; background: #222; border: 1px solid #2a2a2a; border-radius: 20px; color: #aaa; font-size: 13px; cursor: pointer; transition: all 0.15s; font-family: inherit; }
.sugg-btn:hover { background: #2a2a2a; color: #ececec; border-color: #444; }
.msg-row { padding: 20px 0; border-bottom: 1px solid #222; animation: fadeup 0.25s ease; }
@keyframes fadeup { from { opacity:0; transform: translateY(6px); } to { opacity:1; transform: translateY(0); } }
.msg-inner { max-width: 720px; margin: 0 auto; padding: 0 24px; display: flex; gap: 14px; }
.msg-avatar { width: 30px; height: 30px; border-radius: 6px; display: flex; align-items: center; justify-content: center; font-size: 14px; flex-shrink: 0; margin-top: 2px; }
.msg-row.user .msg-avatar { background: #333; }
.msg-row.ai .msg-avatar { background: #ececec; color: #111; font-weight: 800; font-size: 12px; }
.msg-body { flex: 1; font-size: 15px; line-height: 1.7; color: #ececec; }
.msg-body pre { background: #111; border: 1px solid #2a2a2a; border-radius: 8px; padding: 14px; overflow-x: auto; margin: 10px 0; font-size: 13px; font-family: 'Menlo', 'Monaco', monospace; line-height: 1.5; }
.msg-body code { background: #252525; padding: 2px 6px; border-radius: 4px; font-size: 13px; font-family: 'Menlo', 'Monaco', monospace; color: #ccc; }
.msg-img { max-height: 200px; border-radius: 8px; border: 1px solid #2a2a2a; margin-bottom: 8px; display: block; }
.typing-row .msg-body { display: flex; align-items: center; gap: 4px; padding-top: 4px; }
.typing-dot { width: 7px; height: 7px; background: #555; border-radius: 50%; animation: bounce 1.2s infinite; }
.typing-dot:nth-child(2) { animation-delay: 0.2s; }
.typing-dot:nth-child(3) { animation-delay: 0.4s; }
@keyframes bounce { 0%,60%,100% { transform: translateY(0); } 30% { transform: translateY(-5px); } }
#input-area { padding: 16px 24px 20px; background: #1a1a1a; }
.input-wrap { max-width: 720px; margin: 0 auto; }
.img-thumb-row { display: none; margin-bottom: 8px; position: relative; width: fit-content; }
.img-thumb-row img { max-height: 80px; border-radius: 6px; border: 1px solid #2a2a2a; }
.img-remove { position: absolute; top: -5px; right: -5px; width: 16px; height: 16px; background: #444; border-radius: 50%; display: flex; align-items: center; justify-content: center; cursor: pointer; font-size: 9px; color: #ececec; }
.input-box { display: flex; align-items: flex-end; gap: 8px; background: #252525; border: 1px solid #333; border-radius: 12px; padding: 10px 12px; transition: border-color 0.2s; }
.input-box:focus-within { border-color: #555; }
#prompt { flex: 1; background: transparent; border: none; outline: none; color: #ececec; font-size: 15px; font-family: inherit; resize: none; min-height: 24px; max-height: 160px; line-height: 1.5; }
#prompt::placeholder { color: #444; }
.tool-btn { background: transparent; border: none; color: #555; cursor: pointer; padding: 4px; border-radius: 6px; font-size: 16px; display: flex; align-items: center; justify-content: center; transition: color 0.15s; }
.tool-btn:hover { color: #aaa; }
#send { width: 32px; height: 32px; background: #ececec; border: none; border-radius: 8px; color: #111; cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 15px; transition: all 0.15s; flex-shrink: 0; }
#send:hover { background: #fff; }
#send:disabled { background: #2a2a2a; color: #555; cursor: not-allowed; }
.input-hint { text-align: center; font-size: 11px; color: #3a3a3a; margin-top: 8px; }
#tools-panel { overflow-y: auto; }
.panel-head { padding: 28px 32px 16px; border-bottom: 1px solid #222; }
.panel-head h2 { font-size: 20px; font-weight: 600; color: #ececec; }
.panel-head p { font-size: 13px; color: #555; margin-top: 4px; }
.tools-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap: 12px; padding: 24px 32px; }
.tool-card { background: #202020; border: 1px solid #2a2a2a; border-radius: 10px; padding: 18px; cursor: pointer; transition: all 0.15s; display: flex; flex-direction: column; gap: 8px; }
.tool-card:hover { background: #252525; border-color: #444; }
.tc-icon { font-size: 22px; }
.tc-name { font-size: 14px; font-weight: 600; color: #ececec; }
.tc-desc { font-size: 12px; color: #666; line-height: 1.5; }
#vision-panel { overflow-y: auto; }
.vision-body { padding: 24px 32px; display: flex; flex-direction: column; gap: 16px; }
.drop-zone { border: 2px dashed #2a2a2a; border-radius: 10px; padding: 48px; text-align: center; cursor: pointer; transition: all 0.2s; display: flex; flex-direction: column; align-items: center; gap: 10px; }
.drop-zone:hover, .drop-zone.over { border-color: #555; background: #1e1e1e; }
.drop-zone .dz-icon { font-size: 36px; }
.drop-zone .dz-title { font-size: 15px; font-weight: 600; }
.drop-zone .dz-sub { font-size: 13px; color: #555; }
#vis-preview { display: none; flex-direction: column; gap: 14px; }
#vis-img { max-height: 260px; border-radius: 10px; border: 1px solid #2a2a2a; object-fit: contain; align-self: flex-start; }
.vis-actions { display: flex; flex-wrap: wrap; gap: 8px; }
.vis-btn { padding: 8px 14px; background: #202020; border: 1px solid #2a2a2a; border-radius: 20px; color: #aaa; font-size: 12px; cursor: pointer; font-family: inherit; transition: all 0.15s; }
.vis-btn:hover { background: #2a2a2a; color: #ececec; border-color: #444; }
.vis-custom { display: flex; gap: 8px; }
.vis-custom input { flex: 1; background: #202020; border: 1px solid #2a2a2a; border-radius: 8px; padding: 9px 14px; color: #ececec; font-size: 14px; font-family: inherit; outline: none; }
.vis-custom input:focus { border-color: #555; }
.vis-custom button { padding: 9px 16px; background: #ececec; border: none; border-radius: 8px; color: #111; font-size: 13px; cursor: pointer; font-family: inherit; font-weight: 600; }
#vis-result { display: none; background: #202020; border: 1px solid #2a2a2a; border-radius: 10px; padding: 16px; font-size: 14px; line-height: 1.7; color: #ececec; }
.reset-btn { align-self: flex-start; padding: 8px 14px; background: transparent; border: 1px solid #333; border-radius: 8px; color: #666; font-size: 13px; cursor: pointer; font-family: inherit; transition: all 0.15s; }
.reset-btn:hover { border-color: #555; color: #aaa; }
#history-panel { overflow-y: auto; }
.history-list { padding: 20px 32px; display: flex; flex-direction: column; gap: 6px; }
.h-item { display: flex; justify-content: space-between; align-items: center; padding: 12px 14px; background: #202020; border: 1px solid #2a2a2a; border-radius: 8px; cursor: pointer; transition: all 0.15s; }
.h-item:hover { background: #252525; border-color: #444; }
.h-preview { font-size: 14px; color: #ccc; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; max-width: 78%; }
.h-time { font-size: 11px; color: #444; flex-shrink: 0; }
.empty { text-align: center; padding: 60px 20px; color: #444; font-size: 14px; }
#toast { position: fixed; bottom: 20px; left: 50%; transform: translateX(-50%) translateY(60px); background: #2a2a2a; border: 1px solid #333; padding: 9px 18px; border-radius: 20px; font-size: 13px; color: #ececec; transition: transform 0.25s; z-index: 999; }
#toast.show { transform: translateX(-50%) translateY(0); }
@media (max-width: 640px) {
  #sidebar { width: 52px; min-width: 52px; padding: 10px 8px; }
  .logo-name, .logo-sub, .nav-btn span, .sidebar-section, .model-badge span { display: none; }
  .logo { justify-content: center; }
  .nav-btn { justify-content: center; }
  .new-chat-btn span { display: none; }
  .new-chat-btn { justify-content: center; }
  .msg-inner { padding: 0 14px; }
  #input-area { padding: 12px 14px 16px; }
}
</style>
</head>
<body>
<nav id="sidebar">
  <div class="logo">
    <div class="logo-mark">AV</div>
    <div><div class="logo-name">AEVON</div><div class="logo-sub">AI Evolution</div></div>
  </div>
  <button class="new-chat-btn" onclick="newChat()"><span>✏️</span> <span>New chat</span></button>
  <div class="sidebar-section">Menu</div>
  <button class="nav-btn active" id="nb-chat" onclick="switchTo('chat',this)"><span class="icon">💬</span><span>Chat</span></button>
  <button class="nav-btn" id="nb-tools" onclick="switchTo('tools',this)"><span class="icon">🛠️</span><span>Tools</span></button>
  <button class="nav-btn" id="nb-vision" onclick="switchTo('vision',this)"><span class="icon">🖼️</span><span>Vision</span></button>
  <button class="nav-btn" id="nb-history" onclick="switchTo('history',this)"><span class="icon">🕘</span><span>History</span></button>
  <div class="sidebar-bottom">
    <div class="model-badge"><div class="dot-live"></div><span>GLM-5.2 · Free</span></div>
  </div>
</nav>
<main id="main">
  <div class="panel active" id="chat-panel">
    <div id="messages">
      <div class="welcome" id="welcome">
        <div class="welcome-icon">AV</div>
        <h1>AEVON</h1>
        <p>Your all-in-one AI assistant. Chat, write, code, create content, and analyze images.</p>
        <div class="suggestions">
          <button class="sugg-btn" onclick="ask('Write a viral Instagram caption for a tech product')">📱 Instagram caption</button>
          <button class="sugg-btn" onclick="ask('Write a Python REST API with Flask')">💻 Write code</button>
          <button class="sugg-btn" onclick="ask('Give me 10 YouTube content ideas for a tech channel')">🎬 Content ideas</button>
          <button class="sugg-btn" onclick="ask('Explain machine learning in simple terms')">🧠 Explain anything</button>
          <button class="sugg-btn" onclick="ask('Write a professional cold email to a potential client')">📧 Write email</button>
          <button class="sugg-btn" onclick="ask('What are the best free AI tools in 2026?')">🤖 AI tools 2026</button>
        </div>
      </div>
    </div>
    <div id="input-area">
      <div class="input-wrap">
        <div class="img-thumb-row" id="thumb-row"><img id="thumb-img" src=""><div class="img-remove" onclick="removeImg()">✕</div></div>
        <div class="input-box">
          <button class="tool-btn" onclick="document.getElementById('file-in').click()" title="Attach image">📎</button>
          <input type="file" id="file-in" accept="image/*" style="display:none" onchange="attachImg(this)">
          <textarea id="prompt" placeholder="Message AEVON..." rows="1" onkeydown="onKey(event)" oninput="resize(this)"></textarea>
          <button id="send" onclick="send()">➤</button>
        </div>
        <div class="input-hint">Enter to send · Shift+Enter for new line · 📎 attach image</div>
      </div>
    </div>
  </div>
  <div class="panel" id="tools-panel">
    <div class="panel-head"><h2>AI Tools</h2><p>Click any tool — opens in chat with a smart prompt ready</p></div>
    <div class="tools-grid">
      <div class="tool-card" onclick="tool('Write a blog post about: [paste your topic]')"><div class="tc-icon">✍️</div><div class="tc-name">Content Writer</div><div class="tc-desc">Blogs, articles, captions, scripts — any format.</div></div>
      <div class="tool-card" onclick="tool('Help me write and debug this code:\n\n[paste your code or describe what to build]')"><div class="tc-icon">💻</div><div class="tc-name">Code Assistant</div><div class="tc-desc">Write, debug, explain code in any language.</div></div>
      <div class="tool-card" onclick="tool('Summarize the following text into clear bullet points:\n\n[paste your text here]')"><div class="tc-icon">📋</div><div class="tc-name">Summarizer</div><div class="tc-desc">Paste any text and get a crisp summary.</div></div>
      <div class="tool-card" onclick="tool('Write a professional email.\nPurpose: [e.g. follow-up]\nRecipient: [who]\nKey points: [what to cover]')"><div class="tc-icon">📧</div><div class="tc-name">Email Writer</div><div class="tc-desc">Professional emails and cold outreach fast.</div></div>
      <div class="tool-card" onclick="tool('Write a high-engagement post for [Instagram / Twitter / LinkedIn] about:\nTopic: [your topic]\nTone: [casual / professional / funny]\nInclude hashtags.')"><div class="tc-icon">📱</div><div class="tc-name">Social Media</div><div class="tc-desc">Viral posts with hashtags for any platform.</div></div>
      <div class="tool-card" onclick="tool('Do a deep research on this topic with structured key insights:\n\nTopic: [paste your topic]')"><div class="tc-icon">🔬</div><div class="tc-name">Research Helper</div><div class="tc-desc">Deep-dive any topic with structured insights.</div></div>
      <div class="tool-card" onclick="tool('Translate the following text to [target language]:\n\n[paste text here]')"><div class="tc-icon">🌐</div><div class="tc-name">Translator</div><div class="tc-desc">Translate text into 50+ languages naturally.</div></div>
      <div class="tool-card" onclick="tool('Generate a quiz with 8 questions on:\nTopic: [your topic]\nDifficulty: [easy / medium / hard]\nInclude answers.')"><div class="tc-icon">🎯</div><div class="tc-name">Quiz Generator</div><div class="tc-desc">Turn any topic into a smart quiz with answers.</div></div>
      <div class="tool-card" onclick="tool('Brainstorm 10 creative ideas for:\n\n[describe your project or challenge]')"><div class="tc-icon">💡</div><div class="tc-name">Brainstorm</div><div class="tc-desc">10+ creative ideas for any project.</div></div>
    </div>
  </div>
  <div class="panel" id="vision-panel">
    <div class="panel-head"><h2>Vision — Image Analysis</h2><p>Upload any image and ask questions about it</p></div>
    <div class="vision-body">
      <div class="drop-zone" id="drop-zone" onclick="document.getElementById('vis-file').click()" ondrop="onDrop(event)" ondragover="onDragOver(event)" ondragleave="onDragLeave(event)">
        <div class="dz-icon">📸</div><div class="dz-title">Drop image here or click to upload</div><div class="dz-sub">JPG, PNG, GIF, WEBP</div>
      </div>
      <input type="file" id="vis-file" accept="image/*" style="display:none" onchange="loadVis(this)">
      <div id="vis-preview">
        <img id="vis-img" src="">
        <div class="vis-actions">
          <button class="vis-btn" onclick="analyzeVis('Describe this image in detail and generate all possible study questions with answers')">📚 Study Questions</button>
          <button class="vis-btn" onclick="analyzeVis('Extract and explain all text, data, or information visible in this image')">📝 Extract Text</button>
          <button class="vis-btn" onclick="analyzeVis('Do a deep analysis of this image — what is happening, key concepts, and insights')">🔍 Deep Analysis</button>
          <button class="vis-btn" onclick="analyzeVis('Describe this image for content creation — caption, blog idea, and social post suggestions')">✍️ Content Brief</button>
        </div>
        <div class="vis-custom">
          <input id="vis-q" type="text" placeholder="Ask your own question about this image..." onkeydown="if(event.key==='Enter') analyzeVis(document.getElementById('vis-q').value)">
          <button onclick="analyzeVis(document.getElementById('vis-q').value)">Ask</button>
        </div>
        <div id="vis-result"></div>
        <button class="reset-btn" onclick="resetVis()">↺ Upload new image</button>
      </div>
    </div>
  </div>
  <div class="panel" id="history-panel">
    <div class="panel-head"><h2>Chat History</h2><p>Your recent conversations — click to reload</p></div>
    <div class="history-list" id="hist-list"></div>
  </div>
</main>
<div id="toast"></div>
<script>
const SYS = `You are AEVON, a next-generation AI assistant. You help with everything: writing, coding, content creation, research, translation, image analysis, and more. Be clear, direct, and helpful. Format responses with markdown when useful. If asked who you are, say: "I am AEVON — an AI Evolution assistant."`;
let msgs = [], busy = false, chatImg64 = null, chatImgType = null, visImg64 = null, visImgType = null;
function switchTo(name, btn) {
  document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  document.getElementById(name + '-panel').classList.add('active');
  btn.classList.add('active');
  if (name === 'history') loadHist();
}
function newChat() {
  msgs = [];
  document.getElementById('messages').innerHTML = `<div class="welcome" id="welcome"><div class="welcome-icon">AV</div><h1>AEVON</h1><p>Your all-in-one AI assistant. Chat, write, code, create content, and analyze images.</p><div class="suggestions"><button class="sugg-btn" onclick="ask('Write a viral Instagram caption for a tech product')">📱 Instagram caption</button><button class="sugg-btn" onclick="ask('Write a Python REST API with Flask')">💻 Write code</button><button class="sugg-btn" onclick="ask('Give me 10 YouTube content ideas for a tech channel')">🎬 Content ideas</button><button class="sugg-btn" onclick="ask('Explain machine learning in simple terms')">🧠 Explain anything</button><button class="sugg-btn" onclick="ask('Write a professional cold email to a potential client')">📧 Write email</button><button class="sugg-btn" onclick="ask('What are the best free AI tools in 2026?')">🤖 AI tools 2026</button></div></div>`;
  removeImg(); toast('New chat started');
}
function onKey(e) { if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); send(); } }
function resize(el) { el.style.height = 'auto'; el.style.height = Math.min(el.scrollHeight, 160) + 'px'; }
function ask(text) { document.getElementById('prompt').value = text; send(); }
function tool(text) {
  document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  document.getElementById('chat-panel').classList.add('active');
  document.getElementById('nb-chat').classList.add('active');
  document.getElementById('prompt').value = text;
  document.getElementById('prompt').focus();
  toast('✏️ Edit the prompt then press Enter');
}
async function send() {
  const input = document.getElementById('prompt');
  const text = input.value.trim();
  if (!text && !chatImg64) return;
  if (busy) return;
  document.getElementById('welcome')?.remove();
  addMsg('user', text || '📎 Image', chatImg64 ? `data:${chatImgType};base64,${chatImg64}` : null);
  let content = chatImg64 ? [{ type:'image_url', image_url:{ url:`data:${chatImgType};base64,${chatImg64}` } }, { type:'text', text: text || 'Analyze this image in detail.' }] : text;
  msgs.push({ role:'user', content });
  input.value = ''; resize(input); removeImg();
  busy = true; document.getElementById('send').disabled = true;
  const tid = showTyping();
  try {
    const res = await puter.ai.chat(msgs, { model:'z-ai/glm-5.2', system: SYS });
    removeEl(tid);
    const reply = res?.message?.content || res?.content || String(res);
    addMsg('ai', reply); msgs.push({ role:'assistant', content: reply });
    saveHist(text || 'Image', reply);
  } catch(e) { removeEl(tid); addMsg('ai', `⚠️ Error: ${e.message || e}`); }
  busy = false; document.getElementById('send').disabled = false;
}
function addMsg(role, text, imgSrc = null) {
  const c = document.getElementById('messages');
  const row = document.createElement('div');
  row.className = `msg-row ${role}`;
  let body = imgSrc ? `<img class="msg-img" src="${imgSrc}">` : '';
  body += fmt(text);
  row.innerHTML = `<div class="msg-inner"><div class="msg-avatar">${role==='user'?'👤':'AV'}</div><div class="msg-body">${body}</div></div>`;
  c.appendChild(row); c.scrollTop = c.scrollHeight;
}
function showTyping() {
  const c = document.getElementById('messages');
  const id = 'ty' + Date.now();
  const row = document.createElement('div');
  row.className = 'msg-row ai typing-row'; row.id = id;
  row.innerHTML = `<div class="msg-inner"><div class="msg-avatar">AV</div><div class="msg-body"><div class="typing-dot"></div><div class="typing-dot"></div><div class="typing-dot"></div></div></div>`;
  c.appendChild(row); c.scrollTop = c.scrollHeight; return id;
}
function removeEl(id) { document.getElementById(id)?.remove(); }
function fmt(t) {
  return t.replace(/```(\w*)\n?([\s\S]*?)```/g, (_,l,c) => `<pre><code>${esc(c.trim())}</code></pre>`).replace(/`([^`]+)`/g, '<code>$1</code>').replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>').replace(/\*(.*?)\*/g, '<em>$1</em>').replace(/^### (.+)$/gm, '<strong style="display:block;margin:8px 0 3px;font-size:14px">$1</strong>').replace(/^## (.+)$/gm, '<strong style="display:block;margin:10px 0 4px;font-size:15px">$1</strong>').replace(/^# (.+)$/gm, '<strong style="display:block;margin:12px 0 5px;font-size:17px">$1</strong>').replace(/^- (.+)$/gm, '• $1').replace(/\n/g, '<br>');
}
function esc(t) { return t.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }
function attachImg(inp) {
  const f = inp.files[0]; if (!f) return;
  const r = new FileReader();
  r.onload = e => { const src = e.target.result; chatImg64 = src.split(',')[1]; chatImgType = f.type; document.getElementById('thumb-img').src = src; document.getElementById('thumb-row').style.display = 'block'; };
  r.readAsDataURL(f);
}
function removeImg() { chatImg64 = null; chatImgType = null; document.getElementById('thumb-row').style.display = 'none'; document.getElementById('thumb-img').src = ''; document.getElementById('file-in').value = ''; }
function onDrop(e) { e.preventDefault(); document.getElementById('drop-zone').classList.remove('over'); const f = e.dataTransfer.files[0]; if (f?.type.startsWith('image/')) loadFile(f); }
function onDragOver(e) { e.preventDefault(); document.getElementById('drop-zone').classList.add('over'); }
function onDragLeave() { document.getElementById('drop-zone').classList.remove('over'); }
function loadVis(inp) { if (inp.files[0]) loadFile(inp.files[0]); }
function loadFile(f) {
  const r = new FileReader();
  r.onload = e => { const src = e.target.result; visImg64 = src.split(',')[1]; visImgType = f.type; document.getElementById('vis-img').src = src; document.getElementById('drop-zone').style.display = 'none'; document.getElementById('vis-preview').style.display = 'flex'; document.getElementById('vis-preview').style.flexDirection = 'column'; document.getElementById('vis-result').style.display = 'none'; };
  r.readAsDataURL(f);
}
async function analyzeVis(q) {
  if (!visImg64) return toast('Upload an image first');
  const box = document.getElementById('vis-result');
  box.style.display = 'block';
  box.innerHTML = '<div style="display:flex;gap:4px;padding:4px 0"><div class="typing-dot"></div><div class="typing-dot"></div><div class="typing-dot"></div></div>';
  try {
    const res = await puter.ai.chat([{ role:'user', content:[{ type:'image_url', image_url:{ url:`data:${visImgType};base64,${visImg64}` }},{ type:'text', text: q || 'Analyze this image in detail.' }]}], { model:'z-ai/glm-5.2' });
    box.innerHTML = fmt(res?.message?.content || res?.content || String(res));
  } catch(e) { box.innerHTML = `⚠️ Failed: ${e.message || e}`; }
}
function resetVis() { visImg64 = null; visImgType = null; document.getElementById('drop-zone').style.display = 'flex'; document.getElementById('vis-preview').style.display = 'none'; document.getElementById('vis-file').value = ''; }
function saveHist(user, ai) {
  if (!user) return;
  try { const h = JSON.parse(localStorage.getItem('aevon_h') || '[]'); h.unshift({ id: Date.now(), p: user.slice(0, 80), user, ai, t: new Date().toLocaleString() }); localStorage.setItem('aevon_h', JSON.stringify(h.slice(0, 50))); } catch(e) {}
}
function loadHist() {
  const list = document.getElementById('hist-list');
  let h = []; try { h = JSON.parse(localStorage.getItem('aevon_h') || '[]'); } catch(e) {}
  if (!h.length) { list.innerHTML = '<div class="empty">No history yet. Start chatting!</div>'; return; }
  list.innerHTML = h.map(i => `<div class="h-item" onclick="reloadChat(${i.id})"><div class="h-preview">${esc(i.p)}${i.p.length>=80?'...':''}</div><div class="h-time">${i.t}</div></div>`).join('');
}
function reloadChat(id) {
  try {
    const h = JSON.parse(localStorage.getItem('aevon_h') || '[]');
    const item = h.find(i => i.id === id); if (!item) return;
    newChat(); msgs = [{ role:'user', content: item.user }, { role:'assistant', content: item.ai }];
    document.getElementById('welcome')?.remove(); addMsg('user', item.user); addMsg('ai', item.ai);
    switchTo('chat', document.getElementById('nb-chat')); toast('Chat loaded');
  } catch(e) {}
}
function toast(msg) { const t = document.getElementById('toast'); t.textContent = msg; t.classList.add('show'); setTimeout(() => t.classList.remove('show'), 2200); }
</script>
</body>
</html>
