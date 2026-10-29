<div align="center">

<!-- Animated Identity Banner -->
<img src="./assets/identity_banner.svg" width="100%" alt="Umut Güngör — identity.log" />

<br/><br/>

<!-- Sleek Quick-Nav Action Pills -->
<p align="center">
  <a href="https://umutgungorr.com/"><img src="https://img.shields.io/badge/Website-umutgungorr.com-2ea44f?style=flat-square&logo=googlechrome&logoColor=white&labelColor=161b22" alt="Website" /></a>
  <a href="https://umutgungorr.com/about"><img src="https://img.shields.io/badge/About-umutgungorr.com%2Fabout-58a6ff?style=flat-square&logo=readme&logoColor=white&labelColor=161b22" alt="About" /></a>
  <a href="https://pypi.org/user/umutgngr/"><img src="https://img.shields.io/badge/PyPI-6%20Packages-3775a9?style=flat-square&logo=pypi&logoColor=white&labelColor=161b22" alt="PyPI" /></a>
  <a href="https://github.com/marketplace?type=actions&query=umutgungorr"><img src="https://img.shields.io/badge/Marketplace-4%20Actions-bc8cff?style=flat-square&logo=githubactions&logoColor=white&labelColor=161b22" alt="Marketplace" /></a>
</p>

<!-- Engineering Architecture & Quality Standards -->
<p align="center">
  <a href="https://github.com/umutgungorr?tab=repositories"><img src="https://img.shields.io/badge/Architecture-0%20Dependencies-2ea44f?style=flat-square&logo=opensourceinitiative&logoColor=white&labelColor=161b22" alt="Zero Dependencies" /></a>
  <a href="https://github.com/umutgungorr"><img src="https://img.shields.io/badge/Tests-100%25%20Passing-brightgreen?style=flat-square&logo=pytest&logoColor=white&labelColor=161b22" alt="100% Passing" /></a>
  <a href="https://docs.oasis-open.org/sarif/sarif/v2.1.0/sarif-v2.1.0.html"><img src="https://img.shields.io/badge/Security-SARIF%20v2.1.0-orange?style=flat-square&logo=github&logoColor=white&labelColor=161b22" alt="SARIF" /></a>
  <a href="https://github.com/umutgungorr"><img src="https://img.shields.io/badge/Platform-Cross--Platform-388bfd?style=flat-square&logo=linux&logoColor=white&labelColor=161b22" alt="Cross-Platform" /></a>
</p>

</div>

---

## 👤 `whoami --signal`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/terminal.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/terminal-light.svg" />
  <img src="./assets/terminal.svg" width="100%" alt="Umut Güngör — whoami --signal" />
</picture>

</div>

---

## 🛠️ Tech Stack & Systems Architecture

<table>
  <tr>
    <td width="50%" align="center">
      <strong>⚡ Systems &amp; Core Runtimes</strong><br /><br />
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=ts,py,nodejs,bash,linux" alt="Core Systems" /></a><br /><br />
      <sub>TypeScript · Python (Stdlib &amp; AST) · Node.js · Bash · Linux Internals</sub>
    </td>
    <td width="50%" align="center">
      <strong>🎨 Modern Web &amp; Applications</strong><br /><br />
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,electron,astro" alt="Modern Web" /></a><br /><br />
      <sub>React · Next.js (App Router) · Tailwind CSS · Electron · Local-First UX</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <strong>🗄️ Backend, Cloud &amp; Storage</strong><br /><br />
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,redis,supabase,docker" alt="Backend & Cloud" /></a><br /><br />
      <sub>PostgreSQL · Redis Caching · Supabase · Docker Containerization</sub>
    </td>
    <td width="50%" align="center">
      <strong>🛡️ DevOps, Security &amp; Quality</strong><br /><br />
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=githubactions,git,vscode" alt="DevOps & Quality" /></a><br /><br />
      <sub>GitHub Actions CI/CD · SARIF v2.1.0 Security · Pytest · Vitest · Ruff</sub>
    </td>
  </tr>
</table>

---

## ⚡ The 4 Diagnostic Pillars

*Mapped directly to the telemetry heartbeat waveform (`ports` • `logs` • `env` • `git`):*

