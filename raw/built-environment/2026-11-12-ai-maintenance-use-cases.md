# AI in Building Maintenance: Evidence Pack

> Compiled: 2026-11-12
> Purpose: source note for [AI in Building Maintenance: Nine Use Cases Beyond Predictive Maintenance](../../wiki/built-environment/ai-in-maintenance-use-cases.md)
> Scope: quantitative evidence on AI and predictive maintenance in the maintenance stage of the building lifecycle, including industrial benchmarks used as transferable anchors, Singapore deployments, occupant-productivity research and insurer loss data.

This note records each source, the full URL, the access date, the specific figures drawn from it, and the limits that determine how far the figure can be pushed. Evidence tiers follow the article: **Tier 1** government, national laboratory, regulator or peer-reviewed study; **Tier 2** consultancy synthesis or industry survey with a stated method; **Tier 3** vendor case study or customer story.

All URLs accessed **12 November 2026** unless otherwise stated. Where a page was bot-blocked during automated checking (HTTP 403/521), it was still retrievable through the search index and is cited at its canonical URL.

---

## 1. US Department of Energy / FEMP — O&M Best Practices Guide

- **Citation:** US Department of Energy, Federal Energy Management Program, *Operations & Maintenance Best Practices Guide: A Guide to Achieving Operational Efficiency*, Release 3.0, Chapter 5, "Types of Maintenance Programs" (August 2010).
- **URL:** https://www1.eere.energy.gov/femp/pdfs/OM_5.pdf
- **Tier:** 1 (government guidance, but the underlying savings studies are unnamed)
- **Figures drawn:**
  - Average US maintenance programme: **>55% reactive, 31% preventive, 12% predictive, 2% other**.
  - Benchmark ranges: predictive maintenance **10–15% typical, 45–55% best-in-class**; reactive 40–60% typical, <10% best-in-class; preventive 30–50% typical, 25–35% best-in-class.
  - Preventive over reactive: **12–18% cost saving**.
  - Predictive over preventive: **8–12% cost saving**.
  - Predictive over reactive: **30–40%** where the facility is heavily reactive.
  - Industrial averages from unnamed surveys: **10× ROI, 25–30% lower maintenance cost, 70–75% fewer breakdowns, 35–45% less downtime, 20–25% more production**.
- **Limits:** The 8–12% and 30–40% figures are published estimates, not measured outcomes, and depend entirely on the baseline. The older industrial averages (10× ROI, 70–75% fewer breakdowns) are low-confidence and should be labelled as best-case illustrations. PNNL's restatement of the same guide is at https://www.pnnl.gov/projects/om-best-practices/maintenance-approaches.

---

## 2. NIST — maintenance costs and advanced maintenance techniques

- **Citation:** Thomas, D. and Weiss, B. (2021). "Maintenance Costs and Advanced Maintenance Techniques in Manufacturing Machinery: Survey and Analysis." *International Journal of Prognostics and Health Management* 12(1). NIST.
- **DOI:** https://doi.org/10.36001/ijphm.2021.v12i1.2883
- **Record:** https://www.nist.gov/publications/maintenance-costs-and-advanced-maintenance-techniques-manufacturing-machinery-survey
- **Tier:** 1 (government survey, peer-reviewed)
- **Figures drawn:**
  - Estimated total annual US maintenance cost/loss: **$222.0 billion** (Monte Carlo).
  - Reactive-heavy top 50% vs the rest: **52.7% less unplanned downtime** and **78.5% fewer defects** in the less-reactive group.
  - Predictive-heavy vs preventive-heavy: **18.5% less unplanned downtime** and **87.3% fewer defects** for the predictive-leaning group.
- **Limits:** Manufacturing, not buildings. The comparison groups are defined by expenditure mix, not by a controlled intervention, so the result is associational.

---

## 3. Deloitte — Making Maintenance Smarter

