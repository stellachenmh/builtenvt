# Guide to Smart FM (v2.2, 31 July 2026)

> Source: https://isomer-user-content.by.gov.sg/338/033e3b4f-13d8-463d-b6df-25176d687d72/Guide%20to%20Smart%20FM%20v2.2%20(31%20July%202026).pdf
> Collected: 2026-11-10
> Published: 2026-07-31

[Full extracted text of the 142-page BCA Guide to Smart FM, version 2.2. Page markers indicate PDF pages; printed page numbers appear beneath them. Formatting noise from PDF extraction has been cleaned, but wording and figures are unchanged.]


===== PAGE 1 =====
 
GUIDE TO 
SMART FM 
 
 
An initiative from the FMIC (Facilities Management Implementation Committee) Smart FM Taskforce 
 
===== PAGE 2 =====
i 
 
Guide to Smart FM Revision Log 
 
S/N Brief description of changes Revision date 
01 First issue 1 Oct 2019 
02 Second issue 6 Sep 2022 
02.1 Second issue with updates: 
- Updated Preface 
- Added Smart Energy Management 
Committee and contributors to the case 
study writeups under Acknowledgement 
- Updated Section 4.2.4 on Cybersecurity for 
Smart Buildings 
- New case study under Appendix C.6 Smart 
Energy Management for ACMV Systems 
- New Appendix F on Essential Smart FM use 
cases 
7 Oct 2024 
02.2 Second issue with updates: 
- New case studies under Appendix C.6: 
o An Integrated Smart FM Ecosystem 
enabling Outcome-based IFM 
Operations 
o Eliminating Plug-Load Standby 
Waste in a Commercial Office 
 
31 July 2026 
===== PAGE 3 =====
ii 
 
 
Preface 
With our ageing workforce and building stock, there is a need to transform our FM 
industry to shift from the current ways of managing building facilities that are labour 
intensive, to a productive one, using smart solutions, predictive maintenance, and data 
analytics. BCA was tasked to coordinate the development of the FM industry as part 
of the Real Estate Industry Transformation Map (ITM) launched in February 2018. A 
tripartite Facilities Management Implementation Committee (FMIC) was formed in 
April 2018, comprising both public and private building owners, FM service and 
solution providers, trade associations and chambers (TACs), and unions, to 
spearhead and develop detailed action plans to implement the transformation 
strategies identified in the Real Estate ITM. 
An Integrated Smart FM Taskforce under the FMIC was formed to help drive industry 
adoption of technology and leverage on smart FM technology solutions, to streamline 
existing FM work processes and enhance FM productivity and service quality. This 
Guide to Smart FM was developed by the Taskforce and launched on 1 October 2019 
to provide Building Owners and FM Managers with an easy-to-use reference, to guide 
them on the key steps to take in their Smart FM journey. 
Since then, there has been greater awareness and adoption of Smart FM solutions, 
especially Type 1 and 2 Smart FM solutions such as workflow automation and system 
optimization. Going forward, as we make further progress towards Integrated FM and 
Aggregated FM (IFM and AFM), the Taskforce seeks to provide more guidance as we 
start to adopt more advance Type 3 Smart FM technologies. FM processes and digital 
skillset of our workforce would also need to be reviewed and enhanced. These new 
topics would be covered in Chapters 3, 4, and 5. 
In Chapter 3, the concept of Digitalisation Maturity Map is proposed to map out the 
different levels and systems of digital adoption and integration across the FM value 
chain. When there is clarity and digital integration between vendors/sub -contractors, 
FM Companies, and Building Owners, we stand a better chance to unlock the potential 
of digital transformation and harness the synergy within and across the FM supply 
chain for performance optimisation. 
===== PAGE 4 =====
iii 
 
 
To support these new processes, best practices in data management such as 
Common Data Environment (CDE) for FM, data connectivity and interoperability are 
discussed in Chapter 4. In Chapter 5, a list of digital skillsets to support Type 3 Smart 
FM processe s and technologies are mapped out. These skillsets are aligned and 
mapped with the Technical Skills and Competencies (TSCs) under the BE Skills 
Framework (SFw). 
To reflect the latest industry developments, this edition includes new Smart FM case 
studies that demonstrate how organisations are successfully implementing digital 
technologies to achieve measurable operational improvements. The addition of the 
digiHUB case study illustrates how an integrated Smart FM ecosystem combines 
predictive maintenance, IoT, analytics and workflow automation to improve 
productivity and operational visibility across multiple FM functions. The Ecovolt case 
study demonstrates how AI -powered plug -load energy management can deliver 
significant energy savings while supporting sustainability and decarbonisation goals 
through intelligent, occupancy -qaware control. These replace earlier case studies to 
ensure the Guide remains relevant and reflects current industry practices. 
Apart from productivity improvements, FM transformation also has significant 
contribution towards meeting our sustainability goals under the Singapore Green Plan 
2030. In many cases, Smart FM solutions for predictive maintenance can also help 
building operators in energy and resource optimisation simultaneously. Upfront 
considerations on design for maintainability would ensure that the building 
infrastructure can be adequately maintained fo r optimum performance across its life 
cycle. To encourage adoption of such good practices, we have incorporated Smart FM 
solutions into the Intelligence section of the latest GM v7.0 revision. This Guide is 
updated to complement the efforts. 
Extensive consultations were held with various public agencies, building owners, FM 
service and solution providers to understand their challenges, plans, and valuable 
lessons learnt from their experience in implementing Smart FM, integrating, and 
aggregating FM services. With this enhanced Guide, the FMIC and Taskforce hope to 
encourage the industry to shift towards stronger partnerships between service buyers 
and providers to collaboratively achieve greater synergistic outcomes and economies 
of scale. 
===== PAGE 5 =====
iv 
 
 
Acknowledgement 
This Guide to Smart FM was developed with inputs from the Integrated Smart FM Taskforce. 
Special thanks is given to all Taskforce members and resource persons for their significant 
contribution and support. 
Integrated Smart FM Taskforce Members and Resource Persons 
(02/2021 – 03/2024) 
Co-Chairs: 
Mr Mark Koh 
Mr Alfred Lim 
Mr Leonard Oh 
Group Director, Facilities and Estate Management 
Head, Operations Management 
Vice President and Head, Technology Services 
JTC Corporation 
CapitaLand 
Certis CISCO 
 
Members: 
Mr Alex Lau Chief Executive Officer Anacle 
Ms Daphne Boey 
Mr James Chan 
Mr Loh Wei Loon 
Mr Lawrence Kwok 
Assistant Director, Built Environment 
Managing Director 
Senior Managing Director 
Vice President, Operations and Technical Services 
IMDA 
SMM 
CBRE 
CDL 
Mr Melvin Tan Director, Asset Enhancement NUS 
Mr Yeoh Choon Jin 
 
Resource Persons: 
Ms Belinda Cilliers 
Ms Chloe Poh 
Mr Chong Whye Keet 
Dr Clayton Miller 
Mr Kelvin Ong 
Mr Kwok Wai Choong 
Dr Lee Jian Xing 
Mr Marcus Lim 
Mr Robin Li 
Mr Subodh Bahadure 
Mr Tan Sze Tiong 
Mr Tony Choo 
Mr Tong Kok Kwang 
Mr Vincent Shin 
Director, Urban Solutions & Infrastructure Services 
 
 
Head of Digital, Technology (APAC) 
Asset Management Senior Manager, Retail Assets 
Director, CUGE (Industry Development) 
Assistant Professor, Built Environment 
Senior Manager 
Deputy Director, Cluster Development Department 
Principal Consultant 
Deputy Director, Building Systems 
Vice President, Global GM Smart City Infrastructure 
Commercial Solution Leader, APAC 
Group Director, Building & Research Institute 
Deputy Director, Facilities Management 
Managing Director 
Senior Executive Facility Manager 
ESG 
 
 
CBRE 
CDL 
NParks 
NUS 
Schneider Electric 
NEA 
Surbana Jurong 
JTC Corporation 
Envision Digital 
Johnson Controls 
HDB 
RQAM 
Chip Eng Seng 
Surbana Jurong 
===== PAGE 6 =====
v 
 
 
 
Smart Energy Management Committee (2023 – 2024) 
Co-Chairs: 
Mr Ng Eng Sin Director, Facilities Engineering & 
Systems Division 
JTC Corporation 
Mr Toh Eng Shyan Director, Facility Management 
Transformation Department 
BCA 
Members: 
Ms Karen Ng Chief of Staff ENGIE 
Mr Subodh Bahadure Product Manager, Sustainability and 
Building Solutions 
Keppel Land 
Mr Khin Zaw Assistant General Manager / Head, 
EaaS Technology 
Keppel Infrastructure 
Holdings 
Ms Irene Yong 
 
Mr Kho Choon Siong 
Director / Section Head 
 
Deputy Head, Digital Systems / 
Digital Business Innovation 
Beca 
 
SMRT 
 
 
Appreciation is also extended to the following individuals for their valuable contribution to the 
use cases and write up documented in the enhanced Guide: 
Mr Derrick Ong, Director, Facilities & Estates Management (Public) Division, JTC Corporation 
Mr Jake Chia, Deputy Director, Facilities & Estates Management (Public) Division, JTC 
Corporation 
Ms Thien Jia Yu, Assistant Manager, Facilities & Estates Management (Central) Division, JTC 
Corporation 
Mr Joel Phua, Senior Manager, Building Systems Department, JTC Corporation 
Mr Joshua Lim, Digital Business Manager, Schindler Ahead 
Mr Kenneth Lim, Chief Executive Officer, Lingjack 
Mr Koh Liak Huat, Executive Director, Operations & Chief Architect, Azendian 
Ms Chong Ying Yng, Business Development Manager (Engineering), CBM 
Mr Eugene Chia, Chief Operating Officer, Ecovolt Technologies 
 
===== PAGE 7 =====
vi 
 
 
Contents 
 
Guide to Smart FM Revision Log................................................................................ i 
Preface........................................................................................................................ii 
Acknowledgement......................................................................................................iv 
Chapter 1. Introduction.............................................................................................. 1 
Chapter 2. The 5-step SMART Process.................................................................... 5 
Step 1: Set Business Objectives and Outcomes.................................................... 5 
Step 2: Map Out Smart FM Solutions as Enablers................................................. 9 
Step 3: Adopt Suitable Implementation Model..................................................... 12 
Step 4: Review Procurement Contract................................................................. 18 
Step 5: Track Outcomes and Review for Continuous Improvement..................... 22 
Chapter 3. Digitalisation Maturity Map..................................................................... 24 
3.1 Digitalisation Maturity Map.............................................................................. 24 
3.2 Digitalisation Maturity Map: The 3 Categories................................................. 24 
3.2.1 Category 1: Digitally Ready Vendors........................................................ 24 
3.2.2 Category 2: Digitally Ready FMCs............................................................ 26 
3.2.3 Category 3: Digitally Ready Building Owners........................................... 27 
3.3 FM Digitalisation Relationship Mind Map........................................................ 28 
3.4 Digitalisation Maturity Map: Specific Trades................................................... 29 
3.4.1 Cleaning.................................................................................................... 29 
3.4.2 Pest Control.............................................................................................. 31 
3.4.3 Refuse Waste Management..................................................................... 32 
3.4.4 Landscape................................................................................................ 33 
3.4.5 M&E: Lifts, Air-Conditioning & Mechanical Ventilation, Plumbing & 
Sanitary, Fire Protection.................................................................................... 34 
3.4.6 Security..................................................................................................... 36 
Chapter 4. Data Management in Type 3 Smart FM Solution................................... 38 
4.1 Data Management Across Systems is Key..................................................... 38 
4.2 Good Practices to Facilitate Data Management.............................................. 40 
4.2.1 Common Data Environment (CDE) for FM............................................... 40 
4.2.2 Open Communication Protocol................................................................. 43 
4.2.3 Conventions and Schemas for Organising Data....................................... 45 
4.2.4 Cybersecurity for Smart Buildings............................................................. 46 
4.3 Use Cases for Data Management................................................................... 47 
4.3.1 Workflow Tracking and Service Level Delivery......................................... 48 
===== PAGE 8 =====
vii 
 
 
4.3.2 Fault Detection and Diagnostics............................................................... 48 
4.3.3 Condition-based Maintenance.................................................................. 49 
Chapter 5. Digital FM Workforce............................................................................. 51 
Chapter 6. Conclusion............................................................................................. 63 
References............................................................................................................... 64 
Appendix A: List of Smart FM Point Solutions......................................................... 67 
Appendix B: Facilities Management Consortium Operation & Technology Roadmap 
(COTR)..................................................................................................................... 69 
Appendix C: Case Studies....................................................................................... 70 
C.1 Lingjack Digital Smart Fire Safety and Emergency Platform.......................... 70 
C.2 Schindler Ahead............................................................................................. 77 
C.3 Smart Energy Management for ACMV Systems............................................ 84 
C.4 An Integrated Smart FM Ecosystem enabling Outcome-based IFM Operations
.............................................................................................................................. 92 
C.5 Eliminating Plug-Load Standby Waste in a Commercial Office.................... 107 
Appendix D: Fault Detection & Diagnostics........................................................... 121 
Appendix E: Decision Template for 5-Step SMART Process................................ 128 
Appendix F: Essential Smart FM Use Cases........................................................ 134 
 
 
===== PAGE 9 =====
1 
 
Chapter 1. Introduction 
Smart FM refers to the integration of systems, processes, technologies, and personnel 
to enhance the management of a building's facilities. It is a mean to an end and thus, 
should not begin with technology in mind. It is important to consider the process and 
people aspects too to harness the full potential of Smart FM and achieve a holistic 
solution that can support data-driven decisions, create change and improve outcomes 
(see Figure 1). 
 
Figure 1. Transformational change through smart FM requires more than just technology 
 
In recent years, accelerated by the COVID-19 pandemic, there has been a broader 
interest from Building Owners to develop smart buildings, estates and/or districts that 
to meet or exceed sustainability, health, and safety requirements, in addition to 
enhancing the customers' experiences. Beyond automating business and FM 
processes and enabling a higher level of smart control and management 1 for 
Building Owners and FM Managers, it is also about creating connected and 
interactive smart usable spaces for the tenants, residents and visitors to a building, 
coupled with a seamless end-to-end user experience. 
With the rise of technologies such as Artificial Intelligence (AI), Internet of Things (IoT) 
devices, Immersive Media (AR/VR), and cloud-based technologies, the FM industry is 
now able to leverage such technologies to help Building Owners achieve the above 
mentioned, transform their business model, and gain a competitive edge in the market. 
 
1 For example, command-and-control for security and resource deployment, on-demand energy management, use of digital 
twins for simulation and modelling, use of data analytics and machine learning to identify inefficiencies in building systems 
for optimisation, etc. 
Process
TechnologyPeople
===== PAGE 10 =====
2 
 
 
To Foster Stronger Partnerships and Enable Seamless FM 
Processes and Service Delivery, through Purposeful Integration 
and Aggregation 
Building Owners, Facility Management Companies ( FMCs) and Service/ Solution 
Providers are encouraged to forge stronger partnerships to enable seamless FM 
processes and service delivery through purposeful integration and aggregation, 
where: 
• Integration refers to bundling of two or more inter -disciplinary services (e.g., 
Cleaning, Security, M&E, etc) together; and 
• Aggregation refers to consolidating demand and resources, such as across a 
portfolio of buildings or at a district level. 
Integration is not equivalent to single sourcing, multi-tasking nor a loose consortium of 
companies to bid for a project. A truly integrated FM model delivers the full spectrum 
of FM services, coordinated via a single platform. Integration can occur at 3 different 
junctures in this model: 
1. At the point of service delivery with m ulti-functional robots or multi -skilled 
personnel; 
2. At the point of response where s ubsystems are linked to complement each 
other, e.g., robot integration with lift; 
3. At the command level, with workforce management tools that give FMC visibility 
into its service personnel, equipment, and workflow to enable optimal 
deployment and outcome reporting 
Such integration and aggregation can be carried out at the demand side, i.e. Building 
Owners with a portfolio of buildings, to facilitate a better overview and management of 
resources; an d/or supply side, where the FMCs and Service/ Solution Providers 
manage several FM contracts as a pool. 
Integration and aggregation should be seen as two sides of the same Smart FM coin 
and is intrinsic to the delivery of outcome -based contracts. They give the FMC s the 
latitude to fully exploit their competitive edge and manage their FM resources optimally 
while meeting the discerning needs of each Building Owner. 
===== PAGE 11 =====
3 
 
 
Considering the process, technology and people aspects mentioned earlier to 
harness the full potential of Smart FM: 
Process: With increased adoption of integrated FM contracts that are outcome-based, 
the business model between Building Owners, FMCs, and Service/Solution Providers 
will evolve to become a strong and sustainable co-operative partnership that can bring 
about favourable outcomes for all parties. Coupled with a n assurance of a longer 
contracting period, the FMCs and Service/Solution Providers will see greater value in 
investing and leveraging on technology to support its workforce. 
Technology: As a mean to an end, a deliberate review should be carried out to ensure 
that the implementation of proposed Smart FM technology solutions is well aligned 
and integrated with the Building Owner's business requirements and existing FM 
processes to achieve the desired operational outcomes. When deployed and 
replicated or scaled up appropriately, these solutions can facilitate purposeful 
integration and aggregation by automating and monitoring the performance of multiple 
buildings across a portfolio or district and analysing such data centrally to support 
data-driven decisions on predictive and prescriptive maintenance. This can optimise 
and transform the delivery of a FM operation or process and unlock synergies across 
various FM disciplines. 
People: Building Owners, FMCs, and Service/Solution Providers should plan for 
regular training of their FM workforce to enable them to be aptly or deeply skilled for 
more effective application of the Smart FM technology solutions. The adoption of 
outcome-based contracting also allows for the upskilling and cross -training of the 
workforce to expand their existing roles and be multi -skilled. Besides creating new, 
higher value-added jobs within the organisation, this also strengthens the adaptability 
and agility of the workforce to be deployed across various FM disciplines and/or 
facilities. 
With the above in mind, transformational change through integration and aggregation, 
enabled by technology adoption, can translate into economies of scale with improved 
operational or process efficiency, optimised manpower and resource deployment, as 
well as enhanced manpower productivity. 
===== PAGE 12 =====
4 
 
 
Building Owners and their FM Managers can evaluate the outcome and/or contracting 
efficiency by collating occupants' feedback, reporting energy savings or usage, 
tracking the time to resolve incidents, etc. This in turn allows the Building Owners and 
FM Managers to determine how well the Smart FM solutions have been implemented, 
used and managed, thereby streamlining and transforming the way existing FM 
processes and practices are carried out. 
5-Step SMART Process to Smart FM 
A 5-step SMART process, shown in Figure 2 below, is recommended to aid the 
Building Owners and FM Managers in their Smart FM journey. The detailed steps will 
be further explained in Chapter 2. The 5-step SMART Process. 
 
Figure 2. 5-Step SMART process to Smart FM 

===== PAGE 13 =====
5 
 
Chapter 2. The 5-step SMART Process 
Step 1: Set Business Objectives and Outcomes 
 
Figure 3. Fundamentals of Smart FM implementation 
Technological innovation can shape and impact FM practice s, but there is a need to 
evaluate and align its business objectives with its fundamental principles of integrating 
people, place, process, and technology. 
 
The principles shown in Figure 3 are reinforced by the following corporate pillars in the 
implementation of Smart FM: 
• Delivering efficient FM operations 
• Ensuring satisfaction of the occupants (e.g. employees, tenants, etc.) 
• Enhancing building assets through upgrading works or proper maintenance 
 
Building Owners and FM Managers can refer to these principles to identify their key 
business objectives. This will ensure that Smart FM is planned for from the inception 
of a building or estate design which is critical to its successful implementation. 
 

===== PAGE 14 =====
6 
 
 
Setting Business Objectives, Desired FM Outcomes and Corresponding Key 
Performance Indicators (KPIs) 
The adoption of Smart FM technologies should primarily be driven by an organisation's 
business objectives. Building Owners and FM Managers are recommended to first 
identify their top 3 business objectives with the Smart FM fundamentals in mind. 
 
 
Figure 4. Flowchart on Step 1 of the 5-Step SMART process 
 

===== PAGE 15 =====
7 
 
 
The desired FM outcomes can be established based on these identified business 
objectives and pertinent operational issues that need to be addressed. It is 
recommended for Building Owners and FM Managers to determine corresponding 
KPIs to evaluate and monitor the performance of each desired FM outcome. 
Lastly, Building Owners and FM Managers are to decide which FM services to focus 
on. The FM services should be prioritised based on their impact in realising the desired 
FM outcomes and KPIs. The template in Table 1 can help to facilitate this process. 
Top 3 
Business 
Objectives 
Check Point Desired FM Outcomes and Corresponding KPIs High-Priority FM Services 
E.g. 
Cost 
E.g. 
What is my annual FM 
expenditure and cost breakdown? 
 
Which area can be 
improved/reduced? 
E.g. To reduce energy 
cost by 10% by 2022 
E.g. Chiller plant 
maintenance 
E.g. 
Customer 
satisfaction 
E.g. 
What is my customer satisfaction 
level for each services? 
 
 
E.g. Increase user 
satisfaction on general 
area cleanliness and 
reduce complaints by 20% 
E.g. Cleaning of 
toilets (high volume 
of user feedback) 
E.g. 
Productivity 
E.g. 
Does the task or project required 
high amount of manual processes 
or paperwork? 
 
Which area can be improved 
further? 
E.g. Increase internal FM 
staff productivity due to 
headcount freeze and 
ageing workforce 
Increase productivity by 
15% 
E.g. FM 
management 
processes 
(manpower intensive) 
Table 1. Template to rank business objectives, set desired FM outcomes, and determine high-priority FM services to focus on 
===== PAGE 16 =====
8 
 
 
What Should Building Owners and FM Managers Consider in Step 1: 
• What are my top 3 business objectives? 
• What do I want to achieve and set as my desired FM outcomes, based on my 
business objectives and issues faced? 
• What corresponding KPIs can I set to monitor the progress of my desired FM 
outcomes? 
• Which FM services should I prioritise to address the desired FM outcomes? 
• Can I streamline my current FM processes and procurement framework to 
meet the identified business objectives and desired FM outcomes? 
 
Tool to use 
Table 1: Template to rank business objectives, set desired FM outcomes, and 
determine high-priority FM services to focus on 
 
 
 
 
===== PAGE 17 =====
9 
 
Step 2: Map Out Smart FM Solutions as Enablers 
The next step is for Building Owners and FM Managers to determine suitable 
technology solutions for the high-priority FM services identified in Step 1. At this stage, 
it is important for Building Owners and FM Managers to concurrently review and 
streamline current FM processes and explore how Smart FM technologies can be 
integrated. 
Building Owners and FM Managers can refer to Appendix A: List of Smart FM Point 
Solutions for solutions that addresses specific FM pain points related to infrastructure 
and common services. 
The Singapore International Facility Management Association (SIFMA) has also 
collaborated with the Agency for Science, Technology and Research (A*STAR) to 
develop a Consortium Operation and Technology Roadmap ( COTR) in 2019 for the 
FM sector (see Appendix B: Facilities Management Consortium Operation and 
Technology Roadmap (COTR)). The COTR aims to outline the general trends (e.g., 
push and pull drivers towards Smart FM) and direction of the FM sector, and maps out 
Smart FM solutions that are deemed relevant for the sector from short to long term. 
Establish a Smart FM Framework 
Building Owners and FM Managers can take reference to the abovementioned to 
identify technology solutions they can map into the Smart FM Framework as shown in 
Table 2. The Framework serves to facilitate dialogues between Building Owners and 
Service/Solution Providers. Proposals can be reviewed alongside the Framework to 
see how the technology solutions offered can help t o achieve the desired FM 
outcomes. 
The Framework also classifies Smart FM solutions into three types of "smartness" 
where Building Owners and FM Managers can assess the scope and type of solutions 
each FM service requires. It is important to note that the three types of "smartness" 
are not in any order of merit or maturity of technologies. The choice of solutions should 
be determined by a cost-benefit analysis in achieving the desired Smart FM outcomes. 
===== PAGE 18 =====
10 
 
 
 
