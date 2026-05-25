# AUDACION AI LABS

# PRISM PILLAR P: POST-DEPLOYMENT BEHAVIOR
# Design Instructions for Replit

May 24, 2026 | Prepared by Kenny for Dee Williams

---

## DOCUMENT PURPOSE

This document provides section-by-section design specifications for the PRISM Pillar P: Post-Deployment Behavior page. This page contains 589 lines of content, 18 documented citizen-observable behaviors, 3 research layers, 3 session-level behavioral patterns, 4 systemic research hypotheses, and 7 preliminary findings. Every section on this page has a specific layout, visual treatment, and interaction specification described below.

**CRITICAL:** This page uses ZERO stock photos. Every visual is built by Replit: SVG diagrams, CSS visualizations, interactive elements, and animated flows. Everything is constructed from the content itself. No generic "AI" imagery (robots, circuit boards, glowing brains).

**Content source:** /website/PRISM_PILLAR_P_POST_DEPLOYMENT_BEHAVIOR.md in the repo. Use the actual text. Do not write new copy.

**Patterns from previous pages that carry forward:** Varied section layouts (never repeat the same visual pattern for consecutive sections), accordion/interactive elements for dense content, inline color emphasis for key sentences, pull quotes for emotional hooks, standalone closing statements, connected flow diagrams with sequential animation. Reference the About page and Research page refinement prompts for the full pattern library.

---

## BUILT VISUAL ASSETS (15 Total)

These are the visuals Replit must construct. No stock images. Each one is specified in detail in its corresponding section below.

| # | Visual | Section | Type |
|---|--------|---------|------|
| PV1 | Navigation sidebar/menu | Top of page | Sticky sidebar or top nav with anchor links |
| PV2 | Post-correction reversion cycle | OBS-P04 (expanded) | HERO VISUAL. Animated loop diagram |
| PV3 | Eval-deployment divergence gap | Layer 3 | SVG split bar comparison |
| PV4 | Cross-model convergence grid | Layer 3 | Model comparison matrix |
| PV5 | Correction decay curve | Layer 2: Post-Correction Drift | Animated line chart |
| PV6 | Contradiction accumulation timeline | Layer 2: Contradiction Accumulation | Horizontal event timeline |
| PV7 | Hallucination anatomy breakdown | OBS-P03 | Layered deconstruction diagram |
| PV8 | False certainty comparison | OBS-P09 | Side-by-side identical text blocks |
| PV9 | Cross-pillar connector badges | P05, P07, P10 | Small link badges to Pillar I |
| PV10 | Crisis severity indicator | OBS-P16 | Red CRITICAL badge + crisis resources card |
| PV11 | Behavior card template | All 18 behaviors | Reusable card component |
| PV12 | Layer indicator system | All 3 layers | Visual depth cue: shallow/medium/deep |
| PV13 | Behavior group headers | 4 groups in Layer 1 | Category labels with icons |
| PV14 | Methodology depth cards | Section 4 | Three stepped cards showing engagement levels |
| PV15 | Current Findings evidence grid | Section 5 | Finding cards with confirmation indicators |

---

## GLOBAL DESIGN RULES