- **Citation:** Deloitte (2017). *Making Maintenance Smarter: Leveraging Predictive Analytics to Improve Asset Performance*. Deloitte Insights.
- **URL:** https://www2.deloitte.com/content/dam/insights/us/articles/3828_Making-maintenance-smarter/DUP_Making-maintenance-smarter.pdf
- **Tier:** 2 (consultancy synthesis, partly internal client work)
- **Figures drawn:**
  - Predictive maintenance reduces maintenance costs by **5–10%**.
  - Increases equipment uptime and availability by **10–20%**.
  - Reduces maintenance planning time by **20–50%**.
  - Reduces MRO material cost by **5–10%**.
- **Limits:** Benefit ranges are not tied to a single measured sample and the baseline is not always stated. Useful as a conservative planning range.

---

## 4. McKinsey — manufacturing analytics and predictive maintenance

- **Citation:** McKinsey & Company (2017). "Manufacturing: Analytics Unleashes Productivity and Profitability."
- **URL:** https://www.mckinsey.com/capabilities/operations/our-insights/manufacturing-analytics-unleashes-productivity-and-profitability
- **Also:** McKinsey (2015), *Industry 4.0: How to Navigate Digitization of the Manufacturing Sector*, which gives the same ranges: https://www.mckinsey.com/~/media/McKinsey/Business%20Functions/Operations/Our%20Insights/Industry%2040%20How%20to%20navigate%20digitization%20of%20the%20manufacturing%20sector/Industry-40-How-to-navigate-digitization-of-the-manufacturing-sector.pdf
- **Tier:** 2
- **Figures drawn:**
  - Predictive maintenance typically reduces machine downtime by **30–50%**.
  - Increases machine life by **20–40%**.
  - Remote and predictive maintenance typically reduce maintenance costs by **10–40%**.
- **Limits:** Industrial plant evidence, describing mature programmes. Not a building benchmark.

---

## 5. McKinsey — digitising maintenance and reliability

- **Citation:** McKinsey & Company (2021). "A Smarter Way to Digitize Maintenance and Reliability."
- **URL:** https://www.mckinsey.com/capabilities/operations/our-insights/a-smarter-way-to-digitize-maintenance-and-reliability
- **Tier:** 2
- **Figures drawn:**
  - Digital maintenance and reliability levers together can deliver **15–30% cost reduction**.
  - One PdM programme's savings were erased by a **10% false-positive rate**.
  - Lighthouse cases increased profitability by **4–10%**, but are "the exception rather than rule".
  - One offshore operator achieved a **20% average reduction in downtime** after a two-year, 10–15 data-scientist effort building 500+ models.
- **Limits:** The false-positive finding is the most transferable caution; the lighthouse results are explicitly non-typical.

---

## 6. LBNL — automated fault detection and diagnostics characterisation

- **Citation:** Granderson, J., Singla, R., Mayhorn, E., Ehrlich, P., Vrabie, D. and Frank, S. (2017). *Characterization and Survey of Automated Fault Detection and Diagnostics Tools*. LBNL-2001075. Lawrence Berkeley National Laboratory.
- **URL:** https://eta-publications.lbl.gov/sites/default/files/lbnl-2001075.pdf
- **Tier:** 1
- **Figures drawn:**
  - **5–30% of energy used in commercial buildings is wasted** due to faults and errors in control-system operation.
  - AFDD tools detect and isolate those faults; the report characterises 14 market offerings.
- **Limits:** The 5–30% is a literature-derived estimate, not a measured metering study; it bounds the opportunity, not the achievable saving.

---

## 7. LBNL — Smart Energy Analytics Campaign Year 3

- **Citation:** Lawrence Berkeley National Laboratory (2019). *Smart Energy Analytics Campaign Year 3 Report*.
- **URL:** https://bies.lbl.gov/sites/default/files/Smart%20Energy%20Analytics%20Campaign%20Year%203%20Report_LBNL_11.1.19.pdf
- **Tier:** 1
- **Figures drawn:**
  - Participants using **fault detection and diagnostics (FDD)** achieved a **median 9% energy saving**.
  - Participants using only an **energy information system (EIS)** achieved a **median 4% saving** (about $0.04/sq ft).
  - Savings reported from sites with at least two years of EMIS implementation.