Table 2. Example of a Smart FM Framework with multiple solutions identified 
 
Other than looking into adoption of solutions to enhance business operations and 
productivities, Building Owners and FM managers should also consider how data can 
be collected, managed, and analysed for innovation. For example, data collected from 
people-traffic information could help business owners identify the right timing to push 
out attractive store promotion via the mall's customer app or being able to allocate the 
right amount of manpower required for cleaning services during peak and non -peak 
season so as to ensure that the public or workspaces are well maintained. Such 
approaches can bring greater value-add not only for Building Owners but also for the 
tenants and employees. 
Explore Aggregation Opportunities 
Building Owners and FM Managers can explore areas where economies of scale can 
be achieved through aggregation at all 3 types of "smartness" (e.g., Type 1, 2 and/or 
3). For Building Owners with a portfolio of buildings, the aggregation may be done at 
their end (e.g., demand side). For example, a technology solution can be deployed, or 
certain FM functions like security and cleaning can be aggregated, across the portfolio 
of buildings, for a better overview and management of resources. 
Building Owners with a single development may explore aggregation at the supply 
side, through FMCs and Service/Solution Providers. When more Building Owners 
move from traditional prescriptive -based contracting to outcome -based, FMCs and 

===== PAGE 19 =====
11 
 
 
Services/Solution Providers can better manage their resources to meet services 
demands. Greater benefits can be reaped through aggregation for buildings in a 
vicinity or district that adopt outcome-based contracting. This will be covered and 
explained further in Step 4. 
What Should Building Owners and FM Managers Consider in Step 2: 
• What type of "smartness" (Type 1, Type 2, or Type 3) is each high-priority FM 
service currently at? 
• What type of "smartness" do I want to achieve for each high -priority FM 
service? Is it aligned with my business objectives and desired FM outcomes? 
• What are my pain points and gain points for each high-priority FM service? 
• Do the technology solutions proposed by the FMCs and Service/ Solution 
Providers fit the requirements to achieve my desired FM outcomes? 
• How would I like to engage the building occupants and visitors? 
• Are there FM services that could be integrated to provide multi-functional and 
enhanced outcomes, e.g. connected lighting systems? 
• Are there areas where aggregation can be done to achieve economies of 
scale – at demand and/or supply side? 
• Is it advantageous to aggregate demand across a portfolio of buildings? 
Tool to use 
Table 2: Smart FM Framework 
References 
• Appendix A: List of Smart FM Point Solutions 
• Appendix B: Facilities Management Consortium Operation & 
Technology Roadmap (COTR) 
 
 
===== PAGE 20 =====
 
12 
 
 
 
Step 3: Adopt Suitable Implementation Model 
Upon deciding which Smart FM solutions to adopt under Step 2, it is important for 
Building Owners and FM Managers to determine how the se solutions can be 
implemented. 
Where relevant, Building Owners and FM Managers can consider incorporating the 
concept of Services 4.0 2, which envision services to be end -to-end, frictionless, 
empathic, and being able to anticipate customer needs using emerging technologies. 
In Services 4.0, businesses will need to meet changing customer needs quickly, 
innovate, scale and be able to create new value in order to differentiate themselves 
from competitors. 
Model A: Integrated Smart FM Solution 
The following implementation model ( see Figure 5 below) is one in which the smart 
solutions feed data into an integrated software suite, either provided by the appointed 
FMC or acquired by the Building Owner to operate and manage its FM operations. 
The first approach is resource-lite and allows the Building Owner and FM Manager to 
have a reasonably comprehensive management dashboard. While the latter requires 
considerable scale and resource commitment to develop a reasonably comprehensive 
system and management dashboard, it allows customisation based on the 
organisation needs and is beneficial for Building Owners with a big portfolio of 
buildings. Regardless of which approach, both should provide the Building Owner the 
autonomy of its operation. 
 
2 Services 4.0 is Singapore's response to the Services and Digital Economy (SDE) Technology Roadmap, envisioning Singapore 
delivering next -generation services that are end -to-end, frictionless, empathic, and anticipatory to customer needs. 
(Reference: https://www2.imda.gov.sg/infocomm-media-landscape/services-40) 
===== PAGE 21 =====
 
13 
 
 
 
 
 
 
 
Figure 5. Model A: Integrated Smart FM Solution 
 
The use cases of this model include JTC Corporation's J -Ops and the CapitaLand 
Integrated Building Platform (IBP) (Refer to Appendix C: Case Studies). 
Solution-as-a-Service via FMC 
Acquired and Operated by 
Building Owner 
===== PAGE 22 =====
 
14 
 
 
 
Model B: Single Smart FM Solution 
This second implementation model is one in which Building Owners procure specific 
Smart FM services and solutions individually and manage them with the software tools 
provided by each individual Service/Solution Provider. 
 
 
Figure 6. Single Smart FM Solution 
 
It has become more common for specialised FM suppliers to develop smart solutions 
to complement their products and services for remote monitoring, fault detection, 
diagnostics and optimisation. For example, major chiller suppliers have deep expertise 
and extensive performance data of their equipme nt. The leading suppliers have 
developed smart IoT solutions (connected services) for remote chiller plant monitoring 
and predictive maintenance. 
While this approach can leverage on the specialised expertise and data of the 
Service/Solution Providers, Building Owners and FM managers should ke ep in mind 
that if integration of multiple systems or solutions is within the future pipeline, the 
adopted or developed solutions should have open Application Programming Interfaces 
Solution by multiple FM providers 
===== PAGE 23 =====
 
15 
 
 
 
(APIs) to allow integration with a horizontal platform for central command-and-control 
and data exchange, as seen in Model A. 
Additional Considerations 
It should be emphasised that none of the implementation models are superior to 
another. The decision on the type of model to adopt must be based on the Building 
Owner's business objectives, operational priorities and desired FM outcomes. 
A phased adoption, variation or hybrid of the implementation models is entirely 
possible. For instance, a Building Owner with a large portfolio of buildings may start 
with a centralised FM operations centre (i.e. Model A) and have been reaping the 
benefits and cost savings from rectifying poorly commissioned equipment and sensors 
that have "drifted" in accuracy (low-hanging fruits). To attain the next leap of 
optimisation, the Building Owner may see it advantageous to subscribe to a chiller 
vendor's remote monitoring service (i.e. Model B). This is with consideration that the 
chiller vendor has proprietary knowledge of its chillers and the possibility to leverage 
on its collective insights obtained from monitoring its global installed base. 
As Building Owners and FM managers start to enjoy the benefits that can be gained 
from leveraging large data sets, such as optimising business processes or 
accelerating the development of artificial intelligence (AI), there are also concerns over 
trust and security thereby hindering the mass sharing of this information. Data sharing 
is a multi -disciplinary process which involves not only enabling technology, but also 
business and legal considerations. In June 2019, the Info -communications Media 
Development Authority (IMDA) and Personal Data Protection Commission (PDPC) 
have announced the first comprehensive Trusted Data Sharing Framework 3 with the 
aim to guide organisations through the data sharing journey. Building Owners may 
refer to it for key considerations to take into account when planning data partnerships. 
 
 
3 "Enabling Data -Driven Innovation Through Trusted Data Sharing In A Digital Economy ", 28 June 2019, 
https://www2.imda.gov.sg/news-and-events/Media-Room/Media-Releases/2019/Enabling-Data-Driven-Innovation-
Through-Trusted-Data-Sharing-In-A-Digital-Economy 
===== PAGE 24 =====
 
16 
 
 
 
System and Technical Requirements 
The implementation model selected in this Step determines the working arrangement 
with the FMCs and Service/Solution Providers. This will impact the Building Owner 
and FM Manager's ownership ( e.g., cloud-hosted or on-premises) and the degree of 
freedom and access to the i ntegrated FM system (iFMS) and/or individual FM sub -
systems. 
System and t echnical requirements in relation to these should be specified in the 
procurement contracts. The specification should include the data and format to be fed 
to the iFMS of the building, as well as the "north -bound" data interface to which the 
FM sub -systems can lodge incidents w ith the iFMS, for the purpose of logging, 
dispatch and management. 
Besides data fields like data and time of incident and resolution, severity and 
classification, other information required to enable outcome-based KPIs to be 
objectively computed or measured should be detailed as well. For example, number 
of incidents per week, mean time to failure, energy efficiency index, energy savings, 
financial savings, turnaround time or time to resolution. 
Specifications within the procurement contracts are important to ensure that the Smart 
FM solutions and systems are properly put in place to support and contribute to the 
Smart FM platform. This would reduce operational disruptions and any cost 
implications to redesign the Smart FM infrastructure within the building. 
 
===== PAGE 25 =====
 
17 
 
 
 
What Should Building Owners and FM Managers Consider in Step 3: 
• What is my current working model for existing FM processes and services? 
• How would I like to work with my FMCs or Service/Solution Providers? 
• Which implementation model is more viable at this point to incorporate the 
various technology solutions identified in Step 2? Or would phased adoption 
or a variation or hybrid of the implementation models be more applicable? 
• Does the selected implementation model meet my business objectives, 
operational priorities and desired FM outcomes? 
• How to ensure that I own all the data, regardless of the type of implementation 
models selected? 
• Are the system and/or technical requirements specified within my 
procurement contracts adequate? 
 
References 
• IMDA and PDPC's Trusted Data Sharing Framework 
(https://www2.imda.gov.sg/news-and-events/Media-Room/Media-Releases/2019/Enabling-
Data-Driven-Innovation-Through-Trusted-Data-Sharing-In-A-Digital-Economy) 
 
 
===== PAGE 26 =====
 
18 
 
 
 
Step 4: Review Procurement Contract 
After the Building Owners and FM Managers have identified the appropriate 
implementation models and related system and technical requirements in Step 3, they 
can proceed to work out the procurement contracts with the FMCs and 
Service/Solution Providers. 
With the increasing number of data -driven smart technology solutions in the market, 
there is a shift from traditional headcount -based to outcome -based procurement 
methods. This shift has allowed innovative solutions that are less -resource intensive 
to ente r the market 4. At the same time, this has encouraged FMCs and 
Service/Solution Providers to improve their operations to meet the Building Owners' 
expectations5. 
Longer Contract Terms 
When outcome-based measurements become the primary focus of the procurement 
contracts, both Building Owners and the FMCs or Service/Solution Providers can 
achieve more value as working partners, sharing a common interest towards a 
successful business and p erformance relationship 6. With the assurance of a longer 
contracting period, service and solution providers may be more willing to leverage on 
technology as enablers to supplement and complement its workforce to achieve better 
and more insightful outcomes over existing procurement methods, resulting in a win -
win for all parties. 
Employees of FMCs and Service and Solution Providers can be given the opportunity 
to upskill and benefit from job redesign to take up more complex roles resulting in 
greater productivity as well as increase in wages. 
It is recommended that Building Owners and FM Managers should specify a contract 
duration of at least three years, with another three years extension. In some public 
 
4 Ministry of Home Affairs, Guide on outcome-based security contracts 
5 National Environment Agency, Guide on specification for outcome-based cleaning contracts 
6 Interllect's Outcome-Based Agreement Group, A guide to outcome-based agreements – a better way to do business 
===== PAGE 27 =====
 
19 
 
 
 
agencies that have successfully adopted Smart FM, their contract duration ranges 
between five to ten years. 
A longer contract term can incentivise the FMCs or Service/Solution Providers to 
invest in technology solutions, and upgrade the supporting infrastructure of the 
buildings to be ready for Smart FM. 
Define Outcome-based Measurements 
Each class of stakeholder will have different expectations, requirements, and desired 
outcomes. 
When Building Owners and FM Managers work out the procurement contracts with 
the FMCs and Service/Solution Providers, it is also important to identify and 
understand the requirements of various stakeholders. The technical specifications 
within the contract will need to take these into consideration: 
a) Financial stakeholders will desire information on how the Smart FM 
implementation will impact the company's financial metrics and bottom line, as 
well as the interfacing to its accounting system. 
 
b) Operational stakeholders that keep the building functioning on a day -to-day 
basis will be concerned with occupant satisfaction, ease of operation, access 
to critical systems' information, and productivity of the maintenance staff. They 
will also want access to all the building's systems to have better situational 
awareness, and address issues in real time, where required. 
 
c) Sustainability stakeholders will be concerned with energy and water 
efficiency, utility optimisation, and how to reduce carbon emissions and save 
resources. 
 
d) Productivity stakeholders will be concerned with occupant and user comfort, 
and will want to know about utilisation of the building's spaces and how systems 
===== PAGE 28 =====
 
20 
 
 
 
integration can improve the productivity of workflow processes and user 
experience. 
 
e) Security stakeholders may look beyond surveillance and want the building's 
intelligence to maintain a proper access control system, help disseminate 
messages and locate people during an emergency. 
 
f) Public communications stakeholders will want to include performance data 
in lobby displays to promote various initiatives deployed within the building 
(e.g., sustainability efforts) and help visitors with registration and wayfinding. 
All the parties mentioned above will be interested in obtaining detailed data in their 
specific areas so that they can analyse the data gathered and optimise relevant 
building systems according to best practices. Defining metrics and outcome-based 
KPIs for tracking, i.e. outcome-based measurements, will help to clarify the data flow, 
technical requirements and reporting or data visualisation to fulfil their respective work 
scope. 
Building Owners and FM Managers can refer to g uides listed in [2], [3] and [4] of 
References that will provide details on specifying operational requirements aligned 
with an outcome-based procurement approach for energy performance contracting, 
security and cleaning services. 
Integrated Facilities Management (IFM) Contract 
Building Owners and FM Managers can explore areas where greater economies of 
scale can be achieved by aggregating their demand within a building and/or across a 
portfolio of buildings through an IFM contract. IFM, together with a longer outcome -
based contract term, will allow FMCs and Service/Solution Providers greater payback 
certainty and flexibility to explore innovative Smart FM solutions (e.g., IoT, integrated 
command centre, digital twin modelling, interoperability of FM solutions ) that enable 
on-demand and more optimal deployment of resources to meet the desired outcomes. 
Such integration of manpower, technology and processes enables FM service delivery 
to be optimised, leading to better service, at lower costs in the longer term. 
===== PAGE 29 =====
 
21 
 
 
 
What Should Building Owners and FM Managers Consider in Step 4: 
• What are the outcome-based measurement, incentives and penalty for each 
FMC or Service/Solution Provider? 
• Can I work together with the FMCs or Service/ Solution Providers to adopt a 
longer contract term? 
• Can the FMCs or Service/Solution Providers optimise delivery of their 
services and solutions if I aggregate demand across my portfolio of buildings? 
• What system or technical requirements should I take note of and incorporate 
within the procurement contract? 
• Have my technical specifications for the Smart FM solutions taken into 
consideration the various stakeholders' requirements? 
• Can I aggregate demand within a building and/or across my portfolio of 
buildings through an Integrated FM contract? 
 
 
 
===== PAGE 30 =====
 
22 
 
 
 
Step 5: Track Outcomes and Review for Continu ous 
Improvement 
After the procurement and implementation of the Smart FM solutions, it is essential for 
the Building Owners and FM Managers to monitor and review the Smart FM solutions 
adopted for continual improvement. It is also recommended that they re -examine 
Steps 1 to 4 to explore areas for further improvement. 
Review Adopted Solutions 
This last step will help Building Owners and FM Managers to evaluate if the adopted 
solutions are able to address the business objectives and smart FM outcomes 
identified earlier. It may also surface areas for improvement that can be taken into 
consideration when adopting other Smart FM solutions in the future. 
Table 3 below shows how Building Owners and FM Managers can tabulate their 
findings to ascertain if the adopted Smart FM solutions have met their business 
objectives and desired FM outcomes. 
Top 3 
Business 
Objectives 
Check Point Desired FM Outcomes and Corresponding KPIs Evaluate Adopted Solutions Recommended Areas for Improvement 
Cost 
E.g. 
Desired Outcomes and 
KPIs Achieved? 
 
Are the Smart FM solutions 
adopted effective? 
 
What went well or wrong? 
 
Which area can be 
improved? 
 
How can it be improved? 
E.g. To reduce energy cost 
by 10% by 2022 
 
Customer 
satisfaction 
E.g. Increase user 
satisfaction on general area 
cleanliness and reduce 
complaints by 20% 
 
 
Productivity 
E.g. Increase internal FM 
staff productivity due to 
headcount freeze and ageing 
workforce 
Increase productivity by 15% 
 
 
Table 3. Sample table to review if the adopted solutions have addressed desired FM outcomes 
 
 
 
 
===== PAGE 31 =====
 
23 
 
 
 
Explore Further Opportunities 
After the review, Building Owners and FM Managers can continue to explore further 
opportunities. This can be done by re-visiting: 
• Step 1 – To verify if business objectives, desired FM outcomes and FM service 
priorities have changed; 
• Step 2 – To check if new and emerging Smart FM technology solutions in the 
market can help provide better service; and 
• Step 3 – To evaluate if a different implementation model(s) should be adopted; 
and whether the system and technical requirements to be specified in the 
procurement contracts needs to be enhanced. 
• Step 4 – To review and better define the outcome -based measurements that 
can help improve the service quality of the FMCs or Service/ Solution Providers. 
What Should Building Owners and FM Managers Consider in Step 5: 
• Has the adopted Smart FM technology solution been well implemented and 
integrated within my existing FM processes and systems? 
• Has it addressed the business objectives and desired FM outcomes earlier 
identified in Step 1? 
• What are the tangible benefits and issues of each adopted solution? 
• Are there areas for improvement that can be taken into consideration when 
adopting other Smart FM solutions in the future? 
• Have the business objectives, desired FM outcomes and high-priority FM 
services changed? 
• Are there new technology solutions in the market that can span across 
various FM services and better meet my needs? 
• Do the high-priority FM services need to be changed to other types of 
"smartness"? 
• Do I need to review and change the outcome-based measurements to better 
meet the needs/ requirements of various stakeholders? 
 
 
===== PAGE 32 =====
 
24 
 
 
 
Chapter 3. Digitalisation Maturity Map 
3.1 Digitalisation Maturity Map 
Although many FM stakeholders and companies have adopted Smart FM technology 
and/or practices, minimal progress has been made on system -to-system integration. 
There is hence a need to align the different levels and systems of digital adoption 
carried out by the industry so greater insights can be obtained and synergy within and 
across the FM value chain can be optimized. The Digit alisation Maturity Map 
encourages stakeholders across the value chain to co -share and integrate their data 
to achieve the following objectives: 
a) Improve operational efficiencies on site; 
b) Improve performance and productivity of the sub-contractor workforce; 
c) Cost optimization through insights gathered from trend analysis; and 
d) Improve quality of maintenance services provided from the analysis derived 
from data collection. 
The Digitalisation Maturity Map seeks to map out and align the level of digital maturity 
across the FM industry, spanning across 3 Categories of FM stakeholders, including: 
• Category 1: Digitally Ready Vendors 
• Category 2: Digitally Ready Facilities Management Companies ("FMCs") 
• Category 3: Digitally Ready Building Owners 
Vendors, FMCs, and Building Owners may use the respective roles in Section 3.2 to 
chart their own digitalisation journey. As each plays a critical part of the FM ecosystem, 
the FM Digitalisation Relationship Mind Map (Fig ure 7) and section 3.4 describe the 
interaction and data exchange between these 3 digital entities to cohesively delivers 
the benefits of FM integration and aggregation. 
 
3.2 Digitalisation Maturity Map: The 3 Categories 
3.2.1 Category 1: Digitally Ready Vendors 
Category 1 represents the vendors and contractors providing all the necessary FM 
services such as cleaning, pest control, and security. For them, digitising would mean 
===== PAGE 33 =====
 
25 
 
 
 
to collect and process daily site data or feedback into useful information that can help 
to improve business operations. 
There are three stages these service providers must take to embark on the 
digitalisation process to improve resource and process efficiency. 
 
Category 1.1: Sense and Capture 
Sensing and capturing data allow vendors to digitise information for better collection 
and control. This can be done through sensing technologies such as Internet of 
Technology (IoT) or smart devices, surveillance and/or video analytics technologies, 
inventory and asset registry, document management systems, and maintenance and 
audit logs. 
For example, pest control providers may use smart devices such as smart mosquito 
and rat traps to improve their services, while security contractors may utilise CCTVs 
and access controls in their security operations. 
'Schindler Ahead' is a real -world remote monitoring system that can detect any 
abnormalities or problems in Schindler's lifts. KK Women's and Children's Hospital 
(KKH) also uses KONE to monitor equipment performance remotely. 
 
Category 1.2: Adaptive Actions 
Vendors may translate data into actions and operation outcomes via incident 
management systems, and feedback/alert and response management systems, and 
workflow management/automation systems. 
Data and alerts captured by the smart devices mentioned in Category 1.1 would be 
transmitted to the respective management systems utilised by the pest control and 
security vendors. Through this system, management staff off -site can be alerted of 
any incidents or feedback and act accordingly. 
In Schindler, each technician has access to a company mobile application that is linked 
to their 'Schindler Ahead' system, a remote monitoring system that can automatically 
dispatch technicians and provide suggested actions for them to take in repair works. 
Similarly, KONE collects and analyses data and can assist to alert technicians when 
===== PAGE 34 =====
 
26 
 
 
 
