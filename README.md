<!-- Showcase repository: the product is real and in use, its source code is private. -->

<a href="https://spead.ai"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg"><img src="assets/banner-light.svg" width="100%" alt="Spead AI. A multi-company AI workspace for cited chat, document Q&A and document creation."></picture></a>

<p align="center"><a href="https://spead.ai"><b>Open spead.ai</b></a> · <a href="https://github.com/nugrahalabib">More of my work</a> · <a href="https://nugrahalabib.com">nugrahalabib.com</a> · <a href="mailto:nugrahalabib@gmail.com">Email</a></p>

<p align="center"><a href="#the-business">The business</a> · <a href="#product-tour">Product tour</a> · <a href="#for-developers">For developers</a></p>

## Overview

Spead AI is an AI workspace for organisations. Staff chat with an AI Partner that cites its sources, ask questions over the company's own documents, and create documents, slide decks and infographics from templates and letterheads.

Generic language models do not know a company's templates, approval chains or past reports. Spead AI indexes those documents, lets admins approve what enters the knowledge base, and keeps each company's data and agent workspace separate from every other company.

The product started as a 2025 prototype and moved to production in 2026. It is built for private cloud or on-premise deployment, for government bodies, state-owned enterprises and regulated companies. Spead AI was incubated at Caliana Indonesia and graduated from the Google for Startups: AI Solution Lab Program 2025.

