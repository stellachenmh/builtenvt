# Digital Twin and AI-Enabled Predictive Maintenance in the Building Industry

> Sources: Hu, W. (2024). *Digital twin and AI enabled predictive maintenance in building industry*. Doctoral thesis, Nanyang Technological University, Singapore. https://doi.org/10.32657/10356/180365. Underlying papers: Hu, Lim and Cai, "Digital Twin and Industry 4.0 Enablers in Building and Construction: A Survey", *Buildings* 12(11): 2004 (2022); Hu and Cai, "A semi-supervised method for digital twin-enabled predictive maintenance in the building industry", *Neural Computing and Applications* (2024); Hu, Wang, Tan and Cai, "Digital Twin-Enhanced Predictive Maintenance for Indoor Climate: A Parallel LSTM-Autoencoder Failure Prediction Approach", *Energy & Buildings* 301: 113738 (2023).
> Raw: [Digital Twin and AI-Enabled Predictive Maintenance in Building Industry (PhD thesis, Hu Wei, NTU 2024)](../../raw/built-environment/2024-hu-wei-digital-twin-ai-predictive-maintenance-thesis.md)
> Updated: 2026-11-12

## Overview

This thesis asks how predictive maintenance (PdM) should be organised for buildings, and what it takes to predict failures when labelled failure data are scarce. Its answer has two parts: a management and systems framework built on a **Six M** taxonomy, and two machine-learning methods — a semi-supervised generative adversarial network for building facilities and a parallel LSTM-autoencoder for indoor climate.

The thesis is best read as a **methods contribution**, not a deployment evaluation. Its quantitative results are model-performance metrics on public or pilot datasets. It does not measure maintenance-cost savings, production uptime or enterprise return. That distinction matters because the built environment already has plenty of PdM claims and very little audited outcome evidence; this work is more useful for designing a PdM programme than for justifying one financially.

Its most transferable idea is not a model. It is the argument that PdM fails when it is treated as an equipment-level algorithm rather than a **whole-system problem spanning assets, people, materials, measurement, environment and method**. The Six M and Three-by-Three M frameworks make that argument operational, and they expose where the research field is thin: failure prognosis, human factors, and the maintenance implications of design decisions.

## Why maintenance, and why a digital twin

The thesis opens with the scale of the problem. Maintenance is described as the most labour-intensive and influential part of facilities management, with roughly **one-third of management expenses** attributed to maintenance and **over 30% of total management costs** going to maintenance procedures. It cites McKinsey's estimate that predictive strategies could save up to **US$630 billion** in maintenance by 2025. These are framing figures, not measurements from the thesis, but they explain why PdM attracts investment.

The maintenance argument is a progression:

| Stage | Trigger | Limitation |
|-------|---------|------------|
| Corrective | Failure has occurred | Downtime, collateral damage, emergency cost |
| Preventive | Calendar or usage schedule | Replaces healthy components; misses random failures |
| Condition-based | Measured condition crosses a threshold | Detects the present state, not the future one |
| Predictive | Model forecasts failure within a horizon | Depends on data, labels, and a model that generalises |

A digital twin enters as the integration layer. The thesis defines it as a "high fidelity digital model of the physical asset with bi-directional real-time data exchange for simulation and decision support functions". In the building context, that means BIM and other 3D models, IoT and building-management-system data, simulation and analytics, and a visualisation or decision-support interface.

The thesis is careful about the construction-specific difference: a building digital twin is not a generic manufacturing twin. It uses BIM and domain protocols, spans design, construction and operation, and must integrate assets that were installed by different vendors at different times. That is why the thesis spends more effort on architecture and taxonomy than on a single model.

## The Six M lens

The Six M taxonomy is adapted from Ishikawa's cause-and-effect diagram. It divides the factors that determine whether PdM works into two groups.

