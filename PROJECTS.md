# Project catalogue

[Back to my profile](README.md) · [Français](PROJECTS.fr.md)

Personal and founder projects by **Enzo Buidine**. I direct the product and design work and use coding agents to help implement and iterate. The technologies below describe the projects, rather than a claim of independent expertise in every part of each stack.

Public links and documentation reviewed on **10 November 2026**. Local prototype descriptions are based on their source documentation; their test suites were not rerun for this catalogue.

## RFQ Review

**Document comparison and human review.** A working demonstration connects a request, a supplier quote and a purchase order. Its 100/100/150 quantity example makes the discrepancy and supporting document available in the same flow.

- **My contribution:** workflow, information hierarchy, review states and agent-assisted implementation.
- **What to inspect:** the quantity comparison, source disclosure and explicit review controls.
- **Status:** public synthetic demonstration; decisions remain in the browser tab.

[Open RFQ Review](https://v1-revue-rfq-enzo.netlify.app/app?lang=en)

## Lexia

<img src="https://lexiafordev.netlify.app/brand/lexia-handmade-symbol.png" alt="Lexia — approved handmade blue symbol" width="42" />

**AI evidence and review workflows.** Lexia connects observations, source material, findings and review. Its public workshop exposes content, signature and reference-key checks separately so a reader can see what changes when a record is edited.

- **My contribution:** founder, product scope, visual identity, interface and agent-assisted development.
- **Project technologies:** React, TypeScript, Vite, FastAPI, Python, PostgreSQL/SQLite; GitHub integration and report exports.
- **Status:** public presentation and interactive examples. Online scans are paused. Examples use fictitious data and do not establish legal compliance.

[Open Lexia](https://lexiafordev.netlify.app/) · [Explore the visual work](https://enzo-buidine-portfolio.vercel.app/#lexia)

## BUIDINE Galerie

**Curation and spatial interaction.** A digital art gallery with a rotunda, a dome, exhibition journeys and Maison intérieure. The project explores how selecting and arranging artworks changes a digital space.

- **My contribution:** curation, visual direction, experience design and agent-assisted prototyping.
- **Project technologies:** Next.js, React, TypeScript and Three.js; Supabase for the wider application.
- **Status:** gallery and Maison intérieure are public. Artworks remain attributed to their artists. Architectural studies are digital interpretations; this catalogue makes no claim of sales or payment collection.

[Visit the gallery](https://buidine-galerie.vercel.app/) · [Maison intérieure](https://buidine-galerie.vercel.app/maison-interieure) · [The dome](https://buidine-galerie.vercel.app/coupole)

## Lexia Audit Action

**A companion GitHub integration.** The action submits an audit, polls its progress and exposes a job summary and report outputs. It supports workflow metadata, retries and a configurable result policy.

- **My contribution:** product direction and agent-assisted release work within Lexia.
- **Project technologies:** TypeScript, Node.js and GitHub Actions.
- **Status:** public MIT-licensed source and a `v1.0.0` release. End-to-end audits require a configured Lexia backend; the public backend is currently paused.

[Source and usage](https://github.com/uti-blip/lexia-action) · [Release](https://github.com/uti-blip/lexia-action/releases/tag/v1.0.0)

## AXIOM

**Permissions and approval for agent actions.** A prototype gateway evaluates a proposed tool action, asks for approval when required and records the outcome in a receipt. The first implementation targets GitHub issue creation in an explicitly permitted repository.

- **My contribution:** product framing, approval/review experience and development with coding agents.
- **Project technologies:** Python, FastAPI, Next.js, TypeScript, PostgreSQL, a policy engine and an MCP adapter.
- **Status:** local private-beta implementation. Hosted identity and real provider execution remain unverified. Source is private; this public catalogue contains a description only.

## Counterfactual

**Inspectable economic simulation.** A research application compares marketplace scenarios with explicit assumptions, paired random seeds, source configurations and downloadable reports.

- **My contribution:** product framing, decision and comparison workflows, and agent-assisted implementation.
- **Project technologies:** Python, FastAPI, Next.js, TypeScript, ECharts, SQLite/PostgreSQL and a separate simulation worker.
- **Status:** local research and private-pilot prototype. Simulated outcomes are conditional on the model; real-world forecasting and customer decision value have not been established. Source is private.

## EconPlay

**Learning finance through play.** Interactive lessons, budgeting scenarios and progression systems. A separate local extension explores investment mandates, approval, delegation limits and a fictitious portfolio.

- **My contribution:** product direction, learning and decision flows, and agent-assisted development.
- **Project technologies:** React, Vite, TypeScript, Hono/tRPC, Drizzle and PostgreSQL in the full local application.
- **Status:** a public static learning demo and a separate local agent prototype. The public demo does not provide the full persistent backend. No brokerage access, real orders or investment returns are claimed.

[Open the public learning demo](https://econplay-app.vercel.app/)

## Outreached

**A B2B prospecting workspace.** Prospect records, CSV import, deduplication, editable drafts, manual follow-up, opposition records and exports.

- **My contribution:** workflow framing and agent-assisted implementation for prospecting operations.
- **Project technologies:** Python, FastAPI, Next.js, TypeScript and SQLite/PostgreSQL.
- **Status:** public source; the hosted workspace requires authentication. A recorded send does not prove delivery or response. Recruiters can inspect the code without access to prospect data.

[Read the source and setup](https://github.com/uti-blip/outreached)

## Fabric Passport

**Textile traceability.** A prototype for supplier onboarding, digital product passports, product records and audit trails.

- **My contribution:** product exploration and development with coding agents.
- **Project technologies:** Next.js, TypeScript, Tailwind, FastAPI and SQLite.
- **Status:** public source. The repository describes the prototype; a current hosted deployment and regulatory readiness were not verified for this catalogue.

[Read the source and setup](https://github.com/uti-blip/fabric-passport)

## PrediData

**Prediction markets with virtual points.** An earlier project exploring market discovery, binary predictions, a user portfolio and reputation-based rankings.

- **My contribution:** personal product exploration and development with AI tools.
- **Documented technologies:** Next.js, TypeScript, FastAPI and PostgreSQL.
- **Status:** earlier private prototype, described from its repository. Current runtime and external integrations were not verified. Virtual points are the documented scope; no real-money market or legal approval is claimed.

## ChainClose

**USDC financial-close workflows.** An earlier exploration of transaction review, categorisation, invoice matching and period-close checklists, with a frontend prototype and a backend API specification.

- **My contribution:** personal product exploration and AI-assisted prototyping.
- **Documented technologies:** React and TypeScript; the specification describes a FastAPI/PostgreSQL backend.
- **Status:** private prototype and specification, not presented as a verified operating financial service. No real transaction execution or completed accounting engagement is claimed.

## GrailSignal

**Watch resale intelligence.** A dashboard, product tracker, alert centre and reporting workflow. Listing matches retain a confidence value so ambiguous references can be separated from aggregate metrics.

- **My contribution:** product exploration, dashboard direction and agent-assisted implementation.
- **Project technologies:** Next.js, TypeScript, FastAPI, PostgreSQL and generated OpenAPI contracts.
- **Status:** source-documented prototype with demo data. This catalogue does not establish current live ingestion, commercial operation or customer adoption. Source is private.

## CopyLab

**Reproducible simulation research.** Local experiments in wallet-copying mechanics and a separate historical SOL price backtest. The work records assumptions, data provenance, costs, execution rules and independently recalculated reports.

- **My contribution:** experiment framing and agent-assisted implementation and documentation.
- **Project technologies:** Python, SQLite, JSONL/CSV and standalone HTML reports.
- **Status:** local research. All capital, decisions and executions are fictitious. This is not a live trading system or evidence of future returns. No trading credentials or private datasets are published here.

## Catalogue preparation

**Traceable data transformation.** A small local demonstrator converts a synthetic supplier file into a PrestaShop-style product CSV and produces an anomaly report. Missing or ambiguous business values remain flagged.

- **My contribution:** scope, output requirements and agent-assisted implementation.
- **Project technologies:** Python and CSV.
- **Status:** local demonstrator using synthetic records; no production import or completed customer engagement is claimed.

## Personal portfolio and atelier

**A visual practice across drawings, objects and space.** Original drawings become interactive compositions and 3D volumes, with source-image comparison and GLB export. The atelier also contains architectural interpretations and clothing silhouette studies.

- **My contribution:** original drawings, visual direction, composition, interactions and agent-assisted implementation.
- **Project technologies:** HTML, CSS, JavaScript, Three.js and GLB assets.
- **Status:** public interactive portfolio. Architectural volumes are digital studies. Clothing work is concept development; physical sampling and manufacturing are not established. Artists’ works displayed in the gallery remain separately credited.

[Open the portfolio](https://enzo-buidine-portfolio.vercel.app/) · [Interactive atelier](https://enzo-buidine-portfolio.vercel.app/#atelier) · [Clothing studies](https://enzo-buidine-portfolio.vercel.app/#vetement)

## Repository map

The public repositories linked above expose source that can be inspected today. Private projects are represented by their public demos or the descriptions on this page. The earlier `LEXIAAA` repository belongs to the history of Lexia. The empty `lexia.ai-` repository and the `lexia-test-repo` scanner fixture are not additional finished products.

[Back to my profile](README.md) · [Contact on LinkedIn](https://www.linkedin.com/in/enzo-buidine-48b92830b/)
