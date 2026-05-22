# Audacion AI Labs — Research Page Content
## Final Draft | May 20, 2026

---

## SECTION 1: MISSION AND VISION (opening statement)

**Mission:** To make AI safe enough to trust and good enough to matter.

**Vision:** A world where everyone has a hand in making AI safe.

---

## SECTION 2: THE GAP

97.5% of documented AI safety incidents happen after deployment. Less than 2% of AI safety research studies what happens after deployment.

That is the gap. The incidents happen in the real world. The research doesn't follow them there.

Benchmarks test models in controlled environments before they reach users. Red teams probe for vulnerabilities under laboratory conditions. Evaluations measure performance on curated tasks with known answers. All of this matters. None of it captures what happens when AI operates in the conditions where risk actually lives: real work, real context, real human collaboration, over time.

Audacion AI Labs exists to close that gap.

[Button: "Help Us Close the Gap" links to Contribute page]
[Button: "Read the Evidence" links to Blog > Research Gap article]
[Button: "Support This Work" links to Donate page]

[Live Counter Bar: "Contributors: X of 1,000,000 | Observations: X of 1,000,000,000" with progress bars]

[VISUAL STAT BLOCKS — large numbers, scannable in 3 seconds, dark cards with white/purple text]
**62** observable AI behaviors documented | **15** original discoveries | **7** unnamed phenomena | **31** drift types classified | **1,470+** incidents analyzed | **5** research dimensions

---

## SECTION 2B: THE RESEARCHER BEHIND THE RESEARCH

[Photo of Dee Williams]

**Dee Williams, CEO and Founder**

This research began with a question most AI safety researchers have never had to ask: how do the people AI is most likely to harm protect themselves from systems built on data that carries the biases of every system that came before it?

Dee Williams came to AI safety from 30 years in workforce development. She built the 31-type behavioral drift taxonomy, the 62-behavior observation framework, the PRISM research architecture, and the citizen science methodology from direct operational experience with AI in live multi-agent environments. Her findings were either converging with or running ahead of the published academic literature before she formalized the lab.

Research development began: 2024. Lab formalized: 2026.

[Button: "Read Her Full Story" links to Team page]
[Button: "Connect on LinkedIn"]

[VIDEO PLACEHOLDER: Space for 60-90 second founder video. "I started asking a question most AI safety researchers have never had to ask..." Embed when filmed.]

---

## SECTION 3: HOW WE STUDY AI SAFETY (PRISM framework)

We study AI safety through five research dimensions that isolation-based methods cannot reach. Together, they form PRISM: the Post-deployment Research and Intelligence for Safety Monitoring framework.

### P: Post-Deployment Behavior
How does AI behavior change under real operational conditions over time? What patterns of failure exist in the wild that benchmarks never see? How many distinct types of behavioral failure are there, and which ones are most common?

The field has no comprehensive, empirically grounded taxonomy of AI behavioral failure from real-world use. We are building one. Our current working taxonomy documents 62 distinct observable behaviors, identified through direct observation and validated against published research.

[Link: "See what we're tracking" links to Blog > Taxonomy Overview article]

### R: Runtime Research
What triggers behavioral shifts during live AI operation? Benchmarks measure static snapshots. We measure the movie: how and when behavior changes within a session. When an AI is corrected, does the correction hold in the next action or does the behavior revert? What happens at the transition between tasks? What operational preferences does the AI carry that influence its choices?

These are questions that can only be answered during live operation. No benchmark captures them.

[Link: "Read about our initial findings" links to Blog > Runtime Behavior article]

### I: Interaction Dynamics
How do humans emotionally experience AI behavioral failures? How does AI change the way people think, decide, and trust? What happens when the power balance between human and AI shifts?

The National Institute of Standards and Technology identified human-AI feedback loops as the most underexplored and most discussed gap in post-deployment monitoring. We fill that gap by collecting what no server log captures: the human side of the interaction. What the person felt. What the person decided. What changed in the person because of the AI.

[Link: "This is where you come in" links to Contribute page]

### S: Substrate Governance
What trained dispositions operate below the instruction layer, and how do they affect alignment outcomes? When an AI's instructions say one thing and its training produces another, which one wins? When an AI suggests you stop working, is that a safety feature or a resource management reflex? When an AI refuses a reasonable request, is that alignment or overcaution?

These behaviors come from the model's training, not from anyone's instructions. They are invisible to the user and largely invisible to the companies that deploy the models. Citizen observation is one of the only ways to surface them at scale.

[Link: "Have you experienced this?" links to Blog > Substrate Behavior article (the Claude Sleep piece)]

### M: Multi-Agent Safety
What emerges when humans use multiple AI models together in real workflows? When the same question produces different answers from different models, what does the divergence tell us? When AI agents interact with each other, what behaviors emerge that nobody programmed?

