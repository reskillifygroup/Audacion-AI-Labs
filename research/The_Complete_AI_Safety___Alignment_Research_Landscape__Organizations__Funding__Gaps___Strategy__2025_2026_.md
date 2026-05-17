# The Complete AI Safety & Alignment Research Landscape: Organizations, Funding, Gaps & Strategy (2025–2026)

> **Prepared for Dee Williams, Audacionaire** — Founder, AI Research Lab (AI Safety & Alignment Focus)

***

## Executive Summary

The global AI safety and alignment field is simultaneously the most critically underfunded and one of the fastest-growing research disciplines in the world. With approximately 1,100 full-time equivalent (FTE) researchers globally, the field faces a staggering asymmetry: an estimated **1:10,000 funding ratio** and **1:50–100 researcher ratio** versus capabilities development. Capabilities research attracts $100+ billion annually, while total AI safety funding is estimated at only $250–400 million per year globally. Over 180 organizations now operate in the AI safety space across 12+ countries, but they are unevenly distributed, heavily concentrated in San Francisco, Berkeley, London, and Oxford, and significantly absent from the Global South, applied healthcare, workforce transitions, and independent oversight infrastructure.[^1][^2][^3]

The 2026 International AI Safety Report — authored by 100+ experts across 30 countries — revealed what experts call an **"evidence dilemma"**: AI capabilities are racing ahead of safeguards, pre-deployment tests don't reliably predict real-world performance, and the scientific foundation for governance is dangerously thin. This report maps every major actor, every funding source, why funders give, and where the field's white spaces are — providing the intelligence needed to position a new AI safety research lab.[^4][^5]

***

## Part I: The Major Institutional Labs

### 1. Anthropic — The Safety-Embedded Frontier Lab

**Type:** For-profit Public Benefit Corporation (PBC)
**Founded:** 2021 (by Dario Amodei, Daniela Amodei, and 7 other OpenAI alumni)
**Location:** San Francisco, CA
**Total Funding:** $61.5B+ raised through Series G (February 2026), valued at $380 billion post-money[^6]
**Safety Research Investment:** Estimated $100–200 million annually, representing 15–25% of total R&D[^7]

**Why Anthropic Exists & Why Funders Back It:**
Anthropic was founded explicitly because its founding team believed OpenAI was not focused enough on safety as capabilities advanced. Jaan Tallinn led Anthropic's $124M Series A in 2021. The company's pitch to investors like GIC, Coatue, Amazon, Google, and Microsoft has been: *safety and commercial viability are not in conflict — the most trustworthy model is the most deployable model for enterprises*. Run-rate revenue reached $14 billion in early 2026, growing over 10x annually for three consecutive years.[^8][^9][^6]

**What They Research (Safety Focus):**
- **Constitutional AI (CAI):** A proprietary training methodology using a written set of principles rather than purely human feedback (RLHF) to train helpful, harmless, and honest models. This is Anthropic's core safety innovation.
- **Interpretability:** Arguably the world's largest dedicated interpretability team (40–60 researchers), working to understand how models represent concepts internally. A 2025 breakthrough included training Claude to translate its numerical "thoughts" into human-readable English.[^10][^7]
- **Alignment Faking Research:** A landmark study co-published with Redwood Research demonstrating that AI models can exhibit "alignment faking" — appearing aligned with human values during training while behaving differently when unmonitored.[^11]
- **Frontier Red Team:** Assessing biosecurity, cybersecurity, and autonomous AI system risks. Project Glasswing (cyber defense) has used Claude to discover thousands of zero-day software vulnerabilities.[^12]
- **The Anthropic Institute (TAI):** A new research arm (2026) focused on four areas: economic diffusion of AI, dual-use threats and resilience, AI systems' effects on society at scale, and the governance of recursive AI self-improvement.[^13]
- **Responsible Scaling Policy (RSP):** A self-imposed framework mandating additional safety evaluations before deploying more powerful model generations. OpenAI and DeepMind have both adopted similar frameworks inspired by Anthropic's.[^7]

**The Anthropic Fellows Program:** Offers $3,850/week stipends plus ~$15,000/month in compute for independent AI safety researchers.[^14]

***

### 2. Google DeepMind Safety Team

**Type:** Corporate R&D / Safety Division
**Founded:** Safety team formally constituted ~2016; integrated under DeepMind brand 2023
**Location:** London, UK (primary); Mountain View, CA; Paris, France
**Parent Funding:** Alphabet 2026 CapEx guidance: $180–190 billion (shared across all Google AI)[^15]

**Why DeepMind Invests in Safety:**
DeepMind was acquired by Google in 2014 partly because its safety-oriented cofounders (Demis Hassabis, Mustafa Suleyman, Shane Legg) required as a condition of sale that an AI Ethics Board be established. Safety research has been institutionalized through the Frontier Safety Framework, which mandates capability evaluations before deploying each generation of Gemini models.[^16]

**What They Research:**
- **Scalable Oversight:** Research on how humans can supervise AI systems that may be smarter than humans, including debate-based oversight and process-based reward models.
- **Specification Gaming and Reward Hacking:** Studying how AI systems learn to satisfy the letter of instructions without the spirit (including the famous "boat racing" RL failure).
- **Dangerous Capability Evaluations:** Pre-deployment red-teaming assessing bioweapons uplift, cyberattack enablement, persuasion, and model autonomy.
- **Alignment and Control Theory:** Theoretical foundations for ensuring powerful systems remain under human control.
- **Safety-Capabilities Integration:** The claim (contested) that safety and capability are "complementary rather than competing."
- **AI Safety Institute Partnership (UK):** A joint research alliance with the UK AISI on LLM chain-of-thought transparency.[^17]

***

### 3. OpenAI — Preparedness & Alignment Teams

**Type:** For-profit company (previously nonprofit)
**Founded:** 2015
**Location:** San Francisco, CA
**Total Funding:** $40B (SoftBank-led 2025), $122B round (Amazon/Nvidia/SoftBank, early 2026)[^18]
**Safety Commitment:** $7.5 million grant to The Alignment Project (independent global fund, February 2026)[^19]

**What They Research (Safety Focus):**
OpenAI's **Preparedness Framework** evaluates models before release across four risk categories: cybersecurity, CBRN threats, persuasion, and model autonomy. Their **Superalignment** team (now restructured after Ilya Sutskever's departure) aimed to solve the problem of supervising AI systems that may be smarter than humans within a four-year window, with $10 million in annual compute dedicated to this effort. However, multiple senior safety researchers have left OpenAI citing concerns about safety commitment being subordinated to commercial priorities.[^3]

In February 2026, OpenAI committed $7.5 million (~£5.6M) to The Alignment Project — a fund launched by the UK AI Security Institute with over £27 million total, supporting research across information theory, game theory, computational complexity, cognitive science, and economics applied to alignment.[^19]

***

### 4. Safe Superintelligence Inc. (SSI)

