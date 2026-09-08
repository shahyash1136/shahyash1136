<p align="center">
  <img src="https://avatars.githubusercontent.com/u/43175218?v=4" width="120" style="border-radius:50%;" alt="Yash Shah" />
</p>

<h1 align="center">Hey, I'm Yash Shah 👋</h1>
<h3 align="center">Frontend Engineer (10 yrs) → building toward AI / Agentic AI Engineering</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Senior+Consultant%2C+Frontend+%40+EY;Building+multi-agent+systems+with+OpenAI+Agents+SDK;React+%2F+TypeScript+specialist+%E2%80%94+10+years+in+production" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/shahyash1136"><img src="https://skillicons.dev/icons?i=github" width="38" title="GitHub" /></a>
  <a href="https://medium.com/@shahyash1136"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/medium.svg" width="34" title="Medium" style="filter:invert(1); margin: 0 6px;" /></a>
</p>

<p align="center"><sub>📍 Mumbai, India</sub></p>

<br/>

## 💫 About Me

- 🧑‍💻 **Frontend Engineer, 10 years** — React, TypeScript, Redux, micro-frontend architecture
- 🏢 Currently **Senior Consultant, Frontend @ EY**
- 🤖 Actively building **agentic AI systems** with the **OpenAI Agents SDK** — multi-agent orchestration, guardrails, tracing, approval workflows
- ✍️ Writing a Medium series on building AI agents in TypeScript as I build them
- 🎯 Not switching lanes — extending 10 years of production frontend discipline into AI engineering

<br/>

## 🧭 Engineering Journey

## 🧭 Engineering Journey

```mermaid
flowchart LR
    A["🎓 Software Engineering"] --> B["⚛️ Frontend Specialization"]
    B --> C["🏗️ Scalable Architecture"]
    C --> D["🤖 AI Engineering"]
    D --> E["🕸️ Agentic Systems"]

    classDef phase1 fill:#1e1b4b,stroke:#818cf8,stroke-width:2px,color:#ffffff
    classDef phase2 fill:#312e81,stroke:#a5b4fc,stroke-width:2px,color:#ffffff
    classDef phase3 fill:#4c1d95,stroke:#c084fc,stroke-width:2px,color:#ffffff
    classDef current fill:#6d28d9,stroke:#e9d5ff,stroke-width:3px,color:#ffffff

    class A phase1
    class B,C phase2
    class D phase3
    class E current
```

| Phase | What it means |
|---|---|
| 🎓 Software Engineering | 10 years across web design, React development, and enterprise consulting |
| ⚛️ Frontend Specialization | Deep React/TypeScript work at Sportz Interactive and TCS |
| 🏗️ Scalable Architecture | Micro-frontend and Module Federation work at scale, now at EY |
| 🤖 AI Engineering | Learning and applying the OpenAI Agents SDK |
| 🕸️ Agentic Systems | *(current)* — Employee AI Assistant: multi-agent orchestration, guardrails, tracing |

Frontend engineering is still the foundation — the agentic work is built with the same architecture-first, production-quality bar.

<br/>

## 🚀 Featured Project — Employee AI Assistant

A multi-agent backend for querying and acting on employee data, built with **TypeScript, Node.js, Express, React, and the OpenAI Agents SDK**.

```mermaid
flowchart TD
    U["User Query"] --> O["Orchestrator"]
    O --> E1["Employee Agent"]
    O --> E2["Attendance Agent"]
    O --> E3["Department Agent"]
    O --> E4["Performance Agent"]
    O --> E5["Project Agent"]
    O --> E6["Salary Agent"]
    E1 & E2 & E3 & E4 & E5 & E6 --> G["Guardrails\n(hallucination · injection · sensitive-info · tool misuse)"]
    G --> AP["Approval Workflow"]
    AP --> T["Tracing & Structured Logging"]
    T --> R["Streamed Response"]

    style O fill:#312e81,stroke:#818cf8,color:#fff
    style G fill:#7f1d1d,stroke:#f87171,color:#fff
    style AP fill:#78350f,stroke:#fbbf24,color:#fff
    style T fill:#064e3b,stroke:#34d399,color:#fff
```

| Area | Implementation |
|---|---|
| Orchestration | Central orchestrator routes to six domain agents (employee, attendance, department, performance, project, salary), each built from a shared agent factory |
| Guardrails | Dedicated checks for hallucination, prompt injection, sensitive-info exposure, and tool misuse — each with its own test script |
| Approvals | Approval-store workflow gates sensitive actions before execution |
| Observability | Structured tracing with a dedicated trace store, logging processor, and trace API |
| Conversation | Session-managed, streaming chat over a dedicated chat route/controller |
| API surface | JWT auth, rate limiting, Zod validation, Swagger/OpenAPI docs |
| Data layer | CSV-backed services across all six domains |

**→ [github.com/shahyash1136/employee-ai-assistant](https://github.com/shahyash1136/employee-ai-assistant)**

<br/>

## 📁 Other Projects

| Project | What it does | Stack |
|---|---|---|
| **agentic-ticket-processing** | Support-ticket triage built on a layered agent architecture — intent classification, detection, and routing | Python |
| **pdf-to-excel-python** | Desktop app extracting tables from digital and scanned PDFs (OCR), merging matched tables into an Excel workbook | Python, pdfplumber, pytesseract, openpyxl |
| **micro-frontend** | Two federated apps exploring Module Federation patterns used in production frontend work | TypeScript |

<br/>

## 🛠️ Tech Stack

**Frontend**

<img src="https://skillicons.dev/icons?i=react,typescript,javascript,redux,sass,vite,webpack" alt="frontend stack" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,python" alt="backend stack" />

**AI / Agentic & Testing**

<img src="https://skillicons.dev/icons?i=openai,jest,vitest" alt="ai and testing stack" />

<br/>

## 📚 Currently Exploring

- Structured ML/AI coursework, tracked against a phased learning plan
- DSA and system design, preparing for product-company interviews
- Docker, with a roadmap toward containerizing a full React/Node/MongoDB stack

<br/>

## ✍️ Writing

*Building AI Agents with OpenAI Agents SDK (TypeScript)* on Medium — walking through the agentic concepts (agents, tools, handoffs, MCP, tracing) as I apply them to the Employee AI Assistant build.

**→ [medium.com/@shahyash1136](https://medium.com/@shahyash1136)**

<br/>

## 💼 Experience

| Company | Role | Dates |
|---|---|---|
| EY | Senior Consultant, Frontend | Oct 2024 – Present |
| Tata Consultancy Services | I.T. Analyst | Mar 2022 – Oct 2024 |
| Sportz Interactive | Associate → Senior Associate, React/CSS Developer | May 2018 – Feb 2022 |
| Senseware Infomedia | Jr. Web Designer | Apr 2016 – May 2018 |

<br/>

<p align="center"><sub>Open to product-company frontend and AI engineering conversations</sub></p>