- **Limits:** Campaign participants are self-selected and motivated; medians conceal a wide spread.

---

## 8. LBNL — HVAC fault prevalence from 18 million rows

- **Citation:** Crowe, E., Chen, Y., Granderson, J., Reeve, H., Troup, L., Yuill, D. and Chen, Y. (2022). "What We Learned From Analyzing 18 Million Rows of Commercial Buildings' HVAC Fault Data." LBNL / ACEEE Summer Study.
- **URL:** https://smartersmallbuildings.lbl.gov/publications/what-we-learned-analyzing-18-million
- **Supporting slide deck:** https://www.energy.gov/sites/default/files/2023-05/bto-peer-2023-fault-prevalence-lbnl-crowe.pdf
- **Tier:** 1
- **Figures drawn:**
  - Dataset: **317 buildings, 3,660 AHUs, 53,865 terminal units**, almost 18 million rows.
  - Median faults reported: **245 per building per month**; **3 per AHU per month**; **1 per terminal unit per month**.
  - Office example: 8 AHUs and 175 terminal units produced **61 unique faults over 365 days** and **98,234 daily fault records**.
- **Limits:** Data comes from buildings that already run FDD tools, so it may over-represent instrumented, fault-prone or unusually well-monitored sites.

---

## 9. GAO — federal deferred maintenance

- **Citation:** US Government Accountability Office (2025). *Federal Real Property: Disposing of Unneeded Facilities Could Help Reduce Maintenance Backlog*. GAO-25-108400.
- **URL:** https://www.gao.gov/assets/gao-25-108400-highlights.pdf
- **Tier:** 1
- **Figures drawn:**
  - Department of Defense and federal civilian deferred maintenance and repair backlogs **more than doubled from $171 billion to $370 billion between fiscal years 2017 and 2024**.
  - GSA's deferred maintenance backlog **exceeded $17 billion** in March 2025.
  - GAO added building condition to its 2025 High Risk List.
- **Limits:** US federal property only. The **3–4× deferral multiplier** often quoted in industry material could not be traced to a primary source and is not used as a figure in the article.

---

## 10. IFMA — 2026 AI and digitalisation in FM

- **Citation:** International Facility Management Association (2026). *2026 AI & Digitalization in Facilities Management Report*.
- **URL:** https://s3.us-east-2.amazonaws.com/knowledgelibrary.ifma.org/KL_Documents/2026-AI-Digitalization-in-FM-Report.pdf
- **Tier:** 2 (industry survey; 260 US-based facility managers plus business leaders)
- **Figures drawn:**
  - **67% of facility managers** say their organisation is already using AI to improve operation, utilisation and maintenance of facilities (65% of business leaders say the same).
  - Among organisations that have deployed AI for facilities, **47% of FMs** use it to enable predictive maintenance (42% of business leaders).
  - Among those planning AI in the next year, **52% of FMs** and 47% of business leaders are adopting PdM.
  - AI-driven predictive maintenance is the **top planned investment for 2026**.
  - Enabling predictive maintenance is the **third-most popular long-term potential** response (14% of FMs, 15% of business leaders).
- **Limits:** US sample, self-reported adoption. "Using AI" is not defined to a capability level.

---

## 11. ASHB — 2025 smart building trends and technology adoption

- **Citation:** Association for Smarter Homes & Buildings (2025). *2025 Smart Building Trends & Technology Adoption*.
- **URL:** https://www.ashb.com/wp-content/uploads/2025/12/Survey-Executive-Summary.pdf
- **Tier:** 2
- **Figures drawn:**
  - **91%** of respondents report deployed smart devices, systems or software (90% in 2024).
  - **78%** report a BMS/BAS installed and in use; 17% lack one.
  - Top five AI applications: energy optimisation 62%, **predictive maintenance/fault detection 51%**, security and safety 50%, occupant comfort personalisation 48%, space utilisation 34%.
  - Digital twin purposes: real-time monitoring 56%, energy optimisation 43%, **predictive maintenance 41%**.
  - Despite this, the report observes **"only modest adoption of condition-based maintenance … and predictive/prescriptive maintenance"**, and describes "a significant opportunity … to transition from reactive to proactive maintenance strategies".
