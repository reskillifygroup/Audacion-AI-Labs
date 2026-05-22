# REPLIT BUILD PROMPT — Audacion AI Labs Website
## Paste this into Replit. It has access to the repo for all content.

---

## WHAT THIS IS

Build the full website for Audacion AI Labs, a post-deployment AI safety research lab. This is a real research organization, not a startup demo. The site needs to look and feel like a legitimate research institution: credible enough for grant reviewers, accessible enough for everyday people, and distinctive enough to not look like every other AI site on the internet.

ALL content is in the GitHub repo under /website/. Each page has a .md file with full text, section structure, CTAs, and design notes. DO NOT write placeholder copy. Use the actual content from the repo files.

---

## DESIGN REFERENCES (what to aim for)

Look at these sites for design tone. We are NOT copying them. We are matching their level of credibility and restraint:

- anthropic.com/research (typography-driven, minimal, lots of white space, serious)
- deepmind.google/research (data-driven, real imagery, structured)
- hai.stanford.edu (academic but modern, clean navigation)
- cohere.com/research (community-focused, open science energy)

DO NOT make this look like a SaaS landing page, a startup pitch deck, or a Y Combinator demo day site. No gradient text on headlines. No generic hero illustrations. No "smooth scroll reveal" animations on every section. No placeholder energy.

---

## BRAND IDENTITY

**Logo:** The Prism "A" — a prism shape forms the letter A, with five color beams refracting out the right side. Logo file is in the repo: /website/Audacion AI Labs Logo Design Idea.png

**Brand Colors (exact hex codes):**
- Primary Brand Purple: #6C3483 (headings, CTAs, accent elements)
- PRISM Pillar P (Post-Deployment Behavior): #C0392B (Red)
- PRISM Pillar R (Runtime Research): #D4AC0D (Gold)
- PRISM Pillar I (Interaction Dynamics): #27AE60 (Green)
- PRISM Pillar S (Substrate Governance): #2980B9 (Blue)
- PRISM Pillar M (Multi-Agent Safety): #8E44AD (Violet)
- Dark Background (marketing pages): #1C1C1C
- Light Background (citizen tool): #FFFFFF with #F8F9FA for cards
- Harm Report Accent: #E74C3C
- Text (dark mode): #FFFFFF primary, #BDC3C7 secondary
- Text (light mode): #1C1C1C primary, #7F8C8D secondary

**Typography:**
- Primary: Inter (Google Font) — all headings, body, UI
- Monospace: JetBrains Mono — observation IDs, behavior codes, technical data
- Headings: Inter Bold or Semi-Bold
- Body: Inter Regular, 16px base

**PRISM colors are accents, not themes.** They appear on pillar cards, observation card borders, section dividers, and badge designs. They never dominate a page. They orient.

---

## TWO VISUAL MODES (same domain, different treatments)