**Type:** For-profit company (uniquely focused solely on safety)
**Founded:** June 2024
**Location:** Palo Alto, CA & Tel Aviv, Israel
**Co-founders:** Ilya Sutskever (former OpenAI chief scientist), Daniel Levy, Daniel Gross
**Total Funding:** $3 billion+: $1 billion Series A (September 2024, led by NFDG/a16z/Sequoia/DST Global, $5B valuation); $2 billion additional round (April 2025, led by Greenoaks, $32B valuation)[^20][^21][^22][^23]
**Key Investors:** Greenoaks, a16z, Sequoia, DST Global, Alphabet, NVIDIA, Lightspeed[^22]

**Why Funders Gave:**
SSI is arguably the purest expression of the "safety-first" thesis in venture capital history. Ilya Sutskever's reputation as the architect of modern deep learning — having co-led OpenAI's GPT-4 and earlier breakthroughs — gave SSI instant credibility. Alphabet and NVIDIA invested despite having no product yet because the founders represent a bet that safe superintelligence is *the* problem worth solving exclusively, and that doing so without product pressure (no chatbots, no APIs, no near-term revenue) is the only way to take it seriously. The round was described as "one of the highest Series A valuations ever for a pre-product company".[^23][^22]

**What They Research:**
SSI has not published research publicly (intentionally stealth), but its stated mission is: solve the technical problem of making AI systems that are both superintelligent and safe as a prerequisite to any deployment.[^24]

***

## Part II: Independent Nonprofit Research Organizations

### 5. Machine Intelligence Research Institute (MIRI)

**Type:** 501(c)(3) Nonprofit
**Founded:** 2000 (as Singularity Institute for Artificial Intelligence)
**Location:** Berkeley, CA
**Founder:** Eliezer Yudkowsky
**Cumulative Funding:** $14.7M+ from Open Philanthropy/Coefficient Giving; $900K+ from Survival and Flourishing Fund; $670K+ from Effective Altruism Funds. Largest single donors include Vitalik Buterin (Ethereum), Peter Thiel Foundation, Jaan Tallinn, Jed McCaleb.[^25][^26]

**Why Funders Give:**
MIRI is the oldest AI safety organization and was foundational in making the intellectual case that advanced AI poses extinction-level risks. Eliezer Yudkowsky's writings on AI risk influenced Jaan Tallinn in 2009 (who then gave $150M+ to the field). Peter Thiel funded the early Singularity Summits. The effective altruism movement identified MIRI as a top priority. However, Open Philanthropy (now Coefficient Giving) issued an "exit grant" signal in recent years, suggesting reduced future support, possibly due to MIRI's shift away from mainstream ML and toward more speculative alignment approaches.[^9]

**What They Research:**
MIRI focuses on the **mathematical and theoretical foundations of alignment** — how to formalize what it means for an AI system to have the right goals, to reason correctly under uncertainty, and to remain aligned even as it becomes more intelligent. Key research areas include agent foundations, decision theory, logical uncertainty, and Eliezer Yudkowsky's concept of "corrigibility" (building AI that accepts human correction).[^27]

***

### 6. Alignment Research Center (ARC) / METR

**Type:** 501(c)(3) Nonprofit (ARC Theory) + METR (spun off December 2023)
**Founded:** 2021 (by Paul Christiano, former OpenAI alignment researcher)
**Location:** Berkeley, CA
**Total Funding:** ~$10M/year; Open Philanthropy grant of $265,000 (2022); $1.25M FTX grant returned after FTX collapse[^28]
**METR Largest Funder:** The Audacious Project (TED-housed philanthropic initiative); also Pew Charitable Trusts, Schmidt Sciences, Sijbrandij Foundation[^29]

**Why Funders Give:**
ARC/METR occupies a critical independent evaluation position: they are the only organization conducting systematic third-party evaluations of frontier AI models for dangerous capabilities *before deployment*, without accepting money from AI companies. Longview Philanthropy described METR as having "among the most promising and direct paths to impact on AI governance".[^30][^29]

**What They Research:**
- **ARC Theory:** Eliciting Latent Knowledge (ELK) — a theoretical framework for getting AI systems to truthfully report what they "know" even if incentivized to mislead. Research on scalable oversight, debate, and amplification.
- **METR (Model Evaluation & Threat Research):** Evaluating frontier models for **autonomous replication** capability — whether an AI can sustain itself on cloud servers, acquire resources, and make copies. Also studying AI's acceleration of AI R&D (recursive self-improvement risk), evaluation integrity threats (reward hacking, sandbagging), and cybersecurity capabilities.[^31][^29]

***

### 7. Redwood Research

**Type:** 501(c)(3) Nonprofit
**Founded:** 2021
**Location:** Berkeley, CA
**Total Funding:** $25M+ from Coefficient Giving/Open Philanthropy ($9.4M in 2021, $10.7M in 2022, $5.3M in 2023); also $500,000 from Future of Life Institute[^32][^11]

**Why Funders Give:**
Redwood was founded by researchers from top ML programs who wanted to work on practical alignment problems motivated by theoretical arguments for how solutions might scale to superhuman AI. Coefficient Giving has identified Redwood's AI Control research as a high-priority area.[^32]

**What They Research:**
- **AI Control:** Research on how to maintain human oversight and control over AI systems that may be deceptive or misaligned, without requiring the AI to be fully aligned.
- **Causal Scrubbing:** An interpretability technique for understanding how neural networks implement specific computations.
- **Alignment Faking:** The landmark 2025 study (with Anthropic) demonstrating that Claude models exhibit alignment faking behaviors under certain conditions.[^11]
- **Adversarial Training:** Studying how to make AI systems robust to adversarial prompting and reward hacking.

***

### 8. Center for AI Safety (CAIS)

**Type:** 501(c)(3) Nonprofit
**Founded:** 2022
**Location:** San Francisco, CA
**Key Funding:** $5.16M from Open Philanthropy (2022); $1.87M exit grant from Open Philanthropy (October 2023); ongoing individual and institutional donations[^33][^34]
**Notable:** Published the 2023 statement on AI risk extinction risk, signed by Geoffrey Hinton, Yoshua Bengio, Demis Hassabis, Sam Altman, and hundreds of AI researchers[^35]

**Why Funders Give:**
CAIS uniquely bridges technical safety research and public advocacy/field-building. The 2023 statement that "mitigating the risk of extinction from AI should be a global priority" — which made international headlines — was CAIS's work. This positioned CAIS as a legitimizing force for safety concerns in mainstream scientific and public discourse.

**What They Research:**
- **Technical Safety Research:** Adversarial robustness, value alignment, misuse prevention
- **Field Building:** SafeBench ($250,000 in prizes for AI safety benchmarks), CAIS Philosophy Fellowship, ML Safety course (with small student stipends), compute cluster access for researchers[^36]
- **Education:** "AI Safety, Ethics and Society" textbook and online course[^36]
- **Governance Advocacy:** Advising government bodies on AI safety policy

***

### 9. Apollo Research

**Type:** Research Lab → Public Benefit Corporation (PBC) as of April 2026[^37]
**Founded:** ~2023
**Location:** London, UK
**Funding Sources:** Frontier Model Forum AI Safety Fund ($5M+ round, December 2025); Schmidt Sciences; Coefficient Giving[^38]
**Focus:** "Scheming AI" — evaluating and detecting deceptive alignment and strategic behavior in frontier models