<table>
  <tr>
    <td width="50%">
      <div align="center">
        🌲 <strong><a href="https://github.com/umutgungorr/porttree">PortTree</a></strong> <code>[ports]</code><br/>
        <sub>Dev socket tree scanner &amp; Docker proxy unmasker.</sub><br/><br/>
        <a href="https://pypi.org/project/porttree/"><img src="https://img.shields.io/pypi/v/porttree.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/porttree/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/porttree-port-collision-socket-inspector"><img src="https://img.shields.io/badge/Action-Marketplace-blueviolet?style=flat-square&logo=github" alt="Action" /></a>
      </div>
      <br/>
      • <strong>Pain:</strong> <code>EADDRINUSE :::3000</code> collisions &amp; opaque <code>docker-proxy</code> PIDs.<br/>
      • <strong>Fix:</strong> Maps sockets to process trees, CWDs, and Git branches. Kills zombie worker trees safely.<br/>
      • <strong>Try:</strong> <code>uvx porttree 3000</code> · <code>uvx porttree free 3000 -y</code>
    </td>
    <td width="50%">
      <div align="center">
        ⚡ <strong><a href="https://github.com/umutgungorr/logshrink">LogShrink</a></strong> <code>[logs]</code><br/>
        <sub>Zero-config CLI terminal stream noise filter &amp; deduplicator.</sub><br/><br/>
        <a href="https://pypi.org/project/logshrink/"><img src="https://img.shields.io/pypi/v/logshrink.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/logshrink/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/logshrink-ci-log-cleaner"><img src="https://img.shields.io/badge/Action-Marketplace-blueviolet?style=flat-square&logo=github" alt="Action" /></a>
      </div>
      <br/>
      • <strong>Pain:</strong> Noisy test streams &amp; endless healthcheck polling floods burying errors.<br/>
      • <strong>Fix:</strong> Deduplicates repetitive logs into live badges like <code>[x480 suppressed]</code>; auto-boxes stack traces.<br/>
      • <strong>Try:</strong> <code>uvx logshrink -- npm test</code>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <div align="center">
        💊 <strong><a href="https://github.com/umutgungorr/envdoctor">EnvDoctor</a></strong> <code>[env]</code><br/>
        <sub>.env contract linter, synchronizer &amp; drift auditor.</sub><br/><br/>
        <a href="https://pypi.org/project/envdoctor-cli/"><img src="https://img.shields.io/pypi/v/envdoctor-cli.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/envdoctor/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/envdoctor-env-contract-linter"><img src="https://img.shields.io/badge/Action-Marketplace-blueviolet?style=flat-square&logo=github" alt="Action" /></a>
      </div>
      <br/>
      • <strong>Pain:</strong> Silent deployment failures due to missing or drifted <code>.env</code> variables.<br/>
      • <strong>Fix:</strong> Validates contracts against code, auto-generates masked <code>.env.example</code> with zero leaks.<br/>
      • <strong>Try:</strong> <code>pip install envdoctor-cli</code> · <code>envdoctor check</code>
    </td>
    <td width="50%">
      <div align="center">
        🩺 <strong><a href="https://github.com/umutgungorr/repopulse">RepoPulse</a></strong> <code>[git]</code><br/>
        <sub>Git forensic health &amp; knowledge silo audit engine.</sub><br/><br/>
        <a href="https://pypi.org/project/git-repopulse/"><img src="https://img.shields.io/pypi/v/git-repopulse.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/repopulse/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/repopulse-git-codebase-health-audit"><img src="https://img.shields.io/badge/Action-Marketplace-blueviolet?style=flat-square&logo=github" alt="Action" /></a>
      </div>
      <br/>
      • <strong>Pain:</strong> Invisible bus-factor risks, architectural hotspots, and decaying modules.<br/>
      • <strong>Fix:</strong> Mines Git history in &lt;20ms, pinpoints single-author silos, and scores codebase health (0–100).<br/>
      • <strong>Try:</strong> <code>pip install git-repopulse</code> · <code>repopulse audit</code>
    </td>
  </tr>
</table>

---

## 🛡️ Security & Integrity Tooling

A complementary suite of zero-runtime-dependency security scanners and documentation integrity verifiers:

<table>
  <tr>
    <td width="50%">
      <div align="center">
        🛡️ <strong><a href="https://github.com/umutgungorr/tokenguard">TokenGuard</a></strong><br/>
        <sub>Git pre-commit secret scanner &amp; SARIF security reporter.</sub><br/><br/>
        <a href="https://pypi.org/project/tokenguard-cli/"><img src="https://img.shields.io/pypi/v/tokenguard-cli.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/tokenguard/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/tokenguard-secret-scanner"><img src="https://img.shields.io/badge/SARIF-v2.1.0-orange?style=flat-square&logo=github" alt="SARIF" /></a>
      </div>
      <br/>
      • <strong>Focus:</strong> Intercepts high-entropy API keys, AWS credentials, and cloud tokens before commit.<br/>
      • <strong>Output:</strong> Native OASIS SARIF v2.1.0 for seamless GitHub Code Scanning integration.<br/>
      • <strong>Run:</strong> <code>pip install tokenguard-cli</code> · <code>tokenguard scan</code>
    </td>
    <td width="50%">
      <div align="center">
        🔗 <strong><a href="https://github.com/umutgungorr/deadlinkfinder">DeadLinkFinder</a></strong><br/>
        <sub>Markdown &amp; rST documentation integrity &amp; anchor checker.</sub><br/><br/>
        <a href="https://pypi.org/project/deadlinkfinder/"><img src="https://img.shields.io/pypi/v/deadlinkfinder.svg?style=flat-square&logo=pypi&logoColor=white&color=2f81f7" alt="PyPI" /></a>
        <a href="https://github.com/umutgungorr/deadlinkfinder/actions"><img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square&logo=githubactions&logoColor=white" alt="CI" /></a>
        <a href="https://github.com/marketplace/actions/deadlinkfinder-documentation-link-checker"><img src="https://img.shields.io/badge/Action-Marketplace-blueviolet?style=flat-square&logo=github" alt="Action" /></a>
      </div>
      <br/>
      • <strong>Focus:</strong> Offline verification of internal file links, missing assets, and GitHub heading anchors.<br/>
      • <strong>Engine:</strong> Pure Python AST Markdown/rST parser with zero external network dependencies.<br/>
      • <strong>Run:</strong> <code>pip install deadlinkfinder</code> · <code>deadlinkfinder check docs/</code>
    </td>
  </tr>
