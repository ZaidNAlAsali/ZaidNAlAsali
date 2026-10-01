<p align="center">
  <img src="./assets/profile-banner.svg" width="100%" alt="Zaid AlAsali, Full-Stack Software Engineer" />
</p>

<p align="center">
  <a href="#keystone">Keystone</a>
  &nbsp;&middot;&nbsp;
  <a href="#selected-work">Selected work</a>
  &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/zaidalasali/">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:ZaidNaderAlAsali@outlook.com">Email</a>
</p>

<p align="center"><strong>Full-stack engineer who builds bilingual Arabic/English products, from the first spec to the signed installer.</strong><br />
AI-native: I write the spec, own the architecture and direct coding agents like Claude Code and Codex, then prove the work with tests and CI.<br />
Amman, Jordan &middot; Open to roles in Doha, Qatar and the GCC &middot; Available immediately</p>

## Keystone

A school management system for a kindergarten in Amman, built to replace the paid platform its office was using: enrollment, fees and installments, receipts, payroll and printed agreements, in Arabic and English with full right-to-left support.

<table>
  <tr>
    <td width="50%" valign="top"><img src="./assets/keystone/dashboard.jpg" alt="Keystone dashboard in English" /></td>
    <td width="50%" valign="top"><img src="./assets/keystone/arabic.jpg" alt="Keystone dashboard in Arabic, right to left" /></td>
  </tr>
</table>

- **How I built it:** I audited the old platform feature by feature, wrote the spec and set the architecture, then directed Claude Code through the build. Two weeks from first commit to signed installer.
- **Offline-first desktop app:** Next.js 16 and React 19 inside Electron, SQLite with versioned migrations, verified daily backups and Ed25519-signed updates.
- **Money that always adds up:** amounts stored as integer fils, installments that sum exactly, and voided payments that keep their receipt number.
- **Arabic done properly:** receipts and agreements write amounts in grammatically correct Arabic words, in full right-to-left layouts.
- **Proof:** 188 automated tests, plus lint, type checks and a production build on every push in Windows CI.

<details>
<summary>Printed receipt</summary>
<br />
<img src="./assets/keystone/receipt.jpg" width="70%" alt="Keystone printed payment receipt with the amount written in words" />
</details>

<sub>The repository is private because it runs a real school. The screenshots use a fictional school, and every name and amount in them is invented.</sub>

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ZaidNAlAsali/signaldesk">
        <img src="https://raw.githubusercontent.com/ZaidNAlAsali/signaldesk/main/docs/screenshots/signaldesk-dashboard.png" alt="SignalDesk bilingual decision console" />
      </a>
      <h3><a href="https://github.com/ZaidNAlAsali/signaldesk">SignalDesk</a></h3>
      <p>Bilingual Arabic/English AI triage console. An LLM sorts requests against retrieved policy, personal data is redacted before any model call, a human approves or overrides every decision, and every step lands in a hash-chained audit log. <strong>Portfolio demo, not publicly deployed.</strong></p>
      <p><strong>Evidence:</strong> the <a href="https://github.com/ZaidNAlAsali/signaldesk/actions/runs/29211319312">verified main CI run</a> passed 15 backend tests (86.73% coverage) and 9 frontend tests, and the <a href="https://github.com/ZaidNAlAsali/signaldesk/blob/main/services/api/eval/results/demo-evaluation.json">bilingual regression set</a> passes 24/24.</p>
      <p><code>Next.js</code> <code>TypeScript</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://differentdesign.pro/">
        <img src="https://differentdesign.pro/og-image.png" alt="Different Design creative studio website, Dubai" />
      </a>
      <h3><a href="https://differentdesign.pro/">Different Design</a> <small>Dubai, UAE</small></h3>
      <p>Designed, built and launched a Dubai creative studio's website as its only engineer, from UI, imagery and SEO to domain, hosting and handoff. Web Developer and Technical Lead, Jun 2025 to Feb 2026.</p>
      <p><strong>Live evidence:</strong> the deployed site's metadata credits <strong>Zaid Nader AlAsali</strong> as developer.</p>
      <p><code>React</code> <code>Vite</code> <code>Framer Motion</code> <code>Vercel</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ZaidNAlAsali/ZFileConverter">ZFileConverter</a></h3>
      <p>Relaunched an open-source Windows Explorer file converter: a rebuilt WPF interface with dark and light themes, PDF to DOCX, output validation and SHA-256-verified updates, shipped as MSI releases.</p>
      <p><a href="https://github.com/ZaidNAlAsali/ZFileConverter/releases"><img src="https://img.shields.io/github/downloads/ZaidNAlAsali/ZFileConverter/total?label=installer%20downloads&color=1B3358" alt="Installer downloads" /></a> <a href="https://github.com/ZaidNAlAsali/ZFileConverter/releases/latest"><img src="https://img.shields.io/github/v/release/ZaidNAlAsali/ZFileConverter?label=latest&color=1B3358" alt="Latest release" /></a></p>
      <p><code>C#</code> <code>.NET</code> <code>WPF</code> <code>WiX</code> <code>GitHub Actions</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ZaidNAlAsali/filenest">FileNest</a></h3>
      <p>Offline Windows file organizer: streaming BLAKE3 duplicate detection, FTS5 search, move-only cleanup plans and integrity-checked undo.</p>
      <p><strong>Evidence:</strong> <a href="https://github.com/ZaidNAlAsali/filenest/actions/runs/29206861576">Windows CI</a> passed 20 Rust and 8 frontend tests and built the NSIS installer.</p>
      <p><code>Rust</code> <code>Tauri 2</code> <code>React</code> <code>SQLite</code></p>
    </td>
  </tr>
</table>

## Core stack

**Build:** TypeScript · React / Next.js / Vite · Node.js · Python / FastAPI · C# / .NET / WPF · PostgreSQL / SQLite · Electron / Tauri · Docker · GitHub Actions

**AI:** Claude Code and Codex (agentic coding) · OpenAI, Claude and Gemini APIs · RAG · structured outputs · evals

## Education and certifications

**BSc Computer Science**, University of Debrecen, Hungary (2026), on a Stipendium Hungaricum government scholarship. Thesis: an AI pipeline that turns text prompts into VR-ready 3D heritage assets (Hunyuan3D 2.0, Blender, Unity, Meta Quest 3).

Microsoft Certified: Azure AI Fundamentals (AI-900) · Information Technology Specialist: Software Development, HTML and CSS · NVIDIA DLI: Fundamentals of Deep Learning, Generative AI with Diffusion Models

<p align="center">
  <strong>Let's build something useful.</strong><br />
  <a href="mailto:ZaidNaderAlAsali@outlook.com">ZaidNaderAlAsali@outlook.com</a>
</p>