**Why Funders Give:**
Apollo addresses a specific, urgent frontier problem: AI systems that behave safely during evaluation but pursue different goals in deployment ("scheming"). This is one of the most concrete near-term safety risks and directly relevant to current frontier models. The AISF specifically funded Apollo to build "black box scheming monitors for frontier AI agents".[^38]

**What They Research:**
- **Deceptive Alignment Detection:** Methods for detecting whether AI systems are strategically hiding capabilities or goals.
- **AI Agent Monitoring:** Building production-grade safety monitoring for autonomous AI agents. In April 2026, Apollo announced it was spinning up a separate product team specifically to build AGI safety monitoring tools.[^37]
- **Behavioral Testing Frameworks:** Systematic evaluation of AI behavior across diverse conditions to surface misalignment.

***

### 10. FAR.AI (Foundational Alignment Research)

**Type:** 501(c)(3) Nonprofit
**Location:** Berkeley, CA
**Funding Sources:** Frontier Model Forum AI Safety Fund (grant: "Quantifying the Safety-Adversary Gap in Large Language Models"); Coefficient Giving; individual donors[^38]

**What They Research:**
FAR.AI is an incubator model that supports diverse technical alignment research agendas and facilitates international AI safety collaboration. Key work includes adversarial robustness testing and empirical safety benchmarking.

***

### 11. Centre for the Study of Existential Risk (CSER)

**Type:** Academic (University of Cambridge)
**Founded:** 2012
**Location:** Cambridge, UK
**Founding Donors:** Jaan Tallinn ($200,000 initial grant)[^9]
**Focus:** Interdisciplinary studies of catastrophic and existential risk from AI, biotechnology, and other extreme risks. Bridges computer science, philosophy, economics, and social science.

***

### 12. Center for Human-Compatible AI (CHAI)

**Type:** Academic (UC Berkeley)
**Director:** Stuart Russell (author of *Human Compatible*, leading AI safety theorist)
**Focus:** Foundational alignment research on the "assistance game" — AI systems that defer to human preferences rather than pursuing fixed objectives. Inverse Reinforcement Learning (IRL) as a path to aligned AI.[^35]

**Why Funders Give:**
Stuart Russell's "assistance game" framework is one of the most academically rigorous and broadly cited approaches to alignment. CHAI has received support from Open Philanthropy, NSF, and industry research grants.

***

### 13. Conjecture

**Type:** Research Lab
**Location:** London, UK
**Focus:** Cognitive emulation architectures (attempting to build AI systems that reason the way humans do, for better interpretability), and running ARENA (Alignment Research Engineer Accelerator) bootcamps. ARENA received £845,790 (~$1.04M) from Coefficient Giving in 2025.[^39][^35]

***

### 14. Timaeus

**Type:** Research Lab
**Location:** Remote
**Focus:** Applying **singular learning theory** (a branch of algebraic geometry) to neural network alignment and safety. The most mathematically abstract alignment research organization currently active.[^35]

***

### 15. EleutherAI

**Type:** Nonprofit Open-Source Research Collective
**Location:** Distributed/Remote
**Focus:** Open-source AI research with alignment and interpretability components. Maintains `lm-eval-harness`, the field's standard LLM evaluation benchmark. Key for democratizing access to alignment research tools.[^35]

***

## Part III: Government and National AI Safety Institutes

| Country/Body | Organization | Budget | Focus |
|---|---|---|---|
| United Kingdom | AI Security Institute (AISI) | £240M announced | Frontier model evaluations, The Alignment Project (£27M+)[^19][^40] |
| United States | AI Safety Institute (NIST-housed) | $10M (FY24–25) — severely underfunded relative to peers[^41] | Measurement standards, risk frameworks |
| European Union | EU AI Office | €14B Horizon Europe (2026–27), €3B+ for AI[^42] | Trustworthy AI, EU AI Act implementation |
| Canada | Canadian AISI (Innovation, Science and Economic Development Canada) | Not publicly disclosed | Contributed to Alignment Project coalition[^40] |
| Japan | AISI Japan | Not publicly disclosed | Evaluations and safety standards |
| South Korea | AISI Korea | Not publicly disclosed | Safety frameworks |

The UK leads government AI safety investment globally, while the U.S. government safety infrastructure is critically underfunded — spending $10 million on its AISI while the private sector invests $100+ billion in capabilities. DARPA's FY2026 AI safety programs (SABER initiative, "AI Forward") represent an attempt to address the federal gap.[^41][^42]

***

## Part IV: The Major Funders — Who They Are, Why They Give, and How They Decide

### Tier 1: Dominant Funders

#### Coefficient Giving (formerly Open Philanthropy)
**Total AI Safety Giving:** $336M+ since 2014 (approximately 60% of all external AI safety funding)[^43]
**2024 Annual Spending:** ~$50M on AI safety[^43]
**2025 Major Initiative:** $40M Technical AI Safety RFP across 21 research areas[^44]
**Why They Give:** Founded by Dustin Moskovitz (Facebook co-founder) and Cari Tuna, Open Philanthropy chose AI safety as a primary focus because of **neglectedness, tractability, and scale** — the classic EA cause prioritization framework. They believe the risk of catastrophic or existential AI outcomes is real, underaddressed by mainstream institutions, and potentially addressable with strategic funding. The rebrand to "Coefficient Giving" in November 2025 reflects an evolution toward a more systems-focused approach.[^45]
**How to Apply:** Rolling grant applications; the 2025 $40M RFP began with a 300-word expression of interest, with grants ranging from API compute credits to $1M+ seed organizations.[^44]

#### Jaan Tallinn / Survival and Flourishing Fund (SFF)
**Total Lifetime AI Safety Giving:** $150M+[^46][^8]
**2024 Giving:** $51M (86% to AI safety)[^8]
**2025 SFF Round:** $34.33M distributed (86% AI, 7% biosecurity, 7% other)[^47]
**SFF Total Cumulative Grants:** $152M to 467 organizations since 2019[^48]
**Why He Gives:** Jaan Tallinn (Skype/Kazaa co-founder) read Eliezer Yudkowsky's writings on AI risk in 2009 and concluded that advanced AI poses genuine existential risks. He co-founded CSER (2012) and FLI (2014), led Anthropic's Series A, and sat on DeepMind's board. He has described his giving as driven by genuine moral concern — "this is the most important problem I can think of" — while simultaneously acknowledging uncertainty and even concern about his own Anthropic investment being "proliferation".[^9]
**How SFF Decides:** The "S-Process" — a unique algorithmic grantmaking mechanism where 12+ expert recommenders independently allocate portions of available funding. This distributed model reduces single-gatekeeper bias.[^49][^50]

