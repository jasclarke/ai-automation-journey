# AI Automation Engineering Journey

A public log of my path to becoming a competent AI Automation Engineer, built around real automation projects and checked every week.

**Started:** October 14th 2026· **Target:** portfolio and first applications by month 12, solid junior-to-mid capability by month 15 ·

## Status

| | |
| --- | --- |
| **Current month** | 1 of 15 |
| **Current focus** | Python fundamentals and the document automation project |
| **Hours this week** | 0 of 12 |
| **Last log entry** |  N/A |
| **Next check-in** | Oct 15th 2026 5:00am |

## Goal

To design, build, test and run systems that connect LLMs to real business processes (triggers, data, APIs, decisions and human approval), and to prove each skill with working, measured projects rather than certificates.

## How This Repo Works

- **Weekly log:** one entry per week in [`log/`](log/), committed before my weekly check-in. Each entry records hours, what I built, exit criteria met, energy rating (1 to 5), blockers and next week's three commitments.
- **Accountability:** a fixed 20-minute weekly check-in with my accountability partner, who sees the log first and asks four questions: did I do what I committed to, what did I ship or learn, what is blocking me, and what are my next three commitments.
- **Monthly exit criteria:** pass or fail. If I miss one, that month extends by up to two weeks. I never skip it.
- **Light weeks:** every sixth week runs at half volume to protect against burnout.
- **Shipping rhythm:** something visible (a repo, a demo video or a short write-up) every two to three weeks.

## The Projects

| # | Project | Months | Main lesson |
| --- | --- | --- | --- |
| 1 | Document automation: merge emailed Word and PDF files into one PDF and publish it to a website | 1 to 3 | Python first, then n8n orchestrating and Python handling custom logic |
| 2 | Website and social media performance report with recommendations | 3 to 6 | Multi-API data engineering, with SQL doing the arithmetic and the LLM interpreting |
| 3 | Content drafting with human approval before publication | 7 to 8 | LLM workflows, human-in-the-loop, evals and untrusted input |
| 4 | Legal and regulatory assessment assistant with citations | 10 to 11 | Retrieval with citations, agents, security and auditability |

Project code lives in separate repositories and is linked here once it is sanitized and approved for sharing.

## Monthly Exit Criteria

- [ ] **Month 1:** working document processor, GitHub repo with a README, basic logging and error handling
- [ ] **Month 2:** end-to-end Python automation with website upload working, tests, configuration and documentation
- [ ] **Month 3:** n8n version of project 1 running, Python plus n8n hybrid documented, project 2 proof of concept pulling real data, deployed webhook receiver with tests, LLM summary step passing its number check
- [ ] **Month 4:** two data sources flowing into PostgreSQL on a schedule, validated data models, automated tests
- [ ] **Month 5:** multi-source pipeline, FastAPI service, automated tests, first report delivered to a real recipient
- [ ] **Month 6:** AI-enhanced report with structured output, a measured accuracy figure from my eval, a written prompt-versioning approach
- [ ] **Month 7:** working draft-to-approval workflow, source tracking, approve and edit rates logged, a prompt-injection test set
- [ ] **Month 8:** portfolio-ready project 3, architecture diagram, eval results with numbers, cost report, failure-modes document
- [ ] **Month 9:** containerized project, automated deployment pipeline, operational documentation, first case study published
- [ ] **Month 10:** written scope, working retrieval with correct citations on a test set, evidence and citation model
- [ ] **Month 11:** capstone prototype, evaluation dataset with results, security and audit controls documented
- [ ] **Month 12:** portfolio with case studies, application package, a written service or product hypothesis with at least three conversations held
- [ ] **Months 13 to 15:** buffer for anything that slipped, first paid or pro bono delivery, optional certification

## Weekly Log Index

| Week | Dates | Hours | Energy | Highlight |
| --- | --- | --- | --- | --- |
| 1 | [dates] | | | |

Each entry follows the template in [`log/TEMPLATE.md`](log/TEMPLATE.md).

## Repository Layout

```
.
├── README.md        This file
├── log/             Weekly entries and the template
├── notes/           Learning notes by month
└── projects/        Links to project repositories
```