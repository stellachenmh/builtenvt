# AI in Building Maintenance: Nine Use Cases Beyond Predictive Maintenance

> Sources: US Department of Energy, Federal Energy Management Program, *Operations & Maintenance Best Practices Guide*, Release 3.0, Chapter 5 (2010), https://www1.eere.energy.gov/femp/pdfs/OM_5.pdf; Thomas and Weiss, "Maintenance Costs and Advanced Maintenance Techniques in Manufacturing Machinery: Survey and Analysis", NIST, *International Journal of Prognostics and Health Management* 12(1) (2021), https://doi.org/10.36001/ijphm.2021.v12i1.2883; Deloitte, *Making Maintenance Smarter* (2017), https://www2.deloitte.com/content/dam/insights/us/articles/3828_Making-maintenance-smarter/DUP_Making-maintenance-smarter.pdf; McKinsey, "Manufacturing: Analytics Unleashes Productivity and Profitability" (2017), https://www.mckinsey.com/capabilities/operations/our-insights/manufacturing-analytics-unleashes-productivity-and-profitability; McKinsey, "A Smarter Way to Digitize Maintenance and Reliability" (2021), https://www.mckinsey.com/capabilities/operations/our-insights/a-smarter-way-to-digitize-maintenance-and-reliability; Granderson et al., *Characterization and Survey of Automated Fault Detection and Diagnostics Tools*, LBNL-2001075 (2017), https://eta-publications.lbl.gov/sites/default/files/lbnl-2001075.pdf; LBNL, *Smart Energy Analytics Campaign Year 3 Report* (2019), https://bies.lbl.gov/sites/default/files/Smart%20Energy%20Analytics%20Campaign%20Year%203%20Report_LBNL_11.1.19.pdf; Crowe et al., "What We Learned From Analyzing 18 Million Rows of Commercial Buildings' HVAC Fault Data", LBNL (2022), https://smartersmallbuildings.lbl.gov/publications/what-we-learned-analyzing-18-million; US Government Accountability Office, *Federal Real Property: Disposing of Unneeded Facilities Could Help Reduce Maintenance Backlog*, GAO-25-108400 (2025), https://www.gao.gov/assets/gao-25-108400-highlights.pdf; IFMA, *2026 AI & Digitalization in Facilities Management Report* (2026), https://s3.us-east-2.amazonaws.com/knowledgelibrary.ifma.org/KL_Documents/2026-AI-Digitalization-in-FM-Report.pdf; ASHB, *2025 Smart Building Trends & Technology Adoption* (2025), https://www.ashb.com/wp-content/uploads/2025/12/Survey-Executive-Summary.pdf; BCA, *Guide to Smart FM*, version 2.2 (31 July 2026), https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf; BCA, "Periodic Façade Inspection (PFI)", https://www1.bca.gov.sg/regulatory-info/building-control/periodic-fa%C3%A7ade-inspection-pfi; Zhu, van Jaarsveld and Dekker, "Spare Parts Inventory Control Based on Maintenance Planning", *Reliability Engineering & System Safety* 193: 106600 (2020), https://doi.org/10.1016/j.ress.2019.106600; Smith and Mobley, *Rules of Thumb for Maintenance and Reliability Engineers* (2007), summarised at https://www.prometheusgroup.com/resources/posts/5-things-you-need-to-know-about-measuring-wrench-time; Microsoft, "Textron Aviation Enhances Maintenance Efficiency with Azure AI" (2025), https://www.microsoft.com/en/customers/story/23024-textron-aviation-azure-open-ai-service; C3 AI, "Leading Tire Manufacturer Reduces Equipment Troubleshooting Time" (2025), https://c3.ai/customers/leading-tire-manufacturer-reduces-equipment-troubleshooting-time-with-c3-generative-ai; The Business Times, "AI-Driven Inspection Platform Boosts Productivity by 70% for H3 Zoom" (8 April 2026), https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/ai-driven-inspection-platform-boosts-productivity-70-h3-zoom; JTC, "Flight of the Inspection Drones" (2023), https://www.jtc.gov.sg/about-jtc/news-and-stories/feature-stories/flight-of-the-inspection-drones-one-start-ups-crazy-idea-to-disrupt-building-inspections-with-tech; Screening Eagle, "Digital Periodic Structural Inspection (PSI) for Higher Efficiency" (2021), https://www.screeningeagle.com/en/inspection/efficient-periodic-structural-inspection; Aon, *Liquid Damage: A Significant Cause of Property Losses* (2023), https://www.aon.com/getmedia/987f3b69-86ac-42af-9af4-6845519485dc/Liquid-Damage-A-Significant-Cause-of-Property-Losses.pdf; Munich Re/HSB, "HSB Adds WINT Water Intelligence Technology to Water Leak Detection Portfolio" (2024), https://www.munichre.com/hsb/en/press-and-publications/press-releases/2024/2024-06-24-wint-water-intelligence-technology-leak-detection.html; Seppänen, Fisk and Lei, *Effect of Temperature on Task Performance in Office Environment*, LBNL-60946 (2006), https://eta-publications.lbl.gov/sites/default/files/lbnl-60946.pdf; Milton, Glencross and Walters, "Risk of Sick Leave Associated with Outdoor Air Supply Rate, Humidification, and Occupant Complaints", *Indoor Air* 10(4): 212–221 (2000), https://doi.org/10.1034/j.1600-0668.2000.010004212.x; Allen et al., "Associations of Cognitive Function Scores with Carbon Dioxide, Ventilation, and Volatile Organic Compound Exposures in Office Workers", *Environmental Health Perspectives* 124(6): 805–812 (2016), https://doi.org/10.1289/ehp.1510037.
> Raw: [AI in Building Maintenance: Evidence Pack](../../raw/built-environment/2026-11-12-ai-maintenance-use-cases.md)
> Updated: 2026-11-12