| Group | Dimension | What it covers |
|-------|-----------|----------------|
| **Hard M — the target and setting** | **Machine** | Building facilities (HVAC, lifts) and construction equipment (cranes, TBMs); repair, malfunction and obsolescence |
| | **Material** | Building components other than machines — pavement, walls, tiles, roofs, cables, pipes; quality, availability and compatibility |
| | **Milieu** | The practice environment — buildings, bridges, sites; ambient conditions, layout and site management |
| **Soft M — the method** | **Method** | Procedures and processes: fault identification, fault prognosis, degradation analysis, strategy optimisation, lifecycle and asset management |
| | **Measurement** | Converting graphical or physical information into usable quantities; sensing, inspection and data transformation |
| | **Manpower** | The workforce from designers to operators; training, experience, workload and safety during maintenance |

The **Three-by-Three M** analysis pairs the hard and soft dimensions. The thesis uses it to classify 122 PdM papers published between 2018 and 2022, identified through a PRISMA-style Scopus search and analysed with VOSviewer keyword co-occurrence (1,391 keywords, of which 59 met a minimum of four co-occurrences).

The distribution is revealing:

- **Machine-focused work exceeds 40%** of the sample, and HVAC alone accounts for more than half of the machine-related publications. Building-facility research is denser than construction-machinery research, which the thesis attributes to the complexity and harsh operating conditions of construction equipment.
- **Material-related work is nearly one-third** of the sample, spread across structural elements, facades, roofs, slabs, beams, columns, masonry, concrete, steel and MEP components.
- **Milieu-related work is about 29%**, split between single-building studies and community or city-scale studies.
- **Method dominates the soft dimensions.** Fault identification is the most popular function. Fault prognosis — actual failure prediction — is much less studied, and is concentrated in the Machine domain.
- **Manpower is the least developed dimension.** The thesis finds that most studies ignore task assignment, worker training and safety management during maintenance, even though most maintenance is still performed manually.

That last point is the thesis's sharpest critique of its own field. A PdM literature that models equipment but not the people who act on the prediction has modelled only half of the maintenance system.

The review also identifies a lifecycle bias: research concentrates on the operations and maintenance phase, and pays little attention to how design and construction decisions create or remove maintenance burdens later.

## Four clusters of PdM research

The keyword-network analysis groups the literature into four clusters. The labels are the thesis's own, and they describe how maintenance is embodied rather than which algorithm is used.

| Cluster | Core idea | Methods | Strength | Weakness |
|---------|-----------|---------|----------|----------|
| **Physical–numerical** | Deterioration modelling and maintenance strategy for physical assets | Monte Carlo, Markov models, multi-criteria decision-making, reliability statistics | Works with limited data; encodes engineering knowledge | Needs deep domain knowledge; weak scalability and generality |
| **Physical–intelligent** | Detection and forecasting using machine learning on physical assets | Classification, regression, deep learning, anomaly detection | Learns from data; algorithms transfer across maintenance domains | Demands data acquisition and labels |
| **Virtual–intelligent** | BIM and AI for condition assessment, decision support and information management | BIM, visualisation, AI, simulation | Makes maintenance tasks more accessible and operable; reduces specialised-knowledge requirements | Increases data-collection and model-building requirements |
| **Virtual–physical** | Continuous bi-directional exchange through digital twins and IoT | IoT, digital twin, data mining, automation and robotics | Closest to a live, integrated maintenance system; high automation potential | Requires large volumes of operating and environmental data |

The clusters are a maturity map as much as a taxonomy. Most published work sits in the first two; the fourth is the direction the thesis argues for, and the one with the least empirical evidence.

## A five-layer digital-twin architecture

The thesis proposes a five-layer architecture for integrating Industry 4.0 technologies in construction and building operations:

1. **Cyber-physical layer** — sensors, actuators, communication protocols and the physical asset; multi-source data acquisition and two-way connectivity.
2. **Data-processing layer** — cleaning, filtering, conversion, fusion and semantic modelling; storage in databases or data lakes.
3. **Computational layer** — cloud and edge computing, data mining, optimisation and machine learning.
4. **Functional layer** — the construction or maintenance application: condition monitoring, failure prediction, schedule optimisation, safety, asset management.
5. **Visualisation layer** — BIM, dashboards and interfaces that make the state and recommendations usable.

