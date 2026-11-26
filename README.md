<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg" />
    <img alt="Nguyen Thanh Long — Fullstack Web Developer" src="assets/banner-light.svg" width="100%" />
  </picture>

  <br />

  <a href="mailto:thanhlongnguyen101105@gmail.com">
    <img alt="Email Nguyen Thanh Long" src="https://img.shields.io/badge/Email-thanhlongnguyen101105%40gmail.com-0284c7?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://planora-ivory-tau.vercel.app">
    <img alt="Planora Live Demo" src="https://img.shields.io/badge/Live_App-Planora-0f172a?style=flat-square&logo=vercel&logoColor=white" />
  </a>
  <a href="https://ai-slide-generator-omega.vercel.app">
    <img alt="DeckAI Live Demo" src="https://img.shields.io/badge/Live_App-DeckAI-0f172a?style=flat-square&logo=vercel&logoColor=white" />
  </a>
  <a href="https://eat-now-app.vercel.app">
    <img alt="EatNow Live Demo" src="https://img.shields.io/badge/Live_App-EatNow-0f172a?style=flat-square&logo=vercel&logoColor=white" />
  </a>
</div>

---

### About Me

I am a **Fullstack Web Developer** focused on building reliable, maintainable web products end-to-end — from responsive **React & TypeScript** workspaces to structured **Node.js, Express, PostgreSQL, and MongoDB** backends.

- **Product & Systems Focus:** Experienced in designing human-in-the-loop workflows, multi-stage worker pipelines, JWT/OAuth session security, rate-limited APIs, and real-time Server-Sent Events (SSE).
- **Engineering Discipline:** Strong emphasis on clear API contracts, database schema migrations, reproducible Docker environments, and automated testing.
- **Contact:** Reach me directly at **[thanhlongnguyen101105@gmail.com](mailto:thanhlongnguyen101105@gmail.com)**.

---

### Core Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Backend & Database** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=black) |
| **DevOps & Tooling** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) |

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Planora — AI Workflow Automation Platform</h3>
      <p>
        <code>React 19</code> · <code>TypeScript</code> · <code>Tailwind 4</code> · <code>Zustand</code> · <code>Node.js</code> · <code>Express 5</code> · <code>PostgreSQL 16</code> · <code>Docker</code>
      </p>
      <ul>
        <li>Chat-driven multi-step automation across GitHub, Trello, Slack, Jira, Notion, and Google Workspace with a mandatory SHA-256 <code>plan_hash</code> human approval gate before any external write.</li>
        <li>Streams live step execution via Server-Sent Events (SSE), isolates workspace OAuth credentials with AES-256-GCM, and runs Vitest + Playwright E2E suites in CI.</li>
      </ul>
      <p>
        <a href="https://planora-ivory-tau.vercel.app"><strong>Live Demo</strong></a> ·
        <a href="https://planora-ivory-tau.vercel.app/?view=sandbox"><strong>Interactive Sandbox</strong></a> ·
        <a href="https://github.com/longnguyen005/planora"><strong>Frontend Repo</strong></a> ·
        <a href="https://github.com/VinhDat267/ATI_Project"><strong>Fullstack Monorepo</strong></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>DeckAI — AI Slide Generator</h3>
      <p>
        <code>React 19</code> · <code>JavaScript</code> · <code>Node.js</code> · <code>Express</code> · <code>MongoDB</code> · <code>Mongoose</code> · <code>JWT</code> · <code>Docker</code>
      </p>
      <ul>
        <li>Stage-gated presentation studio (Prompt &rarr; Outline &rarr; 5-Layout Canvas &rarr; 4 Brand Themes &rarr; Presenter View) with SlideVersion restore, PDF handouts, and themed <code>.pptx</code> export.</li>
        <li>Engineered with hybrid Instant Demo (server seeding + &lt;3.5s offline sandbox fallback), multi-key Gemini rotation/fallback chains, Zod validation, and GitHub Actions CI.</li>
      </ul>
      <p>
        <a href="https://ai-slide-generator-omega.vercel.app"><strong>Live Demo</strong></a> ·
        <a href="https://github.com/longnguyen005/AI-SLIDE-GENERATOR"><strong>Source Code</strong></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>ResumeAI — ATS Resume Analyzer &amp; Job Fit Scoring</h3>
      <p>
        <code>React 18</code> · <code>FastAPI</code> · <code>SQLAlchemy 2.0 Async</code> · <code>PostgreSQL 16</code> · <code>Alembic</code> · <code>Docker</code> · <code>n8n</code> · <code>OCR</code>
      </p>
      <ul>
        <li>Fullstack ATS optimization platform featuring server-verified Keyword Gap Matrices, parser readability diagnostics, cached JD re-scoring, side-by-side 2-version CV comparison, and print-ready PDF reports.</li>
        <li>Engineered with Hybrid Instant Demo (24h ephemeral PostgreSQL seeding + &lt;3.5s browser sandbox fallback), <code>SELECT ... FOR UPDATE</code> row locking across <code>inline</code> &amp; <code>n8n</code> worker pipelines, and PostgreSQL 16 CI suites.</li>
      </ul>
      <p>
        <a href="https://github.com/longnguyen005/SS2_Project_Resume-Analyzer-Job-Fit-Scoring"><strong>Source Code &amp; Architecture Docs</strong></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>EatNow — Food Discovery &amp; FootBot</h3>
      <p>
        <code>Next.js</code> · <code>React 19</code> · <code>TypeScript</code> · <code>Tailwind CSS</code> · <code>Supabase (PostgreSQL)</code> · <code>Google Maps API</code>
      </p>
      <ul>
        <li>Fullstack restaurant discovery and ordering web app featuring interactive Google Maps browsing, real-time menu filtering, and cart checkout flows.</li>
        <li>Includes <code>FootBot</code>, an AI food-discovery assistant powered by Gemini function calling and atomic per-user PostgreSQL RPC rate limiting.</li>
      </ul>
      <p>
        <a href="https://eat-now-app.vercel.app"><strong>Live Demo</strong></a> ·
        <a href="https://github.com/kurumi-hub/Eat_now_app"><strong>Team Repository</strong></a>
      </p>
    </td>
  </tr>
</table>

---

### Additional Engineering Work

- **[Explainable_GEC_Long](https://github.com/longnguyen005/Explainable_GEC_Long)** (`Python` · `spaCy` · `Reproducible ML`): Audited grammatical error detection pipeline (`SVA`/`VFORM`/`NNUM`) built with strict train/dev/test isolation guards, SHA-256 artifact manifests, dependency-parse feature extraction, and automated unit tests.