**Mode 1: Public Marketing Pages (dark background #1C1C1C)**
Pages: Home, About, Research, Team, Blog, Careers, Contact, Contribute, Donate, Support the Research, Partners, Press, Training, PRISM Summit, Paper Submission Guidelines, Start Observing, Sign Up / Get Started, Report AI Harm, Privacy Policy, Terms and Conditions, Cookies Policy, Taxonomy Explorer, Services, Sponsored Research, Premium Reports, Consulting and Advisory, Follow the Research

These pages tell the world what the lab does, why it matters, and how to get involved. Dark background. White and muted gray text. PRISM colors as accents. The tone is: bold, independent, scientific without being academic. A research lab that a founder built, not a university department.

**Mode 2: Citizen Tool (light background #FFFFFF, with dark mode toggle)**
Pages (behind login): Dashboard, Submit Observation, My Observations, EOT, Profile, Leaderboard, Investigation Mode, Settings, Tools/Downloads

These pages are where citizens submit observations, track their contributions, and access the research tools. White background by default. Light gray (#F8F9FA) for cards and panels. Dark mode toggle in settings. PRISM colors on observation card left-borders (each observation shows its pillar color). Audacion purple for navigation and buttons. Clean, functional, SaaS-standard.

**Exception:** Report AI Harm page uses LIGHT background even though it is a public page. This is a care page, not a marketing page. A person in distress should not be staring at a dark screen.

---

## PERSISTENT HEADER (every page)

**Left side or center:** Live counters. Two animated counters showing:
"Contributors: [X] of 1,000,000" and "Observations: [X] of 1,000,000,000"
with progress bars underneath. Audacion purple fill. These update from the system_metrics database table. They are visible on EVERY page automatically because they live in the header.

**Right side:** Two persistent buttons:
[Donate] — Audacion purple, styled button
[Report AI Harm] — Red (#E74C3C), distinct from all other UI. Cannot be missed.

These two buttons appear on every single page of the site. They are not part of the nav. They are persistent action buttons.

---

## TOP NAVIGATION

About (dropdown): About Audacion AI Labs, Team, Press, Partners
Research (dropdown): Our Research, Taxonomy Explorer, Publications
Services (dropdown): Sponsored Research, Premium Reports, Consulting and Advisory, Training
Get Involved (dropdown): Contribute, Support the Research, Start Observing, Sign Up / Get Started, Careers, Follow the Research
Blog (no dropdown)
PRISM Summit (dropdown): Summit Overview, Paper Submission Guidelines
Contact (no dropdown)

---

## FOOTER (four columns)

Column 1 "About": About, Team, Press, Partners, Privacy Policy, Terms and Conditions, Cookies Policy
Column 2 "Research": Our Research, Taxonomy Explorer, Publications, Paper Submission Guidelines
Column 3 "Get Involved": Contribute, Sign Up / Get Started, Careers, Training, Follow the Research, Support the Research
Column 4 "Support": Donate, Services, PRISM Summit, Contact

Bottom row: Copyright 2026 Audacion AI Labs. Social links. Fact sheet download link (lead magnet, PDF in repo at /website/FACT_SHEET.pdf).

---

## PAGE-BY-PAGE BUILD INSTRUCTIONS

For each page below, the full content is in the repo at /website/[FILENAME].md. Read the .md file. Use the actual text. Follow the section structure. Implement the CTAs. Follow the DESIGN NOTES at the bottom of each .md file.

### Public Pages (dark background unless noted)

| Page | File | Key Notes |
|------|------|-----------|
| Home | HOME.md | Hero stat (97.5%), PRISM beam visual, live counters, scroll prompt |
| About | ABOUT.md | Origin story, mission, vision, values |
| Research | RESEARCH.md | 10 sections. Mission/vision, The Gap, PRISM five pillars (colored accents per pillar), Featured Research, Research Questions, How We Are Different, Publications, Citizen Science Model, Latest from Lab (dynamic blog pull), Report Harm. CTAs throughout. |
| Team | TEAM.md | Founder bio with photo placeholder, hiring sections, advisory board placeholder |
| Blog | BLOG.md | Blog listing page. Individual posts TBD. |
| Careers | CAREERS.md | Mission-driven hiring. Link to ATS (external: Crelate or ZipRecruiter) |
| Contact | CONTACT.md | Contact form, email, phone (424) 999-0548 |
| Contribute | CONTRIBUTE_TO_THE_RESEARCH.md | How citizens contribute, three depths |
| Donate | DONATE.md | Stripe integration, donation tiers |
| Support the Research | SUPPORT_THE_RESEARCH.md | Institutional and individual support options |
| Partners | PARTNERS.md | Partnership tiers, Partner API description |
| Press | PRESS.md | Media kit, press releases, journalist resources |
| Training | TRAINING.md | PRISM Professional Certification, Learning Academy |
| PRISM Summit | PRISM_SUMMIT.md | Annual conference overview |
| Paper Submission | PAPER_SUBMISSION_GUIDELINES.md | Academic submission guidelines |
| Follow the Research | FOLLOW.md | Newsletter signup, social links, update preferences |
| Start Observing | START_OBSERVING.md | Three depths explained, behaviors in plain language, fellowship tiers with LinkedIn credential, platform compatibility, points system |
| Sign Up / Get Started | SIGN_UP_GET_STARTED.md | Account creation form, post-signup dashboard, FAQ. Light background for the form section. Google/Apple OAuth. |
| Report AI Harm | REPORT_AI_HARM.md | LIGHT BACKGROUND. Crisis resources at top (red accent). Three paths: platform tool, standalone form, phone (424) 999-0548. Form fields specified in the .md. |
| Taxonomy Explorer | NEW — build as interactive page | Public, no login. Five PRISM pillar cards (colored). Click a pillar, see its behaviors. Click a behavior, see plain-language description. Future: live aggregate counts per behavior. |
| Services (main) | NEW — create from nav structure | Landing page for paid services. Links to sub-pages. |
| Sponsored Research | NEW | Commission specific research studies |
| Premium Reports | NEW | Quarterly PRISM data access |
| Consulting and Advisory | NEW | Enterprise consulting services |
| Privacy Policy | NEW | Standard privacy policy for citizen data platform |
| Terms and Conditions | NEW | Terms of service including data export no-resale clause |
| Cookies Policy | NEW | Cookie consent and policy |

### PRISM Pillar Pages (individual research pages, dark background)

| Page | File | Accent Color |
|------|------|-------------|
| Pillar I: Interaction Dynamics | PRISM_PILLAR_I_INTERACTION_DYNAMICS.md | Green #27AE60 |
| Pillar P: Post-Deployment Behavior | TBD (next to be written) | Red #C0392B |
| Pillar R: Runtime Research | TBD | Gold #D4AC0D |
| Pillar S: Substrate Governance | TBD | Blue #2980B9 |
| Pillar M: Multi-Agent Safety | TBD | Violet #8E44AD |

Each pillar page follows the same 8-section template (see Pillar I as the format model):
1. Pillar Overview
2. Why It Matters
3. What We Study (three layers: Moment, Session Arc, Long Arc)
4. Methodology
5. Current Findings
6. Forthcoming Publications
7. How to Contribute
8. A Note on Origins

---

## CITIZEN TOOL PAGES (light background, behind login)

These are Phase 1 backend features. Build the logged-in experience:

**Dashboard:** Observation counter (personal), points and tier with LinkedIn credential badge, global counters, "submit your first observation" prompt, quick-start options.

**Submit Observation:** Three-path form. Default: text box ("What happened? Describe it in your own words.") with system-suggested behavior matches. Toggle to browse by PRISM pillar. Toggle to see all 62 behaviors. Emotion selector. Optional response capture (paste AI response). Submit.

**My Observations:** Card view of all submitted observations. Each card shows: behavior name, emotion tag, timestamp, depth level, PRISM pillar color as left border. Expandable for full details.

**EOT (End-of-Session Reflection):** Two panels side by side. Left: AI's self-assessment. Right: citizen's reflection. Independent entries. Neither sees the other until both are submitted.

**Profile:** Display name, tier badge, total observations, total points, discoveries, data export button, account settings, LinkedIn credential link.

**Leaderboard:** Top contributors by points. Tier distribution. Anonymized unless citizen opts to show display name.

---

## TECHNICAL REQUIREMENTS

**Full technical specification is in the repo at:** /operations/AUDACION_TECHNICAL_SPEC_v1.docx

This contains: 13 database tables with full schemas, 5 user roles, Partner Integration API endpoints, security requirements, harm report flow, media handling, Stripe integration, phased build sequence, and the complete design brief.

**Architecture:** Enterprise-ready. Multi-tenant. Multi-user. Build this to scale from hundreds to millions of users. Four user roles (Citizen, Research Team, Data Partner, Admin) with different access levels, dashboards, and permissions. Data isolated between roles.

**Security:** The tech spec has 10 security requirements. The short version: production-grade authentication (protect against brute force, session hijacking, unauthorized access). All sensitive data encrypted. Harm reports get the highest protection level (restricted access, audit-logged). Automated backups outside the primary platform. Rate limiting on all endpoints. No secrets in code or Git. GDPR/CCPA compliance. Build for portability (no platform lock-in). Show us what security measures you are implementing. We trust your platform expertise. Meet the requirements however works best on your platform.

**Key integrations:**
- Stripe: donations
- Credly (or equivalent): LinkedIn credential issuance for fellowship tiers
- Google/Apple OAuth: frictionless signup
- AIID (future): incident database submission with citizen consent

**Phased build:**
- Phase 1: Website + web portal + API + citizen signup + observation form + Stripe + counters + LinkedIn credentials
- Phase 2: Browser extension
- Phase 3: Research dashboard (internal)
- Phase 4: Partner Integration API

---

## WHAT NOT TO DO

- No gradient text on headlines
- No generic hero illustrations or abstract AI imagery
- No smooth-scroll-reveal animations on every section
- No placeholder text anywhere. Every page has real content in the repo.
- No cookie-cutter "built with AI" aesthetic. This should look like it was designed by humans who care about the content, not generated by a prompt.
- No lorem ipsum. No "coming soon" on pages that have content.
- The PRISM colors are accents, not a rainbow theme. Use them deliberately and sparingly.
- Do not skip the Report AI Harm button. It must be on every page. Red. Persistent. Impossible to miss.
- Do not skip the live counters. They are a core brand element.

---

## THE ENERGY

This is a research lab built by a Black American woman who spent 30 years in workforce development and saw something in AI that the safety field was not studying. The site should feel like walking into a space that takes you seriously. Not corporate. Not academic. Not flashy. Real. The content does the work. The design gets out of the way and lets the content land.

If a grant reviewer, a journalist, a potential citizen contributor, and a teenager who was just emotionally manipulated by an AI companion all land on this site on the same day, every one of them should find what they need within two clicks.

Build it like it matters. Because it does.
