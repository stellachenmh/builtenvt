# Quantified AI Benefits for BCA's Five Built Environment Use Cases: Compiled Evidence

> Source: compiled during research on the quantitative case for AI in the built environment, drawing on the published sources listed inline below. Unlike other raw files in this collection, this is a synthesis of many sources rather than a single article; every statistic is attributed to its original publisher and linked.
> Collected: 2026-11-12

Research question: for each of the five AI use cases published by Singapore's Building and Construction Authority (BCA), what is the measured time and cost burden today, and what measured saving has AI produced? Singapore evidence is prioritised; where none exists, global proxies are flagged.

The five use cases are taken from BCA, "AI Use Cases for the Built Environment", 20 July 2026 ([raw ingestion](2026-07-20-ai-use-cases-built-environment.md); [PDF](https://isomer-user-content.by.gov.sg/338/90e893e1-a3cc-440b-9359-bf7e26ff35b4/AI%20Use%20Cases%20for%20BE_2026.07.20.pdf)):

1. Knowledge management with AI querying and review
2. AI-enhanced BIM workflow
3. Tender, cost and contract management
4. AI-assisted inspections and progress analytics
5. Site documentation and project management

## How the evidence is graded

The figures below are graded on four levels. The distinction matters because the gap between the best and worst evidence is roughly an order of magnitude.

| Grade | Meaning | Typical source |
|-------|---------|----------------|
| **A — official measured** | Government or regulator reporting outcomes across a population of projects | BCA/URA circulars, MOM survey, BCA media releases |
| **B — operator-reported with method** | Named organisation reports a before/after or pilot result, method stated | JTC, Demaco, Surbana Jurong, H3 Zoom |
| **C — vendor case study** | Vendor publishes a customer result; methodology rarely stated; success-only sample | Invigilo, Buildots, OpenSpace, Evercam |
| **D — vendor marketing claim** | No customer, no method, no sample | Civils.ai homepage figures, Togal.AI, Buildxact, Luminance headline claims |

Two further labels are used throughout:

- **Automation, not AI.** Many of the strongest "AI" results in construction are rule-based automation, digital forms or computer vision — not generative AI or machine learning. These still count as evidence for BCA's use cases, because BCA's own framing of the use cases is capability-based (what the workflow can do differently), not model-based. But a business case that assumes an LLM is doing the work will misattribute the benefit.
- **Baseline burden vs measured saving.** The two are frequently conflated. A figure like "34,000 man-hours a year" describes the size of the workload, not a saving. Only a before/after comparison, or an explicit projection from a deployed system, supports a saving.

## 1. Singapore adoption and labour-market context

### MOM, "Adoption of Artificial Intelligence Among Firms" (inaugural release, 30 April 2026)

Sources: https://www.mom.gov.sg/newsroom/press-releases/2026/0430-adoption-of-ai-among-firms ; https://stats.mom.gov.sg/iMAS_PdfLibrary/mrsd-Adoption-of-Artificial-Intelligence-Adoption-Among-Firms.pdf

Establishment-based survey of **2,560 private-sector establishments** employing **486,600 workers**, fieldwork January–March 2026.

- **28.5%** of firms had adopted AI; **71.5%** had not
- Only **3.8%** had integrated AI into core business processes; most adopters were at planning (**7.4%**) or piloting (**6.0%**)
- Among AI-using firms, **70.7%** reported improved worker productivity; **13.3%** better decision-making; **11.9%** improved innovation
- **18.9%** redesigned job roles; **13.9%** created new AI-related jobs; only **6.2%** reported AI-attributable headcount reduction
- Barriers: implementation cost **44.9%**, lack of in-house expertise **42.4%**, no clear strategy **32.4%**, low trust in AI **30.8%**; larger firms cited integration complexity (**56.1%**) and data security (**55.4%**)
- Adoption is concentrated in large firms and knowledge-intensive sectors (information and communication **74.1%**)

This is the single most important Singapore number for the assignment's talent-scarcity framing: at current adoption, AI is reported as complementing labour, not substituting for it. The 6.2% headcount-reduction figure sits alongside 18.9% role redesign — the labour-market effect is task recomposition, not net reduction.

### IMDA / GovTech, public-sector AI use (context only, not built environment)

- Approximately **80%** of **150,000** public officers have used Pair Chat, and more than **20,000** AIBots have been created (GovTech/MDDI reporting, 2025–2026).

This is a Singapore knowledge-management proxy, not built-environment evidence: it shows a large white-collar workforce adopting conversational AI at scale, but does not measure time saved.

## 2. Use case 1 — Knowledge management with AI querying and review

### The baseline burden

**Autodesk and FMI, "Harnessing the Data Advantage in Construction" (2021; 3,916 respondents globally, 500+ in APAC)**

Source: https://constructioncloud.autodesk.com/rs/572-JSV-775/images/harnessing_the_data_advantage_in_construction_fmi_apac.pdf

Share of the working week that project management and field supervision staff spend **collecting, managing and analysing project data**:

| Geography | Share of week |
|-----------|---------------|
| Singapore | **56%** |
| APAC | 52% |
| Europe | 44% |
| North America | 40% |

Singapore is the highest of the four reported geographies. This is the best available Singapore-specific measure of the information-handling burden that knowledge-management AI is aimed at — but note it measures *all* data tasks (collection, management, analysis), not document search alone.

**PlanGrid and FMI, "Construction Disconnected" (2018; 600+ construction professionals)**

Source: https://pg.plangrid.com/rs/572-JSV-775/images/Construction_Disconnected.pdf

- **35%** of working hours (**14+ hours per week**) spent on non-optimal activities — looking for project information, resolving conflicts, rework
- **5.5 hours per week** spent looking for project information
- **52%** of rework attributed to poor project data and miscommunication

**FMI, "Big Data = Big Questions" (2018)**

- **13%** of engineering and construction working hours spent looking for project data
- **95–96%** of data captured in engineering and construction goes unused

**RIBA AI Report 2026**

- **40%** of architecture practices using AI use it for standards and regulatory compliance checking

### The Singapore evidence

**No Singapore measurement of knowledge-management AI was found.**

This is a genuine gap, not an oversight. No Singapore firm publishes a before/after measurement of querying a codes-and-project-documents repository, or of AI-assisted compliance review measured per user or per project. The Singapore evidence that exists covers two adjacent but different workflows:

- **Automated model checking** (CORENET X), below — a compliance-review workflow, but one that checks a BIM model against machine-readable rules rather than answering questions over a document corpus.
- **Drawing and document cross-checking** (Civils.ai), which belongs to use case 3 and is documented there.

BCA's use case 1 bundles two capabilities that are often conflated: a **knowledge base** (a centralised, queryable repository of codes, standards and project documentation) and a **review function** (AI-assisted checking of documents and designs). Evidence for document checking does not transfer to knowledge retrieval, and vice versa. A firm procuring "AI knowledge management" should test the two separately, because a tool that cross-checks drawings will not answer "what does the code require here?" — and a retrieval tool will not verify a drawing set.

**CORENET X (BCA and URA), official circular, 23 July 2026**

Sources: https://www.ura.gov.sg/guidelines/circulars/dc26-08 ; https://info.corenet.gov.sg/docs/default-source/bca-circulars/circular-for-updates-to-corenet-x-implementation-plan.pdf

BCA Reference APPBCA-2026-12 / URA Reference URA/PB/2026/08-DCG:

- More than **140 projects** involving **300 firms** have submitted via CORENET X since mandatory implementation for new projects ≥30,000 m² GFA from 1 October 2025
- Those projects "achieved time savings of **up to two months**, alongside cost savings from reduced abortive work"
- Firms reported "greater certainty through improved cross-discipline coordination, **fewer resubmissions** to agencies, and shared visibility within project teams"
- Time savings and productivity gains are "most pronounced for projects that are larger in size and of greater complexity"

CORENET X is a regulatory submission platform built on BIM and automated model checking, not a knowledge-management chatbot. It is included here because it is the only Singapore evidence with Grade A status on the *review and compliance-checking* workflow that use case 1 describes — and because it captures the mechanism the use case is really about: fewer iterations, not faster typing.

**Enterprise Singapore, CORENET X programme page**

Source: https://www.enterprisesg.gov.sg/smepeo/corenet-x

- CORENET X consolidates **more than 20 approval touchpoints** across multiple agencies into three gateways
- "Projects can save **up to 20%** in the overall time taken to obtain regulatory approvals throughout the project timeline"

The 20% figure and the "up to two months" figure are consistent: two months is roughly 20% of a typical 9–12 month approvals sequence. Prefer the official circular's absolute figure when quoting, because it names the population of projects.

## 3. Use case 2 — AI-enhanced BIM workflow

### The Singapore evidence

**Surbana Jurong with Ideate BIMLink (vendor case study, Singapore-headquartered firm)**

Sources: https://ideatesoftware.com/surbana-jurong-shares-significant-time-savings-achieved-with-ideate-bimlink ; https://irp.cdn-website.com/83063b3b/files/uploaded/surbana-jurong-client-testimonial.pdf

- Created **361 Revit sheets in 3 minutes**, reduced from **24 hours**
- Implied task-level time reduction: **~99.8%**

This is the most dramatic figure in the pack and the one most likely to be misused. It is **automation, not AI**: a Revit data-link add-in populating sheet parameters. The 24-hour baseline is a single batch task, not a share of project effort. The correct claim is "one repetitive BIM documentation task went from a day to three minutes," not "BIM work became 99.8% faster."

**CORENET X automated model checking**

- As above: **140+ projects**, **300 firms**, **up to two months** saved, fewer resubmissions. The mechanism is automated checking of IFC-SG models against regulatory requirements — the closest Singapore has to at-scale AI-assisted BIM quality checking.

**Tiong Seng, Kallang Polyclinic (BIM and Integrated Digital Delivery; not AI)**

Source: https://www.tiongseng.com.sg/services-1

- BIM/IDD adoption reduced the construction timeline by **25%**, equivalent to more than **5,000 hours** on the project

Included as a benchmark for what a full digital-delivery workflow change can produce, to show that the largest measured gains come from process change rather than from a tool. It is not evidence for AI.

**AECOM, sustainable design optioneering (Singapore, Business Times, 8 April 2026)**

Source: https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/aecom-builds-singapores-first-ai-enabled-sustainable-design-optioneering-ecosystem

- Evaluated **600+ design combinations** for a single transit station entrance, narrowing to optimal solutions
- Carbon reductions of **up to 45%**; improved multidisciplinary coordination
- Tools: ScopeX (whole-life carbon) and AecomZero (parametric design), deployed across AECOM's global operations

This is a design-quality benefit, not a time saving. It belongs in the design lifecycle stage and is the best Singapore evidence that AI changes *what* gets designed, not just how fast.

### Global proxies

**Buildots (vendor case studies, computer vision progress tracking)**

- Losinger Marazzi: **10 hours per week** freed from progress-reporting work
- NCC: **70%** reduction in time spent on manual reporting; **2.3x** more tasks completed on time
- Intel: **4.3%** rework cost avoided per fabrication facility; **4 weeks** of delay avoided per facility

Buildots' computer-vision progress tracking maps to both use case 2 (model-versus-reality checking) and use case 4 (progress analytics). Figures are Grade C.

## 4. Use case 3 — Tender, cost and contract management

### The baseline burden

**JTC Corporation, Evaluation Virtual Assistant (EVA) — baseline workload (Business Times, 8 April 2026)**

Source: https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/jtc-bids-goodbye-paper-heavy-world-construction-tenders

- Each JTC construction tender involves roughly **8 evaluators**
- Approximately **14 man-days of work per evaluator**
- Submissions can run to **30 documents per tenderer**
- Around **40 construction tenders** evaluated annually
- Cumulative: approximately **34,000 man-hours a year**

Arithmetic check: 8 × 14 × 40 = **4,480 man-days**; 34,000 ÷ 4,480 ≈ **7.6 hours per man-day**. The published figures are internally consistent.

This is the best-quantified built-environment AI baseline in Singapore, because it states the unit (per tender), the population (40 tenders a year) and the aggregate. It is a **workload**, not a saving.

**Navigant Construction Forum, "RFI Costs and Consequences" (2013; US projects)**

- Average cost per RFI: **$1,080**
- Median time to resolve: **9.7 days**; **21.9%** of RFIs receive no response
- Typical frequency: **15–20 RFIs per $1 million** of project value

Dated and US-specific, but it is the only widely cited quantification of the contract-administration burden, and it converts an RFI into a dollar figure. Use for scale, not precision.

### The Singapore evidence

**JTC EVA (Business Times, 8 April 2026)**

- Large language models perform extraction and initial scoring of tender submissions against evaluation criteria
- Human-in-the-loop by design: evaluators retain full authority over scores and recommendations
- Documented example: EVA flagged that a tenderer's stated performance ratings were not substantiated by supporting documents
- JTC estimates faster evaluations could shorten overall project schedules by **two to three months**

Note the evidence status: the **34,000 man-hours** is measured; the **2–3 months** is a JTC projection, not a post-deployment result, and no post-deployment time saving has been published.

**Civils.ai, JTC (quantity takeoff and drawing/document cross-checks)**

Capability description, per BCA's media release of 2 September 2026 ([raw ingestion](2026-09-02-bca-construction-startup-competition-apac.md)):

> "Civils.ai is an AI co-pilot for civil engineers that extracts and cross-checks data from drawings, contracts, and geotechnical reports, cutting takeoff time by up to 90%."

Vendor-published deployment figures, from the homepage of https://www.civils.ai/:

- "We help firms like JTC automate quantities measurements from drawings and run AI checks across their projects — with ROI verified over 12 months of Civils.ai usage across a team of 38 users"
- **38 users**; **2,842 AI prompts** over 12 months
- **5–15 minutes saved per prompt**
- **528+ hours** of efficiency saving over 12 months
- **97%** takeoff accuracy on modern PDFs
- **200+ firms across 8 countries**; **$3bn+** of projects supported (currency as published)

Evidence status: **Grade C at best, and closer to D.** The figures appear only on the vendor's marketing homepage. There is no published case study, methodology note or audit, and the "ROI verified over 12 months" phrasing is the vendor's own. JTC is named on the vendor's site, but no JTC document or statement confirming or quantifying the deployment was found.

Arithmetic check on the vendor's own claim: 2,842 prompts × 5–15 minutes = **237–711 hours**, so the reported 528 hours implies about **11 minutes saved per prompt** — internally consistent, and consistent with the idea that not every prompt produced a saving. Spread across 38 users, 528 hours is **~13.9 hours per user per year**, or **about 16 minutes per user per week**.

That per-user figure is the reason this deployment, even taken at face value, should not be described as a transformation. It is a task-level saving inside a pilot. But because the source is unaudited marketing copy, it should be treated as an order-of-magnitude indication only, not as a measured result.

Note also the discrepancy in how the benefit is described: BCA calls it "cutting takeoff time by up to 90%", while the vendor calls the same capability "reducing manual effort by up to 90%". Takeoff time and manual effort are not the same measure, and neither is defined.

**Autodesk customer story, KTC (global)**

Source: https://construction.autodesk.com/resources/customer-success-stories/how-digital-document-management-helped-ktc-reduce-rfi-handling-time-by-65-percent

- **65%** reduction in RFI handling time through digital document management

Grade C, and again largely digitalisation rather than AI.

### Vendor claims not used in the headline table

- **Civils.ai Scope Agent**: scope packages completed in **under 60 minutes** versus **30–40 hours** manually; **99.5%** risk-review accuracy; **$1.8 million** in avoided costs on a JTC project (vendor blog, no method published)
- **Togal.AI**: takeoffs **5x faster**, **98%** accuracy on floor plans
- **Buildxact**: estimates up to **7x faster**, takeoffs **50%** quicker
- **Luminance**: **90%** time savings on contract review; **98%** reduction in contract-management costs

The $1.8 million claim is the most tempting and the least supported: it is an unattributed avoided-cost estimate, not an audited saving. Excluded from headline use.

## 5. Use case 4 — AI-assisted inspections and progress analytics

### The Singapore evidence

**H3 Zoom, Facade Inspector (Business Times, 8 April 2026)**

Source: https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/ai-driven-inspection-platform-boosts-productivity-70-h3-zoom

- Productivity improvement of **more than 70%**; costs **halved**
- Inspection completion times improved by about **90%**
- Accuracy improved by **up to 4x**
- About **20% more defects** identified through the AI-assisted workflow
- Detects **30+ building types and facade defect types** across glass and concrete surfaces
- Launched 2019; **10,000+ inspections** completed across APAC as at 2025; operates in **7 markets**
- Clients include JLL, CBRE, Takenaka, and Singapore and Hong Kong government agencies
- **JTC case study: 160+ properties, 80% increase in inspection productivity**

Grade B/C: a named Singapore company with named clients and a stated method (guided capture, AI detection and segmentation, human-in-the-loop verification). The figures are company-reported; no independent audit. This is the strongest single package of Singapore evidence for any of the five use cases, because it reports a productivity figure, a cost figure, a speed figure, an accuracy figure *and* a quality-of-output figure (more defects found).

**Demaco Consultants with Screening Eagle INSPECT (Singapore; Periodic Structural Inspection)**

Source: https://www.screeningeagle.com/en/inspection/efficient-periodic-structural-inspection

- **30–40%** of time saved per project
- **50%** reduction in manpower deployed on site
- Proceq research cited in the same case study: **up to 65%** of time on an inspection job is spent writing the inspection report
- Demaco has inspected **100,000 m²** of facades and **200,000 m²** of floor area over 30+ years

The 65% figure is the most consequential number in this section: it locates the bottleneck in *reporting*, not in the inspection itself. That is why inspection AI and site-documentation AI (use case 5) overlap so heavily in practice.

**Invigilo Technologies, HDB public housing project delivered by Teambuild (vendor case study, 2026)**

Source: https://www.invigilo.ai/case-study-hdb-construction

- **60%** fewer safety incidents and near misses
- **40%** faster incident response
- **8x** more observations than manual patrols
- Measurement method: **six months before** go-live compared with **six months after**, on the same site
- Deployed on **30 cameras already installed** on site, connected over RTSP — no new hardware or cabling
- Detection scope: work at height, PPE compliance, restricted-zone entry, with zone rules per camera
- Every detection saved as a timestamped clip, used in toolbox talks and corrective actions

This is the only source in the pack reporting a **safety outcome** with a before/after design, and it is therefore disproportionately valuable for a BCA audience — safety is the outcome the sector is most accountable for. Treat with the usual vendor caveat: single site, vendor-run analysis, no control site, and incident counts on one project are small numbers where a 60% change can rest on a handful of events.

**Ailytics (Singapore; IMDA blog, 20 February 2024)**

Sources: https://www.imda.gov.sg/resources/blog/blog-articles/2024/02/enhancing-safety-and-efficiency-ai-in-construction ; https://telecom.economictimes.indiatimes.com/news/internet/tin-men-capital-leads-2-7-mn-investment-in-ai-startup-ailytics/108930475

- Customers reduce manual inspections by **up to 50%**
- Hazard detection increased by **up to 7x**
- **70%** improvement in spotting unsafe conditions after deployment
- Raised **$2.7 million** led by Tin Men Capital (2024; currency as published)

**BCA whole-of-government virtual inspection (WOG VI), announced 2 September 2026**

Sources: https://www.edgeprop.sg/property-news/new-virtual-site-inspection-process-could-cut-top-approval-time-two-months ; https://www.asiaone.com/money/new-condo-owners-may-now-get-their-keys-2-months-earlier-new-process ; https://isomer-user-content.by.gov.sg/338/177b6779-d7b3-4b05-933e-8c5be9a17b11/Guidebook%20for%20Whole-of-Government%20Virtual%20TOPCSC%20Inspections%20v1.01%20(Sep%202026).pdf

- Pilot projects including **Grand Dunman** (1,008 units) showed **up to 30% manpower savings** for project parties on inspection work
- Phased submission could enable **TOP approval up to two months earlier** than conventional physical inspections
- Process available immediately, with a guidebook published September 2026

This is Grade A and directly relevant to the maintenance/handover stage. It is also the clearest Singapore example of a *regulatory* AI-adjacent workflow producing a schedule benefit.

### Global proxies

**Buildots**: **70%** less manual reporting (NCC); **10 hours per week** freed (Losinger Marazzi); **4.3%** rework cost and **4 weeks** delay avoided per Intel fab.

**OpenSpace (vendor case studies)**

- Documentation **5x–30x faster** than manual methods
- Lendlease: **30x faster**, nearly **half a workday per week** saved
- JLL: **50%** lower travel costs
- Customers report **50%** reduction in travel time

**Evercam (vendor case studies)**

- **20%** fewer physical site visits and **15%** travel-cost savings (Shell Vito project)
- Another case: **80%** of site visits reduced

## 6. Use case 5 — Site documentation and project management

### The Singapore evidence

**Demaco Consultants with Screening Eagle INSPECT**

- **30–40%** overall time saved per project; reports generated "with a few clicks" from captured data
- **65%** of inspection job time previously spent writing reports (Proceq)
- **50%** fewer staff deployed on site

**Novade with Hwa Seng Builder (Singapore; project completed 2018)**

Source: https://fr.novade.net/cas-client/hwa-seng-builder

- **75%** reduction in permit-to-work submission time, from **more than two hours to 5–30 minutes**
- **28,000+** electronic PTWs created
- Project (160 m road bridge over Sungei Serangoon, linking Punggol Central to KPE/TPE) completed **9 months ahead** of schedule
- Hwa Seng is BCA A1-classified for civil engineering works

The strongest Singapore site-documentation number, with an important caveat: this is **digitalisation** (mobile forms replacing paper), not AI, and the project finished in 2018. It establishes the size of the paperwork burden and the achievable saving from digitising it — which is the floor that AI-driven reporting has to beat, not a demonstration of AI.

**Novade with Tiong Seng Contractors, Sol Acres**

Sources: https://www.novade.net/us/tiong-seng-contractors-sol-acres ; https://www.novade.net/en/project-management-software-singapore

- Digital quality, safety and activity tracking eliminated travel and paperwork on Singapore's largest executive condominium
- No published percentage for time saved
- Novade separately claims **up to 80%** reduction in compliance costs (vendor claim, no customer attached)

**AISI Asia, AI inspection-report agent (Singapore vendor, 2026)**

Source: https://www.aisi-asia.net/ai-agent-case-study-inspection-report-generation

- AI agent converts inspection notes and photos into structured reports, turning "hours of paperwork into minutes"
- No precise measured figure published

### Global proxies

**Buildots**: **70%** reduction in manual reporting time (NCC).

**OpenSpace / Lendlease**: nearly **half a workday each week** saved on documentation.

**Mobile daily reports (secondary source only)**

- Daily report completion reduced from **25 minutes to ~8 minutes** (~68% reduction); RFI response from **8.2 to 2.6 business days**
- Source: https://www.dirtchamp.com.au/articles/reduce-construction-paperwork.html — a secondary compilation, **not** a primary study. Excluded from headline use; listed here only so the figure is traceable if it appears elsewhere.

**Supervisor time returned (secondary)**

- Supervisors gain **2–3 hours per week** back from paperwork (AGC Digital Transformation Survey, cited via hh2). Secondary citation; not independently verified.

## 7. Derived arithmetic and sensitivity (illustrative, not measured)

These calculations combine cited inputs. They are **not** measured savings and should be labelled as scenarios wherever used.

### JTC EVA

Baseline **34,000 man-hours/year**. If EVA reduces evaluator effort by:

| Reduction | Man-hours saved per year | Equivalent |
|-----------|--------------------------|------------|
| 25% | ~8,500 | ~1,100 man-days |
| 30% | ~10,200 | ~1,340 man-days |
| 50% | ~17,000 | ~2,240 man-days |

At a loaded cost of S$60–100 per man-hour for a professional evaluator, the 30% case is roughly **S$0.6–1.0 million a year** — but this conversion is an assumption, not a published figure, and should be shown as a sensitivity range rather than a point estimate.

### Knowledge management

Autodesk/FMI: Singapore project management and field supervision staff spend **56%** of the week on data tasks = **22.4 hours** of a 40-hour week. If AI removes **10%** of that time across a **100-person** project management and supervision group:

- 2.24 hours per person per week × 100 people × 46 working weeks ≈ **10,300 hours a year**

There is no Singapore measurement to anchor the downside of that range. The Civils.ai per-user figure (~16 minutes a week) was previously used as the low case, but it measures takeoff and drawing checks, not knowledge retrieval, and it is unaudited — so it cannot calibrate this use case. Treat the 10% scenario as an upper-bound illustration only, and expect pilot variance of an order of magnitude until a firm measures its own baseline.

### Takeoff and drawing cross-checks (Civils.ai, as claimed)

Vendor claim: **2,842 prompts**, **5–15 minutes saved per prompt**, **528+ hours** over 12 months across **38 users**.

- Implied average: 528 hours ÷ 2,842 prompts ≈ **11 minutes per prompt**
- Implied per user: 528 ÷ 38 ≈ **13.9 hours per user per year** (~16 minutes per week)

If the claim were accurate and the task recurred at the same frequency, a 100-person team would save ~**1,400 hours a year**. Because the claim is unaudited and appears only in marketing copy, this should be presented as the size of the prize if verified, not as an expected return.

### Inspections

Demaco: **30–40%** of project time saved, with **50%** fewer staff on site. On an inspection contract with a 100 man-day baseline, that is 30–40 man-days saved — but the two figures measure different things (calendar time versus headcount deployed) and should not be multiplied together.

## 8. Sources that could not be verified

- **BCA annual report** and **MOM AI survey PDF**: local PDF text extraction was unavailable in this environment; MOM figures were verified through the press release and multiple independent reports instead. No figure in this pack depends solely on the unparsed PDFs.
- **PwC Singapore AI case study**: returned HTTP 403; excluded.
- **IMDA blog (Ailytics)**: the page is now JavaScript-rendered and the original figures could not be re-extracted on 2026-11-12; figures retained from an earlier retrieval and flagged as vendor-reported.
- **CORENET X circular PDF** on the isomer CDN returned HTTP 403 (CloudFront) on 2026-11-12; the identical text was verified on the URA circular page (dc26-08) and the corenet.gov.sg mirror.
- **Civils.ai JTC case study**: no case study document, methodology note or audit could be found. The 38-user, 2,842-prompt and 528-hour figures exist only as marketing copy on the vendor's homepage. Treated as Grade D. No JTC publication confirming or quantifying the deployment was found either.

## 9. Methodological notes

- **Task-level versus role-level.** Almost every strong figure in this pack measures a task ("this report", "this sheet", "this prompt"), while business cases are usually built at role or project level. Converting one to the other requires an assumption about task frequency, which no source in this pack publishes. State the assumption.
- **Selection bias.** Vendor case studies publish successes. The population of failed deployments is invisible in this literature, which is why the cross-industry failure statistics in [AI Adoption Risks in the Built Environment: Compiled Statistics](2026-11-11-ai-risks-built-environment-statistics.md) are a necessary counterweight.
- **Attribution.** Several results bundle AI with process reengineering, BIM adoption or mobile digitalisation. Tiong Seng's 25% timeline reduction and Novade's 75% PTW reduction are process-and-digitalisation results; Surbana Jurong's 24 hours to 3 minutes is rule-based automation. Only H3 Zoom, Invigilo, Civils.ai, JTC EVA and AECOM describe AI/ML as the operative technology.
- **"Up to" figures.** Many Singapore sources report ceilings ("up to two months", "up to 50%", "up to 90%"). These describe the best-performing projects, not the average. Where a median or mean is available it is used instead; where it is not, the ceiling is labelled.
- **Small denominators.** A 60% reduction in safety incidents on one site may rest on fewer than twenty events. Percentage changes on small counts are unstable and should be reported alongside the count wherever possible.
- **Currency and period.** Figures span 2013 (Navigant) to 2026 (CORENET X circular). Cost figures are not inflation-adjusted. The 2018 Novade and 2018 PlanGrid results describe workflows that have since changed.
- **Singapore representativeness.** Singapore's regulatory environment (CORENET X, mandatory PSI, TOP/CSC inspections) creates burdens and savings that do not transfer directly to other markets — for example, a two-month approvals saving is a function of a multi-agency gateway process that few jurisdictions have.
- **Automation versus AI.** Where a figure comes from computer vision, rule-based checking or digital forms, it is labelled. Readers should not assume an LLM is responsible for results published before 2023.

## 10. Corrections

**2026-11-12 — Civils.ai reclassified from use case 1 to use case 3.**

An earlier version of this pack placed the Civils.ai/JTC figures under use case 1 (knowledge management) and described them as a "12-month ROI review". Two corrections were required:

1. **Classification.** Civils.ai extracts and cross-checks data from drawings, contracts and geotechnical reports and performs quantity takeoffs. That is a tender, cost and contract workflow (use case 3). It does not provide a queryable knowledge base over codes and project documents, and it does not answer compliance questions in natural language, so it is not evidence for knowledge management.
2. **Sourcing.** The 38-user, 2,842-prompt, 528-hour figures appear only on the vendor's marketing homepage. There is no published case study, methodology or audit, and no JTC document confirming them. The figures were downgraded from Grade C to Grade D and the phrase "ROI review" removed.

The consequences propagate: use case 1 now has **no Singapore per-person measurement**, and the derived "low case" of ~1,200 hours a year that rested on the Civils.ai per-user figure has been removed. The independent capability description now used is BCA's media release of 2 September 2026, which describes Civils.ai as "an AI co-pilot for civil engineers that extracts and cross-checks data from drawings, contracts, and geotechnical reports, cutting takeoff time by up to 90%" — a vendor-supplied description reproduced by BCA, not a measurement.
