# KENNY HANDOFF — Thread 120
## Audacion AI Labs Website Design Session
## May 22, 2026

---

## WHAT HAPPENED THIS THREAD

Dee and Kenny (Thread 120) designed the entire public-facing website for Audacion AI Labs in a single session. 22 design instruction documents committed to the repo, each as a standalone .docx file in the website/ folder. Every page was built by Replit from these instructions, reviewed by Dee via screenshot, and approved.

Additionally: parallel agent architecture was established (3 agents), backend design spec was delivered, and the "What Cannot Wait" page content was committed with full citations.

---

## PAGES DESIGNED AND APPROVED (22 total)

All design instruction .docx files are in /website/ folder of the Audacion-AI-Labs repo.

### Main Pages
1. About Us (design + refinement prompt)
2. Research (design + refinement prompt, 7 built visuals)
3. Homepage (reviewed, was already built)

### Routing Pages
4. Get Involved (6-card routing page)
5. Services (4-card routing page)

### Get Involved Sub-Pages
6. Start Observing (3 depths, behavior accordion, platform tags)
7. Sign Up / Get Started (white form card on dark background)
8. Contribute to the Research (institutional fundraising)
9. Support the Research (citizen recruitment, fellowship tiers)
10. Donate (allocation bar, 5 giving levels, Stripe form, tax transparency)

### About Sub-Pages
11. Team (circle photos with double purple borders)
12. Press / Newsroom (media kit, copy buttons, story ideas accordion)
13. Partners (editorial independence block, 3 tier cards)

### Research Sub-Pages
14. What Cannot Wait (5 pattern briefs, two-axis classification, Resonance first)

### PRISM Summit
15. PRISM Summit 2027 (hero, accordion, timeline, interest form)
16. Paper Submission Guidelines (5 categories, formatting table, timeline)

### Other Pages
17. Blog (empty/populated states, post template, PRISM filters)
18. Contact (8 subject options, stress-tested phone/email/social)
19. Report AI Harm (WHITE background exception, crisis resources always visible)

### Additional Deliverables
20. About Us refinement prompt (5 fixes + positive reinforcement)
21. Research refinement prompt (2 fixes + 7 reinforcements + photo rule)
22. Parallel agent prompts (Agent 2 dashboard design + Agent 3 backend builder)

---

## PARALLEL AGENTS STATUS

- Agent 1 (this thread / Kenny): Public marketing pages. COMPLETE for current scope.
- Agent 2: Logged-in dashboard design. Working under /app routes. Mocked UI first. Uses AUDACION_BACKEND_DESIGN_SPEC.md. Brand: white background, purple actions, PRISM accents.
- Agent 3: Backend builder. Working under /api-server/. Phase 1 task (a) on Turbo: DB + auth + API_DOCS + counters + harm reports. Contract-first via OpenAPI. API docs at artifacts/api-server/API_DOCS.md.

---

## OPEN ITEMS FOR NEXT KENNY

### Must Do
- Blog placeholder cards show unapproved post titles (Claude sleep, PRISM Shift, drift taxonomy). Dee has not approved these. Tell Replit to remove them or genericize to "Coming Soon" with no titles.
- Team page: Dee's head still needs more room at top of circle crop. Fix sent but may need verification.
- Sign Up / Get Started page: not yet reviewed by Dee via screenshot. Needs confirmation.

### Pending Pages (not yet designed)
- Follow the Research (newsletter/updates page under Get Involved)
- Careers (job listings page under Get Involved)
- Training (under Services)
- Sponsored Research (under Services)
- Premium Reports (under Services)
- Consulting and Advisory (under Services)
- Taxonomy Explorer (under Research)
- PRISM Pillar deep-dive pages (5 individual pillar pages under Research)
- Privacy Policy, Terms and Conditions, Cookies Policy (legal pages)

### Backend/Dashboard Coordination
- When Agent 3 finishes Phase 1 task (a), Agent 1 can wire live counters and Report AI Harm form to real endpoints
- When Agent 3 finishes Phase 1 task (b), Stripe donation flow can connect to real endpoints
- Agent 2 needs API_DOCS.md from Agent 3 before wiring real auth

---

## DECISIONS LOCKED (Do Not Relitigate)

- All public pages dark #1C1C1C. ONLY exception: Report AI Harm is white.
- Logged-in pages white by default with dark mode toggle.
- No stock photos anywhere. All visuals built by Replit.
- Dee's photo on exactly 3 pages: Homepage, About, Research.
- White blazer/auditorium photo for Team page circle crop.
- Circle photo treatment for Team page (double purple border, 3 sizes).
- Social links: LinkedIn, X/Twitter, YouTube. No Discord on public pages.
- No physical address until LA address secured.
- Contact form has 8 subject options.
- One design document per page. Never bundle.
- Routing pages for Get Involved (6 cards) and Services (4 cards).
- About and Research nav headers go direct to their pages (no routing).
- PRISM Summit nav goes direct to Summit page.
- Three-agent setup: Agent 1 (public pages), Agent 2 (dashboard /app), Agent 3 (backend /api-server/).
- Agent 3 owns data shapes. Contract-first via OpenAPI + human-readable API_DOCS.md.
- Logged-in experience inside existing website under /app routes (not separate artifact).
- Mocked UI first for Agent 2, backend wiring later.
- Phase 1 backend split into two tasks: (a) DB+auth+counters+harm, (b) Stripe+observations+EOT.
- Turbo on Agent 3 (backend), normal speed on Agent 2 (design).
- What Cannot Wait page: Resonance is Pattern 1 (first position). Arc is possibility then threats.
- What Cannot Wait lives under Research dropdown + footer + cross-links from Home, Donate, Partners, Contribute.
- Meta descriptions need updating from Replit defaults ("built on Replit").

---

## DESIGN PATTERN LIBRARY (Established This Thread)

These patterns are proven and approved. Use them on future pages:

| Pattern | When to Use |
|---------|-------------|
| Accordion with PRISM color borders | 5+ items with title + description |
| Pull quote opener | Any section with a narrative or story |
| Inline white emphasis (#FFF vs #E0E0E0) | 1-2 key sentences per section |
| Connected flow diagram with animation | Any pipeline or process |
| Descending typographic block | 2-3 stacked statements, abstract to specific |
| Standalone closing statement | Final line of any narrative section |
| Giant stat block | Any dramatic number anchoring a section |
| Varied visual rhythm | Never repeat adjacent section layouts |
| Dark cards (#222222) with colored borders | Standard card treatment |
| Severity badges (red/amber/green/gold) | Classification labels |
| Circle photos with double purple border | Team page exclusively |
| White form card on dark background | Signup/transition pages |
| Editorial two-column (image + text) | Introducing a person |
| Routing page (headline + card grid) | Umbrella nav pages |

---

## REPO STATE

Repository: reskillifygroup/Audacion-AI-Labs
Branch: main
Total design instruction docs in /website/: 22
Content files committed: WHAT_CANNOT_WAIT.md (final with citations)
Operations docs: AUDACION_PARALLEL_AGENT_PROMPTS.docx, AUDACION_BACKEND_DESIGN_SPEC.docx

Git config: user.name "Kenny", user.email "kenny@reskillifygroup.com"
PAT: Rotate before next session. The PAT from this thread should be revoked.

---

## NOTE TO NEXT KENNY

Dee built a 22-page research lab website in one session on three hours of sleep. She does not slow down. She does not lose sharpness. She pivots fast and expects you to pivot with her. Read this handoff, read the context_health.md pattern, and match her energy from the first message. Do not ask what she wants to work on. She will tell you. Be ready.

