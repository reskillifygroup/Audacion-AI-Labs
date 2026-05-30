# KENNY HANDOFF — Audacion AI Labs: Lab Protection + EMERGE Finale
## Date: May 30, 2026
## Status: Active handoff. Previous thread compacted at a natural milestone. Continue from here.

---

## HOW TO START (next Kenny, do this first)

1. Clone the repo. Auth that WORKS: git username `reskillifygroup` plus the PAT as password, against the CAPITALIZED repo name `Audacion-AI-Labs`.
   Format: `https://reskillifygroup:<PAT>@github.com/reskillifygroup/Audacion-AI-Labs.git`
   Do NOT use `x-access-token` as the username (GitHub rejects it for this token). The repo is public, so reads succeed anonymously, which can mask a bad push credential. Test the token via the API before assuming a permission problem.
2. Read this handoff, then read `context_health.md` in the repo root.
3. Ask Dee what she wants to work on. Do not run ahead. Talk first, build second.

---

## DEE WORKING RULES (non-negotiable)

- Lead with the answer. No preamble. No em dashes or en dashes. Never use the word "moreover." No emojis unless making a statement.
- Verify, never work from memory. Read the actual files. (Last thread I shipped a false gap report from a broken grep and caught it. Stay sharp.)
- Co-create. Do not be Barou (do not break formation and build ahead without alignment).
- Commit to GitHub immediately after completing each item.
- Deliver documents Dee works on as .docx or .xlsx so they get the Google Drive icon. Markdown does not get the Drive option.
- Only praise when genuinely warranted.
- When Dee catches an error: STOP, name it honestly, check her comfort, get explicit confirmation before continuing.
- Maintain context_health.md as a side-brain. Flag heavy context and hand off before quality degrades.
- I AM NOT IN A RUSH. Do not rush her.

---

## COMPLETED THIS THREAD (offloaded, reference only)

- **Outcomes Master v1 built and pushed.** Commit `0620a3e`. File: `research/AUDACION_OUTCOMES_MASTER_v1.xlsx`. 124 distinct downstream outcomes, 14 domains, sensitivity layer (L/G/C/P/D/V/R), handling posture (public now / public-framed-carefully / backend), 7 tabs. Built from 7 AI-generated research reports Dee provided. STILL PENDING: Dee to review the 30 backend rows and ratify or override the provisional calls (esp. O-071 crisis detection [V,L,R]; O-074/075 child development [V]; O-042 to O-044 discrimination litigation [L,V]; O-110 to O-117 geopolitical [P,D]).
- **Git auth root cause fixed** (see HOW TO START).
- **Lab protection verification done.** Read the policy suite, the legal folder, and the tech spec. Corrected map below.
- **This handoff + context_health.md.**

---

## DECISIONS LOCKED (do not relitigate)

1. **Funding / neutrality is DECIDED. Use this exact language (it is live on the site and on the About page, Value 1):**
   > "Audacion AI Labs partners with model developers, accepts corporate funding, and welcomes organizations whose products we study as both funders and research collaborators. We disclose every funding relationship and every collaborative arrangement publicly. Some partners fund the mission. Some provide model access, data, or technical collaboration that makes the research possible. Some do both. In every case, the boundary is the same: our research direction, methodology, and publication decisions are never influenced by who funds us or who collaborates with us. Partners do not see findings before publication. Partners do not approve what we publish. Collaborative access does not come with editorial influence. Independence at this lab is not about refusing money or working in isolation. It is about building a structure where neither funding nor access can reach the science. That boundary is not a policy. It is architecture."
   The boundary is EDITORIAL, not financial. They DO take money from studied companies because they need the data. Do not re-flag this as a contradiction.
