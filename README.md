[scale.html](https://github.com/user-attachments/files/35419111/scale.html)
# kioelk2.github.io<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="robots" content="noindex, nofollow">
<title>气质类型小测｜陈会昌气质类型量表</title>
<style>
:root{
  --navy:#1f3864; --blue:#2e5c8a; --warm:#c55a11; --orange:#e8a33d;
  --ink:#262626; --gray:#595959; --mid:#7f7f7f; --line:#d9e1ea;
  --bg:#f7f9fc; --card:#ffffff; --pale:#eef3fa; --pale-warm:#fdf2e9;
  --green:#548235; --red:#c0392b; --shadow:0 10px 30px rgba(31,56,100,.08);
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;padding:0;width:100%;overflow-x:hidden}
body{
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI","PingFang SC","Hiragino Sans GB","Microsoft YaHei",sans-serif;
  background:var(--bg); color:var(--ink); line-height:1.65; min-height:100vh;
}
.wrap{width:100%;max-width:680px;margin:0 auto;padding:18px 16px 34px}
.top{display:flex;align-items:center;justify-content:space-between;gap:10px;padding:6px 2px 12px;color:var(--mid);font-size:12px;min-width:0}
.top .brand{font-weight:700;color:var(--navy);letter-spacing:.04em;min-width:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.card{width:100%;background:var(--card);border:1px solid var(--line);border-radius:16px;box-shadow:var(--shadow);padding:22px 20px}
.hidden{display:none !important}
h1{font-size:26px;line-height:1.3;color:var(--navy);margin:0 0 8px;letter-spacing:.01em}
h2{font-size:20px;line-height:1.35;color:var(--navy);margin:0 0 10px}
p{margin:0 0 12px;overflow-wrap:anywhere}
.small{font-size:12.5px;color:var(--mid)}
.tag-row{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0 16px}
.tag{display:inline-flex;align-items:center;gap:6px;background:var(--pale);color:var(--blue);font-size:12px;font-weight:600;padding:6px 10px;border-radius:999px}
.tag.warm{background:var(--pale-warm);color:var(--warm)}
.rule{height:1px;background:var(--line);margin:16px 0}
.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:8px;border:none;border-radius:12px;
  padding:13px 20px;font-size:15px;font-weight:700;cursor:pointer;transition:transform .12s ease,opacity .12s ease;
  font-family:inherit;
}
.btn:active{transform:scale(.98)}
.btn-primary{background:var(--navy);color:#fff;width:100%}
.btn-primary:disabled{opacity:.35;cursor:not-allowed}
.btn-ghost{background:transparent;color:var(--blue);border:1px solid var(--line)}
.btn-warm{background:var(--warm);color:#fff}
.btn-row{display:flex;gap:10px;margin-top:18px}
.btn-row .btn{flex:1}
.notice{background:var(--pale-warm);border-left:4px solid var(--orange);border-radius:8px;padding:12px 14px;color:var(--gray);font-size:12.5px}
details{background:#fafbfd;border:1px solid var(--line);border-radius:12px;padding:12px 14px;margin-top:14px}
summary{cursor:pointer;color:var(--blue);font-weight:700;font-size:13px;outline:none}
details p, details li{font-size:12.5px;color:var(--gray)}
details ul{padding-left:18px;margin:8px 0 0}
.progress-head{display:flex;justify-content:space-between;align-items:center;color:var(--mid);font-size:12px;font-weight:600;margin-bottom:8px}
.progress-track{height:8px;background:#e8eef6;border-radius:999px;overflow:hidden;margin-bottom:20px}
.progress-fill{height:100%;width:0;background:linear-gradient(90deg,var(--blue),var(--orange));border-radius:999px;transition:width .18s ease}
.q-index{font-size:12px;font-weight:800;color:var(--warm);letter-spacing:.06em;margin-bottom:8px}
.q-text{font-size:21px;line-height:1.55;font-weight:700;color:var(--navy);margin:0 0 20px;min-height:96px;overflow-wrap:anywhere}
.options{display:grid;gap:10px}
.opt{
  display:flex;align-items:center;gap:12px;width:100%;text-align:left;background:#fff;border:1.5px solid var(--line);
  border-radius:12px;padding:13px 14px;font-size:15px;color:var(--ink);cursor:pointer;font-family:inherit;
  transition:border-color .12s ease,background .12s ease,transform .12s ease;
}
.opt:active{transform:scale(.995)}
.opt .dot{width:20px;height:20px;border-radius:50%;border:2px solid #c7d3e2;flex:0 0 20px;display:flex;align-items:center;justify-content:center;font-size:11px;color:#fff}
.opt .lab{flex:1}
.opt .val{font-size:11.5px;color:var(--mid);font-weight:700}
.opt.selected{border-color:var(--navy);background:var(--pale)}
.opt.selected .dot{background:var(--navy);border-color:var(--navy)}
.nav-row{display:flex;gap:10px;margin-top:20px}
.nav-row .btn{flex:1}
.nav-row .btn-primary{width:auto}
.footnote{text-align:center;font-size:11.5px;color:var(--mid);margin-top:18px;line-height:1.7}
.result-hero{text-align:center;padding:6px 0 2px}
.result-label{font-size:12px;color:var(--mid);letter-spacing:.12em;font-weight:700}
.result-type{font-size:28px;color:var(--navy);font-weight:800;line-height:1.35;margin:8px 0 4px}
.result-level{display:inline-block;background:var(--pale-warm);color:var(--warm);font-size:12px;font-weight:700;padding:5px 12px;border-radius:999px}
.bars{margin:20px 0 8px;display:grid;gap:14px}
.bar-row .bar-head{display:flex;justify-content:space-between;align-items:baseline;font-size:13px;font-weight:700;color:var(--ink);margin-bottom:5px}
.bar-head .score{font-size:14px;color:var(--navy)}
.track{position:relative;height:12px;background:#edf2f8;border-radius:999px;overflow:hidden}
.track .zero{position:absolute;left:50%;top:0;bottom:0;width:1px;background:#c8d4e3;z-index:2}
.track .fill{position:absolute;top:0;bottom:0;border-radius:999px;z-index:1}
.bar-note{font-size:11.5px;color:var(--mid);margin-top:4px}
.result-note{background:var(--pale-warm);border-radius:10px;padding:12px 14px;font-size:12.5px;color:var(--gray);margin-top:14px}
.help{background:var(--pale);border-radius:10px;padding:12px 14px;font-size:12.5px;color:var(--gray);margin-top:12px}
.help b{color:var(--navy)}
.kv{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:10px}
.kv div{background:#fff;border:1px solid var(--line);border-radius:8px;padding:8px 10px;font-size:12px;color:var(--gray)}
.kv b{display:block;color:var(--navy);font-size:13px}
@media (min-width:560px){
  .wrap{padding-top:28px}
  .card{padding:28px 30px}
  .q-text{min-height:110px}
}
</style>
</head>
<body>
<div class="wrap">
  <div class="top"><span class="brand">与“社恐”和解 · 让连接发生</span><span>匿名 · 不收集数据</span></div>

  <!-- 开始页 -->
  <section id="start" class="card">
    <h1>气质类型小测</h1>
    <p class="small">陈会昌气质类型量表 · 60题 · 约6—8分钟</p>
    <div class="tag-row">
      <span class="tag">匿名作答</span>
      <span class="tag">自动计分</span>
      <span class="tag warm">结果仅自己可见</span>
    </div>
    <p>这个量表帮助你大致了解自己更接近哪一类气质倾向：胆汁质、多血质、黏液质、抑郁质。气质没有好坏，多数人是混合型。</p>
    <div class="notice">这不是心理疾病诊断，也不能替代专业评估。结果只作自我觉察的参考，不要用它给自己或同学贴标签。</div>
    <details>
      <summary>计分与隐私说明</summary>
      <p>共60题，每题5级计分：非常不符合-2、不太符合-1、中立0、比较符合+1、非常符合+2。四个维度各15题，分别相加，单维范围-30到+30。</p>
      <p>本网页没有后台，不上传、不保存任何作答；关闭页面后作答即清除。请放心按第一感觉作答。</p>
    </details>
    <div class="btn-row">
      <button class="btn btn-primary" id="startBtn">开始作答</button>
    </div>
    <div class="footnote">建议在安静环境下独立完成；不必反复思考，不要与他人商量。</div>
  </section>

  <!-- 答题页 -->
  <section id="quiz" class="card hidden">
    <div class="progress-head"><span id="progressText">已答 0 / 60</span><span id="progressPct">0%</span></div>
    <div class="progress-track"><div class="progress-fill" id="progressFill"></div></div>
    <div class="q-index" id="qIndex">第 1 题 / 共 60 题</div>
    <div class="q-text" id="qText"></div>
    <div class="options" id="options"></div>
    <div class="nav-row">
      <button class="btn btn-ghost" id="prevBtn">上一题</button>
      <button class="btn btn-primary" id="nextBtn">下一题</button>
    </div>
    <div class="footnote">匿名 · 无后台 · 不保存 · 结果仅自己可见</div>
  </section>

  <!-- 结果页 -->
  <section id="result" class="card hidden">
    <div class="result-hero">
      <div class="result-label">你 的 气 质 倾 向</div>
      <div class="result-type" id="resultType">—</div>
      <span class="result-level" id="resultLevel">—</span>
    </div>
    <div class="bars" id="bars"></div>
    <div class="result-note">
      气质类型没有好坏，混合型、倾向不明显都很常见。这个结果只是课堂自我觉察的参考，不是心理疾病诊断，也不能替代专业评估。
    </div>
    <details>
      <summary>这个结果是怎么算出来的？</summary>
      <p>每题从-2到+2计分，四个维度各15题相加，得到四个分数。某维明显高于其他三维（高4分以上）时，判为相应类型倾向；两维接近且明显高于其他两维时，判为混合型；三维接近且均高于第四维时，判为三型混合。具体判定以标准版本为准。</p>
      <p>分数会受当时情绪、睡眠、环境等影响；一次结果不能代表“你是什么人”。</p>
    </details>
    <div class="help">
      <b>需要聊一聊？</b><br>
      学校心理健康教育中心（地址/预约见学校资源卡）· 辅导员李龙梅老师 · 班级心理委员龚文韬 · 全国心理援助热线 12356（24小时）。<br>
      紧急情况请拨打 110 / 120。
    </div>
    <div class="btn-row">
      <button class="btn btn-ghost" id="againBtn">重新作答</button>
      <button class="btn btn-warm" id="clearBtn">关闭并清除</button>
    </div>
    <div class="footnote">不需要把结果发给任何人，也不要在群里比较分数与类型。</div>
  </section>
</div>

<script>
const ITEMS = [
  "做事力求稳妥，不做无把握的事。",
  "遇到可气的事就怒不可遏，想把心里话说出来才痛快。",
  "宁肯一个人干事，不愿很多人在一起。",
  "到一个新的环境很快就能适应。",
  "厌恶那些强烈的刺激，如尖叫、噪声、危险镜头等。",
  "和人争吵时，总是先发制人，喜欢挑衅。",
  "喜欢安静的环境。",
  "善于和人交往。",
  "羡慕那种善于克制自己的感情的人。",
  "生活有规律，很少违背作息制度。",
  "在多数情况下情绪是乐观的。",
  "碰到陌生人觉得很拘束。",
  "遇到令人气愤的事，能很好地自我克制。",
  "做事总是有旺盛的精力。",
  "遇到问题常常举棋不定，优柔寡断。",
  "在人群中从不觉得过分地拘谨。",
  "情绪高昂时，觉得干什么都有趣；情绪低落时，又觉得干什么都没有意思。",
  "当注意力集中一个事物时，别的事很难使我分心。",
  "理解问题总是比别人快。",
  "碰到危险情景时，常有一种极度的恐怖感。",
  "对学习、工作、事业怀有很高的热情。",
  "能够长时间做枯燥、单调的工作。",
  "符合情趣的事情，干起来劲头十足，否则就不想干。",
  "一点小事就能引起情绪波动。",
  "讨厌那种需要耐心、细致的工作。",
  "与人交往不卑不亢。",
  "喜欢参加热烈的活动。",
  "爱看感情细腻、描写人物内心活动的文学作品。",
  "工作学习时间长了，常感到厌倦。",
  "不喜欢长时间谈论一个问题，愿意实际动手干。",
  "宁愿侃侃而谈，不愿窃窃私语。",
  "别人说我总是闷闷不乐。",
  "理解问题常比别人慢一些。",
  "疲倦时只要短暂的休息就能精神抖擞，重新投入工作。",
  "心里有话宁愿自己想，不愿说出来。",
  "认准一个目标就希望尽快实现，不达目的，誓不罢休。",
  "学习、工作同样一段时间后，常比别人更疲劳。",
  "做事有些莽撞，常常不考虑后果。",
  "老师或师傅讲授新知识、技术时，总希望他讲慢些，多重复几遍。",
  "能够很快地忘记那些不愉快的事。",
  "做作业或完成一件工作总比别人花的时间多。",
  "喜欢运动量大的剧烈体育活动，或参加各种文艺活动。",
  "不能很快地将注意力从一件事情转移到另一件事情上去。",
  "接受一个任务后，就希望把它迅速解决。",
  "认为墨守陈规比冒风险强些。",
  "能够同时注意几件事。",
  "当我闷闷不乐时，别人很难使我高兴起来。",
  "爱看情节跌宕起伏、激动人心的小说。",
  "对工作抱认真、严谨、始终如一的态度。",
  "和周围人们的关系总是相处不好。",
  "喜欢复习学过的知识、重复已掌握的工作。",
  "希望做变化大、花样多的工作。",
  "小时候会背的诗歌，我似乎比别人记得清楚。",
  "别人说我“出语伤人”，可我不觉得这样。",
  "在体育活动中，常因反应慢而落后。",
  "反应敏捷，头脑机智。",
  "喜欢有条理而不甚麻烦的工作。",
  "兴奋的事常使我失眠。",
  "老师讲新概念，常常听不懂，但弄懂以后很难忘记。",
  "假如工作枯燥无味，马上就会情绪低落。"
];
const DIMS = {
  "bile": {
    "name": "胆汁质",
    "color": "#c0392b",
    "items": [
      2,
      6,
      9,
      14,
      17,
      21,
      27,
      31,
      36,
      38,
      42,
      48,
      50,
      54,
      58
    ],
    "desc": "精力旺盛、直率热情、反应快、情绪易冲动"
  },
  "blood": {
    "name": "多血质",
    "color": "#c56a12",
    "items": [
      4,
      8,
      11,
      16,
      19,
      23,
      25,
      29,
      34,
      40,
      44,
      46,
      52,
      56,
      60
    ],
    "desc": "活泼灵活、善交际、兴趣易转移"
  },
  "phlegm": {
    "name": "黏液质",
    "color": "#2e5c8a",
    "items": [
      1,
      7,
      10,
      13,
      18,
      22,
      26,
      30,
      33,
      39,
      43,
      45,
      49,
      55,
      57
    ],
    "desc": "安静稳重、耐受、反应较慢"
  },
  "melancholic": {
    "name": "抑郁质",
    "color": "#4f7a35",
    "items": [
      3,
      5,
      12,
      15,
      20,
      24,
      28,
      32,
      35,
      37,
      41,
      47,
      51,
      53,
      59
    ],
    "desc": "敏感深刻、内倾、体验深"
  }
};
const LETTERS = ["A","B","C","D","E"];
const OPTIONS = [
  {v:-2, label:"非常不符合", short:"-2"},
  {v:-1, label:"不太符合", short:"-1"},
  {v:0,  label:"中立 / 说不准", short:"0"},
  {v:1,  label:"比较符合", short:"+1"},
  {v:2,  label:"非常符合", short:"+2"}
];

let answers = new Array(ITEMS.length).fill(null);
let current = 0;
let autoTimer = null;

const $ = (id) => document.getElementById(id);
const startEl = $("start"), quizEl = $("quiz"), resultEl = $("result");

function show(el){
  [startEl, quizEl, resultEl].forEach(x => x.classList.add("hidden"));
  el.classList.remove("hidden");
  window.scrollTo({top:0, behavior:"smooth"});
}

function answeredCount(){ return answers.filter(v => v !== null).length; }

function updateProgress(){
  const n = answeredCount();
  const pct = Math.round(n / ITEMS.length * 100);
  $("progressText").textContent = `已答 ${n} / ${ITEMS.length}`;
  $("progressPct").textContent = pct + "%";
  $("progressFill").style.width = pct + "%";
}

function renderQuestion(){
  const q = ITEMS[current];
  $("qIndex").textContent = `第 ${current + 1} 题 / 共 ${ITEMS.length} 题`;
  $("qText").textContent = q;
  const box = $("options");
  box.innerHTML = "";
  OPTIONS.forEach((o, idx) => {
    const btn = document.createElement("button");
    btn.type = "button";
    btn.className = "opt" + (answers[current] === o.v ? " selected" : "");
    btn.setAttribute("aria-label", `${LETTERS[idx]} ${o.label}`);
    btn.innerHTML = `<span class="dot">${answers[current] === o.v ? "✓" : ""}</span><span class="lab">${LETTERS[idx]}　${o.label}</span><span class="val">${o.short}</span>`;
    btn.addEventListener("click", () => choose(o.v));
    box.appendChild(btn);
  });
  $("prevBtn").disabled = current === 0;
  $("nextBtn").textContent = current === ITEMS.length - 1 ? "提交结果" : "下一题";
  updateProgress();
}

function choose(value){
  if (autoTimer) { clearTimeout(autoTimer); autoTimer = null; }
  answers[current] = value;
  renderQuestion();
  if (current < ITEMS.length - 1){
    autoTimer = setTimeout(() => {
      current += 1;
      renderQuestion();
      window.scrollTo({top:0, behavior:"smooth"});
    }, 180);
  }
}

function goNext(){
  if (answers[current] === null){
    alert("这一题还没有选择，请先选一个最接近的答案。");
    return;
  }
  if (current < ITEMS.length - 1){
    current += 1;
    renderQuestion();
    window.scrollTo({top:0, behavior:"smooth"});
  } else {
    submit();
  }
}

function goPrev(){
  if (current > 0){
    current -= 1;
    renderQuestion();
    window.scrollTo({top:0, behavior:"smooth"});
  }
}

function calcScores(){
  const scores = {};
  for (const key in DIMS){
    let s = 0;
    for (const n of DIMS[key].items){
      s += (answers[n - 1] === null ? 0 : answers[n - 1]);
    }
    scores[key] = s;
  }
  return scores;
}

function calcType(scores){
  const arr = Object.keys(DIMS).map(k => ({
    key:k, name:DIMS[k].name, color:DIMS[k].color, score:scores[k], desc:DIMS[k].desc
  })).sort((a,b) => b.score - a.score);
  const [a,b,c,d] = arr;
  let type, level;
  if (a.score >= 20) level = "较明显";
  else if (a.score >= 10) level = "中等";
  else level = "较弱";

  if (a.score - b.score >= 4){
    type = a.name + "型";
  } else if (a.score - b.score <= 3 && b.score - c.score >= 4){
    type = a.name + "—" + b.name + "混合型";
  } else if (b.score - c.score <= 3 && c.score - d.score >= 4){
    type = a.name + "—" + b.name + "—" + c.name + "混合型";
  } else {
    type = "混合型（倾向不明显）";
  }
  return {arr, type, level, top:a};
}

function renderResult(){
  const scores = calcScores();
  const r = calcType(scores);
  $("resultType").textContent = r.type;
  $("resultLevel").textContent = "倾向强度：" + r.level;

  const bars = $("bars");
  bars.innerHTML = "";
  r.arr.forEach(item => {
    const pct = (item.score + 30) / 60 * 100;
    const left = item.score >= 0 ? 50 : pct;
    const width = Math.abs(pct - 50);
    const row = document.createElement("div");
    row.className = "bar-row";
    row.innerHTML = `
      <div class="bar-head"><span>${item.name}</span><span class="score">${item.score > 0 ? "+" : ""}${item.score}</span></div>
      <div class="track"><div class="zero"></div><div class="fill" style="left:${left}%;width:${width}%;background:${item.color}"></div></div>
      <div class="bar-note">${item.desc}</div>`;
    bars.appendChild(row);
  });
}

function submit(){
  const missing = answers.findIndex(v => v === null);
  if (missing !== -1){
    current = missing;
    renderQuestion();
    alert(`还有第 ${missing + 1} 题没有作答，请补完再提交。`);
    return;
  }
  renderResult();
  show(resultEl);
}

function reset(){
  answers = new Array(ITEMS.length).fill(null);
  current = 0;
  renderQuestion();
  show(quizEl);
}

$("startBtn").addEventListener("click", () => {
  reset();
});

$("prevBtn").addEventListener("click", goPrev);
$("nextBtn").addEventListener("click", goNext);

$("againBtn").addEventListener("click", reset);

$("clearBtn").addEventListener("click", () => {
  answers = new Array(ITEMS.length).fill(null);
  current = 0;
  show(startEl);
});

document.addEventListener("keydown", (e) => {
  if (!quizEl.classList.contains("hidden")){
    if (e.key === "ArrowLeft") goPrev();
    if (e.key === "ArrowRight") goNext();
    const n = parseInt(e.key, 10);
    if (n >= 1 && n <= 5) choose(OPTIONS[n - 1].v);
  }
});

renderQuestion();
</script>
</body>
</html>