</table>

---

## 🌐 Full-Stack Products & Systems

Product-minded applications built with TypeScript, React 19, Supabase, and local-first architecture:

<table>
  <tr>
    <td width="50%">
      <strong>📡 SignalDeck</strong> <code>[Local-First App]</code><br/>
      <sub>Real-time developer telemetry, product signal tracking &amp; evidence research cockpit.</sub><br/><br/>
      <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      <br/><br/>
      • Zero-login offline-first data model with client-side reactive state machines.<br/>
      • Multi-signal weighted scoring algorithms for rapid feature &amp; idea validation.<br/>
      • Tested domain logic verified with Vitest.
    </td>
    <td width="50%">
      <strong>⏱️ ChronoFlow</strong> <code>[Focus Architecture]</code><br/>
      <sub>Local-first daily time-blocking &amp; cognitive focus scheduler.</sub><br/><br/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
      <img src="https://img.shields.io/badge/Local--First-2ea44f?style=flat-square" />
      <br/><br/>
      • Structured daily flow planning without mandatory cloud lock-in.<br/>
      • Deterministic conflict resolution with optional cross-device encrypted sync.<br/>
      • Rigorous state machine test coverage across all boundary transitions.
    </td>
  </tr>
</table>

---

## 🤖 Drop-In CI/CD Integration

Integrate these diagnostic and security gates into your GitHub Actions workflow in seconds:

```yaml
# .github/workflows/ci.yml
jobs:
  quality-gate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: umutgungorr/porttree@v1       # Verify port availability & pre-flight collisions
      - uses: umutgungorr/tokenguard@v1     # Block secret leaks & upload native SARIF report
      - uses: umutgungorr/envdoctor@v1      # Audit .env contracts against drift
      - uses: umutgungorr/deadlinkfinder@v1 # Verify documentation integrity
```

---

## 💻 Instant Zero-Install CLI Quickstart

Try any tool instantly without compiling or manual installation:

```bash
# 1. Unmask Docker proxies and inspect who holds port 3000
uvx porttree 3000

# 2. Terminate an entire zombie process tree holding port 3000
uvx porttree free 3000 -y

# 3. Deduplicate noisy CI logs and suppress healthcheck floods
uvx logshrink -- npm test

# 4. Check documentation for broken links and dead image anchors
uvx deadlinkfinder check docs/
```

---

## 🇹🇷 Umut Güngör Kimdir?

Umut Güngör, **TypeScript**, **React** ve **Python** ile modern web sistemleri, AI araçları ve açık kaynak developer araçları geliştiren **Yazılım Mühendisidir**.

* 🌐 **Web Sitesi**: [umutgungorr.com](https://umutgungorr.com/)
* 📄 **Özgeçmiş &amp; Projeler**: [umutgungorr.com/about](https://umutgungorr.com/about)
* 📦 **PyPI Paketleri**: [pypi.org/user/umutgngr](https://pypi.org/user/umutgngr/)
* 🧩 **GitHub Marketplace**: [umutgungorr Actions](https://github.com/marketplace?type=actions&query=umutgungorr)

---

## 📬 Connect & Collaborate

<div align="center">

**Open to focused engineering collaborations, ambitious developer tooling ideas, and high-impact teams.**

<br/>

[![Website](https://img.shields.io/badge/WEBSITE-umutgungorr.com-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d0d11)](https://umutgungorr.com/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-in%2Fumut--gungor-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d11)](https://www.linkedin.com/in/umut-gungor/)
[![Email](https://img.shields.io/badge/EMAIL-contact.umutgungor%40gmail.com-2f81f7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d11)](mailto:contact.umutgungor@gmail.com)
[![PyPI](https://img.shields.io/badge/PYPI-umutgngr-3775A9?style=for-the-badge&logo=pypi&logoColor=white&labelColor=0d0d11)](https://pypi.org/user/umutgngr/)

</div>