| | |
| --- | --- |
| **Status** | Running at [spead.ai](https://spead.ai) |
| **Role** | Founded and led by Nugraha Labib Mujaddid as Founder & Lead AI Engineer, from the first prototype to the production product. |
| **Period** | Since Nov 2025 |
| **Source** | Private. This repository presents the product; the code is not published. |

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/features-dark.svg"><img src="assets/features-light.svg" width="100%" alt="What Spead AI does: AI Partner chat, Doc Assistant, Knowledge Hub with approval, Document Studio, Templates and letterheads, Export to four formats, Collaboration, Connectors, Channels, Schedules."></picture>

## The business

Spead AI is an AI workspace for organisations in Indonesia. Every employee gets a personal assistant that answers from the company's own documents, cites the page it used, and only reads what that employee is allowed to open. The same workspace compares and extracts data from documents, writes official letters, reports and presentations on company templates, and connects to office systems with human approval for any change. Nugraha Labib Mujaddid founded Spead AI in November 2025 as Founder & Lead AI Engineer; the company was incubated at Caliana Indonesia and graduated from the Google for Startups: AI Solution Lab Program 2025.

### The problem

Knowledge workers lose a large part of the day looking for information. The business plan cites McKinsey research that a knowledge worker spends about 1.8 hours a day, or 8.8 hours a week, searching for and gathering internal information, and a Gartner survey in which 47% of digital workers say they struggle to find the information they need to do their job.

General AI tools have not closed that gap. The plan cites MIT Project NANDA, which found that about 95% of enterprise generative AI pilots showed no measurable effect on profit and loss, and McKinsey, which found that 88% of organisations use AI but only 39% report an effect on EBIT. The causes it names are the lack of internal context (a public model does not know a company's templates, SOPs or past reports), hallucination (commercial legal research tools built on retrieval still produced wrong answers on 17% to 33% of test questions) and errors that build up over multi-step work.

Indonesian organisations also carry legal risk when they paste documents into public AI services. The Personal Data Protection Law (UU PDP No. 27/2022) has been in full force since 17 October 2024, with administrative fines of up to 2% of annual revenue, strict rules on transfers abroad (Article 56), and a 3 x 24 hour breach notification duty. Government Regulation 71/2019 Article 20 requires public-sector electronic systems to manage and store data in Indonesia. On consumer AI services, uploaded content may be used for model training unless the user turns it off.

In interviews and user tests with more than 30 professionals across sectors, every respondent confirmed the time lost to manual paperwork and scattered documents, people who had tried public AI complained about generic or invented answers, and respondents from legal, finance and government named PDP compliance and an on-premise option as conditions before they would adopt any outside tool.

### Who uses it

| Role | What they do with it |
| --- | --- |
| **Employee** | Asks the assistant in everyday language through the web app, WhatsApp or Telegram, analyses documents in Doc Assistant and drafts letters, reports and slides in Document Studio. |
| **Company admin** | Sets up the workspace, builds units and positions, writes the rules every assistant follows, turns on connectors and watches quota and adoption. |
| **Knowledge manager** | Approves or rejects documents proposed for the knowledge base, sets confidentiality and labels, and checks what a given position can see. |
| **Template manager** | Maintains letterheads, brand kit, letter numbering and company templates, and decides which parts of a template are locked. |
| **Approver and signatory** | Initials, approves, returns with notes or signs documents that are routed to them, and approves actions the assistant wants to take. |
| **Executive** | Uses the assistant for meeting material and decisions, and reviews documents waiting for approval. |

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/before-after-dark.svg"><img src="assets/before-after-light.svg" width="100%" alt="Before and after: Search shared drives and ask colleagues for the right file becomes Ask the assistant and open the cited page of the source document; Paste confidential files into a public AI chat becomes Answers come only from documents the asker may open, inside the company workspace; Read two vendor contracts side by side to spot differences becomes Doc Assistant builds a comparison table where every cell links to its source; Copy an old letter, fix the letterhead, number and signature by hand becomes Document Studio fills a company template with locked letterhead, automatic numbering and a signing route; Access rules live in people's heads becomes Labels link documents to positions, and admins can preview what any position can see; Automations act without anyone noticing becomes Any action that sends or changes data waits for a person to allow it."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/journey-dark.svg"><img src="assets/journey-light.svg" width="100%" alt="How work flows: Set up the workspace, Shape the organisation, Approve knowledge, Ask with sources, Analyse documents, Create a document, Route and sign, Watch usage."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/value-dark.svg"><img src="assets/value-light.svg" width="100%" alt="What it changes: 1.8 h a day a knowledge worker spends looking for information (McKinsey, cited in the business plan); 47% of digital workers struggle to find the information they need (Gartner 2023, cited in the business plan); 30+ professionals across sectors in user acceptance tests and in-depth interviews; 87% less time on one agreement document in a team simulation (5 h 15 min down to 40 min), not yet measured at a client; 22,497 organisations in the addressable market in the plan's market sizing (14,623 in the serviceable market); 205 paying clients targeted in year five, 1.40% of the serviceable market (five-year projection)."></picture>

### Model and status

Business model. Spead AI is sold to organisations, not individuals, in three tiers named in the business plan: Pro for mid-sized companies and professional services, Enterprise for large corporations, and Custom Sovereign for state-owned enterprises and government bodies that need the system installed on their own servers or in a private cloud. Revenue comes from yearly subscriptions, add-ons for extra seats or compute quota, and one-time professional services for on-premise installation, single sign-on, data cleaning and training.

Go-to-market. The plan follows a barbell strategy: volume from the mid-market and professional services, and fewer, larger contracts with state-owned enterprises and government. Sales are direct and assisted, with a customer success manager during adoption. Caliana Indonesia's integrator network and existing corporate and government relationships act as the door opener, supported by founder-led content on LinkedIn and education on PDP compliance. The plan positions Spead AI against global AI workspaces such as Microsoft 365 Copilot and Notion AI, and against plain document storage such as Google Drive, SharePoint and Dropbox, with three differences: one assistant per employee across company systems, Indonesian official document formats, and an own-server option.

Traction and status. At the time of the business plan, traction came from validation rather than paid contracts: user acceptance tests and interviews with more than 30 professionals, a passed technical qualification and structured discussions for a trial with the National Archives of Indonesia (ANRI) around the SRIKANDI archive system, and the Google for Startups AI Solutions Lab programme. In October 2026 the product was deployed as Spead AI Pro for the tender and contract team of the EPCC Division at PT Wijaya Karya.

Five-year projection (labelled as a projection in the plan). The plan targets 3 paying clients in year one and 205 in year five, which is 1.40% of the serviceable market, and estimates a payback period of 25 months. The business plan was written as a New Venture Project in the Master of Management programme at Universitas Prasetiya Mulya.

## Product tour

<sub>Product screens below are captures of the Spead AI interface prototype with fictional sample data; the same interface runs live in Spead AI Pro. The first and last images are slides from the Spead AI pitch deck.</sub>

### 1. The case for Spead AI

The pitch deck opens with the problem the product answers: people lose hours searching, general AI does not know the company, and Indonesian law limits where data may go. Spead AI's answer is one assistant per employee that follows company rules and access rights.

- Each company has its own AI workspace and each employee has a personal assistant
- Requests come from the Spead screen, WhatsApp or a schedule
- Tools run with safeguards: the assistant opens only what the person may open
- Results come back as answers, documents or scheduled tasks with sources

<img src="assets/screens/01-deck-title.jpg" width="100%" alt="Title slide of the English pitch deck: an AI assistant for every employee that knows the company and respects access rights.">

<sub>Title slide of the English pitch deck: an AI assistant for every employee that knows the company and respects access rights.</sub>

<p><img src="assets/screens/02-deck-search-time.jpg" width="49%" alt="Problem slide: 1.8 hours per employee every working day spent searching for information (McKinsey)."> <img src="assets/screens/03-deck-genai-gap.jpg" width="49%" alt="Why general AI has not delivered results: it does not know the company's documents, SOPs and history."></p>

<sub>Left: Problem slide: 1.8 hours per employee every working day spent searching for information (McKinsey). · Right: Why general AI has not delivered results: it does not know the company's documents, SOPs and history.</sub>

<p><img src="assets/screens/04-deck-how-it-works.jpg" width="100%" alt="How Spead AI works in four steps, from an employee request to a sourced result."></p>

<sub>How Spead AI works in four steps, from an employee request to a sourced result.</sub>

### 2. AI Partner

AI Partner is the personal assistant every employee talks to. It answers from company documents with numbered sources, shows the steps it took, and asks before it sends or changes anything. It can also turn a request into a recurring schedule.

- Streaming answers with the work steps and thinking time shown
- Numbered citations that open the source document at the cited page
- Attachments such as spreadsheets are read together with company documents
- Actions like sending an email wait for Allow once, Always allow in this chat, or Deny
- Reminders and routine tasks created straight from the conversation

<img src="assets/screens/06-ai-partner-home.jpg" width="100%" alt="AI Partner home with suggested questions based on the employee's documents and position.">

<sub>AI Partner home with suggested questions based on the employee's documents and position.</sub>

<p><img src="assets/screens/07-ai-partner-cited-answer.jpg" width="49%" alt="An answer on contract employees' leave with a comparison table; the cited company regulation opens on the right at the highlighted article."> <img src="assets/screens/08-ai-partner-action-approval.jpg" width="49%" alt="Before sending an email through Gmail, the assistant shows the draft and waits for approval (recipient blurred)."></p>

<sub>Left: An answer on contract employees' leave with a comparison table; the cited company regulation opens on the right at the highlighted article. · Right: Before sending an email through Gmail, the assistant shows the draft and waits for approval (recipient blurred).</sub>

<p><img src="assets/screens/09-ai-partner-schedule.jpg" width="100%" alt="A weekly reminder created from one sentence in the chat, linked to the Schedules page."></p>

<sub>A weekly reminder created from one sentence in the chat, linked to the Schedules page.</sub>

### 3. Doc Assistant

Doc Assistant is for focused work on chosen documents. People pick a ready-made task, choose the files, and get a structured result where every statement links back to its source. Answers come only from the documents the person selected.

- Ready-made tasks: summarise, compare, translate and extract data to a table
- Guided setup: documents, aspects to compare, optional note
- Comparison tables with key differences and a differences-only switch
- Follow-up questions about the same set of documents
- Results can be copied, downloaded or opened in Document Studio

<img src="assets/screens/11-doc-assistant-tasks.jpg" width="100%" alt="Doc Assistant start screen with the ready-made tasks.">

<sub>Doc Assistant start screen with the ready-made tasks.</sub>

<p><img src="assets/screens/12-doc-assistant-compare-setup.jpg" width="49%" alt="Setting up a comparison: choose 2 to 5 documents, the aspects to compare and an optional note."> <img src="assets/screens/13-doc-assistant-compare-result.jpg" width="49%" alt="Comparison of two sample vendor contracts with key differences and a cited table (sample money figures blurred)."></p>

<sub>Left: Setting up a comparison: choose 2 to 5 documents, the aspects to compare and an optional note. · Right: Comparison of two sample vendor contracts with key differences and a cited table (sample money figures blurred).</sub>

### 4. Knowledge

Knowledge is the company library Spead answers from. Uploads are read, checked and, when proposed by employees, approved by a manager before the assistant may use them. Labels decide which positions can see each document.

- Status overview: used by Spead, being read, awaiting approval, not readable
- Approve as a new document or as a new version of an existing one
- Confidentiality levels and labels per document
- View as a position to check who can open a document
- Unanswered questions show where the library has gaps

<img src="assets/screens/14-knowledge-library.jpg" width="100%" alt="The knowledge library with read status, who can use each document and how often Spead used it.">

<sub>The knowledge library with read status, who can use each document and how often Spead used it.</sub>

<p><img src="assets/screens/15-knowledge-approval.jpg" width="49%" alt="Documents proposed by employees wait for approval; Spead spots that one is a newer version of an existing SOP."> <img src="assets/screens/16-knowledge-view-as-position.jpg" width="49%" alt="Document detail with the pages Spead read, confidentiality, and a view-as-position check that explains why a role cannot open it."></p>

<sub>Left: Documents proposed by employees wait for approval; Spead spots that one is a newer version of an existing SOP. · Right: Document detail with the pages Spead read, confidentiality, and a view-as-position check that explains why a role cannot open it.</sub>

<p><img src="assets/screens/17-knowledge-labels.jpg" width="100%" alt="Managing labels that link documents to positions."></p>

<sub>Managing labels that link documents to positions.</sub>

### 5. Organisation, onboarding and usage

Admins describe the company once and every assistant inherits it: units, positions, the documents each position may read, and rules that apply to all assistants. New workspaces start with a short setup, and the usage page shows whether the quota will last.

- Guided first setup with industry, first documents or sample documents
- Organisation tree of units, positions and people
- Document access per position through knowledge labels
- Company rules for every assistant, on top of fixed base rules
- Quota forecast, requests for more quota and adoption by person

<img src="assets/screens/10-onboarding-setup.jpg" width="100%" alt="First setup of a new workspace: industry and first documents.">

<sub>First setup of a new workspace: industry and first documents.</sub>

<p><img src="assets/screens/18-organisation-document-access.jpg" width="49%" alt="A position's document access: the labels it holds and the documents its assistants read."> <img src="assets/screens/19-organisation-company-rules.jpg" width="49%" alt="Company rules that every assistant follows, with suggestions, under base rules that nobody can loosen."></p>

<sub>Left: A position's document access: the labels it holds and the documents its assistants read. · Right: Company rules that every assistant follows, with suggestions, under base rules that nobody can loosen.</sub>

<p><img src="assets/screens/20-usage-quota.jpg" width="100%" alt="Usage page: will this month's quota last, who asked for more, and how actively Spead is used."></p>

<sub>Usage page: will this month's quota last, who asked for more, and how actively Spead is used.</sub>

### 6. Connectors, channels and schedules

Three tabs decide how far the assistant reaches. Connectors set what it can reach, channels set where people can contact it, and schedules set when it works on its own. Admins decide which positions may use each connector, and data changes always ask first.

- Catalog of office systems grouped by category, such as Google, Microsoft 365, Odoo and databases
- Per-connector choice of positions and whether data may change, with approval every time
- Employees request access and admins approve per position
- Schedules in plain language, skipping national holidays, with a test run before activation
- Items that need attention are listed first

<img src="assets/screens/21-connectors-catalog.jpg" width="100%" alt="Connector catalog grouped by category.">

<sub>Connector catalog grouped by category.</sub>

<p><img src="assets/screens/22-connector-access-request.jpg" width="49%" alt="Approving an employee's request for the Notion connector, only for the Marketing position."> <img src="assets/screens/23-connector-setup.jpg" width="49%" alt="Setting up Odoo: on for the company, and only for chosen positions."></p>

<sub>Left: Approving an employee's request for the Notion connector, only for the Marketing position. · Right: Setting up Odoo: on for the company, and only for chosen positions.</sub>

<p><img src="assets/screens/24-schedules.jpg" width="100%" alt="Schedules: routine tasks with their next run, plus items waiting for approval or a reconnection."></p>

<sub>Schedules: routine tasks with their next run, plus items waiting for approval or a reconnection.</sub>

### 7. Document Studio

Document Studio turns a short description into a finished document in the company's format. Spead asks a few questions, proposes a plan, then writes section by section. People then edit slides, documents and infographics in the browser.

- Official documents, presentations, reports and infographics
- Questions and an editable plan before anything is generated
- Slide editor with layouts, speaker notes and a side panel to ask Spead for changes
- Infographic blocks with charts driven by editable data
- Waiting-for-you list for documents to initial or approve

<img src="assets/screens/25-studio-home.jpg" width="100%" alt="Document Studio home with document types and documents waiting for the user.">

<sub>Document Studio home with document types and documents waiting for the user.</sub>

<p><img src="assets/screens/27-studio-presentation-plan.jpg" width="49%" alt="The slide plan Spead proposes before creating a presentation."> <img src="assets/screens/29-studio-slide-editor.jpg" width="49%" alt="Slide editor with the slide rail, speaker notes and the Spead panel scoped to one slide."></p>

<sub>Left: The slide plan Spead proposes before creating a presentation. · Right: Slide editor with the slide rail, speaker notes and the Spead panel scoped to one slide.</sub>

<p><img src="assets/screens/30-studio-infographic.jpg" width="100%" alt="Infographic editor with key numbers, steps and a bar chart whose data can be edited."></p>

<sub>Infographic editor with key numbers, steps and a bar chart whose data can be edited.</sub>

### 8. Official letters, signatures and templates

Indonesian official documents follow strict formats: letterhead, reference number, initials before signing and copies. Spead AI builds those rules into templates and a signing route, so a letter is final only when it is signed and numbered.

- Signatory and initials in a set order before signing
- Letter number reserved at signing from the numbering rules
- Saved signature that can be placed and resized, or print and sign by hand
- Template parts set as locked, values only or free
- Reports written section by section with progress shown

<img src="assets/screens/26-studio-letter-signature.jpg" width="100%" alt="Creating an official letter: signatory, initials in order, copies, and the estimated letter number.">

<sub>Creating an official letter: signatory, initials in order, copies, and the estimated letter number.</sub>

<p><img src="assets/screens/28-studio-progress.jpg" width="49%" alt="Spead writing a report section by section from the approved plan."> <img src="assets/screens/31-studio-sign.jpg" width="49%" alt="Signing dialog: the number to be assigned, signature placement, and the note that the letter becomes final."></p>

<sub>Left: Spead writing a report section by section from the approved plan. · Right: Signing dialog: the number to be assigned, signature placement, and the note that the letter becomes final.</sub>

<p><img src="assets/screens/32-template-part-locks.jpg" width="100%" alt="Template Studio: each part of an official letter template is locked, values only or free (sample letterhead contact details blurred)."></p>

<sub>Template Studio: each part of an official letter template is locked, values only or free (sample letterhead contact details blurred).</sub>

### 9. Deployment, security and validation

The same features run in three deployment options; only where the AI workspace and data live changes. The deck states what runs in the product today and what user testing found.

- Managed servers, the client's own servers, or an air-gapped installation
- One AI workspace per company and one assistant per employee
- Searches limited to documents linked to the asker's position
- Personal data encrypted with AES-256-GCM and passwords stored with scrypt
- Changes to assistant authority logged; daily database backups

<img src="assets/screens/05-deck-deployment-options.jpg" width="100%" alt="Deployment options: our servers, the client's servers, or no internet at all.">

<sub>Deployment options: our servers, the client's servers, or no internet at all.</sub>

<p><img src="assets/screens/33-deck-security.jpg" width="49%" alt="Security and data control as it runs in the product today, including where document excerpts go."> <img src="assets/screens/34-deck-user-testing.jpg" width="49%" alt="Three findings from interviews and user tests with more than 30 professionals."></p>

<sub>Left: Security and data control as it runs in the product today, including where document excerpts go. · Right: Three findings from interviews and user tests with more than 30 professionals.</sub>

## For developers

### Architecture

Spead AI is a monorepo with three applications. The API (apps/backend) runs on Node 22 with Fastify 5 and Prisma 6 over PostgreSQL 16 with pgvector. The web app (apps/web) is Next.js 14 with React 18, TipTap for documents, Konva for slides and infographics, TanStack Query, Radix UI and i18next. A separate export engine (apps/export-engine) renders PDF, PNG, PPTX and DOCX with Playwright Chromium, pdf-lib, pptxgenjs and docx, and a Python bridge uses python-docx for Word output.

Every company gets its own isolated agent workspace, and every user gets an agent inside it. Agents do not read the database directly: they search company documents through an internal tool endpoint on the API that is protected by a shared secret, so retrieval always passes through the API's access rules. Internal tools are exposed through the Model Context Protocol SDK (document search, user search, stats).

Retrieval is vector search over 768-dimension embeddings stored in pgvector for document chunks and conversation chunks, followed by reranking. Embeddings come from Gemini embeddings or a local transformer model, chosen by configuration; answers use Gemini models. Answers stream to the browser over server-sent events with citations.

Real-time features use Socket.IO rooms per user and company for notifications and document presence. Request bodies between the web app and the API are encrypted with an RSA key pair.

The newer product interface was designed by Nugi as a clickable prototype in which every module is specified as named scenarios (empty, loading, error, approval, trial, limits) before it is wired to an API. The screenshots in this showcase come from that prototype with its sample data; the same interface code runs in Spead AI Pro against a live API.

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/architecture-dark.svg"><img src="assets/architecture-light.svg" width="100%" alt="How Spead AI is built."></picture>

### Data model

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/data-model-dark.svg"><img src="assets/data-model-light.svg" width="100%" alt="Data model: sys_client, sys_user, sys_division / sys_role, sys_document, sys_document_chunk, log_conversation, generated_document, docstudio_template / docstudio_kop_template, docstudio_document_share / docstudio_comment, connector_koneksi / connector_izin, connector_audit / channel_audit, sys_client_token."></picture>

### Key flows

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/flow-1-dark.svg"><img src="assets/flow-1-light.svg" width="100%" alt="Answering a question with sources: The employee asks in AI Partner; the API checks the session and company. Then The company's agent calls the document search tool on the API. Then The API limits the search to documents tagged for the employee's role and runs vector search with reranking. Then The answer streams back over server-sent events with numbered citations. Then The web app opens the cited document at the right page."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/flow-2-dark.svg"><img src="assets/flow-2-light.svg" width="100%" alt="Adding a document to Knowledge: A user uploads a file; text is extracted on the server. Then An admin approves or rejects it; employees' uploads stay pending until then. Then Approved text is chunked and embedded into pgvector. Then Admins can re-index a document after changes."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/flow-3-dark.svg"><img src="assets/flow-3-light.svg" width="100%" alt="Creating a document in Document Studio: The user picks a type: document, presentation, infographic or report. Then The user picks a company template and letterhead. Then The agent asks about the content and can use chosen internal documents as sources. Then The agent fills the template slots, and the result opens in the matching editor. Then The export engine renders the final PDF, PNG, PPTX or DOCX."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/flow-4-dark.svg"><img src="assets/flow-4-light.svg" width="100%" alt="Calling an external system through a connector: An admin turns on a connector and chooses which roles may use it. Then Credentials are stored for the company, never shown back in logs. Then When the agent calls the connector, the outbound request is checked against the resolved IP address and private ranges are blocked. Then The call is written to the connector audit table. Then A scheduled re-test notifies admins only when a working connector starts failing."></picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/flow-5-dark.svg"><img src="assets/flow-5-light.svg" width="100%" alt="Onboarding a new company: The company is created as a tenant with its own quota. Then Its own agent workspace is provisioned, and each user gets an agent. Then The admin goes through the setup wizard: structure, first documents, invitations."></picture>

### Security

- Tenant boundaries are enforced in the Prisma data layer, computed from the schema at start-up, so a new table with a client_id column is protected without anyone registering it.
- Outbound connector requests are checked on the resolved IP address, not the host name text, which blocks private, loopback, link-local and cloud metadata ranges.
- Credentials in errors and logs are redacted by their shape (token prefixes, JWTs, long hex strings), not by a list of key names.
- The content security policy runs without unsafe-eval and unsafe-inline, using script hashes.
- Rate limits are shared across processes through Redis.
- Request bodies between the web app and the API are encrypted with an RSA key pair.
- Database backups run daily and are encrypted; a health check runs every five minutes.

### Quality

- 36 unit tests run in under one second (Jest).
- 370 end-to-end checks in 16 Playwright suites run against a live server.
- Moving the web app to a production build cut the frontend payload from 7.3 MB to 1.5 MB per page.
- Responsive guards are themselves tested to prove they can fail, so a green run means something.

### Deployment and operations

Linux servers running the API, web app and export engine as systemd services behind nginx with TLS.

The frontend is rebuilt as a production build on every change by a deploy script.

CI runs the unit tests; end-to-end suites run against a live environment.

Encrypted daily database backups, with a copy kept off the machine, and a health check every five minutes.

### Decisions

| Decision | Why |
| --- | --- |
| Tenant checks in the data layer | Checking client_id in every query by hand does not scale; enforcing it where Prisma builds queries protects new tables automatically. |
| One agent workspace per company | Each company's agents, memory and tools stay separate, which is also what regulated buyers ask for. |
| Agents search through the API | Retrieval goes through one endpoint that applies role-based access, so an agent cannot read a document its user may not open. |
| Separate export engine | Rendering PDF, PPTX and DOCX in its own process means an export failure never takes down chat or search. |
| Soft locks instead of character-level merging | Shared documents deliberately use presence, soft locks, comments and live sync rather than character-level CRDT merging, which keeps collaboration simple for office documents. |
| Discuss content before generating | Document Studio separates thinking about content from layout, which the template already fixes, so users do not fight the layout. |
| Notify on state change only | The connector re-test alerts only when a connector goes from working to failing, so alerts stay meaningful. |
| Prototype first, then wire | Every screen and state was agreed in a clickable prototype with sample data before connecting it to a live API, which kept the product consistent across modules. |

### Built with

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg"><img src="assets/stack-light.svg" width="100%" alt="Spead AI stack."></picture>

### Engineering highlights

- Tenant boundaries are enforced in the data layer, so every database query is scoped to one company.
- The content security policy runs without unsafe-eval and unsafe-inline, using script hashes instead.
- Frontend payload per page fell from 7.3 MB to 1.5 MB after the move to a production build.
- Daily database backups are encrypted, and a health check runs every five minutes.
- The suite has 36 unit tests that finish in under a second, plus 370 end-to-end checks.

---

<sub>Built by [Nugraha Labib Mujaddid](https://github.com/nugrahalabib). This page describes a private codebase; questions about the product or a demo are welcome at [nugrahalabib@gmail.com](mailto:nugrahalabib@gmail.com).</sub>

## Related

- [Spead AI Pro for WIKA EPCC](https://github.com/nugrahalabib/spead-pro-wika-showcase)
- [HC Platform for WIKA EPCC](https://github.com/nugrahalabib/wika-hc-platform-showcase)
- [AgentBuff](https://github.com/nugrahalabib/agentbuff-showcase)
- [All my work on GitHub](https://github.com/nugrahalabib)