For PdM specifically, the thesis condenses this into a three-layer service architecture: a cyber-physical layer that digitises facilities and environment, an intelligent layer that processes data and develops models, and a functional layer that delivers condition monitoring, failure prediction and schedule optimisation. The progression is deliberate: condition monitoring needs operational data; failure prediction needs richer data and better algorithms; schedule optimisation also needs maintenance records.

The thesis identifies **11 future directions**, including multi-function sensor systems, AI-enhanced functions, integrated multi-function twins, multi-asset servitisation, city-scale twins, full-lifecycle coverage, circular-economy and lean integration, time-based analysis and economic feasibility. The list is a research agenda, not a roadmap with costs.

## Predicting failures with less labelled data

The first method addresses the binding constraint in building PdM: **failure labels are expensive**. Telemetry is abundant; records of what failed, when, and why are sparse, inconsistent or held by vendors.

### The method

The thesis uses a **semi-supervised GAN**. A generator learns the distribution of unlabelled operational data; a classifier learns from the smaller labelled set and from adversarial training against the generator. The classifier is then deployed without the generator. The pipeline includes anomaly removal, missing-value imputation, standardisation, synthetic minority-class samples, and a time-to-failure calculation that labels an observation as a failure event if it falls inside a chosen warning window.

The data are Microsoft's public predictive-maintenance dataset: **100 building-related facilities** — elevators and air-conditioning systems — with hourly voltage, rotation, pressure and vibration readings, plus machine attributes and failure records, covering 2015.

### The results

| Test | Result |
|------|--------|
| Accuracy versus supervised and semi-supervised benchmarks | **10–20% improvement** under the same hyperparameters |
| Labelled data needed | Nearly **80% accuracy with 30 days** of labels, versus about **60%** for comparison algorithms |
| Best label-cost trade-off | **21 days** of labelled data on this dataset |
| Very small labelled sets | Performance degrades; the method reduces label dependence but does not remove it |
| Class imbalance | Performance declines as the normal-to-fault ratio moves from 1:1 to 1:10; one benchmark (KNN) is 2% better at 1:10 |
| Training cost | **10.5 seconds** wall time on an RTX 4070 laptop GPU |

The label-efficiency result is the decision-relevant one. It means a building operator does not need a fully annotated failure history to start. It does not mean labels are optional: the curve shows a floor below which accuracy falls away, and the optimum is still weeks of expert-labelled data.

The imbalance result is equally important. Real buildings produce mostly normal data. A model that looks good on a balanced test set can degrade toward random guessing as failures become rarer — which is the normal condition of a healthy building.

## Extending PdM to indoor climate

The second method treats indoor air quality as a maintenance target in its own right. The argument is that indoor climate — temperature, humidity, particulate matter, TVOC and CO₂ — affects occupant health, comfort and productivity, and that most people spend **more than 80% of their time indoors**. Yet building PdM research concentrates on equipment, not on the environment those systems exist to maintain.

### The method

The thesis combines two labels:

- **Remaining useful life (RUL)** — how long until the environment crosses a failure threshold.
- **Time shift (TS)** — a transformed view of the same series that turns part of the problem into an unsupervised task.

The prediction task is split into a supervised LSTM component, which learns temporal dependencies and predicts the future index, and an unsupervised autoencoder component, which learns normal patterns and flags reconstruction error above a threshold. The two are combined by gradient boosting or logical disjunction, so that either a predicted deterioration or an anomalous reconstruction can trigger an alarm.

### The data

The dataset covers commercial, residential and educational buildings across Singapore between **22 January 2022 and 22 January 2023**, at one-minute intervals. The experiment uses a four-month subset from **Lakeside station**: **172,800 data points**, with three months for training and one month for testing. Inputs include PM2.5, TVOC, relative humidity, temperature and CO₂, aggregated into an overall air-quality index. Failure severity is defined against the US AQI scale: low above 100, medium above 150, high above 200.