a predictive service need is generated. This allows the switch from reactive 
maintenance to predictive maintenance, which can extend equipment life and reduce 
costs overtime. 
Category 1.3: Resource Optimisation 
To optimise resources, vendors may tap on the potential of data in achieving business 
outcomes through management systems for manpower, fleet, scheduling, and 
inventory. 
For example, contractors may make use of the historical data collected to plan ahead 
and deploy more manpower and resources in certain areas that are more problematic. 
A real-world example would be 'Schindler Ahead' which provides a holistic overview 
of all the elevators in the building (can be merged with owners' Smart FM systems by 
using Schindler's 'CoLab' toolbox). 
 
3.2.2 Category 2: Digitally Ready FMCs 
FMC will go through a similar digitalisation process and enabling supply chain 
management to ensure service delivery governance in the following stages. 
Category 2.1: Integrated Service Management 
FMCs should have an integrated service management to augment supply chain 
management with data. This data can be used to increase and enhance FM functions 
such as supply chain management, incident management, customer management, 
adjacent data management, service delivery (SLA/KPI) governance. 
Examples of integrated service management include vendor procurement and 
management systems (computerized maintenance management systems, integrated 
workplace management systems etc.) and automatic performance report generators. 
For instance, Yale NUS uses an 'Integrated Performance Dashboard' that contains 
multiple dashboards displaying Key Performance Indicators. It allows facility 
managers to track 'live' and outstanding cases and collects performance related 
statistics such as the officers' response rate to close a feedback, which can then be 
used to generate real-time appraisal on staff performance. 
===== PAGE 35 =====
 
27 
 
 
 
It should be noted that it is also possible for the vendor's management system to 
trigger a direct alert to both the FMCs and owners concurrently (e.g., emergency alert 
for trespassing). The data and notifications from the management system of each 
individual trade would then be transmitted to the FMC centralised system, which is 
illustrated in Category 2 of Figure 7 below. 
Category 2.2: Intelligent Insights 
Intelligent insights can be achieved with the use of data analytics involving features 
such as data visualization, fault analysis, feedback analysis, trend analysis, and 
predictive maintenance. 
Examples of data analytics technologies include operation dashboards, fault and 
feedback trackers, master maintenance schedules, and anomaly alerts. For instance, 
the automated reports generated by the FMC's centralised system can aid in 
developing intelligent insights by carrying out trend and fault analysis, presenting the 
data through dashboards. 
'CoLab', the recently launched building integration toolbox and Application 
Programming Interfaces (APIs) platform by Schindler offers performance, contractual, 
and operational information to clients. The 'Integrated Performance Dashboard' from 
Yale NUS can help identify the most frequently occurring problems for analysis. Yale 
NUS also uses a real -time 'Campus Health Index' platform that aims to reflect the 
current state of its ease of maintenance, impact on customer service, staff 
performance standards, safety, and sustainability. 
3.2.3 Category 3: Digitally Ready Building Owners 
With the information and reports submitted by the vendors and FMCs, the building 
owner can then enable data aggregation at the portfolio level to facilitate data -driven 
decision making. 
Building owners would be more confident in business decisions that are supported 
with statistics and professional insights and will be able to better predict any future 
obstacles to avoid and potential opportunities to capitalize on. In this way, information 
can aid in strategic long -term planning where building owners can align business 
decisions with their big picture goals and plans. Benefits may come in the form of 
===== PAGE 36 =====
 
28 
 
 
 
better investments or purchases for the property, improved estate planning and safety, 
and ultimately reduced operational and maintenance costs. 
Category 3.1: Integration and Aggregation 
The integration and aggregation of information can provide a holistic overview for 
client's portfolio management. Clients may make use of various technologies and 
strategies to achieve this. Examples include portfolio management and benchmarking 
tools, GIS overlay, Location-based Data (e.g., Hotspots), asset management system, 
and data overlays. Other than incorporating technology, owners may also compare 
building performance across different portfolios and/or set targets for FMCs and 
vendors to achieve. 
Following the examples mentioned in the earlier stages, the automated reports 
generated by the FMC containing insights and analyses will be transferred to the 
building owners under Category 3, increasing the ease of building management on a 
portfolio level. 
CapitaLand implemented their 'Intelligent Building Platform' that can provide benefits 
such as visibility of their asset performance, KPI tracking, and predictive and 
continuous maintenance regime. 
 
3.3 FM Digitalisation Relationship Mind Map 
The stages mentioned above will come together cohesively as shown in the 
relationship mind map illustrated in Figure 7 below. This mind map shows the 
digitalisation relationship among the 3 categories so stakeholders can be clear on the 
flow of information and upstream/downstream actions in the Smart FM ecosystem. 
===== PAGE 37 =====
 
29 
 
 
 
 
Figure 7. FM Digitalisation Relationship Mind Map 
 
3.4 Digitalisation Maturity Map: Specific Trades 
This chapter will illustrate the relationship between each Category by showing 
examples for each building trade. 
3.4.1 Cleaning 
 
Figure 8. FM Digitalisation Maturity Map (Cleaning) 

===== PAGE 38 =====
 
30 
 
 
 
For cleaning, the smart devices under Category 1.1 would be devices like ammonia 
sensors, soap dispenser sensors, smart bins, etc. that would help to trigger alerts for 
cleaning activities and allow ease of tracking of consumables and feedback. The 
readings from these sensors will then be sent to the vendor's system to trigger alerts 
for cleaning activities and tracking of consumables and feedback (Category 1.2). 
Insights generated through data analysis will enable the vendor to design workflows 
that respond to the alerts in appropriately. With these historical alerts and operational 
data, the cleaning vendor will be able to optimise the cleaning frequency, which aids 
in the scheduling of cleaners, and possibly enable an on-demand cleaning (Category 
1.3). 
Moving on to Category 2, the cleaning data and 1st level analysis done by the vendor 
will be transferred to the FMC's centralised management system. Together with the 
information collected from other building trades, the FMC's centralised management 
system will serve as a data hub consolidating all the operational data across the FM 
supply chain (Category 2.1). 
There can be various modules in the centralised management system including 
feedback management modules and performance tracking modules, which can help 
in reporting and monitoring the service levels of the FMCs and vendors. FMCs would 
also be able to perf orm data analytics, translating data into operational insights 
(Category 2.2 ). Numbers and trends can be presented through an operation 
dashboard to identify hotspots and show which building or location requires more 
attention. 
Lastly under Category 3 for clients, data and insights provided by the FMC's 
centralised management system will enable operations and asset management on a 
portfolio level (Category 3.1). 
===== PAGE 39 =====
 
31 
 
 
 
3.4.2 Pest Control 
 
Figure 9. FM Digitalisation Maturity Map (Pest Control) 
 
This section will only touch on Category 1 as Categories 2 and 3 will be the same as 
that outlined in the cleaning trade. 
Smart devices for pest control would include detection systems and remote mosquito 
traps (Category 1.1). For example, the Anticimex SMART technology is a smart data 
hub that can monitor the movement of pests and send live notifications to the 
management system in the form of rodent or mosquito capture alerts (Category 1.2). 
Information collected would be the detailed location of where the rodent was caught, 
while insights generated may include identification of a hotspot area. Such data will 
allow the vendor to deploy resources more efficiently (Category 1.3). 
 

===== PAGE 40 =====
 
32 
 
 
 
3.4.3 Refuse Waste Management 
 
Figure 10. FM Digitalisation Maturity Map (Refuse Waste Management) 
 
This section will only touch on Category 1 as Categories 2 and 3 will be the same as 
that outlined in the cleaning trade. 
Smart devices used in this trade would include sensors measuring fill-level sensors, 
smart bins, and RFID tracking (Category 1.1). Fill-level sensors can be translated to 
full bin alerts, while the RFID tracking of bins allow for routing optimisation and route 
visualisation for management (Category 1.2). An asset and fleet management system 
can be set up to optimise resources (Category 1.3). 

===== PAGE 41 =====
 
33 
 
 
 
3.4.4 Landscape 
 
Figure 11. FM Digitalisation Maturity Map (Landscape) 
 
This section will only touch on Category 1 as Categories 2 and 3 will be the same as 
that outlined in the cleaning trade. 
Smart devices used in this trade would include sensors measuring tree tilt, rainfall, 
and grass height, or drones that may aid in arborist inspections (Category 1.1). These 
smart devices can help in manpower scheduling and may also capture data associated 
with external factors such as weather or rainfall. Should a tree exceed any pre -
allocated parameters assigned in the sensor, alerts will be generated and sent to th e 
system (Category 1.2). The vendor then may plan for pruning or tree removal works 
in response. This system will hence aid to detect health issues in trees prior to actual 
failure and can reduce a lot of downtime and resources spent on-site. Resources may 
be better optimised via a manpower or fleet management system (Category 1.3). 

===== PAGE 42 =====
 
34 
 
 
 
3.4.5 M&E: Lifts, Air-Conditioning & Mechanical Ventilation, Plumbing & 
Sanitary, Fire Protection 
 
 

===== PAGE 43 =====
 
35 
 
 
 
 
 
Figure 12. FM Digitalisation Maturity Map (M&E) 
 
Under Category 1. 1 for M&E, smart devices largely include various sensors (lift 
sensors, temperature and occupancy sensors, water leak and water quality sensors, 
heat, and smoke detectors) and user feedback module where building users may 
submit feedback of lift breakdowns or water seepage. These data will again be sent 
as alerts through the system, with the common ones being in the form of anomaly 

===== PAGE 44 =====
 
36 
 
 
 
detection, downtime alerts, or user triggered alerts ( Category 1.2). M&E vendors will 
then use such information to plan and schedule for regular or ad -hoc maintenance 
works, as well as to manage manpower and equipment. 
When these information and reports are submitted to the FMC's centralised 
management system, data consolidation and management will kick in. Feedback 
management modules to respond promptly to user feedback, or incident management 
modules to draft incident reports for building owners, may be implemented via 
automatic design workflows ( Category 2.1). Insights such as analysis on common 
feedback and faults can be generated automatically as well with data analytics 
(Category 2.2). Numbers and trends can be presented through an operation 
dashboard and hotspot identification to show which building requires more attention. 
These insights submitted to building owners may then be transformed into more 
comprehensive reports that can refine their overall perspective on the health of the 
property ( Category 3.1). For instance, owners may track and monitor the building 
water consumption and trace high expenditures to water pilferage based on 
information and reports submitted by the FMC. 
3.4.6 Security 
 
Figure 13. FM Digitalisation Maturity Map (Security) 
 

===== PAGE 45 =====
 
37 
 
 
 
Security vendors frequently incorporate smart devices such as CCTV cameras, video 
analytics, access control, and alarms in their operations ( Category 1.1 ). Some of 
these smart devices may digitise security records and reduce downtime usually spent 
on administrative work. Trespassing incidents may be reported immediately with the 
use of access control and alarms, and alerts can be sent immediately and concurrently 
to the vendor's system. Under Category 1.2, the security vendor can design workflows 
that respond efficiently to security incidents picked up by smart devices. They may 
then optimise their manpower and resource allocation through implementing Standard 
Operating Procedures (SOP), incident or asset management, and patrol and vehicle 
routing (Category 1.3). This ensures that incidents can be attended to promptly. 
The security data completed by the vendor will be transmitted to the FMC's centralised 
management system, which may incorporate incident and performance monitoring 
modules. Together with the information collected from other building trades, the FMC's 
centralised management system will serve as a data hub consolidating all the 
operational data across the FM supply chain (Category 2.1). FMCs would be able to 
perform data analytics via analysis on hotspot, visitor count, and system uptime 
(Category 2.2). 
This information provided to building owners will let them have a holistic overview of 
their property, and they may digest and process this information further with processes 
such as GIS data overlay or integrate it all together under the physical security 
information system (Category 3.1). 
 
 
 
===== PAGE 46 =====
 
38 
 
 
 
Chapter 4. Data Management in Type 3 Smart FM 
Solution 
With the shift towards Integrated FM and Aggregated FM (IFM/AFM) contract, the 
adoption of Type 3 Smart FM solution (Integration across systems) becomes apparent. 
As describe d in Chapter 2, Type 3 Smart FM solution aims to optimise resource 
deployment and utilisation across many systems. 
4.1 Data Management Across Systems is Key 
Clear business cases are of paramount importance to justify the investment in time 
and resources to adopting Type 3 Smart FM solutions. Having sophisticated digital FM 
solutions do not help the organization if the products are not able to deliver operational 
and/or financial benefits. The ability to access and analyse data across systems and 
solutions quickly and easily is key in not only developing clear business cases but also 
the adoption of Type 3 Smart FM, failing which would render the adoption of the myriad 
of technologies financially prohibitive and operationally unfeasible. As such, the 
management of data across various systems, applications and operations is key in 
ensuring the smooth implementation of Type 3 Smart FM. 
3 key considerations in managing data: 
 
Figure 14. Key considerations in managing data 

===== PAGE 47 =====
 
39 
 
 
 
1) Ensuring Data Interconnectivity, Avoiding Data Silos 
Bringing in data across multiple solutions enables the Facilities Management 
Companies (FMCs) and Building Owner to have a holistic view of their portfolio 
allowing them to know what is happening on the ground and make data-driven 
decisions. 
 
It is important to consider the data connectivity of every solution and product 
prior to its implementation. Ensuring that implemented systems do not operate 
on stand-alone, closed/proprietary communication protocols is key in avoiding 
not only vendor lock-ins but also ensure that the necessary data that is required 
for decision making are available and accessible for use. Rectification of such 
a situation would not only be costly and time consuming but may also run the 
possibility that the entire solution would need to be replaced, just so that the 
necessary data is available to the organisation. 
 
2) Ensuring Interoperability 
Ensuring interconnectivity enables the ability to move data from one system to 
another system. This alone is insufficient in achieving automation between 
systems. The ability for a system to understand the meaning of the data that 
comes from other systems is referred to as interoperability (specifically data 
interoperability). For example, the correct interpretation of the data coming from 
a BMS point label "ZP.L1.ACMV.Z1.AIR_FLOW_2.FRESH" requires a mix of 
site-specific conventions and implicit domain knowledge. For 3rd party solution 
provider systems, deciphering its meaning is not an easy task, requiring 
extensive times and re-coding of the system to interpret the data for use. The 
issue of data interoperability becomes more pronounced for buildings with 
multiple smart systems that rely on data from each other and for building 
owners with multiple buildings in their portfolio which may have systems from a 
multitude of suppliers (e.g., multiple BMS vendors for multiple buildings) all 
using their own specific conventions. 
 
 
 
===== PAGE 48 =====
 
40 
 
 
 
3) Implementing Cybersecurity 
Type 3 Smart FM solution relies heavily upon IT infrastructure to host and 
interconnect the various components of building systems. As with all IT 
infrastructure and systems, there is a need to ensure that the systems continue 
to function and are not hindered by external threats, especially systems that are 
connected to the internet. Cybersecurity is thus an importan t consideration for 
all smart building systems and owners should take the necessary precaution 
such as securing their network using network security device such as firewalls 
and ensuring that they are correctly installed, updated, and maintained. Other 
fundamental measures such as adopting a strong password combination, 
changing passwords regularly, installing an antivirus program and ensuring 
software are constantly updated and patched will help to reduce the risk 
However, there is a need to balance cybersecurity requirements vis-à-vis cost. 
It is important for building owners to review the criticality of each system and 
the sensitivity of the data it holds, balancing the need/level of security required. 
4.2 Good Practices to Facilitate Data Management 
4.2.1 Common Data Environment (CDE) for FM 
A Common Data Environment (CDE) for FM can be established either by FM 
companies or building owners to manage information during operational stage of the 
assets. Such a CDE could potentially help address issues with data silos as well as 
interconnectivity as multiple systems' data and key information are consolidated into 
a single environment. Following ISO 19650 -3 on Information Management during 
Operational Phase of the Assets (Clause 5.1.9), a CDE is defined as a combination 
of workflow and information storage solutions to support the information 
management process for the asset(s). To provide clarity on the CDE, the following 
guidance is added: 
• A CDE is not necessarily a single large platform that interoperates with all 
other platforms used by all stakeholders, but rather a collection/consolidation 
of key information from the relevant technology stacks to manage specific 
===== PAGE 49 =====
 
41 
 
 
 
use cases with the agreed mechanism 7 to exchange/share the information 
across the stacks. The CDE will thus be the main consolidator and distributor 
of these key information. 
 
• As an example, a CDE can be consolidation of data from an IoT platform and 
FM workflow automation platform to support Fault Detection & Diagnostics 
(FDD) use case. In this example, the CDE can consolidate fault-related 
information (e.g., type of incident, location, etc) from the respective IoT platform 
and/or FM workflow automation platform to gain insights on the service level 
delivery by monitoring the time taken to close the incidents as well as the critical 
assets performance by monitoring the Mean-Time-Between-Failure (MTBF) of 
the assets. 
As in the implementation of all enterprise level solutions, an organisation should go 
through a detailed business case review to determine its use cases, the data that it 
requires and thus value for the organisation. The functional requirements of the 
systems that a CDE should connect with would be determined through the business 
case review. Some common features/functionalities of CDE for FM are as follows: 
• File and data management: It is important that data and information is made 
easily available in the CDE for both human users as well as systems. A data 
lake or data warehouse for data to be queried, viewed, extracted, and stored 
should be considered in tandem with data standards 8, data hierarchy, data 
types as well as frequency of use amongst many others. 
 
• User management: Given that a CDE would be the source of information for 
many within the organisation as well as to selected few outside of the 
organisation, proper user management is required to ensure that data stays 
secure and that only the right people can access the right data for them. For 
example, building owners/FMCs might create access accounts for term 
 
7 Depend on how a use case is defined, the mechanism to exchange/share the information can be in a form of passing the 
key information through email/SMS or open communication protocol as described in Section 4.2.2. 
8 Data standards are documented agreements on representation, format, definition, structuring, tagging, 
transmission, manipulation, use, and management of data. 
===== PAGE 50 =====
 
42 
 
 
 
contractors service providers to only access data and services for which they 
are authorised. The access rights for this group would differ greatly from those 
given to their own staff. User access rights and management is also key in 
ensuring traceability of activities, changes and actions that are carried out in 
the CDE. 
 
• Dashboard, analytics, and reporting: Having a wealth of data, it is important for 
the organisation to make sense of it to derive value. Business intelligence (BI) 
tools, such as dashboards and analytics tools would help the organisation 
understand and analyse its data, generate insights and build predefined reports 
on selected events (e.g., equipment breakdown) or assets (e.g., energy 
consumption) essential for operations. Doing so enables the Facilities Manager 
to better plan his Operations and Maintenance (O&M) schedules, optimise 
resources and identify areas to improve. 
 
• Operation and workflow management: Managing operations and FM workflows 
are the foundation of any organisation involved in FM. Given that much of the 
data and decisions for FM either originate or end with operational task and an 
integral part of FM workflow, a CDE for FM should include functions and 
features around managing such tasks, this may include pulling and pushing 
relevant information to building owners, FMCs and other service providers for 
works to be carried out as well as tracking and overseeing 
feedback/maintenance/repair tickets. 
 
• Open protocols: The use of open protocols as a foundation requirement of any 
CDE is important to ensure ease of interconnectivity between system. More on 
this will be shared in following sections. 
 
• Cloud-based environment: Adopting a cloud-based environment will allow data 
and information to be efficiently accessed, shared, and maintained from any 
location, so long as there is an internet connection. 
===== PAGE 51 =====
 
43 
 
 
 
4.2.2 Open Communication Protocol 
Communication protocols define how devices talk to each other; hence if a building 
has equipment/systems that use proprietary (closed) protocols, they will not be able 
to communicate with another system, without substantial effort and costs to convert 
the protocols to one that is common between the systems. As such, it is important that 
organisations mandate the adoption of open protocols as a foundation in the systems 
it adopts. Many different open protocols have been developed over the years; this 
multitude of choices mean that product manufacturers would need to decide which 
protocol(s) their products will conform to. In choosing a product, users would thus be 
inherently choosing and adopting the protocol(s) that come with it. 
Building owners and FM companies should consider the following when choosing a 
product and the communication protocol requirements for it. 
1. Consider the requirement for compatibility with existing systems and 
equipment. For example, an equipment monitoring system may require 
communication with a workflow system to automatically trigger cases when 
alarms are received. Choosing the right product and the inherent 
communication protocols it use s would determine the complexity of achieving 
this interconnectivity between the systems. 
2. Consider the adoption rate of the protocol among different vendors that provide 
the solution/system. A protocol that is common amongst a large group of 
vendors providing the service not only increase the likelihood that other 
systems would have catered to this protocol but also provides flexibility to 
owners in changing system/vendors without impacting o ther systems that 
would have already been integrated. 
3. Consider the need to add new devices or interconnectivity with additional 
systems in the future. Adopting a protocol that is widely adopted beyond a 
single discipline will enable scalability in the event where new devices and 
solutions need to be connected for new capabilities and further automation. 
Several common open communication protocols and data transmission methods are 
as follows: 
===== PAGE 52 =====
 
44 
 
 
 
• Building Automation and Control Networks (BACnet): A communication 
protocol for Building Automation and Control (BAC) networks that leverage the 
ASHRAE, ANSI, and ISO 16484-5 standard protocol. It supports most building 
operations, such as ACMV, lighting, fire protection, and access control devices. 
The BACnet protocol provides services that are used to communicate between 
building devices. Examples of such services are Who-Is, I-Am, Who -Has, I-
Have, which are used for Device and Object discovery. Services such as Read-
Property and Write-Property are used for data sharing. 
 
• Modbus: Modbus supports communication to and from multiple devices 
connected to the same cable or Ethernet network and is widely used in 
industrial, building, infrastructure, transportation, and energy applications. 
 
• OPC Unified Architecture (OPC UA): able to communicate with major building 
automation protocols such as BACnet and Modbus; hence it can be thought of 
as a universal translator for linking disparate systems. It allow s different 
systems such as security, lighting, elevator, and ACMV to be connected using 
a single connectivity standard. 
 
• Application Programming Interface (APIs): is fundamentally a software 
intermediary that allows applications to talk to each other. It is a set of 
definitions and protocols for integrating application software and are used when 
required to perform a designed function built around sharing data and executing 
pre-defined processes. In FM terms, it could be used when a ACMV diagnostic 
software detects an anomaly, the diagnostic software calls the CMMS to create 
a job ticket where the issue will be track and manage by the technician in the 
CMMS. 
 
• File Transfer Protocol (FTP): is a standard asynchronous communication 
protocol used for the transfer of files from a server to a client. For a more 
secured transmission, users should opt for SSH File Transfer Protocol (SFTP). 
Typically used when data size is large and is not required real -time. In FM 
terms, it could be used when transferring the list of people that enter/exit the 
===== PAGE 53 =====
 
45 
 
 
 
building for the month from the Visitor Management System to the building 
owner's registry. 
In addition to using open protocols to address interconnectivity issue, ensuring data 
accuracy and quality is also important. A way to ensure data accuracy and quality is 
to set the expected max value and the min value for a measured point. This allows the 
system to flag out anomaly. For example, for an office room temperature sensor, the 
max value can be set at 35 ⁰c and the min value to be 15 ⁰c. If the measured point is 
outside of the range, the technician can be informed to check the condition of the 
sensor. 
4.2.3 Conventions and Schemas for Organising Data 
Conventions and schemas ensure the consistency of data across systems. This 
comes into importance when an organisation has multiple similar assets it needs to 
monitor. An example of this is when a CDE or central monitoring system requires 
interoperability with multiple BMSes across different properties under an organisation. 
Having a common set of definition of how the data in the BMSes for every building is 
named and structured would significantly reduce the time, effort, and cost in making 
sense of the data across each building. 
The recent ISO 21823-3 on Interoperability for IoT systems (Semantic Interoperability) 
highlighted the importance of ensuring consistency of the data across systems 
regardless of individual data format through the adoption of common metadata 
schema. 
Having a common Metadata schema addresses data interoperability issue by: 
• Standardising the definition of a "thing" (controlled and shared vocabulary) 
Example: some system suppliers (or building owners) may define zone as a 
group of multiple buildings but others as a group of multiple spaces or a 
separately controlled cooled space. Querying the data that do not adopt a 
common definition of a "thing" (in a metadata schema) may give inconsistent 
outputs that require further data cleaning before it can be used for analytics. 
• Standardising the relationships between "things" 
===== PAGE 54 =====
 
46 
 
 
 
Example: to enable smart analytics such as Automated Fault Detection and 
Diagnostics, relationship between the "things" (e.g. AHU feeds fresh air to VAV, 
VAV has Damper, etc) need to be defined. Inconsistency in defining the 
relationship between "things" may hinder portability of the smart analytics from 
one machine or system to another. 
 
While it is possible to define and create a metadata standard specific to an 
organisation, this may require significant investment in time and effort. Noting this, 
several open-source metadata schemas for buildings have become available and are 
gaining prevalence in the industry. It is important to note that an organisation should 
adopt a single schema and stick to it, having different schemas within an organisation 
portfolio would erode the synergy that adopting a metadata schema brings. Some of 
these are as follows: 
 