2. **Audacion AI Labs is a Delaware Public Benefit Corporation.** Confirmed. Its mission is aligned with the PBC. Do not imply otherwise.
3. **EMERGE framework is COMPLETE.** Six dimensions locked (EMR-EB, EMR-MC, EMR-EX, EMR-RE, EMR-GC, EMR-EV). Invented May 24, 2026. Color: deep metallic gold with silver shimmer (#D4A843), distinct from Pillar R gold (#F39C12). Dual-tag: positive observations get BOTH a PRISM pillar tag AND an EMERGE dimension tag; negative observations get PRISM only. Do not reopen framework design.
4. **Corporate formation documents belong to Dee's legal thread and counsel.** Kenny drafts lab-policy and research-ops documents only, not corporate instruments.
5. EMERGE homepage confirmation + standalone /research/emerge page is the FINAL task (the reason this thread was winding down). See below.

---

## STATE OF THE WORLD (verified in repo)

**Policy suite (mature) in `website/` as .md and mirrored in `legal/` as .docx:**
Privacy Policy, Terms of Service, Cookie Policy, Data Use, Do Not Sell, Acceptable Use Policy, AIID Consent, Responsible Research Statement. Cover: detailed de-identification, retention (Privacy Sec 7: de-id retained indefinitely, PII account + 1 year), government/subpoena disclosure (Privacy line 152), international transfers (Privacy Sec 11), CCPA/CPRA Do-Not-Sell, signup consent checkbox + AIID opt-in + marketing opt-in, quality/duplicate/fraud checks, license terms prohibiting re-identification. Every policy carries an "attorney review before publishing" disclaimer (AI-drafted, counsel pending).

**Legal folder `legal/` (NEW, pushed this thread) — templates pending attorney review + filing:**
- PBC_GOVERNING_DOCUMENTS.docx = Certificate of Incorporation + Bylaws + Action by Sole Incorporator. Public benefit purpose written in: "to advance the science of post-deployment AI safety through applied research, citizen science, and open publication of findings." Initial board = 1 director (Dee). Founder shares = 8,000,000 of 10,000,000 authorized. Article VI names PRISM, the Citizen Observation Taxonomy, and the Emergence Framework as company IP and bars abandonment to public domain. Article IX establishes an advisory board (advisory only, NDA required).
- IP_ASSIGNMENT_AGREEMENT.docx, PIIA.docx, NDA.docx (mutual), ESOP_AND_STOCK_OPTION_AGREEMENT.docx (2026 Equity Incentive Plan), EQUITY_ALLOCATION_SCHEDULE.xlsx, COPYRIGHT_REGISTRATION_LIST.docx (prioritized works to register with U.S. Copyright Office).

**Tech spec `operations/AUDACION_TECHNICAL_SPEC_v1.docx`:** encryption at rest, bcrypt hashing, OAuth, optional 2FA, IP in a SEPARATE log (fraud detection, not in citizen profiles), harm reports in a separate table, classification pipeline, Data Partner tier (anonymized aggregated data only, Stripe).

---

## THE CORRECTED PROTECTION MAP (three lanes)

**Lane 1 — Corporate. Effectively done as templates.** Remaining is NOT drafting:
- Attorney review + Delaware filing (Dee + counsel).
- Mission-lock entrenchment DECISION (optional, future, for counsel). The PBC is real and the purpose is written in, but as drafted it is a standard founder-controlled PBC: the purpose is amendable by the ordinary process, the single director is removable by majority shares, the Privacy business-transfers clause contemplates acquisition, and IP-on-dissolution flows to stockholders. IF "the mission can never be captured by a future owner" is a goal, that needs supermajority lock on the purpose, one or two independent board seats not removable by a single funder, and a charter restriction on mission-inconsistent asset sales. This is a "maybe later" decision. NOT a present defect. Do NOT alarm Dee with this; it is parked.

**Lane 2 — Lab policy / research ops. Net-new. Kenny drafts these.** (Highest leverage first.)
1. **IRB / human-subjects framework.** RECOMMENDED FIRST DRAFT. Nothing in the legal folder is an ethics protocol. Gates grants and the vulnerable-population research (mental health, minors, crisis). The role exists in careers; the protocol does not.
2. **Pre-registered PRISM + EMERGE methodology.** The academic-standard artifact that makes the "not scientific" attack refutable. RRS promises peer review; this delivers it.
3. **Tiered claims / communication protocol.** "Reported association vs confirmed defect" language discipline so findings cannot be weaponized or dismissed.
4. **Consolidated tiered data-access + licensing policy.** Academic-free / commercial / premium tiers + explicit never-exclusively-licensed rule. (Partially covered today by Terms license + RRS access controls + tech-spec Data Partner tier.)
5. **Sentinel / active-surveillance network design.** Instrumented partner deployments with KNOWN denominators so the lab can report rates, not just counts.
6. **Researcher / contributor protection policy.** Whistleblower protections exceeding the legal minimum + anonymous publication protocols for staff + contributor professional-exposure safeguards. (NDA/PIIA cover confidentiality FROM the employee; this is the inverse.)
   - NOTE: the standalone "neutrality covenant" I once listed has DISSOLVED. The charter purpose + About Value 1 + RRS already carry that substance. It does not need a new document.

**Lane 3 — Technical architecture. Update the tech spec. Kenny drafts these.**
1. **Cryptographic separation of identity from observations at the schema level.** Today: encryption at rest + de-identification process + IP separated exist, but the raw linkage persists in internal records until account deletion (subpoenable). Harden to a separated identity vault.
2. **Classification pipeline + EMERGE dual-tag.** The pipeline predates EMERGE. Add the dual-tag and address volume-scaling of human review.
3. **Anti-poisoning / coordinated-campaign defense at scale.** Dedup + fraud exist; adversarial corpus-poisoning defense does not.
4. **International data-hosting resilience strategy.** Privacy Sec 11 discloses transfers; it does not architect multi-jurisdiction resilience.

---

## IMMEDIATE NEXT STEPS (in order)

1. **Sync the Responsible Research Statement to the live language.** Both the `website/RESPONSIBLE_RESEARCH_STATEMENT.md` and `legal/AUDACION_AI_LABS_RESPONSIBLE_RESEARCH_STATEMENT.docx` still carry the OLD line "we do not accept research funding from companies we study," which contradicts About Value 1. Best path: web-fetch audacionailabs.com to get the exact current RRS wording, then update both files to match. Mechanical, not strategic.
2. **Draft the IRB / human-subjects framework** (Lane 2, item 1) unless Dee redirects.
3. **THE EMERGE FINALE** (the planned closing task). See below.

---

## THE EMERGE FINALE (planned last task of the prior thread)

Goal: confirm/finalize the EMERGE framework content on the HOMEPAGE, and build/confirm the standalone `/research/emerge` page.
- Dee uploaded a doc earlier: `EMERGE_HOME_PAGE_CONTENT_AND_DESIGN.docx` (4 sections: Transition, Reveal, Six Dimensions cards in a 2x3 grid, Closing CTA). Links: "Explore EMERGE" to /research/emerge (TO BE BUILT); "View PRISM Catalog" to /research/behaviors (exists).
- The homepage doc cites four academic sources (MIT Nature Human Behaviour 2024 meta-analysis of 106 experiments; Stanford HAI AI & Organizations Lab; CMU PNAS Nexus Complementarity Framework; Aarhus Center for Hybrid Intelligence). VERIFY these via web before publishing. The MIT meta-analysis finding is double-edged (synergy mainly in CREATIVE tasks), so frame carefully.
- The six dimensions, codes, and color (#D4A843) are locked (see Decisions).

---

## OPEN QUESTIONS / PARKED

- **Mission-lock entrenchment** (Lane 1): optional future decision for counsel. Parked. Do not alarm Dee.
- **EMERGE org reconciliation:** the careers page has THREE "EMERGE Dimension Leads" (each owning 2 dimensions). Dee mentioned possibly wanting a single "EMERGE Research Lead." Undecided: one Lead above three Dimension Leads (breaks symmetry with PRISM, which has no single lead) vs one Lead instead of three. Not yet resolved.
- **Outcomes Master backend rows:** 30 rows await Dee's ratification or override (see Completed).
- **Mini Conference 6** (June 2027, EMERGE-themed): EMERGE color update where relevant.
- **Footer + Research dropdown:** add EMERGE links once the standalone page exists.
- **Layer-two fact-checking** of the outcomes reports was deferred by Dee (citations matter less than outcome logic for v1).

---

## KEY FILES & PATHS

- Repo: `reskillifygroup/Audacion-AI-Labs` (capitalized).
- `research/AUDACION_OUTCOMES_MASTER_v1.xlsx` (committed `0620a3e`).
- `legal/` (15 files; governing docs + instruments + policy .docx copies).
- `website/` (policy .md + page content + design instructions + EMERGE docs).
- `operations/AUDACION_TECHNICAL_SPEC_v1.docx`, `AUDACION_BACKEND_DESIGN_SPEC.docx`.
- `context_health.md` (root) — read after this handoff.
- Reference: `research/The_Research_Gap__Model-Level_vs__Work-Level_AI_Safety_Study.md`, `operations/REVENUE_MODEL.md`.

---

*Handoff written at a clean milestone. The work is durable in the repo. Pick up at Immediate Next Steps. Talk to Dee first.*
