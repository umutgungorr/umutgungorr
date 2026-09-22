<div align="center">

# Hi, I'm Umut 👋

**Software Engineer · Open-Source Developer Tooling & Product Engineering**  
*Building zero-dependency security, linting, and documentation tools for modern Git teams.*

<br/>

[![GitHub Marketplace](https://img.shields.io/badge/GitHub_Marketplace-3_Actions_Published-2f81f7?style=flat-square&logo=githubactions&logoColor=white&labelColor=161b22)](https://github.com/marketplace?type=actions&query=umutgungorr)
[![Zero Runtime Dependencies](https://img.shields.io/badge/Architecture-Zero_Runtime_Dependencies-2ea44f?style=flat-square&logo=opensourceinitiative&logoColor=white&labelColor=161b22)](https://github.com/umutgungorr?tab=repositories)
[![SARIF v2.1.0 OASIS](https://img.shields.io/badge/Standard-Native_SARIF_v2.1.0-orange?style=flat-square&logo=github&logoColor=white&labelColor=161b22)](https://docs.oasis-open.org/sarif/sarif/v2.1.0/sarif-v2.1.0.html)

</div>

---

## 🛠️ What I'm Building: The Developer Quality Toolkit

A suite of lightweight, zero-runtime-dependency CLI tools and official GitHub Marketplace Actions designed to catch defects, security leaks, and drift *before* code merges:

<table>
  <tr>
    <td width="33%" align="center">
      🛡️ <strong><a href="https://github.com/umutgungorr/tokenguard">TokenGuard</a></strong><br />
      <sub>Git pre-commit secret scanner & SARIF security reporter.</sub><br /><br />
      <a href="https://github.com/marketplace/actions/tokenguard-secret-scanner"><img src="https://img.shields.io/badge/Marketplace-Live-blue?style=flat-square&logo=githubactions&logoColor=white" alt="TokenGuard Marketplace" /></a>
      <a href="https://github.com/umutgungorr/tokenguard/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Release-v0.2.0-2f81f7.svg?style=flat-square" alt="v0.2.0" /></a>
      <a href="https://github.com/umutgungorr/tokenguard"><img src="https://img.shields.io/badge/SARIF-v2.1.0-orange.svg?style=flat-square" alt="SARIF v2.1.0" /></a>
      <br /><br />
      <sub>Blocks API keys, AWS tokens, and high-entropy secrets from Git history. Supports baseline suppression for legacy credentials.</sub>
    </td>
    <td width="33%" align="center">
      🩺 <strong><a href="https://github.com/umutgungorr/envdoctor">EnvDoctor</a></strong><br />
      <sub>.env contract linter, multiline parser & codebase auditor.</sub><br /><br />
      <a href="https://github.com/marketplace/actions/envdoctor-integrity-linter"><img src="https://img.shields.io/badge/Marketplace-Live-2ea44f?style=flat-square&logo=githubactions&logoColor=white" alt="EnvDoctor Marketplace" /></a>
      <a href="https://github.com/umutgungorr/envdoctor/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Release-v0.2.0-2f81f7.svg?style=flat-square" alt="v0.2.0" /></a>
      <a href="https://github.com/umutgungorr/envdoctor"><img src="https://img.shields.io/badge/Format-JSON%20CI-brightgreen.svg?style=flat-square" alt="JSON CI" /></a>
      <br /><br />
      <sub>Prevents configuration drift between <code>.env</code> and <code>.env.example</code>. Scans codebase AST for unconfigured environment variables.</sub>
    </td>
    <td width="33%" align="center">
      🔗 <strong><a href="https://github.com/umutgungorr/deadlinkfinder">DeadLinkFinder</a></strong><br />
      <sub>Markdown link, image, and heading-anchor integrity verifier.</sub><br /><br />
      <a href="https://github.com/marketplace/actions/deadlinkfinder-markdown-checker"><img src="https://img.shields.io/badge/Marketplace-Live-8957e5?style=flat-square&logo=githubactions&logoColor=white" alt="DeadLinkFinder Marketplace" /></a>
      <a href="https://github.com/umutgungorr/deadlinkfinder/releases/tag/v0.2.1"><img src="https://img.shields.io/badge/Release-v0.2.1-2f81f7.svg?style=flat-square" alt="v0.2.1" /></a>
      <a href="https://github.com/umutgungorr/deadlinkfinder"><img src="https://img.shields.io/badge/SARIF-Fingerprints-orange.svg?style=flat-square" alt="SARIF Fingerprints" /></a>
      <br /><br />
      <sub>Validates local documentation links, missing assets, and GitHub heading anchors offline. Emits stable SARIF fingerprints for Code Scanning.</sub>
    </td>
  </tr>
</table>

```yaml
# Instant CI/CD Integration via GitHub Actions
- uses: umutgungorr/tokenguard@v0.2.0     # Secret leak prevention & SARIF
- uses: umutgungorr/envdoctor@v0.2.0      # Environment contract integrity & JSON
- uses: umutgungorr/deadlinkfinder@v0.2.1  # Documentation anchor & asset verification
```

---

## 🚀 Full-Stack Products

Product-minded web applications built with type safety, clean domain boundaries, and local-first architecture:

- **[ChronoFlow](https://github.com/umutgungorr/chronoflow)** — *Local-first daily time-blocking application.*  
  Built with Next.js, TypeScript, Supabase, and Vitest. Enables structured daily planning without mandatory cloud account requirements.
- **[CVera](https://github.com/umutgungorr/cvera)** — *Privacy-first resume & job description analyzer.*  
  Evaluates technical alignment in-memory with deterministic heuristic rules. Zero external analytics, zero server-side storage of confidential resumes.

---

## ⚙️ Engineering Principles

- **Zero Runtime Dependencies**: CLI tools built strictly on the standard library. No supply-chain bloat, no resolver failures, minimal startup overhead.
- **Deterministic & Machine-Readable**: Reliable exit codes (`0` clean, `1` violation, `2` error), structured JSON output, and OASIS SARIF v2.1.0 standards for seamless CI/CD integration.
- **Security & Privacy by Default**: Local-first execution. Source code, secrets, and private credentials never leave the developer's machine or runner.
- **Defense in Depth**: Strict validation of inputs, isolated code-block analysis, and reproducible baseline tracking.

---

## 🧭 Current Focus

- Native GitHub Code Scanning & SARIF fingerprinting across CI workflows
- Cross-platform CLI performance on Linux, macOS, and Windows
- Pre-commit developer ergonomics and zero-overhead quality gates

---

<div align="center">

### Let's Build Something Meaningful

[![LinkedIn](https://img.shields.io/badge/LinkedIn-in%2Fumut--gungor-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=161b22)](https://www.linkedin.com/in/umut-gungor/)
[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-umutgungorr-2f81f7?style=flat-square&logo=githubactions&logoColor=white&labelColor=161b22)](https://github.com/marketplace?type=actions&query=umutgungorr)
[![Email](https://img.shields.io/badge/Email-umutm7944%40gmail.com-2ea44f?style=flat-square&logo=gmail&logoColor=white&labelColor=161b22)](mailto:umutm7944@gmail.com)

<sub>Open to collaborations, ambitious developer tooling ideas, and high-impact engineering roles.</sub>

</div>