• Brick Schema (https://brickschema.org/): standardise semantic descriptions of 
the physical, logical, and virtual assets in buildings and the relationships 
between them. 
• Project Haystack (https://project-haystack.org/): standardise semantic data 
models and web services with the goal of making it easier to unlock value from 
the vast quantity of data being generated by the smart devices. 
• Digital Buildings Project (https://google.github.io/digitalbuildings/): a uniform 
schema and toolset for representing structured information about buildings and 
building-installed equipment. A version of the Digital Buildings ontology and 
toolset is currently being used by Google to manage buildings in its portfolio. 
4.2.4 Cybersecurity for Smart Buildings 
The Info-communications Media Development Authority (IMDA) published the Internet 
of Things (IoT) Cyber Security Guide in Mar 2020 to provide users and enterprises 
with essential guidance when procuring, deploying, and operating IoT devices and 
systems. This guide also enables FMCs and Service/Solution Providers to verify the 
security posture of their solutions. It includes practical guidelines featuring baseline 
===== PAGE 55 =====
 
47 
 
 
 
recommendations, foundational concepts, and checklists, alongside an annex9 (Annex 
C) containing a Case Study for Smart Buildings. This annex serves as a valuable 
reference for Building Owners, FM Managers, FMCs, and Service/Solution Providers 
aiming to implement and operate IoT devices and systems securely. 
In modern smart buildings, which integrate complex autonomous building automation 
systems, the risk of cyber -attacks is significant if these systems are not properly 
secured. The Technical Reference (TR) 111 on Securing cyber-physical systems for 
buildings10 offers a comprehensive overview of asset management, physical and 
environmental systems, and access control related to building systems. 
To further enhance cybersecurity, the Cyber Security Agency (CSA) has developed a 
certification scheme11 to recognise organisations that demonstrate good cybersecurity 
practices. The Cyber Essentials mark acknowledges organisations that have 
implemented essential cyber hygiene measures, while the Cyber Trust mark is a 
distinction for those with comprehensive cybersecurity strategies and practices. These 
marks serve as visible indicators, demonstrating that organisations have established 
robust cybersecurity measures to protect their operations and customers from cyber 
threats. 
4.3 Use Cases for Data Management 
A use case can be defined as a list/sequence of actions that an actor (a person or 
other external system) performs within a building system to achieve a particular goal. 
It is an effective way for identifying FM processes and functional requirements, 
especially useful in prioritising the scope of work for complex processes with large 
numbers of possibilities and stakeholders. 
 
9 The annex is available at: https://www.imda.gov.sg/-/media/imda/files/regulations-and-
licensing/regulations/consultations/2022/consultation-for-new-annex-c-of-iot-cyber-security-guide/imda-iot-cyber-
security-guide-annex-c-final.pdf 
10 TR111 is available for purchase via the Singapore Standards website: 
https://www.singaporestandardseshop.sg/Product/SSPdtDetail/98cf35ec -5e5b-4850-a0f5-04fa148aac29 
11 More detail at: https://www.csa.gov.sg/our-programmes/support-for-enterprises/sg-cyber-safe-
programme/cybersecurity-certification-scheme-for-organisation 
===== PAGE 56 =====
 
48 
 
 
 
The proper management of FM data, ensuring data interconnectivity, avoiding data 
silos, ensuring interoperability, and implementing cybersecurity, unlocks opportunity 
for enhanced capabilities (or use cases) in FM. The following sub-sections explore 
specific use cases, with additional examples available in Appendix F. 
4.3.1 Workflow Tracking and Service Level Delivery 
Workflow tracking and service level delivery is essentially the consolidation and 
analysis of data pertaining to works detected and carried out within a building or 
multiple buildings. Traditionally, building owners with multiple buildings would procure 
a solution similar to that of a CMMS to create, track, and process such works with their 
service providers being required to use this procured solution. However, for some 
building owners, such methodology might be more costly and not a business focus. 
On the other hand, facility management companies (FMCs) would typically have a 
CMMS as an essential part of their core business. Building owners can thus obtain 
synergy through proper data management and leveraging the CMMS of the FMCs. 
Building owner may consider establishing a cloud data management platform to hold, 
process and track such workflow data. Key information on works, such as completion 
duration, costs, material/part replacement, etc. can be transmitted over from the FMCs 
to the data platform and where the building owner can use the information for reporting, 
tracking, analytics, and decision making. Such a methodology would not only save 
costs for building owners but also save time in maintaining and ensuring uptime for a 
CMMS as well as in training their service providers to use an unfamiliar system. This 
frees up and allows building owners to better look into correlating data across services 
to better understand and optimize t he building, e.g., correlating equipment runtime 
with maintenance regime and part replacement / breakdown. 
4.3.2 Fault Detection and Diagnostics 
Fault Detection and Diagnostics (FDD) is the process of detecting deviations from 
normal or expected operation (faults) and diagnosing the type of problem and/or its 
location. FDD technology is seeing an increased uptake in the market today that aims 
at improving building performance in different areas such as optimising energy 
efficiency, reducing utility expenses, and streamlining operations & maintenance 
===== PAGE 57 =====
 
49 
 
 
 
processes. However, to realise the full potential at scale, some technical barriers must 
be addressed as discussed below. 
Building equipment data is traditionally stored and processed within a building's BMS. 
Traditional BMSes monitor equipment data to ensure the functional operation of the 
building, flagging out critical alerts when a breakdown occurs. Such equipment data 
have a myriad of potential uses when analysed at system level and with complimentary 
data outside of the equipment itself. However, such equipment data are typically 
locked up within the BMS and difficult to extract and make sense of. This is 
compounded when building owners have multiple buildings with different BMS brands. 
Adopting a standard convention/schema for equipment data within different BMSes 
would ease the ability to make sense of the data across different brands. Centralising 
this data into a single environment would enable not only the ability to trend 
performances across equipment types but also provide visibility on differing ways each 
building is managed on the ground. 
It is good to note that centralising raw equipment data might be costly simply due to 
the sheer volume of data. One method around this is to enable a certain amount of 
processing and consolidation at the edge before the data is being sent to a CDE. For 
example, if the use case is to analyse the data over the year, there may not be a need 
for data points of every second, rather an average over a day may suffice. Newer BMS 
systems today would also offer equipment analytics at the BMS level before the 
information is transferred to a CDE. 
4.3.3 Condition-based Maintenance 
Condition-based maintenance is a predictive maintenance strategy where various 
elements of an operating asset are observed and measured over time to identify 
potential failure before it happen s. While condition-based maintenance can be 
adopted on most assets, it is important to focus more on the most critical assets to 
achieve the best return of investment. 
The following are some techniques used in condition-based monitoring: 
===== PAGE 58 =====
 
50 
 
 
 
• Vibration analysis: identifying potential failure by observing changes in vibration 
signature. For example, when compressors or motors degrade or fall out of 
alignment, the intensity of the vibration increases. 
• Infrared and thermal analysis: using Infrared cameras and/or thermal sensors 
to determine when an equipment (e.g., motorised parts that operate at high 
RPM) become too hot and alerting the maintenance team before it burns out or 
starts a fire. 
• Electrical analysis: using clamp-on ammeters to measure the electrical current 
in a circuit which may cause problems for an asset. 
 
Some of these techniques can also be combined to gauge the health of an asset. 
Analysing equipment data in tandem with maintenance cycles would help paint a 
picture of equipment reliability. Understanding how maintenance affects equipment 
data as well as what normal operational data looks like would help enable the 
development of condition-based maintenance strategy where maintenance cycles can 
be extended and, in some cases, only done on demand when required to prevent 
breakdown/deterioration. 
 
 
 
===== PAGE 59 =====
 
51 
 
 
 
 
Chapter 5. Digital FM Workforce 
Smart FM refers to the integration of processes, technologies, and people to enhance 
the management of a building's facilities. Thus, it is important to not just focus on 
sourcing and implementing technologies, but also equipping the people with the 
required understanding of why, when and what technologies should be used and how 
to use them effectively. More often than not, the application of technologies can make 
the work more efficient to yield better results. However, as the saying goes "Use the 
right tool for the right job". 
A lack of understanding on when, what, and how to utilise the right tool may eventually 
lead the users to develop negative connotations such as frustration and confusion, 
towards digitalisation. Consequently, this may lead them to believe that they are 
incapable of navigating the complexities of technologies and eventually choose to 
avoid them as much as possible. Therefore, this chapter aims to guide the readers 
towards a meaningful and practical approach to build up digital capabilities of the 
workforce in various relevant roles within Facilities Management. 
A 4-step process, shown in Figure 15 below, is recommended to aid the organisation 
in developing their digital capabilities. 
 
Figure 15. 4-step process in developing digital capabilities 
Step 1: Identify the required skillsets based on the business needs 
The FMIC and its taskforces have identified a list of digital skillsets that are relevant 
for Facilities Management today to support integrated and aggregated FM and 
mapped them to 10 Technical Skills and Competencies (TSCs) under the Skills 
Framework (SFw). The areas are listed in the table below: 

===== PAGE 60 =====
 
52 
 
 
 
 
SN TSC Description 
1 Technology Scanning Review new developments in emerging 
technology as well as evaluate and determine 
relevance of emerging technologies to the 
organisation 
2 Robotic and Automation 
Technology Application 
Integrate robotic and automation technologies in 
the Built Environment, including construction, 
operations and maintenance to enhance 
productivity and precision and to reduce reliance 
on manual tasks 
3 Internet of Things 
Management (available 
in SFw-BE, to be added 
under FM track) 
Interrelate computing devices, equipment and 
machines data in a networked environment to 
provide specific solutions 
4 Technology Application Integrate technologies into business operations 
of the organisation to optimise efficiency and 
effectiveness of processes 
5 Applications Integration 
(available in SFw-BE, to 
be added under FM 
track) 
Integrate data or functions from one application 
program with that of another application program 
- involves development of an integration plan, 
programming and the identification and utilisation 
of appropriate middleware to optimise the 
connectivity and performance of disparate 
applications across target environments 
6 Smart Facilities 
Management 
Integrate digital technologies and smart 
automation into facility operations and 
maintenance to optimise efficiency and 
performance 
7 Data Collection and 
Analysis 
Collect, extract and interpret data according to 
defined requirements to obtain insights 
8 Design Thinking 
Practice 
Manage design thinking methodologies and 
processes to solve specific challenges, and 
guide stakeholders through the phases of 
inspiration, ideation and implementation 
9 Integrated Digital 
Delivery Application 
Drive the adoption, integration and 
implementation of Integrated Digital Delivery 
(IDD) technologies to manage projects and 
building life-cycle efficiently from digital design, 
digital fabrication, digital construction to digital 
asset delivery and management 
10 Cybersecurity Understand, develop and apply cybersecurity 
policies and procedures to ensure protection 
against cybersecurity risks and vulnerabilities, 
and to respond to cybersecurity breaches 
Table 4. Technical Skills and Competencies (TSCs) under the Skills Framework (SFw) 
===== PAGE 61 =====
 
53 
 
 
 
 
Step 2: Map the required skillsets to the role the user is performing 
In building up digital capabilities, organisation should also avoid taking a "one size fit 
all" approach and overload the ground operations personnel with capabilities that may 
not be required for his/her scope. Instead, organisations should adopt a proact ive 
approach to tailor the proficiency level to the needs of the role that the individual is 
performing. "The right person, in the right job, with the right skills, at the right time". 
In this example, the guide will adopt the SFw career pathway for the Built Environment 
sector as an example. Based on the SFw Job Role, the level of competencies can be 
broadly mapped into 3 groups targeting those in the Senior Management, Middle 
Management and Operational team. The example will map the skillsets to the 3 groups 
based on their respective needs. 
SFw Job Role Possible Job Title/Designation Group 
Associate Director • FM Director 
• Associate Director (Admin and FM) 
• Deputy Director (Building Services) 
Senior 
Management 
Senior Facilities 
Manager 
• Senior Facilities Manager 
• Senior Fire Safety Manager 
• Senior Digital FM Specialist12 
Middle 
Management 
Facilities Manager • Facilities Manager 
• Fire Safety Manager 
• Digital FM Specialist 
Technical/Building/ 
Facilities/Property 
Executive 
• Technical Executive 
• Building Executive 
• Facilities Executive 
• Property Executive 
Operational 
Team 
Technical/Building/ 
Facilities/Property 
Officer 
• Technical Officer 
• Building Officer 
• Facilities Officer 
• Property Officer 
Facilities Technician / 
Building Supervisor 
• Facilities Technician 
• Building Supervisor 
Table 5. SFw Job Role matched to the respective groups 
 
12 Digital FM specialist/Digital Service Officer to develop the technology road map, manage the technology 
implementation and integration, perform data analytics and optimisation for equipment, manpower, and 
resource. 
===== PAGE 62 =====
 
54 
 
 
 
 
 
Technical 
Skills and 
Competencies 
Areas of Focus 
(by industry 
partners) 
Level of Competencies (by industry partners) 
Senior Management Middle Management Operational Team 
Data Collection 
and Analysis 
Data Strategy 
 
Data Quality 
Mgmt 
 
Data 
Engineering 
 
Data 
Governance 
 
Master Data 
Mgmt 
• Overview on how 
data should be 
collected, stored, 
and managed. 
• Principles of Data 
Management 
• Utilise appropriate tools, systems, and 
techniques to collect, store, extract, 
transform and load data according to 
set guidelines. 
• Develop data management structures, 
policies, processes and tools for 
effective data storage, handling, and 
utilisation. 
• Implement data management 
processes and systems to map data 
sources, processes, and relationships, 
and transform and process multiple 
streams of data. 
• Understand the need to input 
accurate data to facilitate 
upstream analytics and 
reporting. 
Predictive 
Analytics 
 
Fault Detection 
& Diagnosis 
 
Artificial 
Intelligence 
 
Machine 
Learning 
• Strategic 
understanding on 
the various tools 
and techniques for 
data analytics 
• Understanding of how analytics is 
used to detect, identify, and diagnosis 
anomalies. 
• Identify underlying trends and patterns 
using basic statistical analysis and 
business intelligence tools. 
• Develop, apply and evaluation 
algorithms, predictive data modelling 
and data visualisation to identify 
underlying trends and patterns in 
data. 
• Lead the procurement of 
advance/proprietary analytics 
software. 
• Able to troubleshoot and act 
on the diagnosis of the 
model. 
===== PAGE 63 =====
 
55 
 
 
 
• Develop operational workflow when 
fault arises. 
• Analyse results and work with FM 
operations to troubleshoot faults or 
optimise building systems. 
Dashboards & 
Reports 
• Overview of 
various 
visualisation tools 
available in the 
market and 
benefits of them 
• Navigate and use 
the tools available 
to track the 
organizations 
performance 
• Assist in strategic 
decision making 
• Generate dashboards and reports to 
reflect data trends, findings and to 
facilitate management reporting 
• Utilise tools to identify focus areas to 
work on 
• Establish effective data visualisation 
architecture, process and system 
integration to get the necessary data. 
• Provision of tools, data and 
techniques to create dashboards 
 
• Able to utilise dashboards 
and reports to identify areas 
to work on e.g. outstanding 
tickets 
Internet of 
Things 
Management 
 
 
IoT Architecture 
 
Technology 
Fundamentals 
 
M2M 
Communications 
 
Network 
Protocols 
• Strategic 
understanding on 
objectives and key 
functions of IT/OT 
systems and 
System-of-
systems 
• Formulate Internet 
of Things (IoT) 
direction and 
platforms so to 
drive operational 
efficiency and 
effectiveness 
• Understanding on objectives and key 
functions of IT/OT systems and 
System-of-systems 
• Identify or develop solutions to 
improve automation and productivity 
• Determine use cases, user and data 
requirements for FM systems 
• Detailed understanding on IoT 
protocols and technology stacks 
• Wired & wireless communication 
technologies 
• Concepts of system scalability, 
interoperability, availability and 
reliability 
• Fundamental understanding 
on Ops Tech 
===== PAGE 64 =====
 
56 
 
 
 
• Sensor and controller reliability 
concepts 
Digital Twin 
 
BIM for FM 
• Identify trends, 
technologies in the 
development of 3D 
operational 
models 
• Overview on the 
principles, value 
proposition, 
requirements, 
components of 
BIM and 
integration of any 
visualization 
solutions 
• Strategic 
understanding on 
the technology 
used in BIM and 
BIM design 
processes, 
standards, and 
implementation 
strategies to allow 
remote access 
• Identify trends, technologies in the 
development of 3D operational 
models 
• Overview on the principles, value 
proposition, requirements, 
components of BIM and integration of 
any visualization solutions 
• Technology used in BIM and BIM 
design processes, standards and 
implementation strategies. 
• Process and methodology in the 
development of 3D operational model 
• Connecting and integration multiple 
building services into a single facilities 
platform. 
• Execute technology used in BIM and 
BIM design processes, standards, and 
implementation strategies. 
• Able to open, utilise the 
Digital Twin / BIM for FM tool 
for day-to-day operations. 
Smart Facilities 
Management 
Cloud BMS 
 
Automation 
• Strategise the 
application of 
digital facilities and 
smart automation 
in different 
functional areas 
and processes 
• Manage facility operations and 
maintenance with digital technologies 
and smart automation 
• Integrate digital technologies and 
smart automation into facility 
operations and maintenance 
• Support facility operations 
and maintenance with digital 
technologies and smart 
automation 
===== PAGE 65 =====
 
57 
 
 
 
• Develop facility operations and 
maintenance procedures for 
integration into smart automation and 
operation technologies 
Design 
Thinking 
User Interface 
 
User Experience 
 
Design Thinking 
• Understanding the 
principles in UI 
and UX/Design 
Thinking 
• Design thinking 
methodologies 
• Streamline processes & workflows 
and utilise process automation tools to 
enhance FM efficiency 
• Understanding the principles in UI and 
UX/Design Thinking to enhance user 
experience 
• Apply design thinking methodologies 
and execute design thinking 
processes to challenge norms and 
conventions 
• Design information architecture, 
process flow, and user interface 
prototypes 
• Create user experience design 
concepts, develop user flow charts 
• Translate key user experience 
concepts and guidelines into simple 
wireframes 
• Establish effective design thinking 
processes, methodologies and 
frameworks to proliferate design 
thinking 
 
Technology 
Application 
 
 
Digital 
Transformation 
 
Digital Strategy 
 
Digital Marketing 
 
• Formulate 
technology 
strategies for 
business 
operations and 
processes, and 
• Execute Digital Transformation 
Roadmap 
• Implement technology plans and 
supervise the use of technology to 
execute tasks 
• Adopt new technologies to 
enhance operations or 
processes 
• Digital Confidence for IoT 
and Cybersecurity 
• Digital Confidence for 
Productivity 
===== PAGE 66 =====
 
58 
 
 
 
Digital 
Communication 
strategies 
 
Change 
Management: 
"Digital" + 
"facilities" 
 
design plans for 
implementation 
• Review the practicality, feasibility and 
risks of new technologies in relation to 
business processes 
• Develop plans to implement cloud 
solutions 
• Deploy cloud solutions and resolve 
basic cloud integration issues 
• Familiarity with Cloud Service 
Providers, Programming languages 
and Database Query Languages 
• Use of Web and Mobile App 
for FM 
 
Technology 
Scanning 
 
Emerging 
technologies 
 
Cloud Solutions 
 
Cost-benefit 
analysis for 
technologies 
implementation 
• Inspire adoption of 
emerging 
technologies to 
enhance 
organisational 
effectiveness and 
competitiveness 
• Identify trends and 
technologies in 
cloud solutions 
• Understanding of 
cloud computing 
such as the 
advantages/disadv
antages of IaaS, 
PaaS, SaaS 
• Evaluate the 
suitability of cloud 
solutions against 
the business 
needs 
 
• Understanding of cloud computing 
such as the 
advantages/disadvantages of IaaS, 
PaaS, SaaS 
• Track development of emerging 
technologies in the industry and 
collate information for technology 
implementation 
• Perform cost-benefit analysis and 
evaluation of the relevance, viability, 
sustainability and potential value-add 
of emerging technologies to the 
business and identify and select 
compatible emerging technologies 
• Review emerging technology, 
evaluate and determine relevance of 
emerging technologies to the 
organisation 
• Lead analysis of emerging 
technologies and drive 
implementation of industry specific 
technologies for organisational 
effectiveness and competitiveness 
 
===== PAGE 67 =====
 
59 
 
 
 
Integrated 
Digital Delivery 
Integrated Digital 
Delivery 
• Influence the 
adoption of 
Integrated Digital 
Delivery (IDD) 
technologies to 
manage projects 
and building life-
cycle efficiently 
• Lead the adoption 
of Integrated 
Digital Delivery 
(IDD) technologies 
to manage 
projects and 
building life-cycle 
efficiently 
• Assess the viability of the adoption of 
Integrated Digital Delivery (IDD) 
technologies to manage projects and 
building life-cycle efficiently 
• Implement Integrated Digital Delivery 
(IDD) technologies to manage 
projects and building life-cycle 
efficiently 
• Support Integrated Digital 
Delivery (IDD) 
implementation 
Application 
Integration 
Middleware 
Programming 
• Establish a 
business case for 
application 
integration and 
introduce new 
middleware tools 
and 
methodologies to 
enable both intra- 
and inter-
enterprise 
application 
integration 
• Integrate data and functions across 
application programs, and perform 
follow up tests to verify proper 
functioning 
• Oversee end-to-end process of 
application integration, determining 
suitable middleware and testing 
procedures and resolving issues that 
arise 
• System Integration and Migration 
• System Analysis and Design 
 
Cybersecurity Cybersecurity • Establish 
cybersecurity risk 
management 
strategies, policies 
• Develop awareness on cybersecurity 
threats and risks within the industry, 
and apply appropriate risk 
management actions to protect the 
• Do and Don't for 
Cybersecurity 
===== PAGE 68 =====
 
60 
 
 
 
and procedures to 
counter 
cybersecurity 
threats and risks 
as well as respond 
to cybersecurity 
breaches 
organisation and respond to 
cybersecurity breaches 
• Develop appropriate cybersecurity 
procedures and practices to ensure 
protection and response to identified 
cybersecurity breaches, as well as 
guide their implementation within the 
organisation 
Table 6. Technical Skills and Competencies (TSCs) matched to the respective groups 
 
 
 
 
 
 
 
===== PAGE 69 =====
 
61 
 
 
 
 
Step 3: Find suitable methods for users to develop the skillsets 
In building up digital capabilities, organisation should recognise that there are multiple 
approaches aside from just classroom training. Organisation could leverage on more 
experienced staff to provide coaching to less experience staff. This approach will help 
to contextualise the scope of the training to the organisation's needs and be able to 
address the set of problems and challenges within the organisation more accurately. 
Recognising that the pace of learning differs from individual to individual, organisation 
could also consider setting aside an hour each week to hold clinic sessions that are 
hosted by Subject Matter Experts to help and coach. 
 
Figure 16. Multiple training approaches for individuals in an organisation 
 
Step 4: Practice, Refine and Sharpen 
As with every newly acquired skillsets, it is essential that users continue to practice, 
refine, and sharpen the skills to build deep skills and knowledge in key focus areas. 
Users will move from a Basic level to an Intermediate level and to an Advance lev el 
where they will be recognised as a Subject Matter Expert (SME). Through this journey, 
the SME will then be able to help and coach less experience staff and uplift the 
organisation's digital capabilities in the FM sector. 

===== PAGE 70 =====
 
62 
 
 
 
 
Figure 17. 3 levels to uplift digital capabilities in the organisation 
 
 
 
 
 
 

===== PAGE 71 =====
 
63 
 
 
 
 
Chapter 6. Conclusion 
This Guide to Smart FM aims to help Building Owners and FM Managers articulate 
and realise their desired Smart FM outcomes. It has shared on core principles of the 
Smart FM Framework and provided a 5 -Step SMART Process to help the Building 
Owners and FM M anagers in identifying their business objectives, Smart FM 
outcomes and prioritising key FM services for the adoption of suitable technology 
solutions. Appendix E: Decision Template for 5 -Step SMART Process has been 
included to guide Building Owners and FM Managers through this process as they 
embark upon their Smart FM transformation journey. 
This Guide has been enhanced to provide more guidance on Type 3 Smart FM 
processes, technologies, and digital skillsets. Vendors/ sub-contractors, FMCs, and 
Building Owners may use the Digitalisation Maturity Map to understand their roles and 
the interaction between these 3 digital entities to cohesively delivers the benefits of 
FM integration and aggregation. FMCs or Building Owners may also want to set up a 
Common Data Environment (CDE) for FM to be tter manage data and gain insights 
across FM systems/services that empower decision-making process. As we redesign 
processes, adopt new technologies and learn new digital skills, it is important to begin 
with the end in mind, and be guided by clear objectives and desired outcomes in our 
Smart FM journey. 
With this enhanced Guide, the FMIC and the Integrated Smart FM Taskforce hope to 
encourage the FM industry to develop stronger partnerships and strategic alliance to 
reduce fragmentation and to redesign FM processes and jobs & skills while reaping 
the desired outcome of the FM industry transformation. 
 
 
===== PAGE 72 =====
 
64 
 
 
 
References 
[1] Green Mark NRB:2015 (for New Non -residential Buildings) and Green Mark 
ENRB:2017 (for Existing Non -residential Buildings) provides a "Smart Buildings 
Operation" section that provide guidance for "Energy Monitoring", "Demand Control", 
"Integration and Analytics" and "System Documentation" 
[2] Guide on Specifications for Energy Performance Contracting (EPC) Air -
conditioning System Maintenance Contract by Singapore Green Building Council 
(SGBC) 
[3] Guide on Outcome-Based Security Contracts by Security Industry Transformation 
Map (ITM) Tripartite Committee 
[4] Guide on Specifications for Outcome -based Cleaning Contract by National 
Environment Agency (NEA) 
[5] Welcome to the IoT era, Findings and insight from IFMA and JLL's Internet of 
Things (IoT) research by IFMA and JLL 
[6] A guide to outcome-based agreements – a better way to do business by Interllect's 
Outcome-Based Agreement Group 
 
===== PAGE 73 =====
 
65 
 
 
 
List of Figures 
Figure 1. Transformational change through smart FM requires more than just 
technology.................................................................................................................. 1 
Figure 2. 5-Step SMARzT process to Smart FM........................................................ 4 
Figure 3. Fundamentals of Smart FM implementation................................................ 5 
Figure 4. Flowchart on Step 1 of the 5-Step SMART process.................................... 6 
Figure 5. Model A: Integrated Smart FM Solution.................................................... 13 
Figure 6. Single Smart FM Solution......................................................................... 14 
Figure 7. FM Digitalisation Relationship Mind Map.................................................. 29 
Figure 8. FM Digitalisation Maturity Map (Cleaning)................................................. 29 
Figure 9. FM Digitalisation Maturity Map (Pest Control)........................................... 31 
Figure 10. FM Digitalisation Maturity Map (Refuse Waste Management)................ 32 
Figure 11. FM Digitalisation Maturity Map (Landscape)........................................... 33 
Figure 12. FM Digitalisation Maturity Map (M&E)..................................................... 35 
Figure 13. FM Digitalisation Maturity Map (Security)................................................ 36 
Figure 14. Key considerations in managing data..................................................... 38 
Figure 15. 4-step process in developing digital capabilities...................................... 51 
Figure 16. Multiple training approaches for individuals in an organisation............... 61 
Figure 17. 3 levels to uplift digital capabilities in the organisation............................ 62 
Figure 18. Identified business objectives and FM outcomes to address challenges on 
fire safety.................................................................................................................. 71 
Figure 19. Automated Workflow of Smart Fire Safety and Emergency Platform...... 72 
Figure 20. A Cloud and IOT-based Smart Fire Safety and Emergency Platform..... 73 
Figure 21. Smart Nodes connected to the platform.................................................. 73 
Figure 22. Faults and failures detectable by the platform......................................... 74 
Figure 23. Schindler's Developer Portal................................................................... 81 
Figure 24. Reduction in technical callbacks after installation of the cubes in elevators
................................................................................................................................. 82 
Figure 25. Reduction in downtime after installation of the cubes in elevators.......... 83 
Figure 26. Example of baseline for a load range...................................................... 87 
Figure 27. Centralised cloud solution deployed with a dedicated connection to the 
existing BMS system................................................................................................ 88 
Figure 28. Chiller Plant Power consumption before and after implementation......... 89 
Figure 29. Sample for AHU Saving.......................................................................... 90 
Figure 30. A centralised cloud solution connected to the airside system................. 90 
Figure 31. digiHUB Dashboard Interface.................................................................. 95 
Figure 32. digiHUB System Architecture.................................................................. 96 
Figure 33. Fault Detection & Diagnostics Workflow................................................. 98 
Figure 34. Change Management and Workforce Upskiling.................................... 101 
Figure 35. The Everest Building Operating System............................................... 111 
Figure 36. Daily plug-load consumption over the baseline fortnight (Before Ecovolt, 
upper) and the matched post-deployment fortnight (After Ecovolt, lower).............. 117 
Figure 37. Overlaid daily comparison of the baseline (Before Ecovolt) and post-
deployment (After Ecovolt) periods, with aggregate energy, cost, and carbon metrics. 
Charts generated by the Everest platform.............................................................. 118 
===== PAGE 74 =====
 
66 
 
 
 
Figure 38. Fault Detection and Diagnostics flow diagram...................................... 121 
 
List of Tables 
Table 1. Template to rank business objectives, set desired FM outcomes, and 
determine high-priority FM services to focus on......................................................... 7 
Table 2. Example of a Smart FM Framework with multiple solutions identified........ 10 
Table 3. Sample table to review if the adopted solutions have addressed desired FM 
outcomes.................................................................................................................. 22 
Table 4. Technical Skills and Competencies (TSCs) under the Skills Framework 
(SFw)........................................................................................................................ 52 
Table 5. SFw Job Role matched to the respective groups....................................... 53 
Table 6. Technical Skills and Competencies (TSCs) matched to the respective 
groups...................................................................................................................... 60 
Table 7. Lingjack's Smart FM Framework................................................................ 71 
Table 8. Schindler Ahead's capabilities differentiated into three types of "smartness"
................................................................................................................................. 78 
Table 9. Summary of Chiller Plant energy savings................................................... 88 
Table 10. Summary of AHU energy savings............................................................ 91 
Table 11. Key Stakeholders and Roles.................................................................... 94 
Table 12. Productivity Improvements achieved through digiHUB Implementation. 103 
Table 13. Stakeholders and their roles in the deployment...................................... 114 
Table 14. Measured energy reduction, and carbon outcomes, together with the 
platform's projected annual figures........................................................................ 116 
Table 15. Average daily plug-load consumption by occupancy period, derived from 
the hourly data. Transitional hours around the start and end of the working day 
bridge the two bands.............................................................................................. 117 
Table 16. Chiller plant – BMS monitoring points.................................................... 122 
Table 17. Air Conditioning Equipment – BMS monitoring points............................ 124 
Table 18. Mechanical Ventilation Equipment – BMS monitoring points................. 124 
Table 19. Essential parameters to be monitored.................................................... 126 
Table 20. Parameters to be monitored................................................................... 127 
Table 21. The 5-step SMART process – summary of what Building Owners and FM 
Managers should consider..................................................................................... 131 
Table 22. List of essential Smart FM use cases..................................................... 134 
 
===== PAGE 75 =====
 
67 
 
 
 
Appendix A: List of Smart FM Point Solutions 
The market for Smart FM technology solutions is maturing and the product range is 
comprehensive and ever-growing. Examples of smart FM solutions include IoT, data 
analytics and artificial intelligence, to pre -empt fault, optimise energy and manpower 
use, or enhanc e occupants' experience and the FM Team's ability to measure and 
meet desired outcomes. 
To lower the technical hurdle and cost barrier, most FMCs or Service/ Solution 
Providers offer a cloud-hosted option on a subscription basis. 
The cost of Smart FM can be significantly reduced if the necessary supporting 
infrastructure was designed for "smart" from day one within the base building systems. 
Nevertheless, it is still possible to progressively build up the supporting infrastructure 
for Smart FM. Building Owners and FM Managers can explore various point solutions 
such as those listed below to address specific FM pain points related to infrastructure 
and common services. 
The list is non -exhaustive; omitted are commercial systems such as retail signage, 
payment systems; and familiar technologies like the building automation system (BAS) 
and non-routine specialist activities like façade inspection. 
M&E Services 
1. Condition Monitoring of Chillers, Pumps, Lifts etc 
2. Energy Performance Contract 
3. Air-con as a Service 
4. Fault Detection and Diagnostic 
Security 
5. Video Surveillance and Analytics 
6. Visitor Management 
7. Location Tracking 
===== PAGE 76 =====
 
68 
 
 
 
Environment Services 
8. Smart Toilet System 
9. Rodent Management System 
10. Robotic Floor Cleaner 
Converged Services 
11. Connected Light System 
12. Room and Space Management, Hot-desk 
13. Emerging Services 
14. Demand Response Program 
15. Advanced Robot for Façade Cleaning 
===== PAGE 77 =====
 
69 
 
 
 
 
Appendix B: Facilities Management Consortium 
Operation & Technology Roadmap (COTR) 
To build a future -ready FM sector as part of the Built Environment Cluster – Real 
Estate Industry Transformation Map (ITM), t he Singapore International Facility 
Management Association (SIFMA) worked with the Agency for Science, Technology 
and Research (A*STAR), supported by the Building and Construction Authority (BCA) 
and Info -communications Media Development Authority (IMDA), to develop a 
Consortium Operation and Technology Roadmap (COTR) for the sector. 
Aligned to the ITM, the COTR aims to outline the general trends and direction of the 
FM sector, map out technology solutions and prioritise them according to the needs of 
the sector from 2018 to 202 7. The COTR serves as a useful reference to translate 
some of the identified areas, from short to long term, into actionable outcomes for the 
sector. 
More than 100 people from 50 organisations across the industry, academia, and 
government agencies participated in the 3 facilitated workshops and mapped out over 
50 technology solutions under the COTR. 
The COTR report is expected to be released in October 2019, and more information 
can be found in the SIFMA website at https://www.wgs1.net/ifma-sg/. 
===== PAGE 78 =====
 
70 
 
 
 
 
Appendix C: Case Studies 
C.1 Lingjack Digital Smart Fire Safety and Emergency Platform 
Overview 
Lingjack Digital was formally created in 2021 to create and provide IoT (Internet -Of-
Things) solutions that solve Customers real -life problems in an innovative, non -
intrusive manner. At the same time, creating real value to customers/stakeholders to 
maximise operational and cost efficiency, increase productivity, downtime and 
manpower. 
Lingjack Digital's Smart Monitoring and Control Platform was designed and developed 
to provide a one -stop, customisable platform for 24/7 electronic monitoring, control, 
and alerts for different domains such as Environmental, Water, Energy utilisation, 
Flood Detection, Water Pump, Fire Safety and Emergency Monitoring and Control etc. 
Specifically, the Lingjack Smart Fire Safety and Emergency Platform was developed 
to manage fire safety products and assets within an easy -to-use workflow. The 
workflow consists of 5 simple steps: (1) 24/7 active monitoring, (2) Remote automated 
testing, ( 3) Non -compliance detection and notifications, (4) Corrective Action & 
Resolution, (5) Service Records/Reports. 
The Smart Fire Safety and Emergency Platform was deployed at 2 operational sites 
to electronically monitor and manage the operational status fire extinguishers and exit 
lights. 
Step 1: Set Business Objectives and Outcomes 
The Singapore Fire Safety Standards (SS 578 and SS 563) requires fire extinguishers, 
exit lights and emergency lights to be inspected monthly. On the ground, building 
owners and Facilities Managers face the following challenges: 
a. Low productivity: The time consuming and repetitive inspections are carried out 
by FM staff 
b. Manpower constraints: Rising manpower cost and manpower shortage 
c. Risk of equipment failure in-between monthly inspections 
===== PAGE 79 =====
 
71 
 
 
 
To address the challenges above on fire safety, Lingjack Digital has identified the 
following business objectives and FM outcomes to focus on: 
 
Figure 18. Identified business objectives and FM outcomes to address challenges on fire safety 
 
Step 2: Map Out Smart FM solutions as Enablers 
To achieve the business objectives and outcomes, the SMART Fire Safety and 
Emergency Platform was developed to address these challenges. The smart solutions 
on this platform are mapped out below. 
Type Scope Building Level FM Services 
Type 
1 
 
Digitalise 
Assets 
Fire Safety Asset Tracking and Location Tagging 
 
 
 
Digital 
Workflow 
Automation 
Automated Workflow 
• Active 24/7 operational status and fault/non-
compliance monitoring, alerts and management. 
• Regulatory adhoc and routine testing 
• Events Logging 
• Fire Product Asset Management 
• Service Panel for Service Inspection, Incident 
Logging, Tracking and Reports 
Type 
2 
 
Optimisation 
within System 
Type 
3 
Integration 
Across 
Systems 
Bridging APIs could be developed in future for integration 
with other smart systems 
Table 7. Lingjack's Smart FM Framework 
 
 

===== PAGE 80 =====
 
72 
 
 
 
SMART Fire Safety and Emergency Platform (Type 1) 
The SMART Fire Safety and Emergency Platform is an IOT -based platform that 
reinforces regulatory code compliance and increases the operational readiness in fire 
safety products. This is achieved through non -intrusive, distributed, electronics 
monitoring. T he platform simplifies and automate the management of fire safety 
products through 5 simple stages illustrated below. 
 
Figure 19. Automated Workflow of Smart Fire Safety and Emergency Platform 
 
The platform could integrate with third-party service agencies (eg. yearly maintenance) 
into this maintenance eco -system to provide a total management and safety 
preparedness status of the buildings. 
The SMART Fire Safety and Emergency Platform uses Cloud and IoT technologies. 
Wireless Smart Nodes are deployed to monitor different safety aspects of fire safety 
products. (e.g., fire extinguisher for leakage, missing, access obstruction, exit light for 
failed lamps or drained battery). Data are sent wirelessly on a secure mesh network 
and push to the Cloud for analysis and decision-making. Users can view, monitor, and 
control the fire safety products 24/7 remotely on the browser or mobile app. 

===== PAGE 81 =====
 
73 
 
 
 
 
Figure 20. A Cloud and IOT-based Smart Fire Safety and Emergency Platform 
 
Other Smart Nodes (eg. fire door, pump monitoring, energy usage etc) could be easily 
added onto the deployed infrastructure by having them connected to the same 
wireless network. 
 
Figure 21. Smart Nodes connected to the platform 
24/7 monitoring of fire safety systems 
Through the Smart Fire Safety and Emergency Platform, the facilities manager and 
his maintenance team now have visibility of the live fire safety readiness of the fire 
extinguishers, exit lights and emergency lights on a single platform. This leads to 
greater confidence that fire equipment is operational ready in times of emergency. 
 
 

===== PAGE 82 =====
 
74 
 
 
 
Active Fault and Failure Detection 
The platform provides timely alerts to the Facility Manager when faults and failures are 
detected. 
 
Figure 22. Faults and failures detectable by the platform 
 
The FM team is informed of fault conditions through app alerts so they can be 
addressed promptly. The service incidents are captured through the platform, and this 
ensures that all incidents are promptly logged, tracked, and closed. 
Reduced manpower for regulatory monthly inspections 
The maintenance team can fulfil regulatory requirements for monthly inspections, 
records maintenance, incident records, corrective actions etc with reduced manpower, 
time, and effort. The team can spend more time on other value-added or critical tasks. 
Step 3: Implementation/Deployment Model 
The platform adopts Model B: Single Smart FM Solution and will include open APIs to 
integrate or exchange information with other FM platforms. 
Step 4: Review Procurement Contract 
The procurement was based on an initial capital investment with subscription model. 
A platform-as-a-service model could be explored as an alternative to lower initial 
capital investment. 
 

===== PAGE 83 =====
 
75 
 
 
 
Step 5: Track outcomes and review for continuous improvement 
The performance was continuously monitored for improvements and the following 
outcomes were reviewed for continuous improvement: 
a. The platform could replace the conventional practise of manual inspection and 
recording for fire extinguishers which results in manpower savings. This 
centralised archive allows for easy retrieval and maintenance tracking during 
audits. 
b. The emergency lights and exit lights could be tested remotely on a scheduled 
basis, this reduces the manpower required for manual testing. 
c. The monitoring feature provided timely alerts for fire extinguishers approaching 
service expiry which enabled timely servicing and replacement. A feature to 
automatically trigger service actions to external service vendors could be 
explored in the future. 
d. The fault detection system was effective as it provided reliable and consistent 
feedback. The 24/7 monitoring enhanced the building's fire safety. 
Carrying out monthly physical inspection of 200 fire extinguishers and exit lights will 
require about 4 to 5 days. More time will be required for larger developments. With 
electronic monitoring, the FM staff could focus on higher value activities. 
Key lessons learnt 
The following will be considered to enhance the system: 
Site survey to improve the wireless mesh connectivity 
The wireless mesh network is self -healing with redundancy features. Site survey is 
essential to identify potential disruptions due to site interference and to provide for 
alternate communication paths. 
Future expansion of the Smart Fire Safety and Emergency Platform 
In the April 2022 amendment of SS 578, electronic monitoring of fire extinguishers was 
included as an acceptable means to fulfil the regulatory monthly inspections. This 
would likely be extended to other fire safety systems, and these could be added to the 
Smart Fire Safety and Emergency Platform in future. 
===== PAGE 84 =====
 
76 
 
 
 
Interoperability between Smart Fire Safety and Emergency Platform and BMS 
Systems. 
Although not identified as a requirement, it will be beneficial from the information 
captured to be integrated into the BMS or CMMS system. A bridging device that 
supports open standards eg. Modbus or an API could be developed for future 
integration. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
===== PAGE 85 =====
 
77 
 
 
 
C.2 Schindler Ahead 
Towards end -2020, Schindler Ahead was installed in a prominent >500k sq. ft. 
business park in Singapore. The aim was to get better visibility and monitoring of the 
elevators in the building because it was a high -traffic area. The original maintenance 
contract for the building included maintenance, callbacks, and full repair coverage. 
5-Step SMART Process 
Step 1: Set Business Objectives and Outcomes 
 
The building owner and FM manager have several objectives with regards to facilities 
management (FM). These include: 
(1) Ensuring that facilities are working as expected and maintained adequately 
(2) Ensuring that building tenants and building users are satisfied with the facilities 
(3) Enhancing the building assets through maintenance and upgrading. 
 
The following outcomes are desired by the building owner and FM manager: 
(1) Reduce downtime/unavailability of facilities 
(2) Increase building tenant and user satisfaction with facilities 
(3) Improve building assets through maintenance and upgrading 
 
Elevators and escalators (E&E) are used hundreds of times daily by the building 
tenants and users. Smooth functioning of the elevators and escalators is essential for 
tenants and users to have a good experience in the property. 
 
 
Identify Business Objectives 
Set FM Outcomes 
Prioritise FM services 
===== PAGE 86 =====
 
78 
 
 
 
Step 2: Map Out Smart FM Solutions as Enablers 
Schindler offers a remote monitoring solution called "Schindler Ahead", which includes 
the following capabilities: 
(1) Remote monitoring: elevators are connected to Schindler's cloud and monitored 
24/7 for any abnormalities or problems, allowing for prompt responses or pro -active 
interventions 
(2) ActionBoard: ActionBoard is an online dashboard that allows customers to view 
the real-time status of elevators and check the history of actions performed on each 
elevator. 
Type/Scope Description Building Level FM 
Services 
 
Demand side 
aggregation: 
Install 
Schindler 
Ahead 
across 
multiple 
buildings 
 
Supply side 
aggregation: 
Installing 
Schindler 
Ahead will 
allow 
Schindler to 
collect and 
analyse more 
data from 
buildings 
M&E Functions 
Type 1: 
Digitalised 
Workflow 
Automation 
When triggered by an 
incident, automatically 
initiates a process that 
tracks, logs, and 
closes the incident 
- Elevator remote 
monitoring 
- Automatic breakdown 
detection and technician 
dispatch 
Type 2: 
Optimisation 
within 
systems 
Use data analytics to: 
- Optimize systems 
- Quantify FM 
efficiency 
- Perform 
preventive/predictive 
maintenance 
- Perform proactive 
interventions to prevent 
more serious issues in 
the future 
- Gather data from 
multiple connected units 
to improve diagnostic 
capability 
Type 3: 
Integration 
across 
systems 
Optimise resource 
deployment and 
utilisation across many 
systems 
- Integration of 
Schindler API with 
building management 
system 
Table 8. Schindler Ahead's capabilities differentiated into three types of "smartness" 
 
Aggregating across Types 1 to 3 
===== PAGE 87 =====
 
79 
 
 
 
Schindler Ahead includes all three types of "smartness". 
Type 1: Digitalised Workflow Automation 
Schindler connected a communications device called a Cube to each elevator 
controller. The Cube collects raw data from the elevator controller and sends it to the 
Schindler cloud for analysis. If any problems are found, they are sent to Schindler's 
technicians via an app on their company mobile phones. Technicians will then 
intervene as appropriate to either fix the problem or prevent a serious problem from 
occurring. Job details, actions to be taken, start time, end time and technician's 
comments are preci sely logged in the mobile phone app. Schindler also has a 
Technical Operations Centre (TOC) in Singapore staffed by technical experts to 
provide additional guidance to the technicians where necessary. 
Type 2: Optimisation within systems 
Data from connected equipment is routed to Schindler's cloud where it is analysed to 
produce "Symptoms", which either indicate a serious problem or a warning sign of a 
problem about to happen in the future. Schindler has a global team of technical experts 
in Switzerland and Germany who are constantly looking to improve Schindler's data 
analytics technology. On the ground, technicians provide feedback on the Symptoms 
through their company mobile phone, which also helps Schindler to improve the 
capabilities of its data analytics. Schindler has created a n iterative feedback loop to 
collective harvest data from more connected units, leading to better performance of 
its analytics engine. 
Type 3: Integration across systems 
Schindler is currently developing a building integration toolbox and API platform that 
will allow the remote monitoring system to be easily integrated into building 
management systems. 
 
 
 
 
===== PAGE 88 =====
 
80 
 
 
 
Aggregation 
For Schindler Ahead, aggregation occurs at both the demand side (customer side) 
and supply side (Schindler). 
For demand side aggregation, the building owner has installed Schindler Ahead 
across multiple buildings in their portfolio. This has given them a bird's -eye view and 
better management of all the connected units. 
For supply side aggregation, installing Schindler Ahead for many elevators in one 
building has allowed Schindler to closely monitor overall trends in problems, and fix 
them before more serious ones arise. 
Step 3: Adopt Suitable Implementation Model 
Current: Model B (Single Smart FM Solution) 
The current model adopted by the customer is Model B, where the building owner has 
procured the Schindler Ahead service specifically and manages it through an online 
dashboard provided by Schindler. There is currently no integration between Schindler 
Ahead and any other Smart FM systems that the customer is using. 
Long-term goal: Model A (Integrated Smart FM Solution) 
Schindler is currently developing an open, secure, and modular building integration 
toolbox that allows customers to seamlessly integrate Schindler's digital services into 
their overall building management and user experience by offering an Application 
Programming Interfaces (APIs) and other integration tools. Schindler aims to 
implement this new concept with its customers in the future. 
 
===== PAGE 89 =====
 
81 
 
 
 
 
Figure 23. Schindler's Developer Portal 
 
Step 4: Review Procurement Contract 
The standard contract terms for Schindler ahead are as follows: an upfront installation 
fee for each Cube and a small monthly subscription fee per connected unit. Schindler 
recommends a contract duration of 3 years to gather adequate data about the 
performance of the connected units, which will help to improve the performance of the 
system. Schindler technicians will also be more experienced with the specifics of 
connected units if they service them over longer time periods. 
Meetings are held between Schindler and operational stakeholders on the customer's 
side to track the progress of the remote monitoring system in improving maintenance 
outcomes. 
Step 5: Track Outcomes and Review for Continuous Improvement 
Schindler suggested that the following metrics be tracked to monitor the performance 
of remote monitoring: 
(1) Equipment availability (uptime): to determine if the remote monitoring is helping to 
maximise the uptime of connected equipment 

===== PAGE 90 =====
 
82 
 
 
 
(2) Technical faults per equipment rate: to determine if the remote monitoring system 
is helping to reduce the number of technical faults per equipment 
(3) Diagnostic accuracy: to determine how accurate Schindler's system is in 
determining the root cause of problems 
Challenges 
FM staff on the customer's side took some time to fully understand all the features of 
the Schindler remote monitoring system and the ActionBoard, and how to integrate 
these into their daily workflow effectively. Schindler staff were available to aid and 
answer questions where needed, and also to provide suggestions on how to best 
utilize the system. 
Schindler also conducted internal training for its technicians before it was rolled out in 
the field. 
Improvements/Benefits 
Total number of technical callbacks per month decreased by 43% after installation of 
the cubes in the elevators. 
 
Figure 24. Reduction in technical callbacks after installation of the cubes in elevators 
Total downtime per month decreased by 94% after installation of the cube - the remote 
monitoring diagnostics helped Schindler to solve a few big problems with the elevators. 

===== PAGE 91 =====
 
83 
 
 
 
 
Figure 25. Reduction in downtime after installation of the cubes in elevators 
 
Key Lessons Learnt 
Schindler's technology is highly effective in monitoring elevators 24/7. However, efforts 
are also needed on the human side, both by the customer in monitoring the equipment, 
as well as on Schindler's side to perform proactive interventions before more ser ious 
problems arise. 
In the near future, Schindler intends to go one step further, by rolling out its API 
platform to integrate each customer's Building Management System with Schindler 
Ahead monitoring. This will allow for comprehensive monitoring, better visibility, and 
enhanced outcomes of all the facilities in a building. 
 

===== PAGE 92 =====
 
84 
 
 
 
C.3 Smart Energy Management for ACMV Systems 
Smart Energy Management refers to the use of advanced technologies and data-driven 
solutions to monitor, control, and optimise the generation, distribution, and consumption 
of energy. This approach aims to improve energy efficiency, reduce costs, and minimise 
environmental impact. 
Smart Energy Management (SEM), particularly in the context of ACMV (Air Conditioning 
and Mechanical Ventilation) systems, is an emerging solution that has evolved as a 
response to the growing demand for energy efficiency and environmental sustainability. 
Traditionally, ACMV systems operated on set schedules or fixed set of control set points, 
often leading to energy wastage or missed opportunity for saving energy. However, 
advancements in technology have led to the integration of sensors, automation, and 
data analytics into ACMV systems, enabling real-time monitoring and adaptive control. 
This allows for more dynamic control adjustments to respond to a wider set of changing 
parameters such as occupancy density, human traffic flow and weather conditions. 
This guide highlights a case study on SEM for ACMV systems by Azendian, but there 
are several other similar market solutions that building owners and FM companies can 
explore and pilot. It is also important to note that for such data-driven solutions to be 
effective, it has to be applied with a sound understanding of the domain knowledge of 
ACMV systems, and complemented by a robust maintenance regime. Otherwise, the 
potential savings may not be achieved. 
Building owners should also consider the various implementation and business models. 
Some incorporate these solutions into the ACMV maintenance service contracts, while 
others adopt a performance-based model, sharing the savings reali sed from 
implementing the solution. Alternatively, building owners may acquire the solution as 
Software-as-a-Service (SaaS) or require their Facility Management Companies (FMCs) 
to implement it in partnership with the SEM providers. 
Begin your Smart Energy Management journey today to achieve substantial energy 
savings and enhance the sustainability of your building operations. 
===== PAGE 93 =====
 
85 
 
 
 
Azendian Estate HVAC Energy Optimisation Solution 
Products and solutions in the market, such as variable speed drives and building 
automation systems, are often limited in their ability to optimise energy usage in real-
time, relying on manual readjustments of equipment settings. In contrast, the Azendian 
Estate solution offers real -time monitoring and adaptive control for chiller plants and 
AHUs. By applying AI and ML, it automatically adjusts setpoints in real-time, ensuring 
optimal HVAC performance under all conditions. 
 
The solution analyses data from various sources, including weather forecasts, building 
usage patterns, and chiller plant performance, to optimi se energy usage. Based on 
changes in building usage and weather conditions, the solution writes back operating 
parameters in real-time to the models and adjusts the setpoints according to the model's 
outcomes. 
 
The Azendian Estate HVAC Energy Optimisation Solution offers several key benefits 
for buildings and organisations: 
1. Brand-Agnostic and Non -Intrusive Integration: The solution seamlessly 
integrates with any ACMV system without requiring major modifications or 
replacements. 
2. Minimal Upfront Investment: With little to no initial costs, organisations can 
quickly realise benefits and achieve a shorter Return on Investment (ROI) period. 
3. Unified Control Platform: It digitises multiple assets, consolidating them under a 
single control platform for simplified ACMV management. 
4. Cloud-Based Access: The cloud-based system allows for remote access anytime, 
anywhere, providing flexibility for building managers and operators. 
5. Real-Time Write -Back Capability: Changes made to the system are reflected 
immediately, enabling instant feedback and faster decision-making. 
6. Energy Savings: The solution optimises ACMV performance, reducing energy 
costs and CO2 emissions. 
 
 
===== PAGE 94 =====
 
86 
 
 
 
Case Study for Chiller Plant Optimisation 
Background 
Chiller Plant Performance 
Annual Cooling Demand (RTh/year) 2,555,333 
Annual Chiller Plant Energy Consumption (kWh/year) 1,806,729 
Annual Chiller Plant Utility Cost (SGD) 
(Assume Elec Tariff @ SGD 0.34/kWh) ~ 610,000 
 
Project Details 
1. Initial site assessment and exploratory data assessment: 
a. Recommendations were provided to the client to rectify chiller plant 
operation issues. 
b. Faulty temperature sensor replacement. 
c. The existing chiller plant was found to operate at modulating speed with a 
Variable Speed Drive (VSD) but at fixed set points. 
 
Building General Info: 19 storeys grade A office building (GM platinum) at 
CBD (Singapore) 
Estimated Area Served: +/- 35,000 sqm 
Year Built: 2009 
Cooling Load Profile: Office hour: 500 – 650RT 
After Office hour: 50 – 150RT 
Operating Hour: Time 1 Chiller in Operation 2 Chiller in Operation 
Monday to 
Friday 
6pm – 7am the 
following day 7am – 6pm 
Saturday 1pm – 7am the following day 7am – 1pm 
Sunday/Public 
Holiday 24 hours - 
 
Chiller Plant 
Components 
: 4 Chillers 
4 Chilled Water Pumps 
4 Condenser Water Pumps 
2 Cooling Towers 
===== PAGE 95 =====
 
87 
 
 
 
 
2. Baseline Methodology: 
a. A regression model is developed to calculate the chiller plant's baseline 
consumption, capturing various scenarios of power consumption under 
different weather conditions and cooling loads. 
b. A polynomial equation is then generated to calculate the chiller plant's 
baseline power consumption (kW). This equation considers the cooling load 
(RT) and wet -bulb temperature ( ℃), which represent variables related to 
building occupancy and weather conditions. 
c. To further improve the accuracy of the baseline, multiple polynomial 
equations are generated for different cooling load distributions. 
 
Figure 26. Example of baseline for a load range 
 
3. Implementation: A centrali sed cloud solution was deployed with a dedicated 
connection to the existing BMS system, as illustrated in Figure 45 below. To comply 
with the building owner's IT policy, the gateway was configured within a DMZ, 
enabling interface with the existing BMS while routing through the firewall. 

===== PAGE 96 =====
 
88 
 
 
 
 
Figure 27. Centralised cloud solution deployed with a dedicated connection to the existing BMS system 
 
Project Outcomes 
Chiller Plant energy savings summary: 
 A B C C-B (C-B)/C 
Date 
Cooling 
Load 
(RTh) 
Chiller Plant 
Energy 
Consumption 
(kWh) 
Chiller Plant 
Baseline Energy 
Consumption 
(kWh) 
Energy 
Savings 
(kWh) 
Energy 
Savings 
(%) 
April 194,567 140,575 156,003 15,428 9.89% 
May 198,430 145,418 158,978 13,561 8.53% 
June 209,590 149,219 169,383 20,164 11.90% 
July 197,587 139,278 157,714 18,436 11.69% 
August 216,976 147,989 172,471 24,482 14.19% 
Sep 194,805 135,120 159,069 23,949 15.06% 
Table 9. Summary of Chiller Plant energy savings 
 
 

===== PAGE 97 =====
 
89 
 
 
 
 
Figure 28. Chiller Plant Power consumption before and after implementation 
 
Case Study for AHU Optimisation 
Background 
 
Project Details 
1. Initial site assessment and exploratory data assessment. 
2. Baseline Methodology: The baseline for AHU power consumption (kW) is 
established based on the historical power consumption profile over a specified 
period, using daily reference data. A sample of the AHU power consumption 
baseline (kW) is shown below.: 
Building General Info: 7-Storey of multi-purpose building comprises 
of offices, data centre, laboratory, F&B, and 
exhibition hall (Singapore) 
Estimated Area Served: +/- 30,000 sqm 
Year Built: 2013 
Overall Operating Cooling 
Demand: 100 to 600 RT 
AHU Quantity: 20 nos 
Operation Hours: 24 hours operation 
===== PAGE 98 =====
 
90 
 
 
 
 
Figure 29. Sample for AHU Saving 
 
3. Implementation: A centralised cloud solution with dedicated connection to the 
airside system, as shown in Figure 48. 
 
Figure 30. A centralised cloud solution connected to the airside system 
 
 
 
 
 

===== PAGE 99 =====
 
91 
 
 
 
Project Outcomes 
AHU energy savings summary: 
 A B B - A (B-A) / A 
Month 
Total Energy 
Consumption 
(kWh) 
Total Baseline 
Consumption 
(kWh) 
Total Energy 
Savings 
(kWh) 
Total Energy 
Savings 
(%) 
Aug-22 22,814 40,695 17,881 43.94% 
Sep-22 24,223 42,608 18,385 43.15% 
Oct-22 27,621 48,917 21,296 43.54% 
Nov-22 30,579 52,448 21,969 41.89% 
Dec-22 23,758 46,205 22,448 48.58% 
Jan-23 27,630 53,415 25,785 48.27% 
Table 10. Summary of AHU energy savings 
 
Conclusion 
The deployment of the Azendian Optimization Solution in both case studies achieved 
significant energy savings, ranging from approximately 9% to 15% for the chiller plant 
and 42% to 49% for the AHU. The application of data science to ACMV optimi sation 
has proven highly beneficial, particularly through a machine learning algorithm that 
continuously learns from changes in equipment behaviour and load profiles as new 
operational data is collected. Over time, the algorithm retrains itself to adapt and 
optimise the plant under varying conditions. 
 
 
 
 
 
 
 
===== PAGE 100 =====
 
92 
 
 
 
C.4 An Integrated Smart FM Ecosystem enabling Outcome-
based IFM Operations 
Introduction 
CBM Pte Ltd (CBM) is one of Singapore's leading Integrated Facilities Management 
(IFM) providers with more than 50 years of experience across commercial, retail, 
industrial, hospitality, residential and government sectors. As a subsidiary of City 
Developments Limited (CDL), CBM delivers a wide range of integrated services 
including Engineering, Environmental Services, Security, Sustainability Solutions, 
Project Management and Smart FM solutions. 
Over the years, CBM has progressively transformed its Facilities Management (FM) 
operations through the adoption of digital technologies, operational automation and 
data-driven facilities management approaches. This transformation journey led to the 
development of digiHUB, a Smart Properties Management System designed to 
integrate multiple technologies, maintenance workflows and analytics into a 
centralized Smart FM ecosystem. 
The implementation featured in this case study was deployed across a portfolio of 
commercial and retail developments in Singapore under an Outcome-Based IFM and 
AFM framework. The objective was to transform traditional manpower -intensive FM 
operations into a more integrated, predictive and technology -enabled Smart FM 
ecosystem aligned with Singapore's Smart FM direction. 
Background and Problem Statement 
Prior to the implementation of digiHUB, facilities operations relied heavily on 
conventional manpower -intensive workflows and reactive maintenance practices. 
Routine inspections, fault reporting and maintenance activities were largely conducted 
manually using paper-based checklists and fixed preventive maintenance schedules. 
Operational teams were required to perform repetitive inspections and fixed-schedule 
maintenance inspections regardless of actual equipment conditions. Security 
operations also relied significantly on manual monitoring and physical patrol 
deployment. As operational expectations increased alongside manpower constraints, 
there was a growing need for a more efficient and integrated operational model. 
===== PAGE 101 =====
 
93 
 
 
 
In addition, existing operational systems operated independently without centralised 
visibility across different FM functions. Building owners lacked consolidated visibility 
of equipment conditions, maintenance trends, operational performance, manpower 
productivity, asset lifecycle performance and service response tracking. 
These challenges highlighted the need for a centralised Smart FM ecosystem capable 
of improving operational visibility, enabling predictive maintenance and supporting 
workflow automation. 
The implementation of digiHUB was guided by several strategic objectives. From an 
operational standpoint, the initiative aimed to improve manpower productivity through 
workflow automation and digitalisation, reduce reliance on repetitive manual 
inspections and patrols, and transition from conventional preventive maintenance 
towards a more predictive and condition-based approach. From a technology and data 
perspective, the initiative sought to improve operational visibility through centralised 
dashboards and analytics, enhance service responsiveness and accountability, 
improve asset reliability and reduce downtime, enable data -driven decision-making 
and lifecycle planning, and support long-term operational sustainability through Smart 
FM technologies. 
Key Stakeholders Involved 
The implementation of digiHUB required close collaboration among building owners, 
FM practitioners, technology specialists and solution providers. Each stakeholder 
played a distinct role in ensuring that the platform was aligned with operational 
requirements, technology capabilities and desired business outcomes. The key 
stakeholders and their respective roles are summarised in Table 13. 
 
Stakeholder Role 
Building Owner / Asset 
Management 
 Provide governance, establish service objectives 
and KPIs, monitor operational performance, and 
support asset management decision-making. 
CBM Operations Team: 
engineering, cleaning, 
Primary domain experts and end-users who define 
technical requirements, evaluate software usability, 
===== PAGE 102 =====
 
94 
 
 
 
security and command centre 
operations 
test digital tools on -site, and undergo training to 
ensure successful technology adoption. 
CBM Digital Solutions Team Platform integration, dashboards, analytics and 
workflow development 
Technology Partners Provision of IoT sensors, video analytics, robotics, 
visitor management and system integration 
Table 11. Key Stakeholders and Roles 
DigiHUB Platform and Implementation 
As part of its Smart FM transformation journey, CBM developed digiHUB, a Smart 
Properties Management System designed to integrate facilities management 
technologies, operational workflows and data analytics into a single digital ecosystem. 
Unlike conventional FM systems that operate independently, digiHUB was designed 
as an integrated Smart FM ecosystem that consolidates multiple technologies, 
workflows and data sources within a common platform. Through the integration of 
predictive maintena nce sensors, Building Management Systems (BMS), 
Computerised Maintenance Management Systems (CMMS), visitor management 
systems, video analytics, security robotics and toilet monitoring systems, digiHUB 
enables real-time monitoring, workflow automation and data-driven decision-making. 
This integrated approach provides facilities managers and building owners with 
greater operational visibility, improved service accountability and enhanced ability to 
optimise manpower and asset performance across multiple developments. 
The implementation was carried out across a portfolio of commercial and retail 
developments in Singapore under an Outcome-Based IFM and AFM framework. More 
than 2,500 IoT sensors were progressively deployed across multiple developments to 
support predictive maintenance, environmental monitoring and workflow automation. 
The deployment covered a wide range of building systems and operational functions, 
including ACMV equipment, pumps, cooling towers, electrical systems, visitor 
management, cleaning operations and security services. In addition to IoT sensors, 
the implementation incorporated video analytics, virtual patrolling systems, security 
robots, self -service visitor registration kiosks and centralised command centre 
===== PAGE 103 =====
 
95 
 
 
 
operations to support a more integrated and technology -enabled facilities 
management model. 
Figure 31 illustrates the digiHUB dashboard environment, which provides facilities 
management teams and building owners with real -time visibility of building 
performance, equipment conditions, service delivery and operational trends across 
multiple sites. Through a single interface, users are able to monitor key performance 
indicators, asset conditions and service requests, enabling more informed and timely 
decision-making. 
 
Figure 31. digiHUB Dashboard Interface 
 
 
 

===== PAGE 104 =====
 
96 
 
 
 
 
Figure 32. digiHUB System Architecture 
To support integration across different technologies and operational systems, digiHUB 
adopts a centralised architecture that connects on -site devices with cloud -based 
analytics and management platforms. As illustrated in Figure 32, data collected from 
IoT sensors, BMS alarms and FM systems are transmitted through site gateways and 
cloud infrastructure into a common platform for analytics, workflow management and 
reporting. 
The implementation was delivered through a phased approach comprising site 
assessments, infrastructure reviews, system integration, User Acceptance Testing 
(UAT), staff training and operational handover. This approach enabled the various 
technologies to be progressively incorporated into daily facilities management 
operations while minimising disruption to building users and site activities. 
 
 
 

===== PAGE 105 =====
 
97 
 
 
 
Predictive Maintenance 
One of the key objectives of the digiHUB implementation was to transition 
maintenance operations from conventional preventive maintenance towards a more 
predictive and condition-based approach. 
IoT sensors were deployed on critical building systems including chillers, air handling 
units (AHUs), pumps, cooling towers, electrical systems and generators. These 
sensors continuously monitor operating parameters such as vibration, temperature, 
sound le vels and equipment status, transmitting data to the digiHUB platform for 
analysis. 
Using predictive analytics and machine learning algorithms, the system identifies 
abnormal operating patterns and potential equipment degradation before major 
failures occur. Instead of relying solely on fixed maintenance intervals, engineering 
teams are a ble to prioritise interventions based on actual equipment conditions and 
risk levels. 
The adoption of predictive maintenance reduced the reliance on routine inspections 
and enabled maintenance resources to be deployed more effectively. For selected 
equipment, servicing frequencies were optimised from monthly maintenance cycles to 
bi-monthly maintenance cycles while maintaining asset reliability and operational 
performance. 
Beyond improving maintenance efficiency, predictive maintenance also enhanced 
visibility of asset performance trends and supported longer-term lifecycle planning. 
Historical equipment data captured through digiHUB enables facilities managers to 
better understand equipment behaviour, identify recurring issues and make more 
informed maintenance and capital replacement decisions. 
 
 
 
 
===== PAGE 106 =====
 
98 
 
 
 
Ops-Tech Integration 
A key differentiator of the digiHUB implementation was the integration of technology 
directly into daily facilities management workflows. Rather than operating as 
standalone technology solutions, the various systems were designed to support and 
enhance the work processes of engineering, cleaning, security and command centre 
teams. 
 
Figure 33. Fault Detection & Diagnostics Workflow 
Figure 33 illustrates the Ops-Tech integration framework adopted under digiHUB. The 
workflow design began with a review of CBM's existing FM standard Operating 
Procedures (SOPs) across engineering, cleaning, security and command centre 
functions. Through a series o f cross -functional workshops involving operational 
supervisors, engineers and technology partners, each existing SOP was mapped 
against the alert types generated by the connected technologies to determine how 
digital signals should trigger operational resp onses. Key decisions made during this 
process included defining escalation thresholds for engineering alerts based on 
equipment criticality ratings, establishing response time targets for different alerts 
categories, and determining which alert types shoul d route directly to field teams 

===== PAGE 107 =====
 
99 
 
 
 
versus those requiring command centre review first. The result was a closed -loop 
workflow where alerts generated by predictive maintenance sensors, video analytics, 
toilet monitoring systems or other connected technologies are automatically routed to 
the FM platform and assigned to the relevant operational team for investigation and 
follow-up, with all actions tracked from initiation to closure. This alignment between 
technology-generated alerts and actual operational response processes was critical 
to ensuring that the system supported rather than disrupted daily FM operations. 
For engineering -related alerts, engineers review equipment condition data and 
determine the appropriate maintenance intervention. For cleaning operations, toilet 
monitoring sensors trigger cleaning deployment based on actual utilisation levels and 
cleanliness conditions rather than fixed schedules. For security operations, alerts 
generated through video analytics, virtual patrolling systems and security robots are 
routed to security personnel for investigation and response. 
The command centre functions as the central coordination point, providing oversight, 
escalation management and service tracking across all FM functions. Through this 
closed-loop workflow, alerts, service requests, investigations and rectification actions 
are tracked from initiation to closure, improving accountability and response 
effectiveness. 
This integration between operations and technology enabled facilities management 
teams to transition from routine, manpower -intensive activities towards exception -
based management. Rather than spending significant time on repetitive inspections 
and manual coordination, personnel are able to focus on higher -value tasks that 
require professional judgement and technical expertise. 
 
 
 
 
===== PAGE 108 =====
 
100 
 
 
 
Change Management and Workforce Upskilling 
The implementation of digiHUB was supported by a structured change management 
programme designed to address both the technical and human dimensions of the 
transition. Recognising that technology alone does not drive adoption, CBM 
implemented a deliberate p rogramme covering four phases: pre -implementation 
engagement, system design alignment, role -based training, and post -deployment 
reinforcement. 
Prior to implementation, structured workshops were conducted with frontline 
engineering, cleaning and security personnel to understand existing pain points and 
identify where technology could provide the greatest operational benefit. These 
sessions served a dual purpose – they informed the system configuration and 
workflow design, and they gave operational staff early visibility of how their daily work 
would change, reducing uncertainty and resistance before deployment began, 
feedback gathered during these workshops directly influenced decisions on alert 
routing logic, dashboard layouts and escalation procedures. 
Following system commissioning, role-specific training programmes were delivered to 
over 100 operational staff across engineering, cleaning, security and command centre 
functions. Rather than generic technology familiarisation, each programme was 
tailored to the specific tools and workflows relevant to each role. Engineers were 
trained to interpret equipment condition data and make maintenance prioritisation 
decisions based on predictive health indicators, rather than relying solely on fixed 
schedules. Secu rity personnel were trained to integrate video analytics, virtual 
patrolling and robotics outputs into their patrol and response procedures. Cleaning 
supervisors were trained to read real-time toilet utilisation dashboards and deploy staff 
dynamically base d on actual demand. Each training session included hands -on 
practice with live system data and simulated alert scenarios to build confidence before 
going live. Post-training assessments were conducted to verify competency, and on -
site support was provided during the initial weeks of live operations to reinforce 
learning in the actual work environment. 
 
===== PAGE 109 =====
 
101 
 
 
 
 
 
 
 
 
 
Figure 34. Change Management and Workforce Upskiling 
Figure 34 illustrates the structured change management programme implemented to 
support the adoption of digiHUB. The photographs show classroom -based training 
sessions, hands-on system familiarisation at the command centre, and practical on -
site coaching where engineers applied predictive maintenance techniques and digital 
workflows during daily maintenance activities. These activities helped operational 
personnel build confidence in using the new technologies and supported the 
successful transition to data-driven Smart FM operations. 
Through this structured approach, operational teams progressively transitioned from 
reactive, task -based activities towards exception -based and data -driven facilities 
management practices. The phased rollout allowed teams to build familiarity 
progressively, with each technology introduced in sequence rather than all at once. By 
the time full system deployment was complete, operational staff were routinely using 
digiHUB dashboards for daily monitoring, responding to predictive alerts as part of 
standard maintenance workflows, and contributing to data-driven service reviews with 
building owners. User confidence in the technology improved significantly over the 

===== PAGE 110 =====
 
102 
 
 
 
course of the programme, and the structured approach helped to sustain adoption 
beyond the initial deployment phase. 
Beyond technology adoption, the implementation also supported workforce 
transformation through structured skills development and role enhancement. 
Operational personnel were progressively equipped with new competencies in 
dashboard monitoring, data interpr etation, predictive maintenance analysis, video 
analytics and workflow management. By combining domain knowledge with digital 
capabilities, employees were able to take on higher -value responsibilities and 
contribute more effectively to data-driven facilities management operations. 
Benefits and Improvements Achieved 
The implementation of digiHUB delivered measurable improvements across 
engineering, cleaning, security and FM operations through the integration of 
technology with daily operational workflows. 
For engineering operations, predictive maintenance enabled a transition from fixed 
preventive maintenance schedules towards condition -based maintenance. By 
leveraging IoT sensors and predictive analytics, maintenance interventions could be 
prioritised based on actual equipment conditions, reducing unnecessary inspections 
while maintaining asset reliability and performance. 
For cleaning operations, toilet monitoring systems enabled cleaning deployment 
based on actual utilisation levels and cleanliness conditions instead of fixed cleaning 
frequencies. This allowed manpower resources to be allocated more effectively and 
reduced unnecessary touch-up cleaning activities. 
For security operations, video analytics, virtual patrolling systems and security robots 
supplemented physical patrols by providing continuous monitoring and exception -
based alerting. This reduced reliance on repetitive patrol activities while improving 
situational awareness and incident response effectiveness. 
 
===== PAGE 111 =====
 
103 
 
 
 
The integration of 
multiple technologies 
into a common FM 
platform also improved 
coordination between 
engineering, cleaning, 
security and command 
centre teams. 
Automated workflows 
and centralised 
dashboards improved 
visibility, accountability 
and service t racking 
across the 
developments.Function 
Smart FM Solution Productivity 
Improvement 
Engineering IoT Sensors (Predictive 
Maintenance) 
50% 
FM Process Auto-Ticketing System 90.8% 
Cleaning Toilet Monitoring System 20.5% 
Visitor Management Self-Service Kiosk 100% 
Security Virtual Patrol, VA and 
Robotics 
20% 
Table 12. Productivity Improvements achieved through digiHUB Implementation 
The productivity improvements were derived from actual workflow studies conducted 
before and after implementation. Examples of the productivity improvements achieved 
across various FM functions are summarised in Table 12. 
The productivity improvements were calculated by comparing baseline manpower 
hours and workflow effort prior to implementation against actual manpower hours 
required after deployment of the Smart FM solutions. For example, predictive 
maintenance reduced ro utine inspection frequencies for selected equipment from 
monthly servicing cycles to bi-monthly servicing cycles, while toilet monitoring systems 
reduced unnecessary cleaning deployment through utilisation -based scheduling. 
===== PAGE 112 =====
 
104 
 
 
 
Security productivity gains were achieved through virtual patrolling, video analytics 
and robotic assistance, which reduced the need for repetitive physical patrols while 
maintaining service coverage. 
As shown in Table 12, significant productivity improvements were achieved across 
engineering, FM administration, cleaning and security operations through workflow 
automation, predictive maintenance and technology-enabled service delivery. 
Collectively, these improvements contributed to an overall productivity improvement 
of approximately 23% to 25% across the developments. The productivity improvement 
was calculated based on reductions in manpower hours and operational effort 
achieved throu gh workflow automation, predictive maintenance and technology -
enabled operations. 
Based on CBM's digitalisation business case assessment, the implementation is 
projected to generate cumulative cost savings of approximately S$11.3 million over an 
11-year period through manpower optimisation, workflow automation and improved 
maintenance effectiveness. 
Beyond productivity improvements, digiHUB also supported data-driven decision 
making, asset lifecycle planning, KPI monitoring and operational benchmarking. 
These capabilities enabled building owners and FM teams to make more informed 
maintenance and capital planning decisions while supporting more sustainable 
facilities management practices. 
Lessons Learnt and Conclusion 
The implementation of digiHUB yielded several important lessons that are relevant to 
future Smart FM deployments: 
• On the people and change management front, the project reinforced that 
technology adoption is ultimately a human challenge. Workforce adaptation and 
stakeholder engagement proved to be as critical as the technology itself. 
Operational teams that were engag ed early, trained in context and supported 
post-deployment demonstrated significantly better adoption rates and more 
===== PAGE 113 =====
 
105 
 
 
 
effective use of the systems. The structured change management programme 
was not a peripheral activity but a core enabler of the project's success. 
• On the technology and integration front, the project demonstrated that Ops -
Tech integration must be grounded in existing operational workflows to be 
effective. Systems that generate alerts without clear operational ownership or 
response procedures create m ore noise than value. Careful attention to alert 
tuning, workflow alignment and escalation logic was essential to ensuring that 
technology enhanced rather than burdened day-to-day FM operations. 
• On the implementation approach, the phased rollout proved valuable in 
managing complexity and maintaining operational stability. Deploying 
technologies progressively allowed lessons from earlier phases to be 
incorporated into later ones, improved system st ability and gave operational 
teams time to adapt. Centralised dashboards also played an important 
governance role, providing building owners and FM managers with visibility to 
track performance, identify gaps and make evidence -based decisions across 
the portfolio. 
Collectively, these lessons point to a consistent theme: successful Smart FM 
transformation requires equal investment in people, processes and technology, and 
the greatest returns are achieved when all three are aligned. 
The modular design of digiHUB allows Smart FM technologies to be deployed 
progressively according to operational priorities, asset criticality and business 
requirements. This flexibility enables the approach to be adapted across different 
building typologi es, including commercial, retail, industrial and mixed -use 
developments, while supporting varying levels of digital maturity and operational 
complexity. 
Moving forward, CBM will continue enhancing digiHUB capabilities to further support 
Smart FM transformation, operational innovation and sustainable facilities 
management aligned with Singapore's built environment transformation roadmap. 
===== PAGE 114 =====
 
106 
 
 
 
The digiHUB implementation demonstrates how integrated Smart FM ecosystems can 
support Singapore's Built Environment transformation through smarter, more 
sustainable and data-driven facilities management operations. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
===== PAGE 115 =====
 
107 
 
 
 
C.5 Eliminating Plug-Load Standby Waste in a Commercial 
Office 
Introduction: Company and Context 
Ecovolt Technologies Pte. Ltd. is a Singapore-based company that builds an AI-native 
Building Operating System (AIBOS). Its platform, Everest, unifies device -level smart-
plug hardware (Volta Plug), a cloud-based platform and application (Everest), and an 
analytics layer that turns granular energy data into automated control. The platform 
spans energy analytics, role -based access control, occupancy -aware control, 
calendar and scheduling integration, predictive maintenance, ESG and carbon 
reporting, and integration with third -party building systems and business -intelligence 
tools. Ecovolt's p articular focus is the part of a building's electrical demand that 
conventional operating systems rarely see: the plug loads at individual workstations, 
appliances, and equipment. 
Ecovolt's platform addresses the wider building operating environment rather than a 
single device class. For this particular use case, the focus was on the Volta smart plug-
load solution combined with the Everest platform, applied to the standby waste that 
plug loads generate in a commercial office. 
In a typical commercial office, metering and control stop at the floor or zone level, and 
attention is concentrated on air -conditioning and mechanical ventilation (ACMV) and 
lighting. Plug loads, the equipment connected at the socket, are largely a blind s pot. 
Much of this equipment remains energised around the clock, drawing power overnight, 
over weekends, and during idle periods when the spaces it serves are unoccupied. 
This continuous background draw is commonly described as standby or vampire load, 
and across many devices and a portfolio of buildings it represents a meaningful and 
recurring source of waste. 
Like the wider Smart FM movement set out in this Guide, the deployment described 
here rests on the triangulation of people, process, and technology: device -level 
technology to make consumption visible and controllable, processes that align control 
with genuine occupancy, and the facilities team and occupants whose cooperation 
makes automated control acceptable in a live building. 
===== PAGE 116 =====
 
108 
 
 
 
This case study documents a deployment in which Ecovolt instrumented a defined set 
of plug -load circuits in a Grade A commercial office within the portfolio of City 
Developments Limited (CDL), measured their consumption, and used the Everest 
platform to re move standby waste while preserving normal daytime operation. To 
respect site confidentiality, the specific building is not named. The sections below 
outline how the BCA 5 -step SMART framework was applied to deploy and 
operationalise the solution, and how its outcomes are now being scaled across the 
portfolio. 
Step 1: Set Business Objectives and Outcomes 
The coverage 
CDL is one of Singapore's leading real estate developers, with portfolio -wide 
decarbonisation commitments. The approach was to begin with a focused, well -
instrumented deployment on a defined set of plug -load circuits in a single Grade A 
office, establish a credible, measured result, and use it as the basis for scaling across 
more circuits, floors, and buildings. With the business objective of Smart FM and the 
BCA framework as guidepost, the deployment defined its "Why", "What", and "How". 
Why 
Four characteristics of the problem made plug-load standby waste worth targeting: 
• Conventional metering is not sufficient. Because consumption is measured at 
the building or floor level, facilities teams cannot see how much energy individual 
devices consume, nor distinguish active use from standby waste. 
• Standby load is continuous and occupancy-blind. Equipment that is switched 
on but unused continues to draw power regardless of whether anyone is present. 
In an office occupied for roughly a third of the week, a large share of plug -load 
energy can be consumed while the space is empty. 
• The waste is small per device but large in aggregate. For a sustainability -
focused developer such as CDL, even modest per-device wastage scales quickly 
across many devices and many buildings. 
• Any solution must not disrupt operations. Powering down equipment cannot 
interrupt legitimate work, affect occupant comfort, or compromise critical 
===== PAGE 117 =====
 
109 
 
 
 
systems, and it should not require costly rewiring of an occupied, operational 
building. 
What 
The deployment was measured against four outcomes, consistent with the Smart FM 
goals in this Guide: 
• Energy savings: a measurable reduction in plug-load consumption, achieved by 
removing standby waste. 
• Better visibility and asset insight: consumption made visible at the level of the 
individual device. 
• Productivity and convenience: automated, occupancy -aware control that 
removes waste without manual intervention, with remote oversight for the 
facilities team. 
• Sustainability and compliance: cost and carbon savings that support CDL's 
decarbonisation commitments and align with national objectives. 
How 
Device-level metering and remote switching (Volta Plug), an analytics engine that 
learns each device's usage pattern and automates occupancy -aware schedules 
(Everest), all deployed on open protocols (OPENAPI 3.0 compatible) so the solution 
can integrate with CDL's wider systems and scale across the portfolio. 
The question the deployment set out to answer was therefore straightforward: can 
plug-load consumption be made visible at the level of the individual device, and can 
standby waste be removed during unoccupied hours, without affecting daytime 
productivity and without intrusive works? 
Step 2: Map Out Smart FM Solutions as Enablers 
The success of Step 1 depends on the vehicle of delivery. A device -level energy 
management solution for a live commercial building was assessed against the 
following criteria, consistent with this Guide's emphasis on sustainable, future -proof, 
integrable platforms: 
===== PAGE 118 =====
 
110 
 
 
 
• Device-level data: metering at the level of the individual device, at fine time 
resolution, rather than at the floor or zone. 
• Remote, automated control: the ability to switch loads and apply schedules 
without manual intervention or site visits. 
• Intelligent analytics: an engine that learns usage patterns, identifies standby 
waste, and automates occupancy-aware control. 
• Open integration: open communication protocols and APIs so the platform can 
co-exist with existing building systems and feed portfolio -level dashboards, 
avoiding vendor lock-in. 
• Non-intrusive deployment: installation that requires no rewiring or fixed 
electrical works in an occupied building. 
• Security: encrypted communications and independently tested cloud security. 
• Scalability: a cloud, subscription -based model that scales from a floor to a 
building to a portfolio. 
The implementation 
Everest is a full Building Operating System spanning energy analytics, role -based 
access control, occupancy -centric control, calendar and scheduling integration, 
predictive maintenance, ESG and carbon reporting, over -the-air device firmware 
updates, and integration with third-party systems and business-intelligence tools. For 
this particular use case, the focus was on the Volta smart plug-load solution combined 
with the Everest platform. The components used in this deployment are described 
below. 
===== PAGE 119 =====
 
111 
 
 
 
 
Figure 35. The Everest Building Operating System 
The Everest Building Operating System at a glance, spanning device -level analytics, 
role-based access control, trend -logging and energy -savings visualisation, 
occupancy-centric control, calendar and scheduling integration, predictive 
maintenance, and ESG a nd carbon reporting. This case study focuses on the plug -
load energy management capability of the platform. 
Volta Plug (sense and capture) 
Volta Plug is Ecovolt's smart -plug hardware. Installed between a standard socket 
outlet and the equipment it serves, it meters energy consumption in kilowatt -hours at 
the level of the individual device, at per-minute granularity, and can switch its load on 
or off remotely. Because it plugs in rather than being wired in, it provides device-level 
visibility that floor -level metering cannot offer, with no modification to the building's 
electrical installation. 
Everest platform (adaptive action and intelligent insight) 
Everest is the central, cloud-based command layer. It ingests the data from every Volta 
Plug, presents it through dashboards, and applies an AI analytics engine that learns 
each device's usage pattern, identifies standby waste, and recommends and then 
automates occupancy -aware schedules. The before -and-after comparison shown 
later in this case study, including the energy, cost, and carbon figures, is generated 

===== PAGE 120 =====
 
112 
 
 
 
directly by this engine. All of this is available in real time on the cloud-based platform, 
so plug-load behaviour can be reviewed and acted on a per -minute resolution rather 
than waiting for periodic meter reads. 
Scheduling intelligence (calendars and public holidays) 
Beyond fixed weekday and weekend rules, Everest can align its schedules to a 
building's actual calendar of use. The platform integrates with the building owner's 
calendars and event schedules, so that when CDL books a space for an event, or 
leaves it idle, plug-load control can follow the genuine pattern of occupancy rather than 
a static template. Everest also incorporates Singapore's public holiday calendar: on 
gazetted public holidays and the off-in-lieu days that follow them, the platform can treat 
the building as unoccupied by default, extending standby-load removal to days that a 
simple weekday rule would miss. Across a full year, these additional non-working days 
represent further savings headroom beyond the fixed -schedule approach measured 
in this deployment. 
Base (mobile access) 
Base is Ecovolt's mobile application. It gives the facilities team and authorised users 
the same real -time, per-minute data and device control from any location, including 
the ability to override a schedule manually whenever required. Plug -load data and 
control are therefore accessible in real time from both the Everest web platform and 
the Base mobile app. 
Open integration (a Type 3 Smart FM foundation) 
Everest is built on open communication protocols, including BACnet/IP, KNX IP, and 
standard TCP/IP application programming interfaces (APIs). This allows the platform 
to sit alongside, and integrate with, a building's existing systems and a building 
owner's portfolio -level dashboards, consistent with this Guide's emphasis on 
integration across systems and the avoidance of vendor lock -in. Plug -load energy 
management is one use case on this platform; the same open foundation supports 
integration with ACMV, li ghting, and access -control systems, which is central to the 
scale-up and scope expansion described in Step 5. 
===== PAGE 121 =====
 
113 
 
 
 
Security 
Because connected devices and a cloud platform introduce an attack surface, Everest 
encrypts device -to-cloud communications and follows secure cloud practices. All 
network connections are AES 256 encrypted, consistent with the direction of the IMDA 
IoT Cyber Security Guide and CSA's cybersecurity marks. 
Step 3: Adopt Suitable Implementation Model 
For this deployment, a cloud, subscription -based (Software-as-a-Service) model was 
adopted for the Everest platform, with the Volta Plug hardware installed on site. The 
model was chosen for the reasons set out in this Guide: it negates the cost of 
dedicated IT on-premise server infrastructure, making it perfect for both brownfield and 
greenfield buildings. 
Crucially, the installation model was non -intrusive. Because Volta Plug is a plug -in 
device that connects between a standard socket outlet and the equipment it serves, 
installation required no electrical works, no rewiring, and no Licensed Electrical Worker 
(LEW). The devices were fitted by the project team in coordination with the facilities 
team, caused no interruption to building services, and are fully reversible. This 
removed a class of cost, lead time, and disruption normally associated with installin g 
energy-management hardware in an occupied, operational building. 
Implementation framework 
Working with the on-site facilities team, the deployment followed a staged framework 
for installation, measurement, and value capture. 
Stage 1: Baseline measurement (2 Weeks Monitoring) Volta Plug metered the 
selected appliances with no active scheduling in February, establishing the 
equipment's existing consumption and standby profile. This is the "Before" Ecovolt 
period. 
Stage 2: Analysis and scheduling. Everest's analytics engine examined the hourly 
profile and identified a substantial, continuous draw during hours when the space was 
unoccupied. Occupancy-aware schedules were then configured to power down non -
critical equipment outside working hours, with critical loads excluded and manual 
override retained. 
===== PAGE 122 =====
 
114 
 
 
 
Stage 3: Post -deployment measurement (2 weeks). Consumption on the same 
circuits was measured again over a matched 14 -day window in March with the 
schedules active. This is the "After" Ecovolt period. 
Stage 4: Evaluation and scale-up. With the savings validated (Step 5), the schedules 
continue to run in production, and the solution is being extended to further circuits, 
floors, and buildings, and to additional building systems, under continuous review. 
Both measurement windows covered 14 calendar days aligned to the same weekly 
pattern, comprising ten working days and four weekend days, which allows a like-for-
like comparison. 
Stakeholders and roles 
As in any Smart FM deployment, clear identification of roles was central to a smooth 
rollout. The parties and their roles are set out below in Table 13. 
Stakeholder Role in the deployment 
City Developments 
Limited (CDL) 
Building owner, 
sustainability stakeholder 
Provided the site, defined the sustainability outcomes 
the deployment was measured against, and approved 
access to the building's plug-load circuits. 
Ecovolt Technologies 
Solution provider 
Supplied the Volta Plug hardware and the Everest 
platform, installed the plug -in devices, designed the 
schedules, ran the analytics, and produced the before-
and-after measurement. 
On-site facilities 
management team 
Operational stakeholder 
Coordinated access, helped identify which circuits and 
devices were suitable, and confirmed that day -to-day 
operations were not affected. 
Building occupants 
Productivity stakeholder 
The end users of the instrumented equipment, whose 
comfort and daytime productivity the deployment was 
required to preserve. 
Table 13. Stakeholders and their roles in the deployment 
===== PAGE 123 =====
 
115 
 
 
 
Step 4: Review Procurement Contract 
Ecovolt was procured using a hybrid CAPEX –OPEX model, comprising a one -time 
CAPEX for the supply and installation of the hardware, followed by a fixed annual 
subscription covering the AI -powered software platform, cloud hosting, continuous 
monitoring, analytics, feature enhancements, and ongoing software support. 
Compared with a leasing or performance-based (% of savings) commercial model, this 
approach offers several advantages. 
First, the fixed CAPEX and OPEX structure enables customers to accurately evaluate 
the business case and forecast their return on investment. With Ecovolt, customers 
typically see a under 2 years payback period (CAPEX and OPEX included) because 
our solutio n requires no additional cabling, wiring, trunking or any additional 
infrastructure. 
Second, the predictable pricing model provides cost certainty, allowing customers to 
confidently assess the financial impact of scaling deployments across additional areas 
within their existing building or extending the solution across multiple buildings w ithin 
their portfolio after the POC. 
Third, the predictable commercial model enables asset owners to more accurately 
evaluate long -term capital improvements and lifecycle costs. This provides greater 
confidence when assessing portfolio-wide investment decisions, supporting their ESG 
sustainability mandate and quantifying the impact of the energy efficiency initiatives 
on overall asset performance. 
Step 5: Track Outcomes and Review Continuous Improvement 
The results reported in this section are at the granularity of specific areas of a single 
office floor, the scope of this initial deployment. Over the matched 14 -day windows, 
consumption on the monitored plug-load circuits fell from 192.88 kWh to 137.15 kWh, 
a reduction of 55.74 kWh, or 28.9%. Average daily consumption fell from 13.78 kWh 
to 9.80 kWh. 
 
===== PAGE 124 =====
 
116 
 
 
 
Metric Before Ecovolt After Ecovolt Reduction 
Measured over the matched 14-day windows 
Energy consumed (kWh) 192.88 137.15 55.74 (28.9%) 
Average daily energy 
(kWh) 
13.78 9.80 3.98 (28.9%) 
Carbon emissions (kg 
CO₂) 
78.80 56.02 22.77 (28.9%) 
Projected annual, extrapolated from the measured windows 
Energy (kWh per year) 5,029.12 3,575.61 1,453.50 
Carbon emissions (kg 
CO₂ per year) 
2,054.39 1,460.64 593.76 
Table 14. Measured energy reduction, and carbon outcomes, together with the platform's projected annual figures. 
Table 14 summarises the measured energy reduction, and carbon outcomes, together 
with the platform's projected annual figures. Savings are computed from unrounded 
values, so differences between rounded columns may vary by 0.01 in the last place. 
Projected annual figures are extrapolated from the matched 14 -day windows and 
assume they are representative of the full year; actual figures will vary with occupancy 
and seasonal patterns. Carbon emissions is derived using the grid emission factor, 
approximately 0.40 kg CO₂ per kWh respectively. 
===== PAGE 125 =====
 
117 
 
 
 
 
Figure 36. Daily plug-load consumption over the baseline fortnight (Before Ecovolt, upper) and the matched post-
deployment fortnight (After Ecovolt, lower). 
An hour -by-hour analysis of the same data shows where the savings arose. The 
reduction was concentrated in the hours when the office was unoccupied. During 
evenings, nights, and early mornings, plug -load consumption fell by about 85%, as 
standby draw was almost entirely removed. 
During working hours, consumption fell by about 19%, reflecting the automated power-
down of idle equipment during the day, for example over the lunch period, while 
equipment in use continued to operate normally. Table 15 sets out this contrast. 
Period Before 
(kWh/day) 
After (kWh/day) Reduction 
Unoccupied hours (19:00 
to 08:00) 
2.12 0.33 84.5% 
Working hours (08:00 to 
19:00) 
11.65 9.47 18.8% 
All hours 13.78 9.80 28.9% 
Table 15. Average daily plug-load consumption by occupancy period, derived from the hourly data. Transitional hours 
around the start and end of the working day bridge the two bands. 

===== PAGE 126 =====
 
118 
 
 
 
On weekends, when the office was essentially unoccupied, baseline consumption still 
averaged about 3.0 kWh per day, almost all of it standby draw. After deployment, 
weekend consumption fell to about 0.6 kWh per day, a reduction of roughly 80%. 
The overlaid comparison in Figure 3 8 shows the post -deployment profile (green) 
consistently at or below the baseline (red), with the widest gaps on the busiest working 
days and near-complete convergence to very low values on weekends. The aggregate 
energy, cost, and carbon figures are shown in the accompanying panels. 
 
Figure 37. Overlaid daily comparison of the baseline (Before Ecovolt) and post-deployment (After Ecovolt) periods, 
with aggregate energy, cost, and carbon metrics. Charts generated by the Everest platform. 
Outcome: solution scale-up and expanded scope 
With the success of this deployment, two directions are now underway. 
• Scale up. With the savings validated on the initial plug-loads, the solution is being 
extended to further plug -load circuits, additional floors and tenants, and other 
buildings in the portfolio, using the same plug-and-play installation. Because the 
approach needs n o rewiring or LEW, each additional site can be brought on 
quickly and reversibly. Across a portfolio, and including the public holidays and 
off-in-lieu days that a fixed weekday rule would miss, the aggregate savings are 
expected to be substantially larger than those measured on the initial set of 
circuits. 
• Expand scope. Plug-load energy management is one use case on the Everest 
Building Operating System. Building on the same open foundation (BACnet/IP, 
KNX IP, and APIs), the scope is being expanded from plug loads to other building 
systems, including ACMV, lighting, and a ccess control, so that device -level 

===== PAGE 127 =====
 
119 
 
 
 
energy management forms part of a broader, integrated operating picture feeding 
CDL's portfolio-level dashboards. 
Wider benefits for the building owner 
Beyond the immediate savings, the deployment and the wider Everest platform offer 
several capabilities and outcomes relevant to a building owner: 
• Device-level visibility into plug -load consumption that conventional floor -level 
metering does not provide. 
• A non -intrusive method that requires no rewiring and no Licensed Electrical 
Worker, is fully reversible, and preserves occupant comfort and daytime 
productivity. 
• A result achieved with open, integrable technology that scales from a floor to a 
building to a portfolio and feeds a portfolio-level dashboard. 
• A direct contribution to decarbonisation, supporting CDL's sustainability 
commitments and aligning with national objectives under the Singapore Green 
Plan 2030 and BCA's Green Mark. 
• Intelligent scheduling integrations that follow the building's actual calendar of use, 
including CDL's event schedules and Singapore's public holidays and off -in-lieu 
days, so standby waste is also removed on non -working days that a fixed 
weekday rule would miss. 
• Real-time data and control at per -minute, device -level granularity on a cloud -
based platform, accessible from both the Everest web platform and the Base 
mobile app. 
• An attractive commercial case, with projected payback under two years and 
savings that accrue to the owner thereafter. 
Lessons Learnt 
The deployment confirms that plug loads are a real and addressable blind spot in 
commercial office energy management. Device -level metering combined with 
occupancy-aware, automated control reduced consumption on the monitored circuits 
by 28.9% over matched fortnightly windows, with the deepest cuts coming from the 
===== PAGE 128 =====
 
120 
 
 
 
removal of standby waste during unoccupied hours. Several lessons emerged for 
prospective adopters of a similar solution. 
1. The waste is concentrated in unoccupied hours. Targeting evenings, nights, 
and weekends captured the large majority of the savings while leaving daytime 
operations untouched, which is what made the result acceptable to occupants. 
2. A plug-and-play, no-LEW installation removes a major barrier. Because the 
hardware plugs in rather than being wired in, the deployment needed no electrical 
works, no rewiring, and no Licensed Electrical Worker, which made it fast, low -
cost, reversible, and easy to replicate across a portfolio. 
3. Collaboration with the facilities team was essential. Joint selection of circuits, 
exclusion of critical loads, and the availability of manual override allowed the 
deployment to proceed without disruption. 
4. Open protocols matter. Building the platform on BACnet/IP, KNX IP, and APIs 
kept the data accessible, positioned the solution to integrate with the owner's 
wider systems rather than becoming another silo, and made the expansion of 
scope to ACMV, lighting, and access control straightforward. 
5. A measured deployment builds the business case for scale. A matched two-
week baseline and post-deployment measurement were sufficient to quantify the 
benefit and justify the rollout. The natural progression, now underway, is to scale 
across more circuits and buildings and to expand scope to other systems, with 
annual figures confirmed against actual operation rather than projection. 
For building owners and facilities managers, the broader lesson is that granular, 
outcome-based plug-load management complements conventional ACMV and lighting 
controls and contributes to both cost and sustainability objectives. It embodies the 
Smart FM pr inciple of integrating people, process, and technology to remove waste 
without compromising service, and, on the evidence here, does so with a fast payback 
and a clear path to portfolio-wide scale. 
 
 
 
===== PAGE 129 =====
 
121 
 
 
 
Appendix D: Fault Detection & Diagnostics 
In general, the FDD sequence can be illustrated in the flow diagram below. 
 
Figure 38. Fault Detection and Diagnostics flow diagram 
 
Monitoring is a pre-requisite for FDD where it depends heavily on the input from the 
sensors where the type and quality of the monitored data is determined by the method 
used in identifying the faults. 
 
Fault Detection is identifying that a problem has occurred, even if the root cause has 
yet to be identified. Fault may be detected from a single variable (e.g., alarm based on 
high, low, or deviation limits for a process variable ) or multi variables. The fault 
detection method may adopt rule-based algorithm or more advanced techniques such 
as machine learning functions. 
 
Fault Diagnostics is pinpointing one or more root causes of the problems where 
corrective action can be taken. A metadata model following an Open Metadata 
Schema can be developed to facilitate efficient and accurate analytics of the faults and 
reporting of the diagnostics. 
 
Fault Rectification is usually a corrective action to prevent further recurrence of the 
failure, for example through reactive or preventive maintenance activities. It may 
include the use of a Computerized Maintenance Management System (CMMS) to 
track the status of the action either to inspect or fix the fault. 
 
To get started on the journey to use FDD, building owners can make reference to the 
basic parameters that should be monitored for each system in this section. 
Monitoring Fault Detection Fault Diagnostics Fault Rectification
===== PAGE 130 =====
 
122 
 
 
 
 
1. Chiller plant 
 
Main Equipment 
 
BMS monitoring points 
Individual Equipment Level Plant Level 
Chillers 
Chilled water 
and condenser 
water pumps 
Cooling 
Towers 
Chilled water 
and condenser 
water headers 
Running status (on /off) √ √ √ 
Control valve (open / close) √ √ √ 
Bypass valve (open / close) √ 
VSD √ √ 
Selector switch mode 
(auto / manual / off) √ √ √ 
Trip alarm √ √ √ 
Chilled water supply 
temperature √ √ 
Chilled water return 
temperature √ √ 
Condenser water supply 
temperature √ √ 
Condenser water return 
temperature √ √ 
Chilled water flowrate √ √ 
Condenser water flowrate √ √ 
Electrical current √ √ √ 
Electrical voltage √ √ √ 
Electrical consumption √ √ √ 
Electrical breaker status 
(on / off / trip) √ √ √ 
Differential pressure √ chilled water header only13 
Running time √ √ √ 
Individual chiller's internal 
operating parameters, e.g. 
running state, refrigerant 
pressure, saturated 
refrigerant temperature, 
discharge temperature, oil 
pressure and temperature14 
√ 
Table 16. Chiller plant – BMS monitoring points 
 
 
Electrical – Motor Control Centre (MCC) Panel 
• Incoming supply breakers status (on / off / trip) 
 
13 Differential pressure sensor is also required within chilled water system to regulate the pumps 
14 These are available via the BACnet or Modbus communication interface of a chiller 
===== PAGE 131 =====
 
123 
 
 
 
• Outgoing breakers status (on / off / trip) 
• Bus coupler status (on / off / trip) 
Others 
• Refrigerant leak detector 
• Condensate water quality 
• Chemical treatment pump status (on / off) and trip alarm 
• Make-up water tank level alarm (low / mid / high / emergency high / 
overflow) 
• Make-up water pump status (on / off) and trip alarm 
• Weather-station 
 
2. Air Distribution System 
 
Air Conditioning Equipment 
BMS monitoring points Fan coil unit Pre-cooled air handling unit (PAHU) Air handling unit (AHU) 
Running status (on /off) √ √ √ 
Control valve (open / close) √ √ √ 
VSD √ √ 
Selector switch mode 
(auto / manual / off) √ √ √ 
Off coil temperature √ √ 
Air damper position (open / 
close) √ √ 
Trip alarm √ √ √ 
Smoke detector alarm √ √ 
Primary filter differential 
pressure √ √ 
Secondary filter differential 
pressure √ √ 
Chilled water supply 
temperature √ √ 
Chilled water return 
temperature √ √ 
Chilled water flowrate √ √ 
Return air temperature √ √ 
Duct pressure sensor √ √ variable air volume only 
===== PAGE 132 =====
 
124 
 
 
 
BMS monitoring points Fan coil unit Pre-cooled air handling unit (PAHU) Air handling unit (AHU) 
Variable air volume (VAV) 
box √ variable air volume only 
Carbon dioxide sensor √ 
Electrical consumption √ √ √ 
Running time √ √ √ 
Table 17. Air Conditioning Equipment – BMS monitoring points 
Mechanical Ventilation Equipment 
BMS monitoring points Fresh air and exhaust fans Carpark MV and jet fans 
Running status (on /off) √ √ 
VSD √ √ 
Selector switch mode (auto / 
manual / off) 
√ √ 
Trip alarm √ √ 
Carbon monoxide sensor √ 
Electrical consumption √ √ 
Running time √ √ 
Table 18. Mechanical Ventilation Equipment – BMS monitoring points 
3. Electrical System 
Transformer 
• Temperature alarm 
• Trip alarm 
Low tension main switchboard 
• Incoming supply breakers status (on / off / trip) 
• Power consumption – incoming supply 
• Outgoing breakers status (on / off / trip) 
• Power consumption – outgoing supply 
• Bus coupler status (on / off / trip) 
• Automatic Transfer Switch 
 
 
 
 
===== PAGE 133 =====
 
125 
 
 
 
Standby generator 
• Running status (on / off) 
• Trip alarm 
• Selector switch mode 
• High temperature alarm 
• Diesel day tank high level alarm 
• Diesel day tank low level alarm 
• Battery status 
• Circuit breaker status (on / off / trip) 
Sub – switchboard and distribution board 
• Incoming supply breakers status (on / off / trip) 
• Power consumption – incoming supply 
• Lighting status (on / off) 
 
4. Plumbing and Sanitary System 
Plumbing – Domestic water system 
• Transfer pump and booster pump running status (on / off) 
• Transfer pump and booster pump trip alarm 
• Transfer pump and booster pump power consumption 
• Transfer pump and booster pump selector switch mode (auto / manual / off) 
• Transfer tank and storage tank level alarm (low / mid / high / emergency high / 
overflow) 
Sanitary – Ejector system 
• Ejector and sump pump running status (on / off) 
• Ejector and sump pump trip alarm 
• Ejector and sump pump power consumption 
• Ejector and sump pump selector switch mode (auto / manual / off) 
• Ejector tank level alarm (high / overflow) 
 
 
 
===== PAGE 134 =====
 
126 
 
 
 
5. Escalator System 
 
• Number of passengers 
• Handrail speed 
• Handrail direction 
• Step speed 
• Step direction 
• Bearing temperature 
• Running time 
• Power consumption 
• Running current 
 
6. Lift System 
 
Essential parameters to be monitored 
Type Parameters 
Real time 
Car Speed 
Car Acceleration/Deceleration 
Car Jerk 
Car Vibration (x, y and z direction) 
Door Speed 
Door Opening 
Door Fully Opened 
Door Closing 
Door Fully Closed 
Stopping Accuracy (Lift levelling accuracy) 
Aggregate 
Lift Car Mileage 
Lift Car Running Hours 
Lift Car Start/Stop 
Lift Door Opening/Closing Cycles 
Events Lift in Normal mode 
Table 19. Essential parameters to be monitored 
Additional parameters to be monitored 
Type Parameters 
Real time 
Hoisting Rope Elongation 
Lift Car Overload 
Lift Car Lighting 
Lift Car Ventilation 
Lift Car Alarm Bell 
===== PAGE 135 =====
 
127 
 
 
 
Door Protective Device 
Faults 
Safety Circuit Breakage NOTE 
Unintended Car Movement 
Lift Out-of-Service 
Events Lift in Fire Emergency mode Lift in Power Failure Emergency Operation 
Table 20. Parameters to be monitored 
7. Monitoring parameters from Case Study C2 
 
Fire Extinguishers 
• Presence of fire extinguisher 
• Pressure 
• Frontal obstruction 
• Presence of foreign objects on fire extinguisher 
 
Exit Lights 
• Lamp failure 
• Battery lifespan for 1 hour operation 
 
 
 
===== PAGE 136 =====
 
128 
 
 
 
 
Appendix E: Decision Template for 5 -Step SMART 
Process 
The table below summarises the key questions Building Owners and FM Managers 
should ask and consider when going through each of the 5-step SMART Process. 
5-step SMART Process What Should Building Owners and FM Managers Consider 
Step 1 
Set business objectives 
and outcomes 
• What are my top 3 business objectives? 
• What do I want to achieve and set as my desired FM 
outcomes, based on my business objectives and issues 
faced? 
• What corresponding KPIs can I set to monitor the progress 
of my desired FM outcomes? 
• Which FM services should I prioritise to address the desired 
FM outcomes? 
• Can I streamline my current FM processes and 
procurement framework to meet the identified business 
objectives and desired FM outcomes? 
 
Tool to use 
Table 1: Template to rank business objectives, set desired FM 
outcomes, and determine high-priority FM services to focus on 
 
Step 2 
Map out Smart FM 
Solutions as enablers 
• What type of "smartness" (Type 1, Type 2, or Type 3) is 
each high-priority FM service currently at? 
• What type of "smartness" do I want to achieve for each high-
priority FM service? Is it aligned with my business 
objectives and desired FM outcomes? 
• What are my pain points and gain points for each high -
priority FM service? 
===== PAGE 137 =====
 
129 
 
 
 
5-step SMART Process What Should Building Owners and FM Managers Consider 
• Do the technology solutions proposed by the FMCs and 
Service/ Solution Providers fit the requirements to achieve 
my desired FM outcomes? 
• How would I like to engage the building occupants and 
visitors? 
• Are there FM services that could be integrated to provide 
multi-functional and enhanced outcomes, e.g. connected 
lighting systems? 
• Are there areas where aggregation can be done to achieve 
economies of scale – at demand and/or supply side? 
• Is it advantageous to aggregate demand across a portfolio 
of buildings? 
Tool to use 
Table 2: Smart FM Framework 
References 
• Appendix A: List of Smart FM Point Solutions 
• Appendix B: Facilities Management Consortium Operation 
& Technology Roadmap (COTR) 
 
Step 3 
Adopt suitable 
implementation model 
• What is my current working model for existing FM processes 
and services? 
• How would I like to work with my FMCs or Service/ Solution 
Providers? 
• Which implementation model is more viable at this point to 
incorporate the various technology solutions identified in 
Step 2? Or would phased adoption or a variation or hybrid 
of the implementation models be more applicable? 
• Does the selected implementation model meet my business 
objectives, operational priorities and desired FM outcomes? 
===== PAGE 138 =====
 
130 
 
 
 
5-step SMART Process What Should Building Owners and FM Managers Consider 
• Do I own all the data, regardless of the type of 
implementation models selected? 
• Are the system and/or technical requirements specified 
within my procurement contracts adequate? 
 
References 
• IMDA and PDPC's Trusted Data Sharing Framework 
(https://www2.imda.gov.sg/news-and-events/Media-Room/Media-
Releases/2019/Enabling-Data-Driven-Innovation-Through-Trusted-
Data-Sharing-In-A-Digital-Economy) 
Step 4 
Review procurement 
contract 
• What system or technical requirements should I take note 
of and incorporate within the procurement contract? 
• Have my technical specifications for the Smart FM solutions 
taken into consideration the various stakeholders' 
requirements? 
• Does my organisation's procurement framework enable an 
outcome-based contract? 
• What are the outcome-based measurement, incentives and 
penalty for each FMC or Service/ Solution Provider? 
• Can I work together with the FMCs or Service/ Solution 
Providers to adopt a longer contract term? 
• Can the FMCs or Service/ Solution Providers optimise 
delivery of their services and solutions if I aggregate 
demand across my portfolio of buildings? 
• Can I aggregate demand within a building and/or across my 
portfolio of buildings through an Integrated FM contract? 
 
Step 5 
Track outcomes and 
review for continuous 
improvement 
• Has the adopted Smart FM technology solution been well 
implemented and integrated within my existing FM 
processes and systems? 
• Has it addressed the business objectives and desired FM 
outcomes earlier identified in Step 1? 
===== PAGE 139 =====
 
131 
 
 
 
5-step SMART Process What Should Building Owners and FM Managers Consider 
• What are the tangible benefits and issues of each adopted 
solution? 
• Are there areas for improvement that can be taken into 
consideration when adopting other Smart FM solutions in 
the future? 
• Have the business objectives, desired FM outcomes and 
high-priority FM services changed? 
• Are there new technology solutions in the market that can 
span across various FM services and better meet my 
needs? 
• Do the high -priority FM services need to be changed to 
other types of "smartness"? 
• Do I need to review and change the outcome -based 
measurements to better meet the needs/ requirements of 
various stakeholders? 
 
Table 21. The 5-step SMART process – summary of what Building Owners and FM Managers should consider 
 
 
===== PAGE 140 =====
 
132 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
*Choose 3 only 
Business Objective Desired FM Outcome and Corresponding KPI 
☐ Cost e.g. To reduce operating cost by 10% by 2021 
☐ Manpower (Internal/External) 
☐ System Reliability 
☐ Productivity 
☐ Customer satisfaction 
☐ Security requirements 
☐ Others, please specify: 
 
*Identify FM solutions (e.g. Company A Solution - video analytics) to meet business objective and outcome 
*Classify FM solutions into Category 1/2/3 (type not in order of merit) 
 
 
 FM Services 
Towards Aggregation Implementation across cluster 
of buildings 
e.g. M&E 
Functions 
e.g. Security e.g. Cleaning 
Services 
Others, please 
specify: 
 
 
 
☐ Yes ☐ No 
 
Type 1: Digitalised 
workflow automation 
e.g. BCA Smart 
Chiller Portal 
e.g. Company A 
Solution 
 
Type 2: Optimisation 
within system only 
 e.g. Company B 
Solution 
 
Type 3: Integration/ 
Synergy across system 
 
 
 
 
 
 
 
 
 
Aggregation Feasibility: ☐ Yes ☐ No 
 
 
Status: ☐ Behind ☐ On Track ☐ Ahead 
 
Areas for further improvement/ Proposed recommendation: _____ 
 
Any new/emerging smart FM technology: ☐ Yes ☐ No 
If yes, please specify: ____ 
 
Integrated FM contract for all chosen FM services: 
☐ Yes ☐ No, please specify FM services excluded: ________ 
 
Adopt outcome/performance based contract(recommended) 
☐ Yes ☐ No 
 
FM Services Contract Term (recommended 5 to 10 years): 
☐ 3+3 ☐ 5+5 ☐ 8 ☐ Others: _______ 
 
 
 *Sample chart to track outcome KPI 
*Repeat this step for remaining business objectives and outcomes 
 
7,846,294 
7,428,040 
7,318,877 
7,243,416 6,500,000
 6,800,000
 7,100,000
 7,400,000
 7,700,000
 8,000,000
Year 0 Year 1 Year 2 Year 3
Electricity Consumption (kWh)
R 
T 
A 
M 
S 
SET BUSINESS OBJECTIVES & OUTCOMES 
 
MAP OUT FM SOLUTIONS AS ENABLERS 
 
ADOPT SUITABLE IMPLEMENTATION MODEL 
 
*Classify FM solutions into Model A/B 
Implementation Model to Adopt FM Solutions 
Model A: Integrated Smart FM Solutions 
(Each smart FM solution feeds data into one centralised 
system) 
☐ Solution as a Service via FMC 
☐ Acquired & Operated by Building Owner 
e.g. BCA Smart Chiller Portal, Company A Solution 
Model B: Single Smart FM Solutions 
(Multiple smart FM solutions with multiple platforms to use) 
 REVIEW PROCUREMENT CONTRACT 
TRACK OUTCOMES AND REVIEW FOR CONTINUAL IMPROVEMENT 
 
===== PAGE 141 =====
 
133 
 
 
 
 
Cost-Benefit Analysis Table 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
Business 
Objectives 
and Desired 
FM Outcomes 
Smart FM 
Solutions 
Adopted 
Upfront 
Developmental 
Costs (A) 
Recurring or Yearly 
Maintenance Costs (B) 
Total Cost 
of 
Ownership/ 
Life Cycle 
Cost 
(A+B) 
Annual 
Benefit 
Total Benefit 
Over 
Entire Life 
Cycle 
Feasibility Study 
Recommendation 
 
 
 Year 
0 
Year 
1 
Year 
2 
Year 
3 
Remaining 
Years 
#1: e.g. To 
reduce 
electricity cost 
by 20% 
e.g. Chiller 
plant 
optimisation 
 
e.g. Smart 
lighting with 
occupancy 
sensors 
 
#2: Please 
specify 
 
#3: Please 
specify 
 
===== PAGE 142 =====
 
134 
 
 
 
Appendix F: Essential Smart FM Use Cases 
Smart FM leverages technology and data to enhance the efficiency and effectiveness of facility management processes. The table 
below shows a non-exhaustive list of Smart FM use cases and its definition. 
Smart FM Use Cases Definition 
Workflow automation and 
task assignment 
Automated workflow system for FM-related work orders to automate existing work processes and 
enhanced efficiency of service delivery. Faults and issues are documented, tracked, and routed to 
the respective service agents. 
Energy/power monitoring 
system 
A digital system to monitor, benchmark (actual vs target), and report energy usage of a building 
broken down by major energy-consuming sub-systems to identify and flag unexpectedly high or low 
energy usage. 
ACMV energy optimisation 
system 
A digital system to monitor, analyse, and modify control settings by taking into consideration of 
occupancy pattern, weather forecast, etc to achieve the optimum energy usage while maintaining 
occupant comfort. 
Lighting monitoring and 
control 
A digital system to monitor and control the lighting (switch on/off or change levels of light) within 
specific areas based on inputs such as movement, IR radiation or sound to deliver a comfortable 
user experience while reducing energy usage. 
Renewable energy 
monitoring and tracking A digital system to monitor renewable energy generated and consumed on site. 
Greenhouse gas (GHG) 
emissions monitoring and 
tracking 
A digital system that enhances GHG data availability, identifies opportunities for GHG reduction, 
and supports the achievement of GHG reduction targets over time. 
Fault Detection and 
Diagnostics of ACMV system 
A digital system to monitor and automate the process of detecting faults and suboptimal 
performance of building ACMV systems. The solution usually provides several possible causes or 
recommendations for correcting each fault. 
Fault Detection and 
Diagnostics of lifts, 
escalators, or other 
equipment 
A digital system to monitor and automate the process of detecting faults and suboptimal 
performance of lifts, escalators, and other equipment. 
Water monitoring & leakage 
detection 
A digital system to monitor, benchmark (actual vs target), and report water usage of a building to 
identify and flag unexpectedly high or low water usage. 
Water tank level monitoring A digital system to monitor the levels of water tanks remotely without any physical human efforts such as manual meter reading and assessments. 
Indoor Air Quality monitoring A digital system to monitor, benchmark, report, and control the indoor air quality of the regularly occupied spaces to empower occupants & FM team about their environmental quality. 
Thermal comfort monitoring 
A digital system to monitor thermal comfort parameters (e.g. dry-bulb temperature and relative 
humidity) in the regularly occupied spaces that can be used as feedback for facility manager and 
users to take appropriate actions. 
Smart Toilet An advanced toilet system equipped with electronic features and technologies designed to enhance comfort, hygiene, and convenience. 
Space Optimisation A digital system to track and reports space utilisation to help FM teams optimise space use and/or adjust maintenance services. 
Remote tree monitoring A digital system to monitor any sign of tree failures in the urban area (e.g. using electronic tilt sensor). 
Bin status monitoring A digital system that tracks the waste fill levels of bins to optimise collection schedules and improve the efficiency of manpower and deployment 
Fire alarm monitoring A digital system to monitor any sign of temperature spike to trigger alert for inspection. 
Smart Fire Safety and 
Emergency Platform 
An integrated digital system designed to enhance fire safety and emergency response through 
advanced technology (e.g., to electronically monitor and manage the operational status of fire 
extinguishers and exit lights) 
Incident monitoring A digital system that uses tools like video analytics to detect and identify incidents, enabling timely response, impact mitigation, and analysis to prevent future occurrences. 
Tenancy management A digital system to digitalise leasing processes for better control and management of rental properties under its portfolio. 
Foot traffic monitoring 
A digital system to monitor the number of people who walk into or around a given area at a specific 
time (e.g. using wifi analytics) for business owners and retail store owners to evaluate or measure 
the effectiveness and value of a commercial facility. 
Cleaning Robot An autonomous or semi-autonomous machine designed to perform cleaning tasks without the need for constant human intervention. 
Security Robot An autonomous or semi-autonomous machine designed to enhance security by monitoring and patrolling specific areas. 
Drone for Facade and/or 
Rooftop Inspection 
An unmanned aerial vehicle (UAV) specifically designed to inspect and assess the condition of 
building facades and rooftops. 
Condition-based 
Maintenance 
A proactive maintenance strategy that involves performing maintenance tasks based on the actual 
condition of equipment or systems, rather than on a predetermined schedule. 
Table 22. List of essential Smart FM use cases 