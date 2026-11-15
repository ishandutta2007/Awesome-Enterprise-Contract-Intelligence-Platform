# Awesome-Enterprise-Contract-Intelligence-Platform

## Top Enterprise Contract Intelligence Platform Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on AI-Powered Clause Extraction, Obligation Tracking & Self-Hosted Contract Reasoning*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Contract Intelligence**. These tools go beyond contract storage—using AI and NLP to extract obligations, flag risks, and surface portfolio-wide insights from executed agreements, helping legal and procurement teams understand what their contracts actually commit them to.

**Examples** include Icertis, SirionLabs, Ironclad, Evisort (Workday), DocuSign CLM, Agiloft, Conga, ContractPodAi, CobbleStone, Luminance, and open-source alternatives like draftLegal, Aakd, and OpenCLM (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted contract intelligence, open-source AI-assisted extraction, and community-driven CLM platforms—ideal for organizations seeking data sovereignty and avoiding six-figure enterprise licensing. The open-source landscape has matured to genuine viability: **draftLegal** provides AI-native contract reasoning with portfolio-wide hybrid retrieval , **OpenCLM** delivers full lifecycle fundamentals free under AGPL , and **Aakd** focuses on source-linked obligation tracking with human review .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis](https://www.icertis.com/)** | **Enterprise leader for obligation management and compliance at scale.** Gartner and Forrester position Icertis for large organizations with complex processes driven by post-signature obligation tracking. AI discovers commercial terms, compliance obligations, and risk markers, then matches them against invoices for buy-side contracts. Hybrid tenancy and on-premises options available. **AI packaging is cost-prohibitive for many customers**, and customers request better APIs and less cumbersome administration . | Quote-only (enterprise; top of market range)  | No free tier; demo via sales  |
| **[SirionLabs](https://www.sirion.ai/)** | **Specialist in supplier and post-signature obligations.** Ranked #1 in Gartner's Advanced Contract Analytics use case (score 4.03/5) and #2 in Postsignature (4.22/5)—the highest postsignature score in the evaluation . AI-driven analytics mine the portfolio for performance insights and risk analytics. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Ironclad](https://ironcladapp.com/)** | **Most common enterprise default for AI-first contracting.** Named a Gartner Magic Quadrant Leader and Forrester Wave leader. Praised for usability, strong Salesforce integration, native e-signature, and highly adopted AI features. Excels at presignature workflow—scored 3.90 in Presignature use case . **Weaker intelligence layer** compared to pure analytics platforms. | Quote-only (per-user subscription) | No free tier; demo via sales  |
| **[Evisort (Workday)](https://www.evisort.com/)** | **Contract AI folded into Workday.** Acquired by Workday and integrated as Workday Contract Intelligence. Scored 3.96 in Postsignature and 3.89 in Presignature use cases . Brings contract AI inside one of the largest enterprise software platforms. | Quote-only (Workday enterprise contract) | No free tier; demo via sales  |
| **[DocuSign CLM](https://www.docusign.com/)** | **Natural extension for companies already standardized on DocuSign signatures.** Full lifecycle CLM with strong e-signature heritage. Scored 3.82 in Full Life Cycle and 3.43 in Advanced Contract Analytics . | Quote-only (per-user subscription) | No free tier; demo via sales  |
| **[Agiloft](https://www.agiloft.com/)** | **No-code CLM with the highest Full Life Cycle score in Gartner's evaluation (4.08/5).** Also strong in Presignature (4.11) and Postsignature (4.02). No-code platform with multitenant SaaS, dedicated server, or on-premises deployment options . | Quote-only (enterprise; median ~$67,000/year) | No free tier; demo via sales  |
| **[Conga](https://www.conga.com/)** | CLM with structured approval workflows and contract analytics. Scored 3.63 in Full Life Cycle and 2.81 in Advanced Contract Analytics . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[ContractPodAi](https://contractpodai.com/)** | AI-powered legal platform (Leah) with contract management, review/analysis, and legal project management. Scored 3.89 across all three primary use cases (Presignature, Postsignature, Full Life Cycle) and **3.93 in Advanced Contract Analytics**—second only to Sirion . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[CobbleStone](https://www.cobblestonesoftware.com/)** | CLM with VISDOM AI for clause extraction, risk flagging, and post-execution compliance tracking. Scored 3.75 in Full Life Cycle and 3.69 in Postsignature . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Luminance](https://www.luminance.com/)** | Legal-grade AI that surfaces portfolio-wide trends in payment terms, liability exposure, and commercial commitments. Source-backed answers with clause-level citations. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | **The most ambitious open-source contract intelligence platform—positioned as Ironclad + Harvey combined.** Self-hosted, AI-native CLM with **~30 agent tools** over your contracts: search, cite, compare, draft, redline, route approvals—every write proposed on a confirm card first, most undoable . **Portfolio intelligence via hybrid retrieval (pgvector + Elasticsearch + RRF fusion)** lets the agent answer questions across your whole contract history—exposure, counterparties, auto-renewals, notice deadlines—with citations to the clause and section. **Bring-your-own model** (Anthropic, OpenAI, Gemini)—no vendor lock-in. `docker compose up` deployment. **Best for teams wanting Ironclad-class execution plus Harvey-class reasoning without six-figure SaaS fees.** |
| **[OpenCLM](https://openclm.ai/)** | — | **The most complete open-source CLM with full lifecycle fundamentals free forever.** **AGPL v3, self-hosted—no per-user fees, full data ownership**. Covers searchable repository, template and clause library, **multi-stage sequential and parallel approval workflows routed by value, type, or department**, built-in e-signatures, and renewal/obligation tracking with automated reminders . **Free plan includes 1 user with unlimited contracts and 5 e-signatures/month**; Professional from $49/month; Teams from $649/month . **Best for teams wanting Ironclad-class lifecycle fundamentals without licensing fees**—the trade-off is self-hosting and operational responsibility. |
| **[Aakd](https://github.com/aaked-app/aakd)** | [![Stars](https://img.shields.io/github/stars/aaked-app/aakd?style=social&color=white)](https://github.com/aaked-app/aakd/stargazers) | **Focused open-source CLM for source-linked post-signature operations.** AGPL-3.0. Upload executed PDF/DOCX, review **extracted fields, obligations, and exact source citations with page-level evidence**, correct anything wrong or missing, assign owners and due dates, track renewals, approvals, and completion evidence . **AI is optional**—assisted extraction remains reviewable and is never the canonical source of contract truth. Docker Compose with PostgreSQL, Redis, MinIO, and Mailpit. **Early-stage release**—authoring, templates, and autonomous agents are explicitly out of scope for the first version . **Best for teams wanting a narrow, auditable post-signature obligation tracker** rather than a full lifecycle suite. |
| **[OpenContracts](https://github.com/Open-Source-Legal/OpenContracts)** | [![Stars](https://img.shields.io/github/stars/Open-Source-Legal/OpenContracts?style=social&color=white)](https://github.com/Open-Source-Legal/OpenContracts/stargazers) | **Open-source citation graph substrate for legal documents—not a traditional CLM.** **MIT licensed** (fully permissive). Documents are nodes, citations are edges, annotations are the layer humans and agents build the graph from . **Corpuses with version control** (fork, restore, full history), custom label schemas, and **AI agents that reason over curated citation data** rather than hallucinating . **MCP server** exposes the corpus to Claude, Cursor, and any MCP-compatible tool . **Best for legal research, due diligence, and teams building custom contract intelligence pipelines** where the citation graph matters more than lifecycle workflows . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Catala](https://github.com/CatalaLang/catala)** | — | **Programming language for expressing law as code (Apache 2.0).** Developed by French research institute Inria. Intended as an alternative to proprietary rules engines for formalizing legal logic . **Best for teams wanting to encode contract logic as executable rules** rather than extract text with AI . |
| **[Open-Capture](https://github.com/Edissyum/opencapture)** | — | **Fully open-source document capture and reading solution (GPL v3).** French company Edissyum. Handles document ingestion and OCR—the upstream step before contract analysis . **Best for teams needing a self-hosted document intake pipeline** feeding into a custom intelligence layer . |

**Frameworks for building custom systems**: Choose **draftLegal** for AI-native contract reasoning and portfolio-wide cited retrieval , **OpenCLM** for full lifecycle fundamentals with approval workflows and e-signatures free , or **Aakd** for narrow, auditable post-signature obligation tracking —all without six-figure enterprise licensing. For teams needing a citation graph rather than a CLM workflow, **OpenContracts** provides a permissively-licensed substrate for building custom contract intelligence .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract intelligence platforms handle legally sensitive documents and privileged communications; enforce strict access controls, audit logging, and compliance with applicable data protection regulations. **AI-generated extractions and risk scores must be reviewed by qualified legal professionals before reliance.**
- **Enterprise CLM pricing is genuinely six-figure territory.** Mid-market platforms run **$15,000–$100,000/year**, while enterprise deployments reach **hundreds of thousands**, with Icertis typically at the top of the range . Implementations commonly take **three to six months**, and the largest can take longer . **Open-source contract intelligence has matured to genuine viability, but the projects split into distinct approaches.** **draftLegal** is the most ambitious—combining Ironclad-style execution with Harvey-style reasoning and portfolio-wide cited retrieval, but it is a newer project requiring self-hosting . **OpenCLM** provides the most complete lifecycle fundamentals (approvals, e-signatures, renewals) under AGPL v3, with a free tier for 1 user and paid tiers for teams . **Aakd** is explicitly an **early-stage release** focused narrowly on post-signature obligations with human review—not a full CLM . **OpenContracts** is **MIT licensed** but is a citation graph substrate, not a CLM—best for custom intelligence pipelines . **Validate data residency requirements, AI review workflows, and operational capacity** before committing to self-hosting.

---

**Made for legal ops teams, contract analysts, and developers building contract intelligence infrastructure.**  
Let's make enterprise contract intelligence more open, explainable, and auditable.