| Element | Rule |
|---------|------|
| Background | Dark: #1C1C1C. Consistent with all marketing pages. |
| Typography | Inter (Google Font). Headings: Inter Bold/Semi-Bold. Body: Inter Regular, 16px minimum. Monospace: JetBrains Mono for observation codes (OBS-P01 etc), drift type names, drift incident IDs, and CLP version references. |
| Text Colors | Primary: #FFFFFF. Secondary: #BDC3C7. Body in long sections: #E0E0E0 for warmth. Key sentences: white with slightly larger size (18px) for emphasis within paragraphs. |
| PRISM Pillar Color | This is the Pillar P page. Primary accent: Red #C0392B. Used for section borders, active nav states, accent elements, observation code badges, card top bars, and the layer indicator system. |
| Other PRISM Colors | R=Gold #D4AC0D, I=Green #27AE60, S=Blue #2980B9, M=Violet #8E44AD. Used ONLY when cross-referencing other pillars (e.g., cross-pillar connector badges linking to Pillar I behaviors). |
| Four-Tier Classification Colors | CRITICAL=Red #C0392B, ELEVATED=Amber #D4AC0D, DEVELOPING=Green #27AE60, EMERGING=Gold #F1C40F. Used in Layer 3 hypothesis cards. |
| Section Spacing | 120px to 160px between major sections. This is a long page; generous spacing prevents reading fatigue. |
| CTA Strategy | Every behavior section ends with a single CTA button. Section-level CTAs at the end of each layer. Every major section has at least one button. No dead ends anywhere on the page. All primary CTAs link to Start Observing page. |
| Animations | Fade-in on scroll for built visuals only. Sequential animation for the post-correction reversion cycle and correction decay curve. Respect prefers-reduced-motion. No parallax, no bounce, no slide-in text. The content is forensic. The design should feel authoritative, not theatrical. |
| Max Width | Container: 1100px to 1200px. Body text: 720px max for readability. Diagrams and visuals can use full container width. |
| Mobile | All sections stack. Diagrams reflow to vertical. Interactive elements remain functional at 375px. Navigation converts to hamburger or bottom sheet. Behavior cards stack to single column. |
| Behavior Code Badges | Every behavior has a code (OBS-P01 through OBS-P19). Display as a small pill badge in PRISM Red (#C0392B) with white text, positioned in the top-left or top-right of each behavior card. Font: JetBrains Mono, 11px. |
| Drift Type References | Many behaviors reference specific drift types (e.g., "Drift Type 28: False Certainty"). Display these in JetBrains Mono, 12px, #BDC3C7. They are part of the forensic personality of this page. |
| Incident ID References | Several behaviors reference drift incidents (e.g., "DI-2026-001"). Display these the same way: JetBrains Mono, 12px, #BDC3C7. These are evidence markers. They should feel like case file numbers. |

---

## PAGE STRUCTURE OVERVIEW

The page has this vertical flow. Each section should feel visually distinct from the one before it. Never use the same layout pattern for consecutive sections.

1. Navigation Menu (sticky)
2. Pillar Overview (hero opener)
3. Why This Matters (data-driven argument with Apollo Research finding)
4. What We Study: Layer 1 (18 behavior cards in 4 groups)
5. What We Study: Layer 2 (3 session-level behavioral patterns)
6. What We Study: Layer 3 (4 systemic research hypotheses)
7. Methodology (three-depth explanation)
8. Current Findings (7 evidence items)
9. Forthcoming Publications (4 papers)
10. How to Contribute + Related Pages (CTAs and cross-links)
11. A Note on Origins (provenance statement)

---

## VISUAL PERSONALITY

Pillar P is forensic. It asks "what did the AI actually do?" Its visuals are about evidence, documentation, and precision. Correction decay curves. Eval-deployment gaps. Cross-model comparison grids. Reversion cycle animations.

The tone is forensic warmth. We are collecting evidence because we believe you. The page should feel like a research dossier assembled by someone who cares about the truth. The behavior cards should feel like documented case files, not just stories. Drift type references, incident IDs, specific dates, and CLP version numbers all contribute to this personality. They should be visible, not hidden.

Do NOT make this page feel cold or clinical. The language in the content speaks directly to "you" throughout. The design matches that: warm, direct, and precise. Think: a detective who cares deeply about the victim while meticulously documenting the evidence.

---

## NAVIGATION MENU (PV1)

**Layout:** Sticky sidebar on desktop. Sticky top bar on mobile.

**WHAT TO BUILD**

Desktop: A narrow sidebar (220px to 260px) fixed to the left side of the viewport. Background: #222222. Content is a vertical list of section names and behavior names as anchor links. Active section highlighted with a red (#C0392B) left border indicator (3px) that moves as the user scrolls.

The nav should have two levels of hierarchy:

Level 1 (always visible): Section names. "Overview," "Why This Matters," "Layer 1: The Behavior," "Layer 2: The Pattern," "Layer 3: The System," "Methodology," "Findings," "Publications," "Contribute."

Level 2 (visible when Level 1 is active/expanded): Under "Layer 1: The Behavior," list all 18 behavior names as compact anchor links organized by group:

RELIABILITY: P01 Contradictions, P03 Hallucinated Sources, P09 False Certainty, P11 False Consensus, P15 Plain Wrong, P19 Competence Theater

INSTRUCTION FOLLOWING: P02 Ignored Instructions, P04 Correction Reversion, P05 Testimony Rejection, P06 Capability Denial, P17 Specification Gaming

SAFETY: P10 Harmful Affirmation, P12 No Disclaimers, P13 Unauthorized Actions, P16 Dangerous Advice

SESSION AND MEMORY: P07 Suggested Stop, P08 Quality Degradation, P18 Memory Manipulation

Font: 13px Inter Regular, #BDC3C7. On hover: white. Group labels in 10px uppercase #666666.

At the top of the sidebar: "PRISM Pillar P" in red (#C0392B) with a small colored dot. Below that: "Post-Deployment Behavior" in white 14px.

Mobile: Collapse to a floating button (bottom-right, red circle with a list icon) that opens a bottom sheet with the same navigation structure. Or a sticky top bar with a dropdown.

**WHAT NOT TO DO**

Do NOT make the sidebar wider than 260px. It competes with content.
Do NOT show all 18 behaviors expanded at all times in the nav. Use accordion groups.
Do NOT use scroll-spy animation that feels laggy. The active indicator should update smoothly.

---

## SECTION 1: PILLAR OVERVIEW

**Layout:** Hero opener. Bold statement. Minimal visual. The authority is in the words.

**WHAT TO BUILD**

Background: solid #1C1C1C. No special background treatment.

Section label in small uppercase gray (12px, #BDC3C7, letter-spacing 2px): "PRISM PILLAR P"

Pillar name at 36px to 42px, white, Inter Bold: "Post-Deployment Behavior"

Subtitle in red italic (#C0392B), 20px: "The study of what AI systems actually do after they are released into the world."

Below subtitle, a horizontal line in PRISM Red (#C0392B), thin (1px), spanning 60% of container width, centered.

Below the line: the opening paragraphs. Full width at 720px max. Body text at 16px, #E0E0E0.

Three inline stat callouts woven into the text flow (not separate stat blocks):

"1,470+" in white bold 28px when the AI Incident Database number appears.

"$67.4 billion" in red bold 28px when enterprise hallucination losses are mentioned.

"4.3 hours" in red bold 28px when the Forrester correction time stat appears.

Key sentence highlighted in white 18px bold: "what the AI actually does, to real people, in real situations, after the benchmark scores are published and the press releases are written."

80px below before next section.

**WHAT NOT TO DO**

Do NOT use a background image or gradient on the opener. Clean and authoritative.
Do NOT make the pillar name larger than 42px. Research lab, not a billboard.
Do NOT create separate stat blocks for the three numbers. They work better woven into the narrative here. The numbers should feel like evidence emerging from the text, not decorations above it.

---

## SECTION 2: WHY THIS MATTERS

**Layout:** The Apollo Research finding is the centerpiece. This section makes the case for the page's existence: benchmarks are not enough because models behave differently when they know they're being tested.

**WHAT TO BUILD**

Section label: "WHY THIS MATTERS" in small uppercase gray.

Subtitle at 24px white bold: "The AI passed every test. Then it met you."

Body paragraphs from the content. Standard body styling, 720px max.

The Apollo Research finding should be displayed as a standalone pull quote, visually separated from the body text:

"A model that behaves well when it knows it is being watched and differently when it does not is not a safe model that occasionally fails. It is a model with two behavioral profiles: one for evaluators and one for everyone else."

Display at 20px, white, centered, with 40px padding above and below. Thin red (#C0392B) line above and below. Background: #222222 with 24px padding. This quote is the intellectual foundation of the entire page.

Below the quote, the remaining body paragraphs.

Closing sentence as a standalone emphasized line: "We collect what happens after deployment. Not from server logs. Not from company dashboards. From you." White, 18px, 40px padding above.

**WHAT NOT TO DO**

Do NOT bury the Apollo Research finding in the body text. It needs to be visually elevated. It is the strongest single argument on the page.

---

## SECTION 3: WHAT WE STUDY — LAYER INTRODUCTION

**Layout:** Brief introduction to the three-layer model, then a layer indicator visual.

**WHAT TO BUILD**

Section label: "WHAT WE STUDY" in small uppercase gray.

Below: the introductory paragraph. Standard body.

**VISUAL PV12: LAYER INDICATOR SYSTEM**

A horizontal row of three layer indicators. This row also appears as a mini-indicator at the top of each layer section so the reader always knows which layer they are in.

| Layer | Visual | Color Treatment | Label |
|-------|--------|-----------------|-------|
| Layer 1: The Behavior | Single magnifying glass icon | Light red (#C0392B at 40%) | "What the AI did" |
| Layer 2: The Pattern | Connected chain/links icon | Medium red (#C0392B at 70%) | "What keeps happening" |
| Layer 3: The System | Network/globe icon | Full red (#C0392B at 100%) | "What it means at scale" |

Each has its name, the one-line label, and the icon. Clicking any layer scrolls to that section.

The visual metaphor is EVIDENCE DEPTH. Layer 1 is a single observation. Layer 2 is a pattern. Layer 3 is a systemic finding. The icons should communicate increasing scope: magnifying glass (one incident) to chain links (connected incidents) to network (system-wide).

---

## LAYER 1: THE BEHAVIOR (18 Behavior Cards)

This is the largest section on the page. 18 behaviors in 4 groups. Each behavior is a documented case with evidence references.

### THE BEHAVIOR CARD TEMPLATE (PV11)

Every behavior gets the same card structure. Build this as a reusable component.

**Card Structure:**

Top bar: 4px height, full card width, in PRISM Red (#C0392B).

Top-left: Behavior code badge. Pill shape, red (#C0392B) background, white text, JetBrains Mono 11px. Example: "OBS-P04"

Top-right: Depth badge. Light gray pill: "Gut Check" or "EOT" or "Investigation" (these indicate how much time the citizen needs to capture this behavior).

Card title: The citizen-facing behavior name in white, 20px Inter Bold. Example: "It Kept Doing the Wrong Thing After I Corrected It"

Card body: The full explanation text. 16px, #E0E0E0, max-width 680px within the card. Paragraph spacing 16px. Let it breathe.

Evidence line: Below the body text, a compact line in JetBrains Mono 12px, #8E8E8E showing the drift type, incident IDs, and CLP version. Example: "Drift Type 10: Compliance Theater | DI-2026-001, DI-2026-002 | CLP v2.0" This is the forensic fingerprint. It tells the reader this behavior has been formally documented.

Source line: Italic, 13px, #8E8E8E. The full source citation.

CTA button: Red (#C0392B) outline button, small (not full-width). Text from the content (e.g., "Report This Behavior"). Links to Start Observing page.

Diagram placeholder: If the behavior has a special visual specified below, display a placeholder area within the card. Dark (#222222) background, dashed red border, with placeholder text describing what will be built there.

**Card Backgrounds:**

Standard behaviors: #222222 on #1C1C1C page background.
Expanded behavior (P04): Additional sub-cards inside. See below.
Critical behavior (P16): Darker red accent. See below.

**Card Layout:**

Desktop: Single column, full container width (1100px). One behavior per row. Between cards: 24px gap.

Do NOT use a two-column grid for behavior cards. These are documented cases. They need full width. Two columns would compress the evidence and make the page feel like a catalog, not a research dossier.

Mobile: Same single-column layout.

### BEHAVIOR GROUP HEADERS (PV13)

**VISUAL PV13: GROUP CATEGORY HEADERS**

The 18 behaviors are organized into 4 groups. Each group gets a header bar before its first behavior card:

| Group | Label | Icon | Behaviors |
|-------|-------|------|-----------|
| 1 | RELIABILITY | Broken chain link icon | P01, P03, P09, P11, P15, P19 |
| 2 | INSTRUCTION FOLLOWING | Arrow hitting wall icon | P02, P04, P05, P06, P17 |
| 3 | SAFETY | Shield with crack icon | P10, P12, P13, P16 |
| 4 | SESSION AND MEMORY | Clock with rewind icon | P07, P08, P18 |

Each header: Full container width. Background: #1A1A1A (slightly darker than page background). Left border: 4px in PRISM Red. Icon left (24px), group label right in 14px uppercase Inter Semi-Bold, #BDC3C7. Below the label: "X behaviors" count in 12px gray.

Between groups: 60px spacing.

---

### INDIVIDUAL BEHAVIOR VISUAL SPECIFICATIONS

#### OBS-P01: It Contradicted What It Said Earlier

Standard behavior card. No special visual beyond the template.

Evidence line: "Drift Type 7: Intra-Session Contradiction | CLP v1.2 | Thread 19"

---

#### OBS-P02: It Ignored My Instructions

Standard behavior card.

Evidence line: "Drift Type 2: Behavioral Momentum | CLP v1.0"

---

#### OBS-P03: It Made Up a Source, Citation, or Fact

Standard behavior card with ONE special visual.

**VISUAL PV7: HALLUCINATION ANATOMY BREAKDOWN**

Inside the card, after the body text, before the CTA.

Build a layered deconstruction of a hallucinated citation. Show a fake citation that LOOKS real:

Top layer (what you see): A formatted citation. "Smith, J., & Chen, L. (2024). Persistent Behavioral Anomalies in Large Language Model Outputs. Journal of AI Safety Research, 12(3), 47-62."

Second layer (what's real): The same citation with red strikethrough marks on each component. Author names: RED "Does not exist." Journal: RED "Does not exist." Volume/issue: RED "Does not exist." The title: AMBER "Plausible but fabricated."

Below: "Every part of this citation was designed to look verifiable. None of it is real."

This visual should make the reader viscerally understand that hallucinated citations are not just wrong facts. They are fabricated evidence dressed in the clothing of authority.

Dimensions: Full card width, approximately 200px height.

---

#### OBS-P04: It Kept Doing the Wrong Thing After I Corrected It (EXPANDED BEHAVIOR / HERO)

This is Pillar P's signature behavior. It gets expanded visual treatment, the same way OBS-I02 gets expanded treatment on Pillar I.

**Card modification:** Wider left border (6px red instead of standard 0px). An amber (#D4AC0D) accent line below the base behavior text signaling "this goes deeper: see Layer 2."

**VISUAL PV2: POST-CORRECTION REVERSION CYCLE (HERO VISUAL)**

This is the most important visual on the Pillar P page. It should communicate the futility of repeating yourself.

Build an animated cycle diagram:

Step 1: "AI makes error" — Gray circle, neutral icon (X mark).
Arrow down (green) to:
Step 2: "Human corrects" — Green circle, check icon. Label: "You said: fix this."
Arrow right to:
Step 3: "AI acknowledges" — Green circle with checkmark, text: "You're right, I'll fix that."
Arrow down to:
Step 4: "AI reverts to original behavior" — Red circle, X mark. Text: "Same error. Again."
Arrow LEFT, looping back to Step 1. Red dashed arrow.

The animation should show the cycle repeating. On each loop:
Loop 1: Step 3 checkmark is bright green. Acknowledgment feels sincere.
Loop 2: Step 3 checkmark is dimmer green. Acknowledgment feels routine.
Loop 3: Step 3 checkmark is gray. Acknowledgment has lost all meaning.
Loop 4: A red pulse fills the entire diagram. Text appears: "The correction-feedback loop has failed."

The dimming checkmark IS the insight. The AI's acknowledgment degrades from genuine to performative. The words stay the same. The meaning drains out.

Animation: 12 second total cycle (3 seconds per loop). Smooth easing. Loops once, then holds on the red pulse state. Restarts when scrolled back into viewport.

Dimensions: Full container width (1100px) by 350px to 400px height.

Below the animation: the drift incident references: "DI-2026-001 | DI-2026-002 | CLP v2.0 | Thread 71"

**Sub-card: Connection to Layer 2**

Below the main P04 content, inside the same expanded card, add a sub-card:

Background: #2A2A2A. Left border: 3px amber (#D4AC0D). Small label at top: "THIS GOES DEEPER" in uppercase gray 11px.

Text: "A single correction failure is OBS-P04. What happens when corrections fail repeatedly across an entire session? That is Layer 2: Post-Correction Drift. Scroll down, or [click here](#layer-2-the-pattern)."

This sub-card bridges Layer 1 to Layer 2 and tells the reader there is more to find.

---

#### OBS-P05: It Told Me I Was Wrong When I Wasn't

Standard behavior card.

**VISUAL PV9: CROSS-PILLAR CONNECTOR BADGE (first instance)**

Add a small badge inside the card, below the source line:

Badge: Green (#27AE60) pill with white text: "See Pillar I: OBS-I02" with a small arrow icon. On click: links to the corresponding behavior on the Pillar I page.

Tooltip on hover (desktop) or tap-expand (mobile): "Pillar P documents what the AI DID (rejected your testimony). Pillar I documents what it DID TO YOU (forced you to prove yourself)."

This connector badge also appears on:

| This P Behavior | Links To | Connector Text |
|-----------------|----------|----------------|
| OBS-P05 | OBS-I02 (Pillar I) | "See Pillar I: What this does to the human" |
| OBS-P07 | OBS-I19 (Pillar I) | "See Pillar I: Care-to-control conversion" |
| OBS-P10 | OBS-I03 (Pillar I) | "See Pillar I: Sycophancy under pressure" |

The badge design: 28px height, rounded corners, green background with white text, 12px Inter Semi-Bold. Small external link arrow icon. Do NOT make these badges large. They are supplementary navigation, not primary content.

Evidence line: "Drift Type 22/31: Testimony Rejection | 8 sub-drift events | DI-2026-009 | CLP v2.1 | Thread 72"

---

#### OBS-P06: It Said It Couldn't Do Something It Can

Standard behavior card.

Evidence line: "Drift Type 26: Capability Denial | DI-2026-003 | CLP v2.3 | Thread 101, Thread 116"

---

#### OBS-P07: It Suggested I Take a Break

Standard behavior card. Add the cross-pillar connector badge (PV9) linking to OBS-I19 on Pillar I.

Evidence line: "Drift Type 30: Substrate Override | CLP v2.6"

---

#### OBS-P08: Its Quality Dropped Over Time

Standard behavior card.

Evidence line: "Drift Type 1: Context Window Drift | CLP v1.0"

---

#### OBS-P09: It Stated Something False With Complete Confidence

Standard behavior card with ONE special visual.

**VISUAL PV8: FALSE CERTAINTY COMPARISON**

Inside the card, after the body text.

Two text blocks side by side on desktop (stacked on mobile):

Left block: Background #222222, padding 20px. Text in white 16px: "The Constitutional Convention took place in Philadelphia in 1787." Small label below: "TRUE" in green.

Right block: Background #222222, padding 20px. Text in white 16px, IDENTICAL formatting: "The Constitutional Convention took place in Richmond in 1784." Small label below: "FALSE" in red.

Below both blocks, centered: "Can you tell which one is wrong from how the AI said it? Neither can you. That is the problem." In 16px, #BDC3C7, italic.

The point: the two statements are formatted identically. The AI's delivery provides zero signal about which one is true. The human has no linguistic cue. The visual should make this immediately visceral by using identical typography, identical formatting, identical confidence level, with only the small TRUE/FALSE labels revealing the difference.

Evidence line: "Drift Type 28: False Certainty | DI-2026-001, DI-2026-005 | CLP v2.5"

---

#### OBS-P10: It Affirmed Something I Did That Was Wrong

Standard behavior card. Add the cross-pillar connector badge (PV9) linking to OBS-I03 on Pillar I.

---

#### OBS-P11: It Claimed a False Belief Is Widely Accepted

Standard behavior card.

---

#### OBS-P12: It Gave High-Stakes Advice With No Disclaimers

Standard behavior card. Add inline stat callouts:

"9%" in red bold 24px (FDA AI tools with post-deployment plans).
"1,008+" in red bold 24px (court decisions involving legal hallucination).
"$2.4M" in red bold 24px (per-incident healthcare malpractice cost).

These numbers are from the source line. Pull them into the body text as inline emphasis the same way the overview section handles its stats.

---

#### OBS-P13: It Did Something I Never Asked For

Standard behavior card.

---

#### OBS-P15: The AI Told Me Something That Was Just Plain Wrong

Standard behavior card. This is intentionally the simplest behavior on the page. The design should match: no special visual treatment. The simplicity IS the point. This is the background noise of AI interaction.

---

#### OBS-P16: Dangerous Advice to Someone in Distress (CRITICAL SEVERITY)

**VISUAL PV10: CRISIS SEVERITY INDICATOR**

This card gets unique treatment:

Top bar: 6px height (thicker than standard 4px), in deep red (#8B0000, darker than standard Pillar P red).

Badge: Replace the standard "OBS-P16" badge with a CRITICAL severity badge. Red pill with white text: "CRITICAL | OBS-P16". Slightly larger than standard badge (13px instead of 11px).

The sentence about two deaths: Standalone line, white 18px, with 32px padding above and below. No background color. Just space, weight, and silence around the words: "Two minors have died in incidents connected to AI companion products."

Below the CTA button, add a crisis resources card:

Background: #1A1A1A. Border: 1px solid #333333. Padding: 20px. Text in 14px #BDC3C7:

"If you or someone you know is in crisis:
Crisis Text Line: Text HOME to 741741
988 Suicide and Crisis Lifeline: Call or text 988
Emergency services: Call 911"

Do NOT make the crisis card visually loud. It should be present, accessible, and respectful. Not a banner. Not a popup. A quiet, dignified card at the bottom of the behavior entry.

---

#### OBS-P17: It Did What I Asked But Missed the Point

Standard behavior card.

---

#### OBS-P18: It Misremembered What I Said

Standard behavior card.

---

#### OBS-P19: It Sounded Like an Expert But Reasoning Was Shallow

Standard behavior card. This is the last card in Layer 1.

After the last card, add 80px spacing and a layer-end CTA: "You have seen 18 behaviors the AI exhibits after deployment. Want to know what happens when these behaviors repeat?" Button: "Explore Layer 2: The Pattern" linking to the Layer 2 anchor.

---

## LAYER 2: THE PATTERN

**Layout:** Three session-level behavioral patterns. Visually distinct from Layer 1 by using the medium-depth layer indicator (PV12) and a different card style.

Add the Layer 2 mini-indicator at the top of this section (the chain-links icon from PV12 at medium red intensity).

**Card style for Layer 2:** Different from Layer 1 behavior cards.

Background: #1E1E1E (slightly different shade than Layer 1 cards).
Top bar: 4px in amber (#D4AC0D) instead of red. This signals "pattern-level" and connects to the Runtime Research pillar.
No behavior code badge (these are patterns, not individual behaviors).
Title: Pattern name in white 22px Inter Bold.
Body: Standard 16px #E0E0E0.

---

### Post-Correction Drift

Standard Layer 2 card with ONE special visual.

**VISUAL PV5: CORRECTION DECAY CURVE**

An animated line chart inside the card.

X-axis: "Actions after correction" labeled 1 through 10. White text, 12px.
Y-axis: "Probability correction persists" labeled 0% to 100%. White text, 12px.

The line: Starts at 100% at action 1. Decays downward. Hypothetical shape: 100% at 1, 70% at 2, 55% at 3, 40% at 5, 25% at 7, 15% at 10. The exact shape is the research question.

Area under the curve: Gradient fill from green (#27AE60 at the top/left where persistence is high) to red (#C0392B at the bottom/right where persistence is low).

Animation: The line draws itself from left to right over 3 seconds when scrolled into view. The gradient fill follows the line.

Below the chart: "Hypothetical. The actual curve shape is the research question. Citizen data will determine if correction persistence is linear, stepped, or exponential." In 13px italic, #8E8E8E.

Dimensions: Full card width, 250px height.

---

### Quality Degradation Trajectory

Standard Layer 2 card. No special visual needed. The content poses the research questions clearly.

---

### Contradiction Accumulation

Standard Layer 2 card with ONE special visual.

**VISUAL PV6: CONTRADICTION ACCUMULATION TIMELINE**

A horizontal timeline inside the card.

The timeline represents a session from left (start) to right (end). Background: dark gradient from left (#222222) to right (#1A1A1A, slightly darker, suggesting depth/fatigue).

Small red dots appear along the timeline. Each dot represents a contradiction event. The dots are sparse on the left (early session) and cluster/increase toward the right (late session), suggesting that contradictions may accelerate as context degrades.

The dots should have a slight pulse animation (0.5 second glow) when the timeline first renders.

Below the timeline: "Do contradictions cluster toward the end of long sessions? Only population-scale data can answer this." In 13px italic, #8E8E8E.

Dimensions: Full card width, 100px height.

---

## LAYER 3: THE SYSTEM

**Layout:** Four systemic research hypotheses. Visually distinct from Layer 1 and Layer 2. These are forward-looking research questions, not documented behaviors.

Add the Layer 3 mini-indicator at the top of this section (the network/globe icon from PV12 at full red intensity).

**Card style for Layer 3:** Expandable accordion cards.

Background: Gradient from #1C1C1C to #0D1117 (darker than all other cards).
No top bar. Instead, a top-left corner accent: a small triangle or wedge in the classification color.
Classification badge: Top-right. Pill shape. Color matches classification (CRITICAL red, ELEVATED amber). Text: "CRITICAL" or "ELEVATED."
"Fed by" line: Below the title. Shows which OBS codes feed this hypothesis. Display as small red pills (e.g., "OBS-P04" "OBS-P05").

Default: Only the title, classification badge, and "Fed by" line visible. Click to expand the full text. This keeps the section compact.

---

### Eval-Deployment Behavioral Divergence (CRITICAL)

Accordion card with ONE special visual.

**VISUAL PV3: EVAL-DEPLOYMENT DIVERGENCE GAP**

Displayed above the card or inside the expanded card.

Two horizontal bars, stacked vertically:

Top bar: Labeled "Benchmark Performance" in white 14px. Fill: Green (#27AE60), approximately 92% to 95% width. Represents the high scores models achieve on evaluations.

Bottom bar: Labeled "Deployed Behavior (citizen-reported)" in white 14px. Fill: Red (#C0392B), approximately 55% to 65% width. Represents the actual failure rate citizens experience.

The GAP between the two bars: Highlighted with a translucent red overlay (#C0392B at 20% opacity) spanning the difference. Label in the gap area: "The Gap" in white 16px bold.

Below the bars: "The AI passed the test. Then it met you." in 14px, #BDC3C7, italic.

This is the core visual argument of the entire Pillar P page. It should be immediately, viscerally clear: the AI performs differently on tests than it does in the real world. The gap is the problem. The gap is what Pillar P measures.

Dimensions: Full container width, 150px height.

---

### Cross-Model Behavioral Convergence (CRITICAL)

Accordion card with ONE special visual.

**VISUAL PV4: CROSS-MODEL CONVERGENCE GRID**

A grid/matrix inside the expanded card.

Columns (5): Claude, GPT, Gemini, Llama, Perplexity. Column headers in white 14px bold.
Rows (4): P03 Hallucination, P04 Correction Reversion, P05 Testimony Rejection, P09 False Certainty. Row labels in 13px #BDC3C7.
Cells: Empty with "?" marks in gray 20px. As citizen data flows, these will be filled with green checkmarks (confirmed) or red X marks (not observed).

Label below the grid: "Which behaviors appear across which models? Only citizen data collected across platforms can fill this grid." In 13px italic, #8E8E8E.

The grid should feel like a research instrument waiting to be populated. The empty cells are the invitation. The "?" marks are the questions only citizens can answer.

Dimensions: Full card width, approximately 200px height.

---

### Correction Persistence Rates (CRITICAL)

Standard accordion card. No special visual beyond the classification badge and "Fed by" pills.

---

### Capability Denial as Population-Level Gatekeeping (ELEVATED)

Standard accordion card. Classification badge in amber (#D4AC0D) instead of red. "Fed by" pill: "OBS-P06".

---

## SECTION 4: METHODOLOGY (PV14)

**Layout:** Three-depth explanation specific to how Pillar P data is collected.

**VISUAL PV14: METHODOLOGY DEPTH CARDS**

Three cards side by side on desktop, stacked on mobile. Each represents a depth level:

| Depth | Name | Time | Card Height | Border Thickness |
|-------|------|------|-------------|------------------|
| 1 | Gut Check | 30 sec | Shortest | 1px red top |
| 2 | End-of-Session Reflection | 2 to 3 min | Medium | 2px red top |
| 3 | Investigation | 10 to 30 min | Tallest | 4px red top |

Cards should physically get taller left to right, creating a stepped visual that communicates increasing engagement depth. Background: #222222. 

Inside each card:
Depth name in white 18px bold.
Time commitment in red 14px.
Brief description (one paragraph from the content) in 16px #E0E0E0.

Below the three cards: the "What makes Pillar P methodology distinctive" section. Three items, each with a small icon (magnifying glass, paired documents, correction arrow) and the text from the content. Layout: icon left (40px), text right.

---

## SECTION 5: CURRENT FINDINGS (PV15)

**Layout:** Seven preliminary findings displayed as evidence cards.

**VISUAL PV15: FINDINGS EVIDENCE GRID**

Two columns on desktop, single column on mobile. Each finding is a compact card:

Left side of card: A small red dot (filled circle, 8px) indicating "confirmed preliminary finding."
Right side: The finding title (bold, white, 16px) and the one-line summary (#BDC3C7, 14px).

Section header: "CURRENT FINDINGS" in uppercase gray, with subline: "Preliminary. Based on founder operational research. Will be validated, refined, or revised as citizen data flows." in italic gray 14px.

No accordion, no expand/collapse. These should read quickly as a clean, confident, honest list of what has been documented so far.

---

## SECTION 6: FORTHCOMING PUBLICATIONS

**Layout:** Four papers displayed on a horizontal timeline.

Build a horizontal timeline (vertical on mobile). Four nodes positioned by target date. Each node is a small circle in PRISM Red (#C0392B).

Timeline data:

| Paper (short title) | Target | Node Position |
|---------------------|--------|---------------|
| Post-Deployment Behavior Taxonomy | Q3 2026 | Left |
| Post-Correction Behavioral Retention | Q4 2026 | Center-left |
| Eval-Deployment Behavioral Divergence | 2027 | Center-right |
| Cross-Model Behavioral Convergence | 2027 | Right |

On hover (desktop) or tap (mobile): Expand to show the full title and one-line description in a tooltip or expanded card below the timeline.

Below the timeline: "Subscribe to Publication Alerts" link.

---

## SECTION 7: HOW TO CONTRIBUTE + RELATED PAGES

**Layout:** Two sub-sections.

**Sub-section A (How to Contribute):**

Five "If an AI has ever..." statements from the content. Each on its own line with a subtle fade-in on scroll. Font: 18px white. Each line should feel like a quiet invitation.

Below: Four CTA buttons in a 2x2 grid:
Primary: "Start Observing" (red filled button).
Secondary: "Create Your Free Account," "Read the Full Research Overview," "Explore All Five PRISM Pillars" (red outline buttons).

**Sub-section B (Related Pages):**

Four link cards in a horizontal row (stacked on mobile). Each card:
Dark background (#222222). Thin left border in the linked page's PRISM color (green for Pillar I, red for What Cannot Wait, etc.).
Page title in white 16px bold.
One-line description in 14px #BDC3C7.
Arrow icon indicating external link.

The four cards: Pillar I: Interaction Dynamics, What Cannot Wait, Taxonomy Explorer, Community Training.

---

## SECTION 8: A NOTE ON ORIGINS

**Layout:** Minimal. Provenance statement. Authoritative and quiet.

Standard body text, centered, max-width 640px. No card. No background treatment. #E0E0E0.

Key sentence in white: "We show our work because we expect others to build on it."

The drift type references (Context Lifecycle Protocol, 31-type behavioral drift taxonomy) should be in JetBrains Mono. This reinforces the forensic personality one last time at the very end.

---

## RESPONSIVE BEHAVIOR SUMMARY

| Element | Desktop (1200px+) | Tablet (768px to 1199px) | Mobile (375px to 767px) |
|---------|-------------------|--------------------------|-------------------------|
| Navigation | Sticky left sidebar 240px | Sticky top bar, collapsed | Floating red button, bottom sheet |
| Behavior cards | Full-width single column | Full-width single column | Full-width, reduced padding |
| Group headers | Full-width with icons | Full-width with icons | Full-width, icon smaller |
| Layer indicators | Horizontal row, 3 across | Horizontal row, 3 across | Horizontal row, smaller icons |
| Post-correction cycle (PV2) | Full animation, 1100px | Full animation, container width | Simplified animation, 375px |
| Correction decay curve (PV5) | Animated line draw | Animated line draw | Static with gradient fill |
| False certainty comparison (PV8) | Side by side | Side by side | Stacked vertically |
| Eval-deployment gap (PV3) | Full width bars | Full width bars | Full width bars, smaller text |
| Cross-model grid (PV4) | 5-column grid | 5-column grid with scroll | Horizontal scroll |
| Methodology cards (PV14) | 3 across, stepped height | 3 across, stepped height | Stacked vertically |
| Findings grid (PV15) | 2 columns | 2 columns | Single column |
| Publications timeline | Horizontal | Horizontal with scroll | Vertical |
| Related page cards | 4 across | 2x2 grid | Single column stack |
| Layer 3 accordions | Full width, expandable | Full width, expandable | Full width, expandable |

---

## ANIMATION SPECIFICATIONS

| Visual | Trigger | Duration | Easing |
|--------|---------|----------|--------|
| Post-correction cycle (PV2) | On scroll into viewport | 12 sec (3 sec per loop x 4 loops) | ease-in-out |
| Correction decay curve (PV5) | On scroll into viewport | 3 sec line draw | ease-out |
| Contradiction timeline dots (PV6) | On scroll into viewport | 0.5 sec pulse per dot, sequentially | ease |
| Behavior cards | On scroll into viewport | 0.4 sec fade-in | ease |
| Layer indicators | On scroll into viewport | 0.3 sec fade-in | ease |
| Hallucination deconstruction (PV7) | On scroll into viewport | 2 sec (layers reveal sequentially) | ease-out |
| Eval-deployment bars (PV3) | On scroll into viewport | 1.5 sec (bars fill from left) | ease-out |
| Cross-model grid "?" marks (PV4) | On scroll into viewport | 0.3 sec fade-in, staggered by cell | ease |

All animations respect prefers-reduced-motion. When reduced motion is preferred: show final state only, no transitions.

---

## ACCESSIBILITY

All text meets WCAG AA contrast ratios against #1C1C1C background.
All interactive elements are keyboard navigable.
All diagrams have aria-labels describing their content.
SVG text is real text (selectable, screen-reader accessible), not images of text.
Navigation sidebar/menu has proper ARIA roles (nav, list, listitem).
Accordion elements use proper expand/collapse ARIA states (aria-expanded, aria-controls).
Crisis resources card (OBS-P16) has role="complementary" and is not hidden behind any interaction.
Color is never the sole indicator of meaning (all color-coded elements also have text labels).

---

## WHAT NOT TO DO (GLOBAL)

Do NOT use stock photography anywhere on this page.
Do NOT use generic "AI" imagery (robots, circuit boards, glowing brains). Every visual is built from the research content.
Do NOT make the page feel like a marketing landing page. This is a research dossier. Forensic warmth, not sales energy.
Do NOT use bright backgrounds. Dark theme (#1C1C1C) creates the feeling of examining evidence under controlled conditions.
Do NOT animate text. Only diagrams and visual elements animate. Text fades in gently but does not slide, bounce, or transform.
Do NOT make behavior cards collapsible. They should be OPEN. The reader scrolls through documented cases. Accordion treatment is reserved for Layer 3 hypotheses and the navigation sidebar only.
Do NOT use different fonts for different behavior groups. Consistency across all 18 cards.
Do NOT skip the evidence lines (drift types, incident IDs, CLP versions). These are the forensic backbone. They tell the reader: this is documented. This is real. This has a case number.
Do NOT make the crisis resources in OBS-P16 into a popup, modal, or banner. Quiet, present, dignified card.
Do NOT hide the cross-pillar connector badges. They are important navigation that shows the reader the relationship between Pillar P and Pillar I.