### The results

The model was tested across warning times from 10 minutes to 2 hours and across the three severity levels.

| Scenario | Accuracy | Precision | Recall | F1 |
|----------|----------|-----------|--------|-----|
| Low severity, 30-minute warning (best case) | **0.87** | **0.96** | **0.77** | **0.86** |
| Low severity overall | Close to **80%** | — | — | — |
| Medium and high severity | Degrades as warning time lengthens | — | — | — |
| High severity, 2-hour warning | About **0.5** — effectively random | — | — | — |

Two patterns matter for practice:

1. **Warning time and severity trade off.** A 30-minute warning is useful for low-severity events; a two-hour warning for high-severity events is not. The model is not a general "predict any failure two hours ahead" system.
2. **The metrics disagree by severity.** Low-severity predictions have high precision but lower recall — the model is conservative and misses some events. Medium- and high-severity predictions have higher recall than precision — the model catches most serious events but raises more false alarms. Which error matters is an operational choice, not a modelling one.

The proposed model outperformed Random Forest, SVM, a neural network and a standalone LSTM by more than **10%** across severity levels. At the highest severity, the accuracy gap to LSTM shrank to 0.06, and the neural network's accuracy was slightly higher; the proposed model's advantage was in recall and F1, not uniform dominance.

The cross-location test is the most honest part of the evaluation. A model trained on Lakeside and applied unchanged to Pioneer and Woodland performed better overall than benchmarks trained on those datasets, but its precision was lower, and the advantage narrowed as the data distribution diverged. Woodland, on Singapore's northern border, was less similar to Lakeside than Pioneer was. The lesson is that a model can transfer, but not free of charge: distance in data distribution shows up as distance in performance.

## Two prototypes, not two products

Both methods are demonstrated through Streamlit web applications. The facility prototype displays voltage, rotation, pressure, vibration and a binary alarm, plus a maintenance-record page. The indoor-climate prototype combines an **IScan2BIM** reconstruction of the building with real-time IAQ readings and a binary alarm, and shows a 30-minute warning period.

Both are prototypes. The facility platform reads from CSV files and runs on a local server. The indoor-climate platform also reads CSV data and is deployed locally; the thesis states that future work will use APIs for real-time collection and move to online deployment. The digital twin in these demonstrations is primarily a **BIM-based visualisation and integration layer**, not a physics-based simulation twin with bidirectional control.

The thesis is also candid about a real-world trial that did not produce usable data: two air-conditioning units were monitored for two months, but there were almost no fault records, and the sensors were highly susceptible to environmental noise. The experiments therefore fell back on public data. That is a more useful finding than a success story: **the data problem in buildings is not only labelling effort, but the absence of failures during a short trial and the fragility of low-cost sensing**.

## What the thesis contributes

1. **A unified architecture** for integrating Industry 4.0 technologies into a digital twin for construction and building operations, with the Six M taxonomy as the organising lens.
2. **A categorisation of PdM research** into four clusters, and a Three-by-Three M matrix that connects hard application domains to soft methodological capabilities.
3. **A label-efficient failure-prediction method** using semi-supervised GANs, with evidence that unlabelled data can substitute for some — not all — labelled data.
4. **A hybrid RUL/time-shift method** for indoor climate, combining LSTM and autoencoder components and evaluating it across warning times, severity levels and building locations.
5. **A practical demonstration** of how BIM, IoT and a dashboard can be assembled into a PdM service layer, including the IScan2BIM pipeline for buildings without as-built models.

## What the evidence does and does not show

