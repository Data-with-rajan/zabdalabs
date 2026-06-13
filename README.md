<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zabda Labs — Rengarajan G · AI Systems, Independently Built and Verified</title>
<meta name="description" content="Zabda Labs: AI governance, agent-state, and on-device inference systems built independently by Rengarajan G. Every claim on this page is verifiable.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wdth,wght@62..125,100..900&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#F4F5F2;
  --paper-2:#ECEEE9;
  --ink:#171A1E;
  --ink-soft:#4A4F57;
  --hairline:#C9CDC6;
  --verify:#0F6B4D;
  --verify-soft:#E3EFE9;
  --signal:#A05E03;
  --signal-soft:#F5EBDC;
  --research:#5B6470;
  --research-soft:#E8EAEE;
  --live:#1D4ED8;
  --live-soft:#E4EAF8;
  --mono:'IBM Plex Mono',ui-monospace,monospace;
  --sans:'Archivo',system-ui,sans-serif;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}*,*::before,*::after{animation:none!important;transition:none!important}}
body{
  background:var(--paper);
  color:var(--ink);
  font-family:var(--sans);
  font-size:16px;
  line-height:1.55;
  -webkit-font-smoothing:antialiased;
}
::selection{background:var(--verify);color:#fff}
a{color:inherit}
.wrap{max-width:1180px;margin:0 auto;padding:0 24px}

/* ---------- verification strip ---------- */
.strip{
  background:var(--ink);color:var(--paper);
  font-family:var(--mono);font-size:11.5px;letter-spacing:.04em;
  padding:8px 0;
}
.strip .wrap{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap}
.strip b{color:#9BD9C0;font-weight:600}

/* ---------- nav ---------- */
nav{
  position:sticky;top:0;z-index:50;
  background:rgba(244,245,242,.92);backdrop-filter:blur(8px);
  border-bottom:1px solid var(--hairline);
}
nav .wrap{display:flex;align-items:center;justify-content:space-between;height:60px}
.logo{font-family:var(--mono);font-weight:600;font-size:14px;letter-spacing:.06em;text-decoration:none}
.logo span{color:var(--verify)}
.nav-links{display:flex;gap:26px;align-items:center}
.nav-links a{font-family:var(--mono);font-size:12.5px;text-decoration:none;color:var(--ink-soft);letter-spacing:.03em}
.nav-links a:hover,.nav-links a:focus-visible{color:var(--ink)}
.nav-cta{border:1.5px solid var(--ink);padding:7px 14px;color:var(--ink)!important;transition:background .15s,color .15s}
.nav-cta:hover{background:var(--ink);color:var(--paper)!important}
a:focus-visible,button:focus-visible{outline:2px solid var(--verify);outline-offset:3px}

/* ---------- hero ---------- */
.hero{padding:84px 0 64px;border-bottom:1px solid var(--hairline)}
.hero .wrap{display:grid;grid-template-columns:1.25fr .9fr;gap:56px;align-items:start}
.eyebrow{font-family:var(--mono);font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--ink-soft);margin-bottom:22px}
h1{
  font-variation-settings:'wdth' 115;
  font-weight:800;font-size:clamp(34px,5vw,58px);
  line-height:1.04;letter-spacing:-.015em;margin-bottom:24px;
}
h1 em{font-style:normal;color:var(--verify)}
.hero p.lede{font-size:18px;color:var(--ink-soft);max-width:52ch;margin-bottom:30px}
.hero-ctas{display:flex;gap:14px;flex-wrap:wrap}
.btn{
  font-family:var(--mono);font-size:13px;letter-spacing:.04em;text-decoration:none;
  padding:13px 22px;border:1.5px solid var(--ink);display:inline-block;
  transition:transform .12s,background .15s,color .15s;
}
.btn-solid{background:var(--ink);color:var(--paper)}
.btn-solid:hover{background:var(--verify);border-color:var(--verify)}
.btn-ghost:hover{background:var(--ink);color:var(--paper)}

/* audit log block */
.audit{
  background:var(--ink);color:#C8CFC9;font-family:var(--mono);
  font-size:12.5px;line-height:1.9;padding:26px 26px 22px;
  border:1px solid #2A2F36;box-shadow:8px 8px 0 var(--paper-2);
}
.audit .ttl{color:#8A929B;font-size:11px;letter-spacing:.12em;text-transform:uppercase;margin-bottom:14px;display:flex;justify-content:space-between}
.audit .row{display:flex;justify-content:space-between;gap:12px;border-bottom:1px dashed #2A2F36;padding:3px 0}
.audit .row:last-child{border-bottom:none}
.ok{color:#7ED3AC;font-weight:600}
.warn{color:#E5B36A;font-weight:600}
.dim{color:#737B85}
.audit .row span:first-child{white-space:nowrap;overflow:hidden;text-overflow:ellipsis}

/* claims policy */
.policy{padding:26px 0;border-bottom:1px solid var(--hairline);background:var(--paper-2)}
.policy .wrap{display:flex;gap:18px;align-items:baseline;flex-wrap:wrap}
.policy .tag{font-family:var(--mono);font-size:11px;letter-spacing:.12em;background:var(--ink);color:var(--paper);padding:4px 9px;white-space:nowrap}
.policy p{font-size:14.5px;color:var(--ink-soft);max-width:88ch}

/* ---------- sections ---------- */
section{padding:76px 0}
.sec-head{display:flex;align-items:baseline;justify-content:space-between;gap:18px;margin-bottom:44px;flex-wrap:wrap}
h2{font-variation-settings:'wdth' 118;font-weight:800;font-size:clamp(26px,3.4vw,38px);letter-spacing:-.01em}
.sec-note{font-family:var(--mono);font-size:12px;color:var(--ink-soft);letter-spacing:.03em}

/* ---------- ledger rows ---------- */
.ledger{border-top:2px solid var(--ink)}
.entry{
  border-bottom:1px solid var(--hairline);
  padding:38px 0 42px;
  display:grid;grid-template-columns:64px 1fr 190px;gap:30px;
}
.entry-id{font-family:var(--mono);font-size:12px;color:var(--ink-soft);padding-top:6px}
.entry h3{font-variation-settings:'wdth' 112;font-weight:750;font-size:24px;margin-bottom:2px}
.entry .role{font-family:var(--mono);font-size:12.5px;color:var(--verify);letter-spacing:.04em;margin-bottom:16px}
.cols{display:grid;grid-template-columns:1fr 1fr;gap:26px;margin-top:6px}
.col h4{font-family:var(--mono);font-size:10.5px;letter-spacing:.14em;text-transform:uppercase;color:var(--ink-soft);margin-bottom:7px}
.col p{font-size:14.5px;color:var(--ink);line-height:1.6}
.differs{
  margin-top:20px;background:var(--paper-2);border-left:3px solid var(--ink);
  padding:14px 18px;
}
.differs h4{font-family:var(--mono);font-size:10.5px;letter-spacing:.14em;text-transform:uppercase;color:var(--ink-soft);margin-bottom:6px}
.differs p{font-size:14px;line-height:1.6;color:var(--ink)}
.differs p + p{margin-top:6px}
.differs .hon{color:var(--ink-soft)}
.tech{margin-top:16px;display:flex;gap:8px;flex-wrap:wrap}
.tech span{font-family:var(--mono);font-size:11px;border:1px solid var(--hairline);padding:3px 9px;color:var(--ink-soft);background:var(--paper)}

/* stamps */
.stampcol{display:flex;flex-direction:column;gap:14px;align-items:flex-end}
.stamp{
  font-family:var(--mono);font-weight:600;font-size:11.5px;letter-spacing:.12em;
  border:2px solid currentColor;padding:7px 12px;text-transform:uppercase;
  transform:rotate(2.4deg);white-space:nowrap;
}
.entry:nth-child(even) .stamp{transform:rotate(-2deg)}
.stamp.verify{color:var(--verify);background:var(--verify-soft)}
.stamp.live{color:var(--live);background:var(--live-soft)}
.stamp.progress{color:var(--signal);background:var(--signal-soft)}
.stamp.research{color:var(--research);background:var(--research-soft)}
.metric{font-family:var(--mono);font-size:11.5px;color:var(--ink-soft);text-align:right;line-height:1.8}
.metric b{color:var(--ink);font-weight:600}

/* ---------- principles ---------- */
.principles{background:var(--ink);color:var(--paper)}
.principles h2{color:var(--paper)}
.principles .sec-note{color:#8A929B}
.prin-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:#2A2F36;border:1px solid #2A2F36}
.prin{background:var(--ink);padding:30px 26px}
.prin .k{font-family:var(--mono);font-size:11px;letter-spacing:.14em;color:#7ED3AC;text-transform:uppercase;margin-bottom:12px}
.prin p{font-size:14.5px;color:#C8CFC9;line-height:1.65}

/* ---------- extended ---------- */
.ext-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.ext{border:1px solid var(--hairline);padding:22px;background:var(--paper)}
.ext h3{font-size:16px;font-weight:700;margin-bottom:6px;font-variation-settings:'wdth' 110}
.ext .st{font-family:var(--mono);font-size:10.5px;letter-spacing:.1em;color:var(--ink-soft);text-transform:uppercase;margin-bottom:10px}
.ext p{font-size:13.5px;color:var(--ink-soft);line-height:1.55}

/* ---------- about ---------- */
.about .wrap{display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:start}
.about p{font-size:16px;color:var(--ink);margin-bottom:16px;max-width:56ch}
.about p.soft{color:var(--ink-soft);font-size:15px}
.facts{border-top:2px solid var(--ink)}
.fact{display:flex;justify-content:space-between;gap:20px;border-bottom:1px solid var(--hairline);padding:13px 2px;font-size:14.5px}
.fact span:first-child{font-family:var(--mono);font-size:12px;color:var(--ink-soft);letter-spacing:.04em;padding-top:2px}
.fact span:last-child{text-align:right;font-weight:500}

/* ---------- contact ---------- */
.contact{border-top:1px solid var(--hairline);background:var(--paper-2)}
.contact .wrap{text-align:left}
.contact h2{margin-bottom:14px}
.contact p{color:var(--ink-soft);max-width:60ch;margin-bottom:28px}
.contact-row{display:flex;gap:14px;flex-wrap:wrap}

footer{border-top:1px solid var(--hairline);padding:26px 0;font-family:var(--mono);font-size:11.5px;color:var(--ink-soft)}
footer .wrap{display:flex;justify-content:space-between;gap:14px;flex-wrap:wrap}

/* reveal */
.rv{opacity:0;transform:translateY(14px);transition:opacity .5s ease,transform .5s ease}
.rv.in{opacity:1;transform:none}

@media(max-width:920px){
  .hero .wrap{grid-template-columns:1fr}
  .entry{grid-template-columns:1fr;gap:16px}
  .stampcol{flex-direction:row;align-items:center;justify-content:flex-start}
  .metric{text-align:left}
  .cols{grid-template-columns:1fr}
  .prin-grid{grid-template-columns:1fr}
  .ext-grid{grid-template-columns:1fr 1fr}
  .about .wrap{grid-template-columns:1fr}
}
@media(max-width:560px){
  .ext-grid{grid-template-columns:1fr}
  .nav-links a:not(.nav-cta){display:none}
}
</style>
</head>
<body>

<div class="strip">
  <div class="wrap">
    <div>CLAIMS POLICY — every statement on this page is <b>verifiable</b>: demoable, runnable, or filed.</div>
    <div>BENGALURU, IN · <b>ZABDA LABS</b></div>
  </div>
</div>

<nav>
  <div class="wrap">
    <a class="logo" href="#top">ZABDA<span>/</span>LABS</a>
    <div class="nav-links">
      <a href="#ledger">Project ledger</a>
      <a href="#principles">How I work</a>
      <a href="#about">About</a>
      <a class="nav-cta" href="#contact">Get in touch</a>
    </div>
  </div>
</nav>

<header class="hero" id="top">
  <div class="wrap">
    <div>
      <div class="eyebrow">Rengarajan G · AI Engineer · Independent Builder</div>
      <h1>AI systems that can be <em>checked</em>, not just believed.</h1>
      <p class="lede">Ten years running e-commerce operations. Two years building AI infrastructure independently — governance engines, agent-state protocols, and on-device inference. Three patent applications filed. One product live with paying users. Everything below is stated at the level I can demonstrate.</p>
      <div class="hero-ctas">
        <a class="btn btn-solid" href="#ledger">Read the project ledger</a>
        <a class="btn btn-ghost" href="#contact">Request a demo</a>
      </div>
    </div>
    <div class="audit" aria-label="Portfolio audit summary">
      <div class="ttl"><span>portfolio_audit.log</span><span>2026</span></div>
      <div class="row"><span>$ tsc --noEmit · vnol-core</span><span class="ok">0 errors</span></div>
      <div class="row"><span>$ vitest run · vnol-core</span><span class="ok">44 passed</span></div>
      <div class="row"><span>$ tsc --noEmit · sentrix</span><span class="ok">0 errors</span></div>
      <div class="row"><span>$ cargo test · chayt</span><span class="ok">passing</span></div>
      <div class="row"><span>cikitsu · production</span><span class="ok">live + billing</span></div>
      <div class="row"><span>patent filings · IPO India</span><span class="ok">3 filed</span></div>
      <div class="row"><span>phantominfer · benchmarks</span><span class="warn">research</span></div>
      <div class="row"><span class="dim"># run on real hardware, June 2026</span><span></span></div>
    </div>
  </div>
</header>

<div class="policy">
  <div class="wrap">
    <span class="tag">WHY THE STAMPS</span>
    <p>I build verification tools, so this page is written like one. Each project carries the status an auditor would give it — nothing is stamped <strong>verified</strong> unless it compiles, its tests pass, and it runs today. Codebases are private while patent filings are active; architecture walk-throughs and live demos are available on request.</p>
  </div>
</div>

<section id="ledger">
  <div class="wrap">
    <div class="sec-head">
      <h2>Project ledger</h2>
      <span class="sec-note">06 flagship entries · status as independently checked</span>
    </div>

    <div class="ledger">

      <article class="entry rv">
        <div class="entry-id">01</div>
        <div>
          <h3>Sentrix</h3>
          <div class="role">AI execution integrity — patent filed (India)</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>Teams deploy AI tools with no control over what the AI actually does. It can drift from the task it was given, breach policy, or act outside its mandate — with no record of when or how.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>Locks the user's intent at the start of a task, then checks every AI output against it in real time — flagging deviation, drift, and policy violations with a full audit trail. Ships as a CLI, VSCode and Chrome extensions, and an MCP server.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>Most guardrail products inspect <strong>content</strong> — toxicity, PII, unsafe topics. Sentrix checks <strong>fidelity to intent</strong>: did the AI do what was actually asked. Those are complementary layers, not substitutes.</p>
            <p class="hon">Honestly: intent-integrity is a young category and larger security vendors are now entering it. My edge is shipping depth — working IDE, browser, and MCP integrations today — not incumbency.</p>
          </div>
          <div class="tech"><span>TypeScript</span><span>VSCode API</span><span>Chrome Extension</span><span>MCP</span><span>Node.js</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp verify">Verified · Runs</div>
          <div class="metric"><b>~6.9k</b> lines core TS<br><b>0</b> compile errors<br>CLI + clients working</div>
        </div>
      </article>

      <article class="entry rv">
        <div class="entry-id">02</div>
        <div>
          <h3>VNOL</h3>
          <div class="role">Agent-state portability protocol — patent pending</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>When an AI agent crashes, a session ends, or you switch providers, its working state — goals, reasoning, constraints, next steps — is gone. Teams restart complex work from zero and stay locked to one vendor.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>Serializes an agent's full working state into a compact, AES-256-GCM encrypted, integrity-sealed snapshot — and restores it on a different model (OpenAI, Anthropic, Llama, Mistral) so work resumes where it stopped.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>Framework checkpointing (e.g. LangGraph persistence) saves <strong>workflow state inside one framework</strong>. VNOL saves the agent's <strong>cognitive state as a model-agnostic, sealed artifact</strong> designed to boot on a different provider — with a security audit run before anything is sealed.</p>
            <p class="hon">Honestly: if you live entirely inside one framework and one provider, its built-in persistence may be all you need. VNOL is for when you can't afford that lock-in.</p>
          </div>
          <div class="tech"><span>TypeScript</span><span>npm</span><span>MCP</span><span>AES-256-GCM</span><span>Multi-model</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp verify">Verified · Tested</div>
          <div class="metric"><b>7.4k</b> lines core TS<br><b>44/44</b> tests passing<br><b>0</b> compile errors</div>
        </div>
      </article>

      <article class="entry rv">
        <div class="entry-id">03</div>
        <div>
          <h3>Cikitsu</h3>
          <div class="role">Multi-agent business strategy SaaS — in production</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>Small and mid-size businesses can't afford a cross-functional consulting team — finance, marketing, operations — working one problem together.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>Eleven specialised AI consultants collaborate on a submitted business question — challenging each other's reasoning — and deliver a structured strategy report. Deployed with subscription billing and PDF reporting.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>It isn't a wrapper around one chat model: agents form teams dynamically and debate before concluding — and the whole product runs on the same governance and state layer (VNOL, UTCD) I build as infrastructure. It's the working proof of the stack.</p>
            <p class="hon">Honestly: AI consulting tools are a busy space. Cikitsu's claim isn't "the only one" — it's "live, billing, and built on infrastructure I can show you."</p>
          </div>
          <div class="tech"><span>Next.js</span><span>FastAPI</span><span>Python</span><span>PostgreSQL</span><span>Docker</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp live">Live · Paying users</div>
          <div class="metric">Production deploy<br>Subscription billing<br>Built on VNOL + UTCD</div>
        </div>
      </article>

      <article class="entry rv">
        <div class="entry-id">04</div>
        <div>
          <h3>Azhwar</h3>
          <div class="role">AI code governance engine — patent pending</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>AI coding assistants generate code fast, and much of it quietly violates accessibility, security, or design standards — unnoticed until it breaks in production.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>Audits AI-generated code at the syntax-tree level against 250+ rules across 30+ industry profiles, suggests corrections, and runs wherever code is written — npm CLI, GitHub Action, or MCP server inside the editor.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>General linters check syntax and style. Azhwar is profiled for the specific failure modes of <strong>AI-generated</strong> code, mapped to industry compliance profiles rather than generic rules.</p>
            <p class="hon">Honestly: established scanners (Snyk, Semgrep) are strong on classic vulnerabilities. Azhwar's lane is the AI-slop layer they weren't designed for — it complements them rather than replacing them.</p>
          </div>
          <div class="tech"><span>TypeScript</span><span>AST</span><span>npm CLI</span><span>GitHub Actions</span><span>MCP</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp verify">Verified · Ships</div>
          <div class="metric">CLI + Action working<br>250+ rules<br>30+ profiles</div>
        </div>
      </article>

      <article class="entry rv">
        <div class="entry-id">05</div>
        <div>
          <h3>Baliza</h3>
          <div class="role">Bounded AI delegation for founders — launch ready</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>Founders can't hand communication to AI without guardrails — it may approve things they wouldn't, miss their tone, or overstep authority they never granted.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>The founder defines authority rules, escalation triggers, and voice first; the AI drafts only inside those bounds. Every action is logged, explainable, and reversible with a kill switch. Billing and onboarding built.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>Most email-AI products optimise for <strong>more automation</strong>. Baliza optimises for <strong>safe delegation</strong> — the rules engine and audit trail are the product, the drafting is downstream of them.</p>
            <p class="hon">Honestly: it is launch-ready, not launched. The engineering is done; the market test hasn't started.</p>
          </div>
          <div class="tech"><span>Next.js</span><span>Node.js</span><span>PostgreSQL</span><span>Gmail API</span><span>Stripe</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp progress">Launch ready</div>
          <div class="metric">Phases 1–6 complete<br>Billing integrated<br>Pre-launch</div>
        </div>
      </article>

      <article class="entry rv">
        <div class="entry-id">06</div>
        <div>
          <h3>PhantomInfer</h3>
          <div class="role">On-device LLM inference engine — research</div>
          <div class="cols">
            <div class="col">
              <h4>The problem</h4>
              <p>Most AI requires a cloud connection and sends data off-device — unusable in low-connectivity environments and risky in privacy-sensitive sectors.</p>
            </div>
            <div class="col">
              <h4>What it does</h4>
              <p>A C++ inference engine for running language models directly on mid-range Android hardware — custom kernel, mixture-of-experts routing, thermal management, and JNI integration. Groundwork for private, offline AI.</p>
            </div>
          </div>
          <div class="differs">
            <h4>How it differs</h4>
            <p>Rather than wrapping an existing runtime, it's a ground-up engine targeting the constraint nobody optimises for: <strong>6GB-RAM consumer phones</strong>, not flagship hardware.</p>
            <p class="hon">Honestly: this is research-grade. On-device throughput for large models on mid-range hardware is measured in tokens per second, not magic. I publish what the hardware actually does.</p>
          </div>
          <div class="tech"><span>C++</span><span>Android NDK</span><span>CMake</span><span>JNI</span><span>GGML</span></div>
        </div>
        <div class="stampcol">
          <div class="stamp research">Research</div>
          <div class="metric"><b>70+</b> C++ source files<br>Custom MoE router<br>Active development</div>
        </div>
      </article>

    </div>
  </div>
</section>

<section class="principles" id="principles">
  <div class="wrap">
    <div class="sec-head">
      <h2>How I work</h2>
      <span class="sec-note">the rules this portfolio is written under</span>
    </div>
    <div class="prin-grid">
      <div class="prin rv">
        <div class="k">Claims match evidence</div>
        <p>A number appears here only if I can reproduce it in front of you — a passing test suite, a clean compile, a live deployment. Where something is early, it says research; where it's untested in market, it says launch-ready, not launched.</p>
      </div>
      <div class="prin rv">
        <div class="k">Comparisons cut both ways</div>
        <p>Every "how it differs" section also states where the alternative wins. If a built-in framework feature solves your problem, you should use it. The projects here exist for the cases where it doesn't.</p>
      </div>
      <div class="prin rv">
        <div class="k">One stack, not fifteen demos</div>
        <p>The flagship products share infrastructure — the state protocol, the contract layer, the governance engine. Cikitsu runs on it in production. The portfolio is one system seen from different angles, not a pile of prototypes.</p>
      </div>
    </div>
  </div>
</section>

<section id="extended">
  <div class="wrap">
    <div class="sec-head">
      <h2>Extended stack</h2>
      <span class="sec-note">supporting infrastructure · built, private, demoable</span>
    </div>
    <div class="ext-grid">
      <div class="ext rv"><h3>Chayt</h3><div class="st">Rust · builds, tests pass</div><p>Governed memory gateway: AES-256-GCM encrypted memory, Ed25519 signing, contract enforcement at the proxy layer, Prometheus metrics.</p></div>
      <div class="ext rv"><h3>UTCD</h3><div class="st">Python · packaged</div><p>A contract standard for AI agent behaviour — signed, validated tool and conduct descriptors. The protocol layer the other systems enforce.</p></div>
      <div class="ext rv"><h3>cSIM</h3><div class="st">Prototype · patent material</div><p>Portable, hardware-attested AI cognitive state — compact enough to carry as a QR code. Encryption and secret-sharing core implemented.</p></div>
      <div class="ext rv"><h3>Alocaka</h3><div class="st">Python · in development</div><p>Pre-execution governance for agent organisations: budget enforcement, policy checks, and pre-flight simulation before an agent acts.</p></div>
      <div class="ext rv"><h3>aot-engine</h3><div class="st">Python · framework</div><p>Self-assembling multi-agent topology with dynamic leader election and fault absorption. Powers Cikitsu's consultant teams.</p></div>
      <div class="ext rv"><h3>crazyant</h3><div class="st">TypeScript · CLI + MCP</div><p>Takes AI-generated prototypes to production: hybrid AST + LLM security audit, hardening middleware, infrastructure generation.</p></div>
    </div>
  </div>
</section>

<section class="about" id="about">
  <div class="wrap">
    <div>
      <div class="sec-head" style="margin-bottom:24px"><h2>About</h2></div>
      <p>I spent ten years running e-commerce operations — supply chains, vendors, P&amp;L. In 2024 I started building AI systems independently: no team, no funding, no classroom. Two years later the result is a connected stack of governance, state, and inference infrastructure, three patent applications, and one product in production with paying users.</p>
      <p class="soft">The operations decade is why everything here is built around control, audit trails, and accountability: I've been the person responsible when a system silently does the wrong thing. The tools I build exist so that doesn't happen with AI.</p>
      <p class="soft">B.Tech in Information Technology · Scaler Data Science certification · Bengaluru, India.</p>
    </div>
    <div class="facts rv">
      <div class="fact"><span>NAME</span><span>Rengarajan G</span></div>
      <div class="fact"><span>BRAND</span><span>Zabda Labs</span></div>
      <div class="fact"><span>PATENTS</span><span>3 applications filed (India)</span></div>
      <div class="fact"><span>IN PRODUCTION</span><span>1 SaaS, paying users</span></div>
      <div class="fact"><span>LANGUAGES</span><span>TypeScript · Python · C++ · Rust</span></div>
      <div class="fact"><span>SURFACE AREA</span><span>npm · MCP · VSCode · Chrome · GitHub Actions</span></div>
      <div class="fact"><span>GITHUB</span><span><a href="https://github.com/Data-with-rajan">Data-with-rajan</a></span></div>
      <div class="fact"><span>BASE</span><span>Bengaluru, IN</span></div>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="wrap">
    <h2>Verify it yourself.</h2>
    <p>Codebases are private while patent filings are active — but every status stamp on this page can be demonstrated live: test runs, deployments, architecture walk-throughs. If you're hiring, piloting, or evaluating, ask for the demo that matters to you.</p>
    <div class="contact-row">
      <a class="btn btn-solid" href="mailto:rajanprakruti@gmail.com">rajanprakruti@gmail.com</a>
      <a class="btn btn-ghost" href="https://github.com/Data-with-rajan">GitHub</a>
      <a class="btn btn-ghost" href="tel:+918122495981">+91 81224 95981</a>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <span>© 2026 Zabda Labs · Rengarajan G</span>
    <span>No claim on this page exceeds what can be demonstrated.</span>
  </div>
</footer>

<script>
const io=new IntersectionObserver(es=>{es.forEach(e=>{if(e.isIntersecting){e.target.classList.add('in');io.unobserve(e.target)}})},{threshold:.12});
document.querySelectorAll('.rv').forEach(el=>io.observe(el));
</script>
</body>
</html>