## Overview

Maintenance is the stage of the building lifecycle where AI has the shortest feedback loop. A prediction is either followed by a repair or it is not; a work order is either closed or it is not; a chiller either holds temperature or it does not. That is why the maintenance stage produces better evidence than design or construction — and why the evidence still needs to be read carefully.

The common mistake is to treat "AI in maintenance" as a synonym for **predictive maintenance (PdM)**. PdM is one use case, and not even the most mature one. BCA's own Smart FM case studies show a Singapore building portfolio getting a larger productivity gain from auto-ticketing (90.8%) than from IoT-driven predictive maintenance (50%) in the engineering function, while the overall gain across functions was 23–25% ([BCA, *Guide to Smart FM*](https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf)).

A more useful frame is that AI does **four jobs** in maintenance. Every credible use case is a variation on one of them:

| Job | Question it answers | Use cases | Primary metric |
|-----|--------------------|-----------|----------------|
| **Decide** | Which asset, which intervention, when? | 1. Predictive maintenance; 2. Capital-renewal and deferred-maintenance prioritisation | Unplanned downtime avoided; maintenance cost avoided |
| **Detect and diagnose** | What is wrong, and where? | 3. Automated fault detection and diagnostics (AFDD); 4. Water-leak and IAQ monitoring | Energy wasted; loss avoided |
| **Direct and do** | Who fixes it, with what, and how fast? | 5. Work-order triage and dispatch; 6. Technician copilots; 7. Spare-parts forecasting; 8. Computer-vision, drone and robot inspection | Labour hours; mean time to repair; inventory cost |
| **Protect the occupant** | What did the failure cost the people inside? | 9. Occupant-centric triage | Occupant-hours disrupted; productivity loss |

This article works through all nine, gives the best quantitative anchor for each, and then shows how to price the fourth job — occupant inconvenience — which is usually left out of the business case.

## How strong is the evidence

The numbers below are not equal. Three tiers are used throughout:

| Tier | What it is | What it can support | Examples here |
|------|-----------|--------------------|---------------|
| **1** | Government, national laboratory, regulator or peer-reviewed study | A range to plan against; a defensible assumption in a business case | DOE/FEMP, NIST, LBNL, GAO, *Indoor Air*, *Environmental Health Perspectives* |
| **2** | Consultancy synthesis or industry survey with a stated method | Direction and order of magnitude; a sanity check on Tier 1 | Deloitte, McKinsey, IFMA, ASHB |
| **3** | Vendor case study or customer story | An illustration of what is possible, not a forecast | H3 Zoom, Demaco/Screening Eagle, Textron/Microsoft, C3 AI, WINT/Munich Re |

Most of the Tier 1 maintenance evidence comes from **manufacturing and industrial plants**, not commercial buildings. It transfers directionally — the failure physics and work-order economics are similar — but not precisely. Building-specific evidence is strongest for AFDD, inspection and occupant effects, and weakest for PdM cost savings.

## The starting point: maintenance is still mostly reactive

The US DOE's Federal Energy Management Program found the average maintenance programme was **more than 55% reactive, 31% preventive, 12% predictive and 2% other**. Its benchmark ranges put predictive maintenance at **10–15% typical** and **45–55% best-in-class** ([DOE/FEMP, *O&M Best Practices Guide*, ch. 5](https://www1.eere.energy.gov/femp/pdfs/OM_5.pdf)).

The same guide gives the savings ladder that most business cases still use:

- **Preventive over reactive:** 12–18% cost saving.
- **Predictive over preventive:** 8–12%.
- **Predictive over reactive:** 30–40%, depending on how reactive the baseline is.
- The guide's older industrial averages — 10× ROI, 25–30% lower maintenance cost, 70–75% fewer breakdowns, 35–45% less downtime — are widely repeated but rest on unnamed surveys. Treat them as best-case illustrations, not planning numbers.

Two stronger anchors:

- **NIST** surveyed US manufacturers and found the group relying more on predictive and preventive maintenance had **52.7% less unplanned downtime** and **78.5% fewer defects** than the reactive-heavy group. Within the two more mature groups, those relying more on predictive than preventive had **18.5% less unplanned downtime** and **87.3% fewer defects** ([Thomas and Weiss, NIST, 2021](https://doi.org/10.36001/ijphm.2021.v12i1.2883)).
- **Deloitte** puts PdM at **5–10% lower maintenance cost, 10–20% higher uptime and availability, 20–50% less maintenance planning time**, and 5–10% lower MRO material cost ([Deloitte, *Making Maintenance Smarter*](https://www2.deloitte.com/content/dam/insights/us/articles/3828_Making-maintenance-smarter/DUP_Making-maintenance-smarter.pdf)).

The difference between the 8–12% and 30–40% numbers is not a disagreement about technology. It is a disagreement about **the baseline**. A building that already runs a disciplined preventive programme should use 8–12% as the incremental PdM claim and treat the rest as avoided-failure value, which has to be estimated separately.

Adoption is real but shallow. IFMA's 2026 survey found **67% of facility managers say their organisation already uses AI** in facility operations, and **47% of those deployers use it for predictive maintenance**; PdM is also the top planned investment for 2026 ([IFMA, 2026](https://s3.us-east-2.amazonaws.com/knowledgelibrary.ifma.org/KL_Documents/2026-AI-Digitalization-in-FM-Report.pdf)). ASHB's 2025 survey found **91% have deployed smart devices or software** and **78% have a BMS/BAS**, with **51% deploying or planning predictive maintenance or fault detection** — yet it also found "only modest adoption of condition-based maintenance and predictive/prescriptive maintenance" in practice ([ASHB, 2025](https://www.ashb.com/wp-content/uploads/2025/12/Survey-Executive-Summary.pdf)). The gap between "planned" and "operating" is the honest picture.

## Job 1 — Decide: which asset, which intervention, when

### 1. Predictive maintenance

PdM uses sensor and maintenance-history data to estimate the remaining useful life of an asset and schedule intervention before functional failure. In buildings the usual targets are chillers, AHUs, pumps, lifts and critical power assets.

The strongest building-specific deployment evidence in Singapore is BCA's digiHUB case. CBM Private Limited and City Developments Limited integrated IoT sensors, video analytics, cleaning and security systems into one platform. Predictive maintenance cut routine inspection frequency for selected equipment **from monthly to bi-monthly** and delivered a **50% productivity improvement in engineering operations**. Across all functions the portfolio achieved **23–25% overall productivity improvement** and a projected **S$11.3 million in cumulative savings over 11 years** ([BCA, *Guide to Smart FM*, Table 12](https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf)).

For lift-specific evidence, the same guide's Schindler Ahead case reports **43% fewer technical callbacks per month** and **94% less total downtime per month** after monitoring cubes were installed in lifts. That is a vendor deployment reported in a government guide — better than a vendor brochure, but still not an independent evaluation.

The industrial benchmarks give the planning range. McKinsey's widely cited figure is **30–50% less machine downtime and 20–40% longer machine life** ([McKinsey, 2017](https://www.mckinsey.com/capabilities/operations/our-insights/manufacturing-analytics-unleashes-productivity-and-profitability)). Its later work is more cautious: digital maintenance levers together deliver **15–30% cost reduction**, and a **10% false-positive rate erased the savings** on one PdM programme ([McKinsey, 2021](https://www.mckinsey.com/capabilities/operations/our-insights/a-smarter-way-to-digitize-maintenance-and-reliability)). The false-positive caveat matters more in buildings than in plants, because a building has fewer identical assets from which to learn.

For the technical limits of building PdM — label scarcity, operating envelopes, distribution shift — see [Digital Twin and AI-Enabled Predictive Maintenance in the Building Industry](digital-twin-predictive-maintenance.md).

### 2. Capital-renewal and deferred-maintenance prioritisation

The second "decide" use case is not failure prediction but **capital allocation**: which of hundreds of assets gets replaced this year, and which can wait. AI changes this by combining condition data, criticality, failure consequence and cost into a ranked renewal plan, instead of ranking by age or by the loudest complaint.

The problem is large and measurable. The US Government Accountability Office reports that Department of Defense and civilian agency deferred maintenance backlogs **more than doubled from $171 billion to $370 billion between fiscal years 2017 and 2024**, and that the General Services Administration's own backlog exceeded **$17 billion** in March 2025 ([GAO-25-108400](https://www.gao.gov/assets/gao-25-108400-highlights.pdf)).

The financial logic is that deferral is not free: a roof or chiller replaced late costs more than one replaced on schedule, and the gap is usually expressed as a multiplier. The commonly cited **3–4× deferral multiplier** is a rule of thumb, not a figure this article could trace to a primary source. The defensible version is narrower: use your own history of emergency-repair premiums, secondary damage and shortened asset life, and present the multiplier as a modelled assumption with a range.

The AI contribution here is prioritisation quality, not prediction accuracy. A ranked list that a finance committee can audit is more valuable than a model that is 5% more accurate but cannot explain its ranking.

## Job 2 — Detect and diagnose: turning a fault into a finding

### 3. Automated fault detection and diagnostics (AFDD)

AFDD software watches building automation system data and flags operation that deviates from expected performance: simultaneous heating and cooling, stuck dampers, biased sensors, schedules that no longer match occupancy. It is the highest-confidence AI-adjacent maintenance use case in commercial buildings, because it produces a diagnosis rather than a bare alert.

LBNL estimates that **5–30% of commercial building energy is wasted** because of faults and errors in control-system operation ([Granderson et al., LBNL-2001075](https://eta-publications.lbl.gov/sites/default/files/lbnl-2001075.pdf)). In the Smart Energy Analytics Campaign, participants using **FDD achieved a median 9% energy saving**; those using only an energy information system achieved 4% ([LBNL, Year 3 Report](https://bies.lbl.gov/sites/default/files/Smart%20Energy%20Analytics%20Campaign%20Year%203%20Report_LBNL_11.1.19.pdf)).

Faults are not rare events. In an LBNL analysis of 18 million rows of HVAC fault data across **317 buildings, 3,660 AHUs and 53,865 terminal units**, the median building reported **245 faults per month** — about **3 per AHU and 1 per terminal unit per month** ([Crowe et al., LBNL, 2022](https://smartersmallbuildings.lbl.gov/publications/what-we-learned-analyzing-18-million)). A maintenance team that cannot triage 245 alerts a month will ignore the system. This is why AFDD and work-order triage (use case 5) are a pair, not alternatives.

### 4. Water-leak and IAQ monitoring

Water and air are the two failure modes that damage the building and the occupant at the same time. AI adds value by distinguishing a normal flow signature from a leak, and by correlating CO₂, VOC, temperature and humidity readings into an indoor-air-quality diagnosis.

The loss exposure is well documented. Aon reports that **liquid damage accounts for 34% of property claims frequency at AIG**, and **30–40% of all claims** in real estate, education, healthcare, hospitality and retail at FM Global, with **more than $100 million of loss every year** in those occupancies. In hospitals, **more than 40% of damage incidents** can be attributed to water events — more than twice the share from fire, windstorm or earthquake ([Aon, *Liquid Damage*, 2023](https://www.aon.com/getmedia/987f3b69-86ac-42af-9af4-6845519485dc/Liquid-Damage-A-Significant-Cause-of-Property-Losses.pdf)).

On the intervention side, the strongest available study is insurer-led. Munich Re compared sites protected by WINT water intelligence with unprotected sites and found **73% fewer claims and 90% lower payouts** on protected sites ([Munich Re/HSB, 2024](https://www.munichre.com/hsb/en/press-and-publications/press-releases/2024/2024-06-24-wint-water-intelligence-technology-leak-detection.html)). That is a Tier 2 insurer study of a specific product, not a general AI effect, but it is a much better anchor than a vendor ROI claim.

IAQ monitoring is the same detection logic applied to the occupant. The difference is that the "failure" is often invisible — a damper stuck at 30% fresh air produces no complaint until CO₂ climbs. Use case 9 prices the consequence.

## Job 3 — Direct and do: the right person, part and instruction

### 5. Work-order triage and dispatch

Most maintenance labour is lost before anyone turns a wrench: reading alerts, deciding priority, finding the right technician, waiting for parts, writing the close-out. AI triage classifies incoming faults, deduplicates related alerts, assigns priority and routes the work order. It is unglamorous and it is often the largest measured gain.

digiHUB's **auto-ticketing system delivered a 90.8% productivity improvement** in the FM process function — the single largest figure in the case ([BCA, *Guide to Smart FM*, Table 12](https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf)). That is a workflow-automation result, not a machine-learning result, and it should be labelled as such. But it is the number that funds the rest of the programme.

The underlying opportunity is the wrench-time gap. Typical maintenance organisations spend only **18–30%** of a technician's shift on hands-on work; best-in-class is **55–65%** ([Smith and Mobley, *Rules of Thumb*, 2007](https://www.prometheusgroup.com/resources/posts/5-things-you-need-to-know-about-measuring-wrench-time)). SMRP's own metric sheet sets a best-in-class target of **50–55%**, and notes that typical wrench time in a reactive environment without effective planning is **below 30%**. Moving from 35% to 55% is roughly a **57% increase in effective capacity** from the same crew. The rest of the shift goes to travel, waiting, searching for parts and information, and administration — exactly the categories AI triage and copilots compress.

### 6. Technician copilots

A copilot answers a technician's question in the field: which fault code, which procedure, which part, which safety step. The best evidence is industrial but unusually concrete. Textron Aviation deployed an Azure OpenAI assistant over **60,000 pages** of maintenance documentation and cut troubleshooting time **from 20 minutes to 1–2 minutes** ([Microsoft customer story, 2025](https://www.microsoft.com/en/customers/story/23024-textron-aviation-azure-open-ai-service)). A tire manufacturer using C3 generative AI reports a **50% reduction in average time to repair** and **90% answer accuracy** ([C3 AI, 2025](https://c3.ai/customers/leading-tire-manufacturer-reduces-equipment-troubleshooting-time-with-c3-generative-ai)).

Both are Tier 3 vendor cases. The transferable lesson is not the percentage; it is that the bottleneck was **document retrieval**, not diagnosis. A building's equivalent corpus is the O&M manual, the commissioning report, the vendor's fault-code table and the last five work orders on that asset. Most buildings have these documents and cannot search them.

### 7. Spare-parts forecasting

If maintenance is scheduled from a plan, parts demand can be forecast from that plan rather than from noisy historical consumption. Zhu, van Jaarsveld and Dekker tested this against state-of-the-art time-series methods using data from two large maintenance organisations and found **23–51% lower inventory cost** ([Zhu et al., *Reliability Engineering & System Safety* 193: 106600, 2020](https://doi.org/10.1016/j.ress.2019.106600)).

This is one of the few maintenance use cases with a clean, peer-reviewed, building-adjacent result. It also has a useful property for a business case: the saving is in working capital and holding cost, which finance teams recognise immediately, and it does not require the model to predict a failure. It requires the maintenance plan to be real.

### 8. Computer-vision, drone and robot inspection

Inspection is where Singapore has the strongest measured evidence, partly because regulation creates a repeatable workflow. Since **1 January 2022**, buildings more than **20 years old** must undergo Periodic Façade Inspection every **7 years** ([BCA, PFI](https://www1.bca.gov.sg/regulatory-info/building-control/periodic-fa%C3%A7ade-inspection-pfi)). That is a recurring, auditable, photo-heavy task — ideal for computer vision.

H3 Zoom's Façade Inspector uses drones and wall robotics for capture, then AI for defect detection, severity grading and reporting. Reported results:

- Inspection completion about **90% faster**, cost roughly **halved**, and accuracy up to **4×** better.
- About **20% more defects** identified through the AI-assisted workflow.
- At JTC, across **160+ properties**, an **80% increase in inspection productivity**.
- JTC's own account: inspection time reduced by **70%**, with JTC Summit cut **from 4 weeks to 8 days** ([The Business Times, 8 April 2026](https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/ai-driven-inspection-platform-boosts-productivity-70-h3-zoom); [JTC](https://www.jtc.gov.sg/about-jtc/news-and-stories/feature-stories/flight-of-the-inspection-drones-one-start-ups-crazy-idea-to-disrupt-building-inspections-with-tech)).

The reason the gain is so large is documentation, not the site visit. Proceq's research with inspectors found **up to 65% of time on an inspection job is spent writing the report** ([Screening Eagle](https://www.screeningeagle.com/en/inspection/efficient-periodic-structural-inspection)). Demaco Consultants, a Singapore professional engineering consultancy, reports **30–40% time saved per project** and **50% fewer staff deployed on site** after digitising Periodic Structural Inspection with Screening Eagle's INSPECT.

These are Tier 3 vendor cases, but they are consistent across two independent providers and one government estate, which is stronger than a single case study. The caveat is that AI inspection **does not remove the professional engineer**; it changes what the engineer spends time on. BCA's own virtual-inspection programme retains human review.

## Job 4 — Protect the occupant: pricing the inconvenience

### 9. Occupant-centric triage

Most maintenance KPIs are asset-centric: uptime, mean time to repair, cost per work order. None of them answer the question a building owner actually cares about: **how many people were disrupted, for how long, and how badly?**

AI contributes in two ways. It can **prioritise** faults by occupant impact rather than asset criticality — a stuck damper in a 200-person open-plan floor outranks a faulty pump in an empty plant room. And it can **detect** the conditions that harm occupants before they complain: temperature drift, CO₂ buildup, humidity, water intrusion.

The occupant evidence is strong and should be used explicitly:

- **Temperature:** office work performance falls by about **2% per °C** once temperature exceeds **25 °C**, in the 25–32 °C range. At 30 °C, performance is about **91% of maximum** — an 8.9% loss ([Seppänen, Fisk and Lei, LBNL-60946](https://eta-publications.lbl.gov/sites/default/files/lbnl-60946.pdf)).
- **Ventilation and absence:** doubling outdoor-air supply from **25 to 50 cfm per person** was associated with **35% lower short-term sick leave**, worth about **$400 per employee per year** net of energy cost ([Milton, Glencross and Walters, *Indoor Air*, 2000](https://doi.org/10.1034/j.1600-0668.2000.010004212.x)).
- **Ventilation and cognitive performance:** in a controlled office study, cognitive scores were **61% higher** under green conditions and **101% higher** under green-plus-ventilation conditions than under conventional conditions. Doubling ventilation alone raised scores about **25%**. The cost of doubling ventilation was **under $40 per person per year in every climate zone studied**, against a productivity benefit **above $6,500 per person per year** ([Allen et al., *Environmental Health Perspectives*, 2016](https://doi.org/10.1289/ehp.1510037)).

Those are experimental and epidemiological results, not maintenance-software results. Their role in the business case is to price the **consequence** of a failure that maintenance prevents.

#### A bottom-up formula for occupant cost per breakdown

Vendor "cost per hour of downtime" figures (often $25,000/hour or more) are not usable for buildings. They are derived from industrial production lines and cannot be transferred to an office, a mall or a hospital. Build the number from occupants instead:

```
Occupant cost per event =
    Σ over phases [ occupants × hours × productivity loss % × loaded hourly cost ]
  + lost revenue or service capacity   (retail, hospitality, healthcare)
  + remediation and make-good cost
```

For a **full-stop phase** (no power, no air-conditioning, floor unusable), productivity loss is 100%, or less if some staff can work remotely. For a **degraded phase**, use the Seppänen relationship: loss % = 2 × (indoor temperature − 25), floored at zero.

Worked example — 500-person office, loaded cost **S$45/hour** (salary plus overhead; substitute your own payroll number):

| Phase | Occupants | Hours | Loss % | Cost |
|-------|-----------|-------|--------|------|
| Full stop while the chiller is restored | 500 | 1 | 100% | **S$22,500** |
| Degraded, indoor temperature 29 °C | 500 | 3 | 8% | **S$5,400** |
| **Total per event** | | | | **S$27,900** |

That event also disrupts **2,000 occupant-hours**. If it happens three times a year, the occupant cost alone is about **S$84,000**. A planned repair — part, two technicians for four hours, logistics — might cost S$4,000–8,000. The avoided cost per prevented event is therefore roughly **S$20,000–24,000**, before any energy or asset-life saving.

Three things this example makes visible:

1. **Most of the cost is not the repair.** It is the productivity of the people who could not work.
2. **Degraded operation is not free.** A 4 °C excursion for three hours costs more than an hour of full shutdown in this example.
3. **The unit matters.** "2,000 occupant-hours disrupted" is often more persuasive to a building owner than a dollar figure built on assumptions they did not supply.

For a hospital, replace productivity loss with **clinical capacity lost**; for a mall, with **tenant revenue at risk**. The structure is the same.

## The four numbers on a PdM business case

A PdM proposal that reports only "predicted failures" will not survive a finance review. These four metrics cover the four jobs, and each has a defensible anchor:

| Metric | Formula | Defensible benchmark | Anchor |
|--------|---------|---------------------|--------|
| **1. Unplanned downtime avoided** | baseline failure hours × expected reduction | 18.5% predictive vs preventive; 30–50% in mature programmes | NIST; McKinsey |
| **2. Maintenance cost avoided** | reactive cost − planned cost − programme cost | 8–12% over preventive; 30–40% over reactive | DOE/FEMP |
| **3. Energy saved** | fault-driven waste × detection rate × persistence | 5–30% at stake; 9% median FDD saving | LBNL |
| **4. Occupant-hours protected** | occupants × outage hours × frequency × severity | 2% performance loss per °C above 25 °C; 35% lower absence from doubled ventilation | Seppänen; Milton |

Present the range, not a point estimate, and state the baseline explicitly. The single most common error in PdM business cases is comparing a predictive programme against a reactive baseline when the building already runs preventive maintenance — which inflates the claim by roughly a factor of three.

## What the evidence does and does not show

- **Task-level gains are well evidenced; portfolio-level returns are not.** A 50% engineering-productivity gain at one portfolio, or a 90% faster inspection, does not become a 50% or 90% reduction in the maintenance budget. Supervision, integration, data cleaning and change management absorb part of the gain.
- **The baseline determines the headline.** DOE's 8–12% and 30–40% describe the same programme against different starting points. State which one you are claiming.
- **False positives are a real cost.** McKinsey's finding that a 10% false-positive rate erased the savings on one programme is the most useful cautionary number in the literature. In a 245-fault-per-building-per-month environment, precision matters more than recall.
- **Vendor figures are illustrations.** The drone, copilot, leak-detection and CMMS numbers above are Tier 3. They show what a well-run deployment achieved, not what yours will.
- **The occupant cost is a model, not a measurement.** The Seppänen relationship is an average across office tasks; it does not apply to every building or every task, and it says nothing below 25 °C. Use it to size the consequence, then validate against your own complaints, absence and tenant-satisfaction data.
- **Attribution is hard.** A failure that was predicted and prevented leaves no evidence that it would have occurred. Honest programmes report avoided failures as an estimate with a range, not as a realised saving.
- **Singapore evidence is concentrated in workflow and inspection.** The strongest local numbers — digiHUB's auto-ticketing, H3 Zoom's façade inspections, Demaco's PSI workflow — are digitalisation and computer-vision gains. Building-specific PdM cost savings in Singapore remain thinly evidenced. The same pattern holds at condominium scale: at The Floravale, the quantified saving is one security post at almost S$5,000 a month, achieved through QR visitor management and a resident fault-reporting channel, not prediction ([CNA, 2023](https://www.channelnewsasia.com/singapore/more-buildings-putting-artificial-intelligence-ai-smart-sensors-manage-utilities-cut-costs-singapore-3635681)).

## How to sequence it

1. **Fix the work-order record before buying a model.** Failure time, failure mode, severity, asset, action taken and labour hours are the training labels. If they are free text, the first project is data clean-up, not AI.
2. **Start with detection and triage, not prediction.** AFDD plus auto-ticketing produces value in months and generates the labelled history that PdM needs. digiHUB's largest single gain came from ticketing, not prediction.
3. **Instrument the occupant.** Add temperature, CO₂ and humidity to the asset dashboard, and add occupant-hours to the work-order close-out. You cannot prioritise by occupant impact if you do not record it.
4. **Price one asset end to end.** Pick the chiller or AHU with the highest failure cost, build the four-metric case, and include the false-alarm cost. Use the result to set the hurdle for the portfolio.
5. **Write the contract around outcomes, not alerts.** Specify warning horizon, acceptable false-alarm rate, the action that follows an alert, and who is accountable for closing it. An alert nobody is resourced to act on is not a maintenance capability.

## See Also

- [Smart Facilities Management: Integrated, Aggregated and Smart FM](smart-facilities-management.md) — the operating model, Smart FM types, digiHUB and Schindler Ahead cases, and the contract conditions maintenance AI has to fit into.
- [Digital Twin and AI-Enabled Predictive Maintenance in the Building Industry](digital-twin-predictive-maintenance.md) — the technical limits of building PdM: label scarcity, operating envelopes, distribution shift and the Six M diagnostic.
- [Quantified AI Benefits in the Built Environment](quantified-ai-benefits-five-use-cases.md) — measured time and cost evidence for BCA's five AI use cases, including the inspection evidence summarised here.
- [AI in the Built Environment](ai-in-the-built-environment.md) — BCA's five use-case families and the lifecycle view of where maintenance sits.
- [Data Readiness for AI in Construction](data-readiness-for-ai-in-construction.md) — why asset, sensor and failure data must be standardised before prediction or triage is trustworthy.
- [AI Adoption Risks in the Built Environment](ai-adoption-risks-in-the-built-environment.md) — skills, data quality, governance and ROI-failure risks that decide whether a maintenance deployment survives.
- [AI Adoption and Governance in the Built Environment](ai-adoption-in-the-built-environment.md) — readiness, the cost of delaying investment and Singapore's policy and data constraints.