- **Limits:** The 51% figure combines deployed and planned. The report's own qualitative finding — modest operational adoption — is the more important number.

---

## 12. BCA — Guide to Smart FM, version 2.2

- **Citation:** Building and Construction Authority (2026). *Guide to Smart FM*, version 2.2, 31 July 2026. Developed by the Integrated Smart FM Taskforce under the Facilities Management Implementation Committee.
- **URL:** https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf
- **Landing page:** https://www1.bca.gov.sg/growth-and-transformation/facilities-management/smart-facilities-management/
- **Local copy:** [Guide to Smart FM (v2.2, 31 July 2026)](2026-07-31-guide-to-smart-fm.md)
- **Tier:** 1 (government guide reporting deployments)
- **Figures drawn — digiHUB (CBM Private Limited and City Developments Limited):**
  - Engineering IoT sensors / predictive maintenance: **50% productivity improvement**.
  - FM process auto-ticketing system: **90.8% productivity improvement**.
  - Toilet monitoring: 20.5%; self-service visitor kiosk: 100%; virtual patrol, video analytics and robotics: 20%.
  - Overall productivity improvement across the developments: **approximately 23–25%**.
  - Projected cumulative cost savings: **approximately S$11.3 million over 11 years**.
  - Predictive maintenance reduced routine inspection frequency for selected equipment **from monthly to bi-monthly**.
  - Productivity figures derived from before-and-after workflow studies comparing baseline manpower hours with post-deployment hours.
- **Figures drawn — Schindler Ahead (KK Women's and Children's Hospital):**
  - Technical callbacks per month fell **43%**.
  - Total downtime per month fell **94%**.
  - Monitoring cubes installed in lifts; each technician has a mobile app linked to the system.
- **Limits:** Case-study evidence selected for a government guide; the digiHUB savings are a vendor business-case projection, not an audited outcome. The 23–25% overall figure is the more conservative and more useful number.

---

## 13. BCA — Periodic Façade Inspection

- **Citation:** Building and Construction Authority, "Periodic Façade Inspection (PFI)".
- **URL:** https://www1.bca.gov.sg/regulatory-info/building-control/periodic-fa%C3%A7ade-inspection-pfi
- **Tier:** 1 (regulator)
- **Figures drawn:**
  - PFI regime implemented **from 1 January 2022**.
  - Buildings **more than 20 years old** are inspected **every 7 years**, with exceptions for detached, semi-detached and terraced/linked houses.
  - Owners are responsible for maintaining façades and exterior features in a safe condition.
- **Limits:** Establishes recurring inspection demand, not AI savings.

---

## 14. Zhu, van Jaarsveld and Dekker — spare-parts inventory control

- **Citation:** Zhu, S., van Jaarsveld, W. and Dekker, R. (2020). "Spare Parts Inventory Control Based on Maintenance Planning." *Reliability Engineering & System Safety* 193: 106600.
- **DOI:** https://doi.org/10.1016/j.ress.2019.106600
- **Open version:** https://econ.au.dk/fileadmin/user_upload/SpareParts_Zhu.pdf
- **Tier:** 1 (peer-reviewed)
- **Figures drawn:**
  - Using the maintenance plan as advance demand information, instead of time-series forecasting of historical consumption, yields **23–51% cost savings** compared with traditional inventory-control methods.
  - Benchmarked on data from **two large maintenance organisations**, covering thousands of parts.
- **Limits:** Not building-specific; savings are inventory-holding and shortage costs, not maintenance labour.

---

## 15. Wrench-time benchmarks

