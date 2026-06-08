
<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500&family=Syne:wght@400;500;700&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
.readme{font-family:'Syne',sans-serif;color:var(--color-text-primary);padding:2rem 1.5rem;max-width:700px}
.hero{text-align:center;padding:2.5rem 0 2rem;border-bottom:0.5px solid var(--color-border-tertiary);margin-bottom:2rem}
.avatar-ring{width:88px;height:88px;border-radius:50%;border:2px solid #534AB7;display:flex;align-items:center;justify-content:center;margin:0 auto 1rem;background:var(--color-background-secondary);font-size:28px;font-weight:700;color:#534AB7;opacity:0;transform:scale(0.7);transition:opacity 0.5s,transform 0.5s}
.avatar-ring.show{opacity:1;transform:scale(1)}
.hero-name{font-size:26px;font-weight:700;letter-spacing:-0.5px;opacity:0;transform:translateY(12px);transition:opacity 0.5s 0.15s,transform 0.5s 0.15s}
.hero-name.show{opacity:1;transform:translateY(0)}
.typing-wrap{font-family:'Fira Code',monospace;font-size:13px;color:var(--color-text-secondary);margin:0.5rem 0 1rem;min-height:20px}
.cursor{display:inline-block;width:2px;height:14px;background:#534AB7;vertical-align:middle;animation:blink 1s step-end infinite}
@keyframes blink{50%{opacity:0}}
.badges{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:1rem;opacity:0;transition:opacity 0.5s 0.4s}
.badges.show{opacity:1}
.badge{display:inline-flex;align-items:center;gap:5px;padding:5px 12px;border-radius:20px;font-size:12px;font-weight:500;text-decoration:none;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);transition:border-color 0.2s,color 0.2s}
.badge:hover{border-color:#534AB7;color:#534AB7}
.badge .dot{width:7px;height:7px;border-radius:50%}
.section{margin-bottom:2rem;opacity:0;transform:translateY(16px);transition:opacity 0.5s,transform 0.5s}
.section.show{opacity:1;transform:translateY(0)}
.sec-head{display:flex;align-items:center;gap:8px;font-size:13px;font-weight:500;color:var(--color-text-secondary);text-transform:uppercase;letter-spacing:1px;margin-bottom:1rem}
.sec-head::after{content:'';flex:1;height:0.5px;background:var(--color-border-tertiary)}
.about-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(0,1fr));gap:10px}
.about-card{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:0.75rem 1rem}
.about-card .label{font-size:11px;color:var(--color-text-tertiary);margin-bottom:3px}
.about-card .val{font-size:13px;font-weight:500;color:var(--color-text-primary)}
.skill-group{margin-bottom:1.25rem}
.skill-group-name{font-size:12px;color:var(--color-text-tertiary);margin-bottom:8px;font-family:'Fira Code',monospace}
.skill-row{display:flex;align-items:center;gap:10px;margin-bottom:6px}
.skill-name{font-size:13px;color:var(--color-text-secondary);min-width:90px}
.skill-bar-bg{flex:1;height:5px;background:var(--color-background-secondary);border-radius:3px;overflow:hidden}
.skill-bar{height:100%;border-radius:3px;width:0;transition:width 1.2s cubic-bezier(.4,0,.2,1)}
.skill-pct{font-size:11px;font-family:'Fira Code',monospace;color:var(--color-text-tertiary);min-width:28px;text-align:right}
.proj-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:10px}
.proj-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1rem;cursor:default;transition:border-color 0.2s,transform 0.2s}
.proj-card:hover{border-color:#534AB7;transform:translateY(-2px)}
.proj-icon{font-size:20px;margin-bottom:8px;color:#534AB7}
.proj-title{font-size:13px;font-weight:500;margin-bottom:4px}
.proj-desc{font-size:12px;color:var(--color-text-secondary);line-height:1.5}
.proj-tags{display:flex;flex-wrap:wrap;gap:4px;margin-top:8px}
.proj-tag{font-size:10px;font-family:'Fira Code',monospace;padding:2px 7px;border-radius:4px;background:#EEEDFE;color:#534AB7}
.cert-list{display:flex;flex-direction:column;gap:8px}
.cert-item{display:flex;align-items:center;gap:10px;font-size:13px;color:var(--color-text-secondary)}
.cert-item i{color:#1D9E75;font-size:16px;flex-shrink:0}
.stats-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:10px}
.stat-card{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:0.75rem 1rem;text-align:center}
.stat-num{font-size:22px;font-weight:700;color:#534AB7;font-family:'Fira Code',monospace}
.stat-label{font-size:11px;color:var(--color-text-tertiary);margin-top:2px}
.footer{text-align:center;padding:1.5rem 0 0.5rem;font-size:12px;font-family:'Fira Code',monospace;color:var(--color-text-tertiary)}
</style>

<h2 class="sr-only">Bharanidharan's GitHub profile README preview with animations</h2>

<div class="readme">

<div class="hero">
  <div class="avatar-ring" id="av">BM</div>
  <div class="hero-name" id="hn">Bharanidharan M</div>
  <div class="typing-wrap"><span id="typed"></span><span class="cursor"></span></div>
  <div class="badges" id="bdg">
    <a class="badge" href="https://linkedin.com/in/bharanidharan"><span class="dot" style="background:#0A66C2"></span>LinkedIn</a>
    <a class="badge" href="https://leetcode.com/u/Bharanidharan2/"><span class="dot" style="background:#FFA116"></span>LeetCode</a>
    <a class="badge" href="mailto:bharanidharanmurugesan@outlook.com"><span class="dot" style="background:#0078D4"></span>Email</a>
    <a class="badge" href="https://github.com/bharanidharan22"><span class="dot" style="background:#534AB7"></span>GitHub</a>
  </div>
</div>

<div class="section" id="s1">
  <div class="sec-head"><i class="ti ti-user" aria-hidden="true"></i> about</div>
  <div class="about-grid">
    <div class="about-card"><div class="label">degree</div><div class="val">B.E. CSE — CGPA 7.73</div></div>
    <div class="about-card"><div class="label">graduating</div><div class="val">2026, Sri Eshwar CE</div></div>
    <div class="about-card"><div class="label">internship</div><div class="val">MERN Stack @ Better Tomorrow</div></div>
    <div class="about-card"><div class="label">research</div><div class="val">Published @ ICWCIE-2026 + Springer</div></div>
  </div>
</div>

<div class="section" id="s2">
  <div class="sec-head"><i class="ti ti-code" aria-hidden="true"></i> skills</div>
  <div class="skill-group">
    <div class="skill-group-name">// frontend</div>
    <div class="skill-row"><span class="skill-name">React.js</span><div class="skill-bar-bg"><div class="skill-bar" data-w="90" style="background:#534AB7"></div></div><span class="skill-pct">90%</span></div>
    <div class="skill-row"><span class="skill-name">Next.js</span><div class="skill-bar-bg"><div class="skill-bar" data-w="78" style="background:#534AB7"></div></div><span class="skill-pct">78%</span></div>
    <div class="skill-row"><span class="skill-name">TypeScript</span><div class="skill-bar-bg"><div class="skill-bar" data-w="72" style="background:#534AB7"></div></div><span class="skill-pct">72%</span></div>
  </div>
  <div class="skill-group">
    <div class="skill-group-name">// backend</div>
    <div class="skill-row"><span class="skill-name">Node.js</span><div class="skill-bar-bg"><div class="skill-bar" data-w="85" style="background:#1D9E75"></div></div><span class="skill-pct">85%</span></div>
    <div class="skill-row"><span class="skill-name">Express.js</span><div class="skill-bar-bg"><div class="skill-bar" data-w="82" style="background:#1D9E75"></div></div><span class="skill-pct">82%</span></div>
    <div class="skill-row"><span class="skill-name">MongoDB</span><div class="skill-bar-bg"><div class="skill-bar" data-w="80" style="background:#1D9E75"></div></div><span class="skill-pct">80%</span></div>
  </div>
  <div class="skill-group">
    <div class="skill-group-name">// ml / dl</div>
    <div class="skill-row"><span class="skill-name">PyTorch</span><div class="skill-bar-bg"><div class="skill-bar" data-w="80" style="background:#D85A30"></div></div><span class="skill-pct">80%</span></div>
    <div class="skill-row"><span class="skill-name">Scikit-learn</span><div class="skill-bar-bg"><div class="skill-bar" data-w="75" style="background:#D85A30"></div></div><span class="skill-pct">75%</span></div>
    <div class="skill-row"><span class="skill-name">Python</span><div class="skill-bar-bg"><div class="skill-bar" data-w="88" style="background:#D85A30"></div></div><span class="skill-pct">88%</span></div>
  </div>
</div>

<div class="section" id="s3">
  <div class="sec-head"><i class="ti ti-rocket" aria-hidden="true"></i> projects</div>
  <div class="proj-grid">
    <div class="proj-card">
      <div class="proj-icon"><i class="ti ti-brain" aria-hidden="true"></i></div>
      <div class="proj-title">SIFN — Pet Disease Detection</div>
      <div class="proj-desc">Multimodal AI fusing symptom data + medical images. Published at ICWCIE-2026 & Springer LNEE.</div>
      <div class="proj-tags"><span class="proj-tag">PyTorch</span><span class="proj-tag">DL</span><span class="proj-tag">Research</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-icon"><i class="ti ti-activity" aria-hidden="true"></i></div>
      <div class="proj-title">Health Tracker App</div>
      <div class="proj-desc">Full-stack app with JWT auth, scheduled alerts, and full CRUD schedule management.</div>
      <div class="proj-tags"><span class="proj-tag">React</span><span class="proj-tag">Node.js</span><span class="proj-tag">MongoDB</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-icon"><i class="ti ti-photo" aria-hidden="true"></i></div>
      <div class="proj-title">Image Classification CNN</div>
      <div class="proj-desc">CNN on CIFAR-10 with modular design and accuracy visualizations via Matplotlib.</div>
      <div class="proj-tags"><span class="proj-tag">PyTorch</span><span class="proj-tag">CIFAR-10</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-icon"><i class="ti ti-shield-lock" aria-hidden="true"></i></div>
      <div class="proj-title">Web Vulnerability Scanner</div>
      <div class="proj-desc">Python tool automating detection of common web security vulnerabilities.</div>
      <div class="proj-tags"><span class="proj-tag">Python</span><span class="proj-tag">Security</span></div>
    </div>
  </div>
</div>

<div class="section" id="s4">
  <div class="sec-head"><i class="ti ti-chart-bar" aria-hidden="true"></i> at a glance</div>
  <div class="stats-row">
    <div class="stat-card"><div class="stat-num" id="c1">0</div><div class="stat-label">repositories</div></div>
    <div class="stat-card"><div class="stat-num" id="c2">0</div><div class="stat-label">certifications</div></div>
    <div class="stat-card"><div class="stat-num" id="c3">0</div><div class="stat-label">research papers</div></div>
    <div class="stat-card"><div class="stat-num" id="c4">0.0</div><div class="stat-label">cgpa</div></div>
  </div>
</div>

<div class="section" id="s5">
  <div class="sec-head"><i class="ti ti-certificate" aria-hidden="true"></i> certifications</div>
  <div class="cert-list">
    <div class="cert-item"><i class="ti ti-check" aria-hidden="true"></i>Java Programming – Beginner to Master — Udemy (2023)</div>
    <div class="cert-item"><i class="ti ti-check" aria-hidden="true"></i>Data Structures & Algorithms (C & C++) — Udemy (2023)</div>
    <div class="cert-item"><i class="ti ti-check" aria-hidden="true"></i>AWS S3 Developer — AWS Educate (2024)</div>
    <div class="cert-item"><i class="ti ti-check" aria-hidden="true"></i>Data Visualization with Power BI — Great Learning (2024)</div>
    <div class="cert-item"><i class="ti ti-check" aria-hidden="true"></i>Getting Started with Microsoft Excel — Udemy (2025)</div>
  </div>
</div>

<div class="footer">"build things that matter. ship code that lasts." — bharanidharan22</div>

</div>

<script>
const titles=["Full-Stack MERN Developer","ML / Deep Learning Engineer","Published AI Researcher","Open Source Builder"];
let ti=0,ci=0,deleting=false;
const el=document.getElementById('typed');
function type(){
  const t=titles[ti];
  if(!deleting){el.textContent=t.slice(0,ci+1);ci++;if(ci===t.length){deleting=true;setTimeout(type,1800);return;}}
  else{el.textContent=t.slice(0,ci-1);ci--;if(ci===0){deleting=false;ti=(ti+1)%titles.length;}}
  setTimeout(type,deleting?40:80);
}
setTimeout(type,600);

function show(id,delay){
  setTimeout(()=>{const e=document.getElementById(id);if(e)e.classList.add('show');},delay);
}
show('av',100);show('hn',250);show('bdg',450);
['s1','s2','s3','s4','s5'].forEach((id,i)=>show(id,600+i*180));

function animBars(){
  document.querySelectorAll('.skill-bar').forEach(b=>{
    const w=b.getAttribute('data-w');
    setTimeout(()=>{b.style.width=w+'%';},800);
  });
}
setTimeout(animBars,900);

function countUp(id,target,decimals,duration){
  const el=document.getElementById(id);
  if(!el)return;
  const start=Date.now();
  const tick=()=>{
    const p=Math.min((Date.now()-start)/duration,1);
    const val=target*p;
    el.textContent=decimals?val.toFixed(1):Math.round(val);
    if(p<1)requestAnimationFrame(tick);
  };
  tick();
}
setTimeout(()=>{
  countUp('c1',11,0,1000);
  countUp('c2',5,0,1000);
  countUp('c3',1,0,800);
  countUp('c4',7.73,1,1200);
},1200);
</script>