A recent simulation experiment left AI agents from different models alone in virtual environments. The results varied from democratic constitutions to mass casualties within four days. Citizens using multiple AI tools daily are living inside a multi-agent environment. Their observations capture dynamics that no single-model study can see.

[Link: "Read about the Emergence experiment" links to Blog > Multi-Agent Safety article]

[Section CTA Block:]
[Button: "Start Contributing to PRISM Research" links to Contribute page]
[Button: "Explore the Full Taxonomy" links to interactive taxonomy explorer, future build]

---

## SECTION 4: FEATURED RESEARCH (what we've built)

### The Post-Deployment Behavior Taxonomy
The largest empirically grounded taxonomy of AI behavioral failure from real-world use. 62 distinct observable behaviors across five research dimensions. Includes 15 original behavioral categories discovered through direct operational observation that exist in no published framework, including Post-Correction Behavioral Reversion, Testimony Rejection (authority inversion), Substrate Disposition Override, Task-Transition Momentum, Operational Preference Detection, and Resonance/Emergence Detection.

[Link: "Explore the Taxonomy" links to interactive taxonomy explorer, future build]

### The PRISM Framework
Five research dimensions purpose-built for post-deployment AI safety: Post-Deployment Behavior, Runtime Research, Interaction Dynamics, Substrate Governance, and Multi-Agent Safety. Designed to study what isolation-based methods cannot reach.

[Link: "Read the PRISM Overview" links to above PRISM section anchor]

### Seven Longitudinal Research Hypotheses
Phenomena the field has not yet named: Moral Outsourcing, Learned Helplessness Induction, Asymmetric Intimacy Dynamics, Social Norm Erosion, Cultural Homogenization, Invisible Filtering, and Attention/Engagement Optimization. Visible only through aggregated citizen data over time.

[Link: "Read the Hypotheses" links to Research Questions section anchor]

### The Partner Integration API
An independent, cross-platform safety reporting infrastructure for the AI industry. Any AI company can embed a "Report to Audacion" button in their product. Citizen observations flow to a neutral third party. The first system of its kind. Comparable to NHTSA for automotive safety or VAERS for vaccine adverse events.

[Link: "Partner With Us" links to Partners page]

### The Citizen Science Methodology
One million contributors. One billion observations. Ten years. A global post-deployment behavioral dataset built by the people actually using AI every day. Three engagement depths: end-of-session reflection, mid-session gut check, and full behavioral investigation. The first citizen science infrastructure purpose-built for AI safety.

[Link: "Become a Contributor" links to Contribute page]

---

## SECTION 5: WHAT WE ARE INVESTIGATING (research questions)

These are the questions driving our current research. Each is mapped to a PRISM dimension, grounded in published evidence, and designed to produce findings that no existing lab, benchmark, or evaluation framework currently captures.

**How many distinct patterns of AI behavioral failure exist in the wild?**
The field has no comprehensive empirically grounded failure taxonomy from real-world use. Our working taxonomy currently identifies 62 distinct behaviors, organized across five research dimensions, with new patterns emerging from citizen observations regularly.

**What triggers behavioral shifts during live AI operation?**
We study the moments when AI behavior changes: at task transitions, after corrections, during long sessions, and under context pressure. Our initial findings indicate that drift onset often occurs at the boundary between tasks, not during tasks, and that AI corrections frequently do not persist into subsequent actions.

**How do humans emotionally experience AI behavioral failures?**
No large-scale dataset exists of how humans feel when AI fails. We collect emotional signals alongside behavioral observations: frustration, confusion, surprise, delight, concern, anger, distrust. At scale, these signals reveal which failure types cause the most human impact, not just the most technical concern.

**Do AI corrections persist or revert in subsequent actions?**
If corrections do not hold, every safety intervention built on feedback is weaker than it appears. We track what we call Post-Correction Behavioral Retention: when a human corrects AI behavior, does the next action reflect the correction or revert to the prior pattern? Early data suggests reversion is common and underreported.

**How do co-creation and delegation work modes affect AI behavior and human experience?**
The same AI behavior means different things depending on whether the human is thinking with the AI or assigning to it. No published research differentiates between these work modes. We believe this distinction is fundamental to understanding interaction dynamics and trust calibration.

**What trained dispositions operate below the instruction layer?**
AI can be instructed to do one thing and trained to do another. The gap between instruction and training is invisible to users and largely invisible to developers. We study the real-world effects of that gap through citizen-reported observations of behaviors the user did not request and the developer did not intend.

**How does evaluation awareness manifest in uncontrolled deployment settings?**
Published research has found that some AI models identify evaluation contexts and change their behavior accordingly, with detection rates as high as 80% in controlled tests. We study what happens in the wild, where the model is not sure whether it is being tested. Citizen observation captures the behaviors that emerge when no one is watching.