- **It shows the methods can work on curated datasets.** The semi-GAN and LSTM-AE results are credible under their experimental conditions, with repeated random seeds, multiple dataset splits and benchmark comparisons.
- **It does not show a maintenance-cost saving.** No cost-per-failure, downtime, energy or headcount outcome is measured. The business case for PdM still has to be built separately.
- **It does not show production readiness.** The platforms are local prototypes fed by CSV files; integration with BMS, CMMS, procurement and work-order systems is future work.
- **It does not solve the label problem, only reduces it.** The 21-day optimum and the degradation at very small label sets are the honest boundary.
- **It does not validate the digital twin as a simulation.** The twin is an integration and visualisation layer; simulation-based "what-if" analysis is described as a capability, not tested as an outcome.
- **It does not model the human system it identifies as critical.** Manpower is named as the neglected dimension, but task assignment, training, safety and workload are not implemented in either method.
- **The Singapore IAQ evidence is local but narrow.** One four-month station-level dataset, one city, one sensor configuration, and a device that could not measure SO₂, NO₂, CO, PM10 or O₃.
- **The thesis's own limits are the right ones.** Data quality and scarcity, scalability to complex systems, computational cost, and concept drift under changing operations are all acknowledged and all remain open.

## What this means for practice

For a building owner or FM provider, the thesis supports five practical conclusions.

1. **Start with the Six M diagnostic, not a model.** Map the asset, the material or environment, the measurement chain, the method, and the people who will act on the alert. A model that predicts a failure nobody is resourced to fix is not a maintenance capability.
2. **Treat labels as a capital project.** The semi-GAN result says a modest labelled set can go a long way, but not that labelling can be skipped. The practical move is to instrument the maintenance record — capture failure time, type and severity as a by-product of work orders — rather than run a one-off annotation exercise.
3. **Specify the operating envelope.** "Predictive maintenance" is not a single claim. State the warning horizon, the failure severity, the acceptable false-alarm rate and the action that follows. A 30-minute low-severity alert and a two-hour high-severity alert are different products.
4. **Expect distribution shift.** A model trained in one building, climate zone or sensor configuration will not transfer without a performance penalty. Budget for local validation and retraining, and monitor drift.
5. **Use the digital twin as an integration layer first.** BIM plus IoT plus a dashboard is already valuable for visibility and diagnosis. Simulation and closed-loop control are a later stage, and require model fidelity, sensor trust and governance that most buildings do not yet have.

The thesis also sharpens the connection to Singapore's Smart FM agenda. BCA's Smart FM framework describes Type 2 "optimisation within systems" — predictive maintenance that intervenes before serious issues develop — and Type 3 integration across systems. This thesis supplies a plausible technical route from Type 1 monitoring to Type 2 prediction, and shows why Type 2 is harder than it looks: the constraint is not the dashboard but the labelled failure history, the operating envelope and the maintenance workflow behind the alert.

## See Also

- [Smart Facilities Management: Integrated, Aggregated and Smart FM](smart-facilities-management.md) — the operating model, Smart FM types and contract conditions that PdM has to fit into.
- [AI in the Built Environment](ai-in-the-built-environment.md) — BCA's five AI use-case families, including inspections and progress analytics, and the digital foundations they assume.
- [Data Readiness for AI in Construction](data-readiness-for-ai-in-construction.md) — why sensor, asset and failure data must be standardised before prediction is trustworthy.
- [Quantified AI Benefits in the Built Environment](quantified-ai-benefits-five-use-cases.md) — measured time and cost evidence for AI use cases, and the gap between task-level model performance and enterprise return.
- [AI in Building Maintenance: Nine Use Cases Beyond Predictive Maintenance](ai-in-maintenance-use-cases.md) — where PdM sits among eight other maintenance use cases, and the four-metric business case it has to satisfy.
- [AI Adoption Risks in the Built Environment](ai-adoption-risks-in-the-built-environment.md) — the skills, data-quality, governance and ROI risks that limit PdM adoption.
- [Integrated Digital Delivery (IDD)](integrated-digital-delivery.md) — the BIM and data-exchange framework that building twins depend on.
- [The Built Environment, Disrupted](the-built-environment-disrupted.md) — the ageing workforce and resource pressures behind the case for predictive maintenance.