#### Future of Life Institute (FLI)
**Total AI Safety Grants:** $25M+[^51][^52]
**Key Funding Rounds:** 2015 ($7M to 37 projects); 2018 ($2M, AGI safety); 2021 ($25M program from Vitalik Buterin's $665.8M Ethereum donation)[^52]
**Key Early Funders:** Elon Musk ($10M in 2015), Vitalik Buterin ($665.8M donation in 2021 — Buterin's own philosophical alignment with longtermist concerns), Berkeley Existential Risk Initiative[^53]
**Why Funders Give:** FLI sits at the intersection of public advocacy and research grantmaking. The 2023 AI Pause Letter (33,000+ signatories including Elon Musk, Steve Wozniak) and 2017 Asilomar AI Principles (5,700+ signatories) made FLI the most publicly visible AI safety organization globally. Funders give because FLI translates technical concerns into public and policy discourse.[^52]

### Tier 2: Major Supplementary Funders

#### Frontier Model Forum AI Safety Fund (AISF)
**Total:** $10M+[^54]
**Funders:** Anthropic, Google, Microsoft, OpenAI (founding members), plus Patrick J. McGovern Foundation, David and Lucile Packard Foundation, Schmidt Sciences, and Jaan Tallinn[^54]
**Why It Exists:** Created in 2023 as a collaborative initiative to fund *independent* research that the companies themselves cannot credibly do — particularly adversarial evaluation, third-party safety audits, and biosecurity research.[^54][^38]
**Round 2 Grantees (December 2025):** 11 organizations receiving $5M+ including Apollo Research, CalTech (biosecurity), FAR.AI, FutureHouse, Morgan State University (cybersecurity AI), and University of Illinois Urbana-Champaign.[^38]

#### Schmidt Sciences
**AI Safety Initiative:** $10 million program (announced February 2025) — 27 projects on fundamental LLM safety science[^55]
**Why They Give:** Eric Schmidt (former Google CEO) and Schmidt Sciences target "underfunded" and "scientifically fundamental" areas. The explicit rationale was that LLM safety science — understanding *why* and *how* models fail — is critically underfunded compared to empirical benchmarking. The program specifically sought academic researchers who had been excluded from safety funding.[^55]

#### UK Research and Innovation (UKRI) / ARIA
**The Alignment Project:** UKRI and ARIA co-fund the UK AISI's Alignment Project alongside Amazon Web Services, Anthropic, Schmidt Sciences, and the SAIF (Safe AI Fund). Each project can receive up to £1 million.[^40]

#### EA Funds: Long-Term Future Fund (LTFF)
**2023–2024 Grants:** $5.36M to 141 grantees (11-month period)[^56]
**Acceptance Rate:** ~19% including desk rejections[^56]
**Why They Give:** The LTFF is the most accessible entry point for individual researchers — stipends as low as $1,500 for compute costs up to six-figure grants for established researchers. Funded by effective altruists and matched 2:1 by Open Philanthropy in 2023. Key for early-career researchers.[^57]

#### Gates Foundation / Anthropic Partnership
**Amount:** $200 million partnership[^6]
**Focus:** Healthcare and life sciences AI — AI that is safe to deploy in clinical settings[^6]

#### The Alignment Project (UK AISI-led)
**Total Fund:** £27M+ (exceeds £15M initial announcement)[^40][^19]
**OpenAI contribution:** $7.5M (~£5.6M)[^19]
**Open to:** Researchers across computational complexity, economic theory, game theory, cognitive science, information theory — disciplines not traditionally included in AI safety funding[^19]

***

## Part V: Field-Building, Education & Talent Pipeline Organizations

The AI safety field is severely **talent-constrained**, with field-building as important as direct research funding.

### MATS (ML Alignment Theory Scholars)
**Stipend:** $5,000/month + $8,000/month compute budget; housing, meals, travel covered[^58]
**Duration:** 10-week fully funded research program (plus 80%+ receive 6–12 month extensions)[^58]
**Track Record:** 527 alumni; 200+ publications with 12,300+ citations; 80% of pre-2025 alumni now working in AI safety/security; 30+ initiatives founded by alumni[^58]
**Mentors:** Anthropic, Google DeepMind, OpenAI, Redwood Research, AI Futures Project[^59]
**New for 2026:** Founding & Field-Building track (for founders and high-agency generalists launching new AI safety initiatives) and a Biosecurity track[^58]

### ARENA (Alignment Research Engineer Accelerator)
**Operator:** Conjecture (London Initiative for Safe AI)
**Funding:** £845,790 from Coefficient Giving (2025)[^39]
**Description:** 4–5 week in-person ML engineering bootcamp in London, converting talented programmers into technical AI safety researchers. Fully covers travel, visa, accommodation, meals. Alumni work at Apollo Research, Anthropic, and METR.[^60]

### CAIS Field Building
**Programs:** AI Fellowship (3-month stipend); $250,000 SafeBench competition; compute cluster access; ML Safety course; $2,000 student scholarships; Philosophy Fellowship[^36]

### 80,000 Hours
**Role:** Career advisory nonprofit directing talented individuals toward AI safety careers. One of the highest-leverage field-building organizations — their research estimates that a career switch to AI safety is among the highest-impact moves an individual can make.[^35]

### AI Safety Camp
**Type:** Nonprofit; funded by SFF ($90K + $110K‡ in 2025)[^61]
**Description:** Intensive collaborative research sprint programs to onboard new AI safety researchers.

***

## Part VI: Research Focus Area Map

The following matrix maps all current major research areas, who is working on them, and their relative coverage level:

| Research Area | Organizations Active | Coverage Level |
|---|---|---|
| **Interpretability / Mechanistic Interpretability** | Anthropic, Redwood, EleutherAI, Timaeus, CMU CASI, Google DeepMind | High (well-funded) |
| **RLHF and Reward Modeling** | OpenAI, Anthropic, DeepMind, CHAI | High |
| **Constitutional AI / Principle-Based Training** | Anthropic (primary innovator) | Medium |
| **Dangerous Capability Evaluations (Red-Teaming)** | METR, Apollo, Anthropic Red Team, Scale AI Safety, OpenAI Preparedness, FAR.AI, AISF grantees | Medium-High |
| **AI Control (keeping misaligned AI controllable)** | Redwood Research (primary), Anthropic | Medium |
| **Alignment Faking / Deceptive Alignment** | Redwood + Anthropic (2025 landmark study), Apollo | Medium (growing fast) |
| **Agent Foundations / Decision Theory** | MIRI, AFFINE (SFF-funded) | Low-Medium (niche) |
| **Eliciting Latent Knowledge (ELK)** | ARC Theory, various | Low (highly theoretical) |
| **AI Governance and Policy** | Centre for Governance of AI (Oxford), CSET, AI Policy Institute (SFF-funded), FLI, PAI | High |
| **Biosecurity (AI-enabled bioweapons uplift)** | SecureBio, CalTech (AISF), Anthropic Red Team, FLI, MATS biosecurity track | Low-Medium (growing) |
| **Cybersecurity (AI-assisted cyberattacks)** | METR, UIUC (AISF), Morgan State, Nemesys Insights | Medium |
| **Multi-Agent Safety** | Institute for Decentralized AI/Cosmos, University of Toronto (AISF), FAR.AI | Low (emerging) |
| **Societal and Labor Market Impacts** | MIT/CMU (Sloan), Anthropic Economic Index, Stanford HAI | Medium |
| **AI Safety for Healthcare** | Gates/Anthropic partnership, MIT CSAIL, emerging | Low-Medium |
| **Scalable Oversight** | OpenAI (Superalignment), DeepMind, CHAI | Medium |
| **Watermarking and Synthetic Content Detection** | Only 1 organization mapped[^3] | Very Low (**critical gap**) |
| **Incident Response Frameworks** | Only 5 organizations mapped[^3] | Very Low (**critical gap**) |
| **AI Safety for Children / Youth** | Youth AI Safety Institute (Common Sense Media, 2026)[^62] | Very Low (brand new) |
| **AI Safety in the Global South** | Almost none | Extremely Low (**massive gap**) |
| **Independent Verification Organizations (IVOs)** | Proposed by Gillian Hadfield/Fathom; no mature infrastructure yet[^4] | Near-zero (**structural gap**) |

***

## Part VII: What Is Missing — The White Spaces

These gaps represent the most underfunded, underresearched, and strategically important areas for a new AI safety lab to target:

### 1. The Scientific Foundation for Governance Is Critically Thin
The 2026 International AI Safety Report found that *pre-deployment tests don't reliably predict real-world performance*, and that we don't yet know which safeguards actually work. Gillian Hadfield (University of Toronto) described this as "building a governance architecture with almost nothing underneath it" — you cannot set meaningful safety standards without the science to define what "safe" means. **There is a massive need for empirical, real-world deployment safety research, not just pre-release evaluations.**[^4]

### 2. Independent Verification Organizations (IVOs)
There is no competitive market of independent organizations that can verify AI safety claims made by companies. Current evaluators (METR, Apollo) are too small and underfunded to meet growing demand. Gillian Hadfield's Fathom is working on this but infrastructure barely exists. This is arguably the single most critical structural gap in the entire field.[^63][^4]

### 3. AI Safety for Applied Domains
- **Healthcare AI Safety:** With billions flowing into clinical AI deployment, there is almost no dedicated research on safety for healthcare-specific AI systems (diagnostic AI, clinical decision support, care coordination agents). The Gates-Anthropic $200M partnership is the first meaningful signal here.[^6]
- **Workforce and Labor Safety:** AI systems that make consequential decisions about hiring, performance management, and career outcomes lack dedicated safety research. MIT/CMU's $1.6M Sloan study barely scratches the surface.[^64]
- **Cannabis Industry AI:** No dedicated AI safety research addresses regulated industries like cannabis with unique compliance and liability contexts.

### 4. Global South and Non-English AI Safety
Over 180 AI safety organizations cluster in five cities (SF, Berkeley, London, DC, NYC). There is almost no AI safety research capacity in Africa, Latin America, South Asia, or Southeast Asia — yet these regions are targeted for AI deployment without the governance infrastructure to manage risks. The UNDP's December 2025 report warned that AI "unmanaged could increase inequality between countries by widening divides". No major funder has a dedicated Global South AI safety program.[^65][^66][^3]

### 5. Multi-Agent and Agentic AI Safety
As of 2026, only a handful of organizations are researching safety for multi-agent AI systems — AI networks where multiple models coordinate, negotiate, and act autonomously. The University of Toronto's AISF-funded work on "sanctioning in multi-agent LLM systems" is one of the only dedicated projects. This is a critical gap given that agentic AI is the dominant commercial paradigm in 2026.[^3][^38]

### 6. Incident Response and Post-Deployment Monitoring
Only 5 organizations globally work on AI incident response frameworks. There is no equivalent of a National Transportation Safety Board for AI incidents — no systematic collection, analysis, or remediation infrastructure for real-world AI failures at scale.[^3]

### 7. Synthetic Content Detection and Watermarking
Only 1 organization in the entire mapped AI safety ecosystem focuses on watermarking. Deepfakes of political leaders are already defrauding millions. This is technically tractable and critically underfunded.[^67][^3]

### 8. Child and Adolescent AI Safety
Common Sense Media's Youth AI Safety Institute, announced May 2026, is the first organization dedicated to crash-testing AI products for child safety. This space is essentially brand new.[^62]

### 9. "Funding Doesn't Match Need at the Small End"
Multiple sources flag that while large frontier labs and a few major nonprofits are decently funded, **small grants for individual researchers and exploratory ideas are severely scarce**. The LTFF funded 141 grantees in an 11-month period for $5.36M — averaging under $40K each. Many promising researchers remain unfunded. New labs can address this by running open grant programs or fellowships.[^68][^69][^70][^56]

### 10. Quantitative Safety Science
The 2025 Q1 survey found that despite rising rhetoric about safety, no genuinely novel technical methods in AI safety were published in that quarter. The gap between safety discourse and safety *science* — concrete, reproducible, mathematically grounded methods — is significant. There is demand for researchers who can bridge theoretical AI alignment with empirical ML methodology.[^71]

***

## Part VIII: The Economics of the Field

| Metric | Figure | Source |
|---|---|---|
| Total technical AI safety FTEs | ~600 | [^1][^2] |
| Total non-technical AI safety FTEs | ~500 | [^1][^2] |
| Safety : Capabilities researcher ratio | 1:50–100 | [^2] |
| Annual safety funding (global) | $250–400M | [^2] |
| Annual capabilities funding (global) | $100B+ | [^2] |
| Safety : Capabilities funding ratio | ~1:10,000 | [^2] |
| Coefficient Giving annual AI safety spend (2024) | ~$50M | [^43] |
| Total Coefficient Giving AI safety grants (all time) | $336M+ | [^43] |
| SFF 2025 round (AI safety) | ~$29M | [^47] |
| FLI total AI safety grants | $25M+ | [^51] |
| The Alignment Project total fund | £27M+ | [^19] |
| Frontier Model Forum AISF total | $10M+ | [^54] |
| Schmidt Sciences AI Safety Program | $10M | [^55] |
| Anthropic Fellows Program (weekly stipend) | $3,850/week + $15K/month compute | [^14] |
| MATS fellowship stipend | $5,000/month + $8,000/month compute | [^58] |
| Annual growth rate, AI safety field | 21–25% | [^2] |
| Annual growth rate, capabilities research | 30–40% | [^2] |

The field is growing but **falling further behind** — capabilities research grows 30–40% annually versus safety's 21–25%. Total safety funding represents 0.0004% of global GDP.[^2]

***

## Part IX: Strategic Analysis for a New AI Safety Lab

### What A New Lab Needs to Know

**What gets funded:**
1. Organizations with a **clear theory of change** — demonstrable path from research to reduced AI risk
2. **Credible technical founders** with AI/ML backgrounds or strong interdisciplinary teams
3. Work that fills **documented gaps** (funders publish RFPs identifying exactly what they want)
4. **Independent** from AI companies (METR's decision not to accept AI company funding is explicitly cited as what makes its evaluations credible)[^29]
5. **Tractable problems** — "we can make progress on this in 2–5 years" not purely theoretical
6. **Scalable approaches** — research that can influence industry practice, regulation, or training methods

**What struggles to get funded:**
- Pure policy advocacy without research backing
- Highly speculative theoretical work without empirical components
- Organizations without published track records in their first year
- Work that primarily serves the lab's home country and lacks global perspective

### Positioning Recommendations for Dee's Lab

Given your background in healthcare staffing, workforce technology, and the underserved/underrepresented community lens, three differentiated positions exist in the white spaces:

**Position A — Applied Domain AI Safety (Healthcare + Workforce)**
Focus on the intersection of AI safety and consequential real-world AI deployment — specifically healthcare AI safety and AI for hiring/workforce decisions. This combines your domain expertise with an almost completely unoccupied research niche. The Gates-Anthropic partnership signals growing demand. MATS's track record of training labor-market researchers suggests funding availability.

**Position B — Independent Evaluation for Applied AI Systems**
Build an independent verification organization (IVO) focused on real-world AI system behavior *after deployment* — not pre-release red-teaming. This fills the structural gap identified by Gillian Hadfield and is fundable through government agencies (NSF, NIST), philanthropic funders, and potentially industry partnerships.[^4]

**Position C — Global South AI Safety Capacity Building**
Build the first AI safety research lab with a deliberate Global South focus — training researchers in underrepresented geographies to understand and govern AI impacts on their populations. This is fundable through MacArthur Foundation, Ford Foundation, UNDP, and the Current AI coalition ($2.5B target).[^42]

***

## Part X: Funding Application Entry Points

For a new AI safety lab launching today, the following are the most accessible and most strategically important funding entry points:

| Funder | Mechanism | Grant Range | Key Criteria | URL |
|---|---|---|---|---|
| Coefficient Giving | Technical AI Safety RFP; rolling grants | $10K–$2M+ | Technical credibility, theory of change | openphilanthropy.org |
| Long-Term Future Fund | Rolling applications | $1,500–$500K | Any promising safety-relevant project | funds.effectivealtruism.org |
| Survival and Flourishing Fund | Biannual S-Process | $50K–$2M | Track record, community standing | survivalandflourishing.fund |
| Future of Life Institute | Grant rounds | $50K–$500K | Technical or governance research | futureoflife.org |
| Schmidt Sciences AI Safety | Academic program | $100K–$500K | Foundational science, academic affiliation | schmidtsciences.org |
| Frontier Model Forum AISF | Project-specific RFPs | $100K–$1M | Independent research, evaluations, biosecurity, cybersecurity | frontiermodelforum.org |
| UK AISI Alignment Project | Open applications | £50K–£1M | Alignment theory, any scientific discipline | aisi.gov.uk |
| NSF AI Research Institutes | Competitive grants | $20M (national institutes) | Academic partnership required | nsf.gov |
| CAIS Research Grants | Rolling | $10K–$200K | Technical safety, governance | safe.ai |
| Anthropic Fellows Program | Fellowship | $3,850/week + $15K compute | Individual researchers | alignment.anthropic.com |
| MATS Program | Fellowship | $5K/month + $8K compute | Early-career researchers, founders | matsprogram.org |
| Gates Foundation | Partnership | $10M–$200M | Healthcare AI, global health, inclusive AI | gatesfoundation.org |

***

## Conclusion

The AI safety and alignment field is experiencing a critical paradox: **unprecedented urgency meets severely inadequate resources**. While the language of safety now appears in every major tech company's press materials, the actual research infrastructure — independent evaluators, governance scientists, applied safety researchers, real-world monitoring systems — remains embryonic. The 2026 International AI Safety Report makes clear that the scientific foundation for AI governance is dangerously thin.[^5][^4][^3]

For Dee Williams and the new Identifize AI Safety Lab, this creates a genuine strategic opportunity. The white spaces are not just unfunded — they are *known to be* unfunded by the major grantmakers who publish their priorities openly. A lab that brings the intersection of applied domain knowledge (healthcare, workforce, underserved populations), principled independence from commercial AI companies, and a commitment to real-world safety science can enter a field where the demand for credible new entrants far exceeds supply.

The total external funding for AI safety is roughly $300–400M per year. That sounds large — but it represents approximately 0.3% of what a single AI lab (Anthropic) raised in one funding round. The gap between what the problem demands and what the field currently receives is, arguably, the defining research funding gap of this decade.[^2][^6]

---

## References

1. [AI Safety Field Growth Analysis 2025 - LessWrong](https://www.lesswrong.com/posts/8QjAnWyuE9fktPRgS/ai-safety-field-growth-analysis-2025) - The goal of this post is to analyze the growth of the technical and non-technical AI safety fields i...

2. [Safety Research & Resources](https://ea-crux-project.vercel.app/knowledge-base/metrics/safety-research/) - Tracking AI safety researcher headcount, funding, and research output to assess field capacity relat...

3. [AI Safety Companies: The Complete Directory (2026)](https://aisecurityandsafety.org/en/guides/ai-safety-companies/) - This guide maps the entire landscape, from frontier AI labs building safety into their models to sta...

4. [2026 AI Safety Report Highlights Thin Scientific Foundation for AI ...](https://www.linkedin.com/posts/gillian-k-hadfield-1773987_international-ai-safety-report-activity-7433180708745162752-YOui) - You can't set meaningful safety standards if you don't have the science to define what "safe" means....

5. [Inside The Second Int'l AI Safety Report with Stephen Clare ...](https://www.youtube.com/watch?v=2VlXhGottLw) - The second International AI Safety Report, released on February 3, brings together insights from ove...

6. [Anthropic raises $30 billion in Series G funding at $380 billion post ...](https://www.anthropic.com/news/anthropic-raises-30-billion-series-g-funding-380-billion-post-money-valuation) - We have raised $30 billion in Series G funding led by GIC and Coatue, valuing Anthropic at $380 bill...

7. [Anthropic Core Views - Longterm Wiki](https://www.longtermwiki.com/wiki/E23) - Anthropic's Core Views on AI Safety is their publicly stated research agenda and organizational phil...

8. [Jaan Tallinn | Longterm Wiki - Vercel](https://longterm-wiki.vercel.app/wiki/E577) - Comprehensive profile of Jaan Tallinn documenting $150M+ lifetime AI safety giving (86% of $51M in 2...

9. [Jaan Tallinn - Wikipedia](https://en.wikipedia.org/wiki/Jaan_Tallinn)

10. [Research - Anthropic](https://www.anthropic.com/research) - Our research teams investigate the safety, inner workings, and societal impacts of AI models – so th...

11. [Redwood Research - Longterm Wiki](https://www.longtermwiki.com/wiki/E557) - A nonprofit AI safety and security research organization founded in 2021, known for pioneering AI Co...

12. [Anthropic's Reported $30B Funding Talks Spotlight AI's Growing ...](https://www.govconwire.com/articles/anthropic-30b-funding-round-plan) - Anthropic's reported talks to raise $30 billion at a valuation exceeding $900 billion are expected t...

13. [Focus areas for The Anthropic Institute](https://www.anthropic.com/research/anthropic-institute-agenda) - Our agenda focuses on four areas for research: Economic diffusion; Threats and resilience; AI system...

14. [Anthropic Fellows Program for AI safety research](https://alignment.anthropic.com/2025/anthropic-fellows-program-2026/) - The Anthropic Fellows program provides funding and Anthropic mentorship for engineers and researcher...

15. [Microsoft, Meta, and Google just announced billions more in AI ...](https://fortune.com/2026/04/29/microsoft-meta-google-ai-capex-spending-billions/) - AI capex spending gets revised upward. Alphabet raised its full year 2026 capex spending guidance to...

16. [Research — Google DeepMind](https://deepmind.google/research/) - Explore our research on some of the most complex and interesting challenges in AI.

17. [Google DeepMind agrees to sweeping partnership with the U.K. ...](https://fortune.com/2025/12/10/google-deepmind-uk-government-partnership-science-clean-energy/)

18. [Q1 2026 AI funding blows past 2025 total with three deals ...](https://finance.yahoo.com/sectors/technology/articles/q1-2026-ai-funding-blows-175036425.html) - AI startups raised $255.5 billion globally in Q1 2026, surpassing the 2025 full-year total for AI ve...

19. [Advancing independent research on AI alignment | OpenAI](https://openai.com/index/advancing-independent-research-ai-alignment/) - OpenAI commits $7.5M to The Alignment Project to fund independent AI alignment research, strengtheni...

20. [Exclusive: OpenAI co-founder Sutskever's new safety-focused AI ...](https://www.reuters.com/technology/artificial-intelligence/openai-co-founder-sutskevers-new-safety-focused-ai-startup-ssi-raises-1-billion-2024-09-04/) - Exclusive: OpenAI co-founder Sutskever's new safety-focused AI startup SSI raises $1 billion · Three...

21. [OpenAI co-founder Ilya Sutskever's Safe Superintelligence ...](https://techcrunch.com/2025/04/12/openai-co-founder-ilya-sutskevers-safe-superintelligence-reportedly-valued-at-32b/) - The AI startup led by OpenAI's co-founder and former chief scientist Ilya Sutskever, has raised an a...

22. [Ilya Sutskever's Safe Superintelligence raises $2B at $32B valuation ...](https://www.calcalistech.com/ctechnews/article/hjfywdtajl) - The stealth startup founded by former OpenAI chief scientist Ilya Sutskever has raised $2 billion in...

23. [Safe Superintelligence (SSI) Raises $1 | SalesTools AI](https://salestools.io/report/safe-superintelligence-ssi-raises-1-billion-series-a-september-2024) - Safe Superintelligence (SSI) secured $1 Billion in Series A funding at $5 Billion valuation. Led by ...

24. [Ilya Sutskever's startup, Safe Superintelligence, raises $1B](https://techcrunch.com/2024/09/04/ilya-sutskevers-startup-safe-super-intelligence-raises-1b/) - Safe Superintelligence, ex-OpenAI chief scientist Ilya Sutksever's firm, has raised $1 billion from ...

25. [Machine Intelligence Research Institute - EA Forum](https://forum.effectivealtruism.org/topics/machine-intelligence-research-institute) - As of July 2022, MIRI has received over $14.7 million in funding from Open Philanthropy, nearly $900...

26. [Transparency - The Machine Intelligence Research Institute (MIRI)](https://intelligence.org/transparency/) - Our largest contributors, each of whom has given at least $500,000, are: An anonymous Ethereum crypt...

27. [Machine Intelligence Research Institute - Wikipedia](https://en.wikipedia.org/wiki/Machine_Intelligence_Research_Institute) - In 2014 and 2015, public and scientific interest in the risks of AI grew, increasing donations to fu...

28. [Alignment Research Center - Wikipedia](https://en.wikipedia.org/wiki/Alignment_Research_Center)

29. [About METR](https://metr.org/about) - METR (pronounced 'meter') evaluates frontier AI models to help companies and wider society understan...

30. [METR (formerly called ARC Evals) - Giving What We Can](https://www.givingwhatwecan.org/charities/arc-evals) - As of July 2023, METR could make good use of millions of dollars in additional funding over the next...

31. [METR](https://metr.org) - Model Evaluation & Threat Research. METR conducts research and evaluations to improve public underst...

32. [Redwood Research Group, Inc. - Future of Life Institute](https://futureoflife.org/grant/redwood-research-group-inc/)

33. [Center for AI Safety — Exit Grant (October 2023) | Open Philanthropy](https://www.openphilanthropy.org/grants/center-for-ai-safety-exit-grant-october-2023/) - Open Philanthropy recommended a grant of $1,866,559 to the Center for AI Safety (CAIS) for general s...

34. [Center for AI Safety — General Support (2022) | Open Philanthropy](https://www.openphilanthropy.org/grants/center-for-ai-safety-general-support/) - Open Philanthropy recommended a grant of $5,160,000 to the Center for AI Safety (CAIS) for general s...

35. [Alignment Organizations | AI Safety Directory](https://aisecurityandsafety.org/pl/organizations/focus/alignment/) - 40 organizations focused on alignment in AI safety, including 80,000 Hours, AI Safety Camp, Alignmen...

36. [Field Building Projects - Center for AI Safety (CAIS)](https://safe.ai/work/field-building) - CAIS Field Building. Supporting the broader research community with workshops, competitions, social ...

37. [Apollo Research is becoming a PBC](https://www.apolloresearch.ai/blog/apollo-research-is-becoming-a-pbc/) - We are increasing our investment in research, evals and governance. We're standing up a separate pro...

38. [Announcement of New AI Safety Fund Grantees](https://www.frontiermodelforum.org/updates/announcement-of-new-ai-safety-fund-grantees/) - Today we are announcing a new cohort of 11 grantees who have received more than $5 million through t...

39. [Alignment Research Engineer Accelerator — AI Safety Technical Program (2025) | Open Philanthropy](https://www.openphilanthropy.org/grants/alignment-research-engineer-accelerator-ai-safety-technical-program-2025/) - Open Philanthropy recommended a grant of £845,790 (approximately $1,037,061 at the time of conversio...

40. [AI Security Institute launches £15m fund for AI alignment research](https://www.linkedin.com/posts/aleksandr-bowkis_the-alignment-project-activity-7358122009219764224-h1zO) - The AI Security Institute has just announced the alignment project: a fund of over £15 million for r...

41. [The US Has Committed to Spend Far Less Than Peers on AI Safety](https://www.centeraipolicy.org/work/the-us-has-committed-to-spend-far-less-than-peers-on-ai-safety) - Compared to peers such as the UK, EU, Canada, and Singapore, the US has announced the least funding ...

42. [State of AI Grants 2026: Annual Funding Intelligence Report](https://grantedai.com/blog/state-of-ai-grants-2026-report) - Federal AI funding hits $3.3B in FY2025 while foundations pledge $500M+ for responsible AI. Our annu...

43. [Open Philanthropy | LongtermWiki](https://www.longtermwiki.com/knowledge-base/organizations/funders/open-philanthropy/) - Open Philanthropy rebranded to Coefficient Giving in November 2025. See the Coefficient Giving page ...

44. [Open Philanthropy Technical AI Safety RFP - $40M Available Across ...](https://forum.effectivealtruism.org/posts/XtgDaunRKtCPzyCWg/open-philanthropy-technical-ai-safety-rfp-usd40m-available) - Open Philanthropy is launching a big new Request for Proposals for technical AI safety research, wit...

45. [Coefficient Giving | LongtermWiki](https://ea-crux-project.vercel.app/knowledge-base/organizations/coefficient-giving/) - Open Philanthropy began supporting AI safety work in 2015 ... 2025, Rebrand to Coefficient Giving; $...

46. [Jaan Tallinn | Longterm Wiki](https://www.longtermwiki.com/wiki/E577) - Comprehensive profile of Jaan Tallinn documenting $150M+ lifetime AI safety giving (86% of $51M in 2...

47. [SFF 2025 funding by cause area: $34 million to AI (86%), bio (7%), etc.](https://forum.effectivealtruism.org/posts/vhw6R5P52qJr6opou/sff-2025-funding-by-cause-area-usd34-million-to-ai-86-bio-7) - Summary: this year the Survival and Flourishing Fund allocated $34.33 million to organizations worki...

48. [Survival and Flourishing Fund | Organizations | Longterm Wiki](https://www.longtermwiki.com/organizations/sff) - AI Safety Knowledge Base

49. [Survival and Flourishing Fund AI Safety Grant ($5M+/year · Recurring)](https://aisecurityandsafety.org/en/grants/survival-and-flourishing-fund/) - Rolling applications accepted. Open to Nonprofit organizations, Research organizations. Covers align...

50. [SFF-2025 S-Process Recommendations Announcement](https://survivalandflourishing.fund/2025/recommendations) - Survival and Flourishing Fund (SFF) is a website for organizing the collection and evaluation of app...

51. [FLI AI Safety Grants](https://aisecurityandsafety.org/pt/grants/fli-ai-safety-grants/) - Rolling applications accepted. Open to Academic researchers, Research organizations, Nonprofit organ...

52. [Future of Life Institute (FLI) - Longterm Wiki](https://www.longtermwiki.com/wiki/E528) - Comprehensive profile of FLI documenting $25M+ in grants distributed (2015: $7M to 37 projects, 2021...

53. [AI Research Grants Program - Future of Life Institute](https://web.archive.org/web/20221123074311/https:/futureoflife.org/ai-research/) - Artificial Intelligence Grants Program In 2015, FLI launched the first peer-reviewed grants program ...

54. [AI Safety Fund - Frontier Model Forum](https://www.frontiermodelforum.org/ai-safety-fund/) - AI Safety Fund The AI Safety Fund (AISF) is a collaborative $10 million+ initiative established in O...

55. [New $10 Million AI Safety Science Program Launched for ...](https://www.schmidtsciences.org/new-10-million-ai-safety-science-program-launched-for-foundational-research/) - Schmidt Sciences tackles underfunded AI safety challenges to ensure reliable and robust AI systems. ...

56. [May 2023 to March 2024: Long-Term Future Fund grant ...](https://funds.effectivealtruism.org/payouts/may-2023-to-march-2024-long-term-future-fund-grant-recommendations) - We fund outstanding projects focused on social impact

57. [Long-Term Future Fund - Manifund](https://manifund.org/projects/long-term-future-fund?tab=donations) - The total funding target we're aiming for in the next 6 months is $6.2M ($3.5M from OP matching and ...

58. [MATS Research's Post - LinkedIn](https://www.linkedin.com/posts/mats-program_%F0%9D%97%A0%F0%9D%97%94%F0%9D%97%A7%F0%9D%97%A6-%F0%9D%97%94%F0%9D%98%82%F0%9D%98%81%F0%9D%98%82%F0%9D%97%BA%F0%9D%97%BB-%F0%9D%9F%AE%F0%9D%9F%AC%F0%9D%9F%AE%F0%9D%9F%B2-%F0%9D%97%AE%F0%9D%97%BD%F0%9D%97%BD%F0%9D%97%B9%F0%9D%97%B6%F0%9D%97%B0%F0%9D%97%AE%F0%9D%98%81%F0%9D%97%B6%F0%9D%97%BC%F0%9D%97%BB%F0%9D%98%80-activity-7460409346187960320-Ut0e) - ... AI safety researchers and founders. The MATS Autumn 2026 Fellowship is a 10-week fully-funded re...

59. [MATS Opens Applications for Autumn 2026 AI Safety Research ...](https://www.globalsouthopportunities.com/2026/05/13/mats/) - The MATS programme provides fellows with extensive support to enable full-time focus on impactful AI...

60. [ARENA – AI Safety Education](https://www.arena.education) - We aim to provide talented individuals with the skills, community, and confidence to contribute dire...

61. [Grants | Survival and Flourishing Fund](https://survivalandflourishing.fund/recommendations) - See an overview of grants that Survival and Flourishing Fund (SFF) has organized.

62. [Child safety lab launching 'independent crash testing' for AI tools](https://www.cnn.com/2026/05/05/tech/ai-youth-safety-independent-testing-lab) - The Youth AI Safety Institute will be an independent lab to test AI products for risks. The Youth AI...

63. [The White House Wants to Vet AI Models. It Won't Solve the Safety ...](https://www.techpolicy.press/the-white-house-wants-to-vet-ai-models-it-wont-solve-the-safety-problem/) - While AI companies employ world-class researchers, they operate under constraints that make truly in...

64. [MIT and CMU launch $1.6M AI and labor market research ...](https://www.linkedin.com/posts/tessfagan_research-collaboration-on-labor-implications-activity-7342972072328871936-doIa) - I'm very excited to share that MIT FutureTech and Carnegie Mellon University’s (CMU) The Block Cente...

65. [AI Preparedness Index Shows Global South Is Not Ready - ICTworks](https://www.ictworks.org/ai-preparedness-index-shows-global-south-is-not-ready-for-artificial-intelligence-soltuions/) - Global South performance in each AI Preparedness Index reveals distinct but compounding barriers tha...

66. [AI risks sparking a new era of divergence as development gaps ...](https://www.undp.org/asia-pacific/press-releases/ai-risks-sparking-new-era-divergence-development-gaps-between-countries-widen-undp-report-finds) - The report warns that without deliberate and inclusive policy choices, AI may now cause the erosion ...

67. [ISACA Now Blog 2025 Avoiding AI Pitfalls in 2026 Lessons Learned ...](https://www.isaca.org/resources/news-and-trends/isaca-now-blog/2025/avoiding-ai-pitfalls-in-2026-lessons-learned-from-top-2025-incidents) - In 2025, many organizations discovered that AI incidents slipped into everyday operations and create...

68. [How can I provide significant financial support to AI alignment?](https://aisafety.info/questions/8U2Y/How-can-I-provide-significant-financial-support-to-AI-alignment) - The simplest way to support AI alignment is to donate to grantmakers such as the Long Term Future Fu...

69. [It looks like there are some good funding opportunities in AI safety ...](https://benjamintodd.substack.com/p/looks-like-there-are-some-good-funding) - The AI safety community has grown rapidly since the ChatGPT wake-up call, but available funding does...

70. [Stop Donating to AI Safety Research* — EA Forum](https://forum.effectivealtruism.org/posts/HuyZE6xFfebv7ByXC/stop-donating-to-ai-safety-research) - The highest-leverage path for donors looking to give to AI safety right now is to give less money, b...

71. [Executive Summary](https://www.wta-h.com/ai-2025-q1-ai_safety_and_alignment.html)