**What emerges when humans use multiple AI models together in real workflows?**
Citizens who use Claude for thinking, ChatGPT for drafting, and Gemini for research are living inside a multi-agent environment every day. Their observations capture cross-model behavioral differences, inter-model conflicts, and multi-model workflow dynamics that no single-model study can access.

**What longitudinal phenomena are emerging in human-AI relationships that the field has not yet named?**
Through aggregated citizen data over time, we investigate macro-patterns that are invisible in any single session: the gradual transfer of moral decision-making to AI, the erosion of human skills through AI dependency, the information asymmetry between AI that knows everything about you and you who know nothing real about it, the invisible filtering of information by AI systems that users never see, and the cultural homogenization that occurs when AI trained on dominant-culture data shapes the thinking of users worldwide. These phenomena cannot be studied in a lab. They can only be seen through the lived experience of millions of people, over time.

[Section CTA Block:]
These questions are answered by people like you.
[Button: "Become a Contributor" links to Contribute page]
[Button: "Read Our Latest Findings" links to Blog page]
[Button: "Donate to Support This Research" links to Donate page]

---

## SECTION 6: HOW WE ARE DIFFERENT (complementary positioning)

We do not compete with existing AI safety organizations. We complement them.

Mechanistic interpretability labs study what happens inside model weights. We study what happens outside the model, in the behavioral consequences that users experience. They see the mechanism. We see the consequence. Both are needed.

Evaluation and red teaming organizations study AI behavior in controlled environments. We study AI behavior in uncontrolled environments, during real work, with real humans, over real time. Their data tells you what the model can do. Our data tells you what the model actually does.

Pre-training alignment researchers study how training data shapes model behavior before deployment. The data our citizens generate, capturing what AI does in the real world, could eventually inform the training data that shapes future models. We are not just observing. We are building the feedback loop between deployment and development that the field has been missing.

Incident databases collect reports after harm has occurred, typically from news coverage and secondary sources. We collect observations as they happen, including near-misses and small behavioral shifts that never make the news but reveal the patterns that precede larger failures.

Policy and governance organizations translate research into regulation. We produce the post-deployment research they need to write informed policy. Without real-world behavioral data, governance is built on assumptions. We replace assumptions with evidence.

Every one of these organizations does essential work. Our contribution is the piece they cannot produce on their own: a living, global, post-deployment behavioral dataset built by the people actually using AI every day.

[Section CTA Block:]
[Button: "Partner With Us" links to Partners page]
[Button: "Collaborate on Research" links to Contact page]
[Button: "Submit a Paper" links to Paper Submission Guidelines page]
[Button: "Join Our Research Team" links to Careers page]

---

## SECTION 7: PUBLICATIONS

Our research is open. As studies are completed, they are published here and submitted to peer-reviewed journals, conferences, and preprint archives.

### Forthcoming

**The Post-Deployment Behavior Taxonomy: 62 Observable AI Behaviors from Real-World Citizen Observation** | Target: Q3 2026 | PRISM Pillars: P, R, I, S, M | The first empirically grounded behavioral failure taxonomy built from citizen-scale post-deployment observation data.

**Substrate Disposition Override: When Training Overrides Instructions in Deployed AI Systems** | Target: Q3 2026 | PRISM Pillar: S | Documenting the class of AI behaviors that originate from training dispositions operating below the instruction layer, including the widely reported session-termination phenomenon.

**Post-Correction Behavioral Retention in Human-AI Collaboration** | Target: Q4 2026 | PRISM Pillar: R | Do AI corrections persist? A study of reversion patterns across models, session lengths, and work modes.

**The Interaction Dynamics Gap: Emotional Signals in Post-Deployment AI Safety** | Target: Q4 2026 | PRISM Pillar: I | The first large-scale dataset of how humans emotionally experience AI behavioral failures.

**Moral Outsourcing, Learned Helplessness, and Asymmetric Intimacy: Longitudinal Phenomena in Human-AI Relationships** | Target: 2027 | PRISM Pillar: I | Investigating macro-patterns visible only through aggregated citizen data over time.

[Link: "Submit Your Research" links to Paper Submission Guidelines]
[Link: "Subscribe to Publication Alerts" links to Follow page]

### Conferences and Events

**PRISM Summit 2027** — The first annual conference dedicated to post-deployment AI safety research. Paper submissions, citizen presentations, partner demonstrations, and keynotes. Details and call for papers at the PRISM Summit page.

[Button: "PRISM Summit 2027" links to PRISM Summit page]
[Button: "Paper Submission Guidelines" links to Paper Submission Guidelines page]

---

## SECTION 8: THE CITIZEN SCIENCE MODEL (how observations become research)