- **Citation:** Smith, R. and Mobley, R.K. (2007). *Rules of Thumb for Maintenance and Reliability Engineers*. Butterworth-Heinemann. Figures reproduced by Prometheus Group and SMRP.
- **URL:** https://www.prometheusgroup.com/resources/posts/5-things-you-need-to-know-about-measuring-wrench-time
- **SMRP metric sheet:** https://smrp.org/Learning-Resources/SMRP-Library/Best-Practices-Metrics-Guidelines
- **Tier:** 1/2 (professional-body metric with a published primary reference)
- **Figures drawn:**
  - **Most companies: 18–30% wrench time.** World-class: **55–65%**.
  - Widely repeated industry average: **25–35% typical**; SMRP's metric sheet sets a best-in-class target of **50–55%**.
  - SMRP notes that typical wrench time in a reactive environment without effective planning is **less than 30%**.
  - Moving from 35% to 55% is approximately a **57% increase in effective capacity** from the same crew (Palmer's arithmetic).
- **Limits:** Benchmarks are industrial and measured by work sampling. The 57% is theoretical capacity, not a measured field outcome. Building FM teams may run lower because of travel between sites.

---

## 16. Textron Aviation — maintenance copilot

- **Citation:** Microsoft (2025). "Textron Aviation Enhances Maintenance Efficiency with Azure AI." Microsoft Customer Stories.
- **URL:** https://www.microsoft.com/en/customers/story/23024-textron-aviation-azure-open-ai-service
- **Tier:** 3 (vendor customer story)
- **Figures drawn:**
  - Assistant built on Azure OpenAI Service over **60,000+ pages** of maintenance documentation.
  - Troubleshooting time reduced **from 20 minutes to 1–2 minutes**.
- **Limits:** Single aerospace manufacturer; the task is document retrieval, not diagnosis. The percentage is not a maintenance-cost saving.

---

## 17. C3 AI — generative AI troubleshooting

- **Citation:** C3 AI (2025). "Leading Tire Manufacturer Reduces Equipment Troubleshooting Time with C3 Generative AI."
- **URL:** https://c3.ai/customers/leading-tire-manufacturer-reduces-equipment-troubleshooting-time-with-c3-generative-ai
- **Tier:** 3 (vendor case study)
- **Figures drawn:**
  - **90%** answer accuracy for troubleshooting.
  - **50%** estimated reduction in average time to repair downtime issues.
  - 150+ acronyms and shorthand recognised.
- **Limits:** Self-reported by the vendor, single customer, no independent verification.

---

## 18. H3 Zoom — AI façade inspection

- **Citations:**
  - The Business Times (8 April 2026). "AI-Driven Inspection Platform Boosts Productivity by 70% for H3 Zoom." https://www.businesstimes.com.sg/events-awards/design-ai-tech-awards/design-ai-and-tech-awards/ai-driven-inspection-platform-boosts-productivity-70-h3-zoom
  - JTC (2023). "Flight of the Inspection Drones: One Start-up's 'Crazy' Idea to Disrupt Building Inspections with Tech." https://www.jtc.gov.sg/about-jtc/news-and-stories/feature-stories/flight-of-the-inspection-drones-one-start-ups-crazy-idea-to-disrupt-building-inspections-with-tech
  - H3 Zoom product page: https://www.h3zoom.ai/facadeinspector
- **Tier:** 3 (vendor deployment, reported by a newspaper and a government estate owner)
- **Figures drawn:**
  - Inspection completion about **90% faster**; costs roughly **halved**; accuracy up to **4×** better.
  - About **20% more defects** identified through the AI-assisted workflow.
  - At JTC, across **160+ properties**, an **80% increase in inspection productivity**.
  - JTC's own pilot: inspection time reduced by **70%**; JTC Summit cut **from 4 weeks to 8 days**.
  - 10,000+ inspections across APAC as at 2025, in **7 markets**.
- **Limits:** Vendor-reported. The productivity gain is concentrated in capture and reporting, and the comparison baseline is manual rope-access or gondola inspection.

---

## 19. Screening Eagle / Demaco — digital Periodic Structural Inspection

- **Citation:** Screening Eagle Technologies (2021). "Digital Periodic Structural Inspection (PSI) for Higher Efficiency." Case study with Demaco Consultants, Singapore.
- **URL:** https://www.screeningeagle.com/en/inspection/efficient-periodic-structural-inspection
- **Tier:** 3 (vendor case study)
- **Figures drawn:**
  - Productivity increased by **30–40%**; onsite manpower reduced by **50%**.
  - Proceq research cited in the case: **up to 65% of time on an inspection job is spent writing the report**.
  - Demaco has inspected **100,000 m²** of façades and **200,000 m²** of floor area.
- **Limits:** Single consultancy; the 30–40% is time per project, not a cost saving after software and training.

---

## 20. Aon — liquid damage as a cause of property loss

- **Citation:** Aon (2023). *Liquid Damage: A Significant Cause of Property Losses*.
- **URL:** https://www.aon.com/getmedia/987f3b69-86ac-42af-9af4-6845519485dc/Liquid-Damage-A-Significant-Cause-of-Property-Losses.pdf
- **Tier:** 2 (insurance broker synthesis of insurer data)
- **Figures drawn:**
  - AIG reports liquid damage accounts for **34% of property claims frequency**.
  - FM Global reports escaped-liquid losses account for **30–40% of all claims** in real estate, education, healthcare, hospitality and retail, and **more than $100 million of loss every year** in those occupancies.
  - In hospitals, **more than 40% of damage incidents** are attributable to water — more than twice the share from fire, windstorm or earthquake.
  - Many water losses fall below deductibles and are never reported, so the true count is higher.
- **Limits:** Claims frequency, not severity; the insurer mix differs from any single building portfolio.

---

## 21. Munich Re / HSB — WINT water intelligence

- **Citation:** Munich Re / HSB (24 June 2024). "HSB Adds WINT Water Intelligence Technology to Water Leak Detection Portfolio."
- **URL:** https://www.munichre.com/hsb/en/press-and-publications/press-releases/2024/2024-06-24-wint-water-intelligence-technology-leak-detection.html
- **Tier:** 2 (insurer study of a specific product)
- **Figures drawn:**
  - A Munich Re study comparing WINT-protected sites with unprotected sites found **73% fewer claims** and **90% lower payouts** on protected sites.
  - Water damage is described as the leading cause of loss; pipe leaks are among the most common insurance payouts in construction and operational buildings.
- **Limits:** Product-specific and insurer-selected. The comparison may include selection effects (better-managed sites are more likely to install monitoring).

---

## 22. Seppänen, Fisk and Lei — temperature and task performance

- **Citation:** Seppänen, O., Fisk, W.J. and Lei, Q.H. (2006). *Effect of Temperature on Task Performance in Office Environment*. LBNL-60946. Lawrence Berkeley National Laboratory.
- **URL:** https://eta-publications.lbl.gov/sites/default/files/lbnl-60946.pdf
- **Also:** Seppänen, Fisk and Faulkner (2003), *Cost Benefit Analysis of the Night-Time Ventilative Cooling in Office Building*, LBNL-53191, https://eta-publications.lbl.gov/sites/default/files/lbnl-53191.pdf
- **Tier:** 1 (peer-reviewed review and meta-analysis)
- **Figures drawn:**
  - Performance **decreases by 2% per °C** increase in the **25–32 °C** range; no effect in the **21–25 °C** range.
  - Highest productivity is at about **22 °C**; performance increases up to 21–22 °C and decreases above 23–24 °C.
  - At **30 °C**, performance is **91.1% of maximum** — an **8.9% reduction**.
  - The linear relationship used in the 2003 cost-benefit paper is **P(%) = 2 × T − 50** for T > 25 °C.
- **Limits:** The underlying tasks are simple office tasks (text processing, arithmetic, call-centre handling). The authors explicitly caution that transfer to real office work is uncertain. It is an average, not a building-specific measurement.

---

## 23. Milton, Glencross and Walters — ventilation and sick leave

- **Citation:** Milton, D.K., Glencross, P.M. and Walters, M.D. (2000). "Risk of Sick Leave Associated with Outdoor Air Supply Rate, Humidification, and Occupant Complaints." *Indoor Air* 10(4): 212–221.
- **DOI:** https://doi.org/10.1034/j.1600-0668.2000.010004212.x
- **PubMed:** https://pubmed.ncbi.nlm.nih.gov/11089326/
- **Tier:** 1 (peer-reviewed epidemiology)
- **Figures drawn:**
  - 3,720 hourly employees, 40 buildings, 115 independently ventilated work areas.
  - Moderate ventilation ~**25 cfm/person (12 L/s)** vs high ~**50 cfm/person (24 L/s)**.
  - Office workers in moderately ventilated areas were **53% more likely** to take short-term sick leave (relative risk 1.53, 95% CI 1.22–1.92).
  - **35%** of short-term sick leave in the lower-ventilation group was attributable to lower ventilation — about **1.2–1.9 additional days per person per year**.
  - Cost of sick leave attributable to ventilation: **$480 per employee per year**; net saving from increased ventilation about **$400 per employee per year**.
  - National lost-productivity estimate: up to **$22.8 billion per year** (short-term sick leave only).
- **Limits:** One manufacturer, 1994 data, observational. The LBNL indoor-air synthesis notes that only one of three office studies found this association; the other two had high ventilation rates.

---

## 24. Allen et al. — COGfx cognitive function study

- **Citation:** Allen, J.G., MacNaughton, P., Satish, U., Santanam, S., Vallarino, J. and Spengler, J.D. (2016). "Associations of Cognitive Function Scores with Carbon Dioxide, Ventilation, and Volatile Organic Compound Exposures in Office Workers: A Controlled Exposure Study of Green and Conventional Office Environments." *Environmental Health Perspectives* 124(6): 805–812.
- **DOI:** https://doi.org/10.1289/ehp.1510037
- **Open PDF:** https://ehp.niehs.nih.gov/doi/10.1289/ehp.1510037
- **Tier:** 1 (peer-reviewed controlled exposure study)
- **Figures drawn:**
  - 24 participants, 6 full work days, double-blind repeated measures.
  - Cognitive scores **61% higher** on the green building day and **101% higher** on the green-plus-ventilation days than on the conventional day.
  - Doubling outdoor-air ventilation raised scores about **25%** on average.
  - Cost of doubling ventilation: **under $40 per person per year** in every climate zone studied.
  - Productivity benefit: **above $6,500 per person per year** (reported in Allen's Harvard dissertation and widely cited from this work).
  - Largest effects in crisis response, information usage and strategy.
- **Limits:** 24 participants, six days, artificial office environment. Cognitive test scores are not the same as productivity. The $6,500 benefit is a modelled extrapolation, not a measured payroll outcome.

---

## Cross-cutting notes for reuse

1. **Baseline discipline.** Every PdM saving claim must state whether the comparison is reactive or preventive. DOE's 8–12% and 30–40% are the same programme against different baselines.
2. **Tier discipline.** Do not mix Tier 3 vendor figures into a Tier 1 range without labelling. The article keeps them separate and says so.
3. **Occupant cost is modelled.** The 2%/°C relationship is an average for simple office tasks. Use it to size consequence, then validate against complaints, absence and tenant-satisfaction data.
4. **Count the disruption, not just the dollars.** Occupant-hours disrupted is a defensible unit that does not depend on a loaded-cost assumption.
5. **False positives are a cost centre.** McKinsey's 10% false-positive result belongs in every PdM business case.
6. **Singapore evidence is workflow-heavy.** The strongest local numbers are auto-ticketing, façade inspection and PSI reporting — digitalisation and computer vision, not failure prediction.