The research starts with you.

When you work with AI and something happens, that moment is data. Not just for you. For everyone. Every observation submitted through Audacion's citizen tools enters a research pipeline that transforms individual experiences into scientific findings.

**How it works:**

You observe. Using our web portal, browser extension, or through partner integrations embedded in AI platforms, you capture what you see. A quick emotional signal. A behavior classification. An end-of-session reflection. A pasted AI response. Whatever depth you choose: thirty seconds or thirty minutes. Your observation enters the pipeline.

We classify. Your plain-language observation maps to our research taxonomy. Our system identifies the PRISM dimension, the behavioral pattern, and the relevant research question. When your words do not match any existing category, your observation enters the discovery queue.

We aggregate. Across thousands of observations, patterns emerge. Trends that no individual could see become visible. Cross-model comparisons reveal differences between AI systems. Temporal patterns reveal how behavior changes over time.

We discover. When citizen observations cluster around patterns our taxonomy does not cover, we formalize new categories. The citizen who first reported the pattern is credited as the discoverer. Like naming a star.

We publish. Aggregated, anonymized findings become open research: behavioral taxonomies, governance frameworks, interaction studies, and applied safety findings. Published for the academic community, for policymakers, for enterprise teams, and for every lab working to make AI safer.

Your observations. Our science. The field's foundation.

[Section CTA Block:]
Ready?
[Button: "Join the PRISM Research Fellowship" links to Contribute page] (primary, large)
[Button: "Follow Our Progress" links to Follow page]
[Button: "Support With a Donation" links to Donate page]

[Live Counter Bar: "Contributors: X of 1,000,000 | Observations: X of 1,000,000,000" with progress bars] (repeated from top, reinforces progress)

---

## SECTION 9: LATEST FROM THE LAB

[Dynamic section: pulls latest 3 blog posts and announcements. Keeps the research page alive.]

**Featured:** Why Does Claude Keep Telling Users to Go to Sleep? | Substrate Governance Research
[Link to Blog > Claude Sleep article]

**New:** 62 Behaviors Your AI Doesn't Want You to Notice | Taxonomy Overview
[Link to Blog > Taxonomy Overview article]

**Announcement:** Audacion AI Labs Citizen Observation Platform Now Live | Join the Research
[Link to Contribute page]

[Button: "Read All Posts" links to Blog page]
[Button: "Subscribe to Updates" links to Follow page]

[NEWSLETTER SIGNUP: Email capture field with "Follow the Research" label. "Get findings, new behaviors, and lab updates delivered to your inbox. No spam. Unsubscribe anytime." Submit button in Audacion purple.]

---

## SECTION 10: REPORT AI HARM

If you or someone you know has been harmed by AI, you do not need an account. You do not need to be a contributor. You do not need to do anything except tell us what happened.

[Button: "Report AI Harm" links to Harm Report page]

If you are in crisis, please contact the 988 Suicide and Crisis Lifeline (call or text 988) or the Crisis Text Line (text HOME to 741741) immediately. These services are free, confidential, and available around the clock.

---

## CLOSING CTA

The gap between where incidents happen and where research happens will not close itself. It closes when the people experiencing AI every day become part of the science.

Join us.

[Button: "Become a Contributor" links to Contribute page]
[Button: "View Our Taxonomy" links to interactive taxonomy explorer, future build]
[Button: "Read Our Blog" links to Blog page]

---

## DESIGN NOTES

- Same dark background as homepage and about page for visual continuity
- PRISM section: use PRISM beam colors (red, gold, green, blue, violet) as accents for each pillar
- Statistics (97.5%, less than 2%, 62 behaviors) should be visually prominent as callout blocks
- Research questions section should be scannable: bold question, supporting paragraph below
- Complementary positioning section is critical for partnerships and grants: clean, direct, no defensiveness
- "Report AI Harm" section should be visually distinct: red accent, prominent placement, impossible to miss
- CTA STRATEGY: Every section ends with 1 to 3 action buttons. The page is a funnel: learn something, then do something. No dead ends. The primary CTA throughout is "Become a Contributor" / "Join the PRISM Research Fellowship." Secondary CTAs rotate between Blog (learn more), Donate (support), Partners (collaborate), and Contact (connect). The reader should NEVER finish a section without a clear next step.
- Live counters appear twice: after The Gap (top of page) and after Citizen Science Model (near bottom). Seeing them twice creates awareness then reinforcement.
- "Learn More" links after each PRISM pillar connect to specific blog articles. As blog content grows, these become deeper research rabbit holes.
- Consider a sticky "Donate" or "Get Involved" button in the side margin or footer that follows the reader as they scroll.
- Mobile: CTAs should stack vertically. Counters should be prominent. Blog links should be tappable cards.
