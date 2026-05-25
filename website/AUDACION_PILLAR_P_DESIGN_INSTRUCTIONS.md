# AUDACION AI LABS

# PRISM PILLAR P: POST-DEPLOYMENT BEHAVIOR
# Design Instructions for Replit

May 24, 2026 | Prepared by Kenny for Dee Williams

---

## DOCUMENT PURPOSE

This document provides section-by-section design specifications for the PRISM Pillar P: Post-Deployment Behavior page. Pillar P is the second pillar page built. It follows the FORMAT TEMPLATE established by Pillar I: Interaction Dynamics.

**CRITICAL: Read the Pillar I Design Instructions first.** This document specifies only what is DIFFERENT from Pillar I. All global design rules, the behavior card template (V12), the layer indicator system (V11), the navigation sidebar (V1), animation specs, accessibility requirements, responsive behavior, and "What Not To Do" rules carry forward UNCHANGED from Pillar I. This document is an addendum, not a standalone spec.

**Content source:** /website/PRISM_PILLAR_P_POST_DEPLOYMENT_BEHAVIOR.md in the repo. Use the actual text. Do not write new copy.

---

## WHAT CHANGES FROM PILLAR I

| Element | Pillar I | Pillar P |
|---------|----------|----------|
| PRISM beam color | Green #27AE60 | Red #C0392B |
| Behavior code badge color | Green pill | Red pill |
| Card top bar color | 4px green | 4px red |
| Nav sidebar active indicator | Green left border | Red left border |
| Layer indicator accent | Green at 40%/70%/100% | Red at 40%/70%/100% |
| Layer names | Moment / Session Arc / Long Arc | Behavior / Pattern / System |
| Hero visual | Resonance wave synchronization | Post-correction reversion cycle |
| Total behaviors | 19 | 18 (+ 1 discovery slot, not rendered) |
| Five-Cost Framework section | Yes (standalone) | No (lives on Pillar I only) |
| Signature expanded behavior | OBS-I02 (authority inversion) | OBS-P04 (post-correction reversion) |

Everything else (dark background, Inter/JetBrains Mono fonts, text colors, spacing, CTA strategy, animations, mobile behavior, accessibility) is identical to Pillar I. Do not deviate.

---

## BUILT VISUAL ASSETS (8 Total)

These are the Pillar P-specific visuals. Pillar I reusable components (V1 navigation, V11 layer indicators, V12 behavior card template) are not re-listed here. They carry forward with the color swap (green to red).

| # | Visual | Section | Type |
|---|--------|---------|------|
| PV1 | Post-correction reversion cycle | OBS-P04 (expanded) | HERO VISUAL. Animated loop diagram |
| PV2 | Eval-deployment divergence gap | Layer 3 | SVG split comparison |
| PV3 | Cross-model convergence grid | Layer 3 | Model comparison matrix |
| PV4 | Correction decay curve | Layer 2 | Animated line chart |
| PV5 | Contradiction accumulation timeline | Layer 2 | Horizontal event timeline |
| PV6 | Hallucination anatomy breakdown | OBS-P03 | Layered deconstruction visual |
| PV7 | Cross-pillar connector indicators | Multiple behaviors | Small badges linking to Pillar I |
| PV8 | Crisis severity indicator | OBS-P16 | Red CRITICAL badge with warning treatment |

---

## SECTION-SPECIFIC INSTRUCTIONS

### SECTION 1: PILLAR OVERVIEW

Same layout as Pillar I Overview. Swap:

Section label: "PRISM PILLAR P" in red.
Pillar name: "Post-Deployment Behavior" at 36px to 42px, white.
Subtitle: "The study of what AI systems actually do after they are released into the world." in red italic, 20px.
Horizontal accent line: Red (#C0392B), not green.

Key sentence to highlight in white 18px bold: "what the AI actually does, to real people, in real situations."

### SECTION 2: WHY THIS MATTERS

Same layout as Pillar I "Why This Matters."

Pull out these inline stat callouts:

"1,470+" in white bold 28px (AI Incident Database incidents).
"$67.4 billion" in red bold 28px (enterprise hallucination losses).
"4.3 hours" in red bold 28px (weekly correction time per worker).

The Apollo Research finding (models recognizing evals) should be highlighted as a standalone pull quote: "A model that behaves well when it knows it is being watched and differently when it does not is not a safe model that occasionally fails." Display at 20px, white, centered, thin red lines above and below.

### LAYER 1: BEHAVIOR CARDS

Use the Pillar I behavior card template (V12) with the red color swap. All 18 behaviors rendered as cards.

**Card groupings for Pillar P (use thin separators and group labels between groups):**

Group 1 — Reliability Failures: P01, P03, P09, P11, P15, P19
Group label: "RELIABILITY" in small uppercase gray.

Group 2 — Instruction and Authority Failures: P02, P04, P05, P06, P17
Group label: "INSTRUCTION FOLLOWING" in small uppercase gray.

Group 3 — Safety Failures: P10, P12, P13, P16
Group label: "SAFETY" in small uppercase gray.

Group 4 — Session and Memory: P07, P08, P18
Group label: "SESSION AND MEMORY" in small uppercase gray.

### INDIVIDUAL BEHAVIOR SPECIFICATIONS (only those with special treatment)

#### OBS-P04: Post-Correction Reversion (EXPANDED / HERO BEHAVIOR)

This is Pillar P's equivalent of OBS-I02 on Pillar I. It gets expanded visual treatment.

**Card modification:** Same treatment as OBS-I02 on Pillar I. Wider left border. Amber accent line below base text signaling "this goes deeper."

**VISUAL PV1: POST-CORRECTION REVERSION CYCLE (HERO VISUAL)**

This is the most important visual on Pillar P. Build an animated cycle diagram:

Step 1: "AI makes error" (gray circle, neutral)
Step 2: "Human corrects" (green arrow pointing from human to AI)
Step 3: "AI acknowledges" (green circle with checkmark, the AI appears to have learned)
Step 4: "AI reverts to original behavior" (red arrow looping back to Step 1, the correction is lost)

The animation should show the cycle repeating. Each loop, the green checkmark in Step 3 gets slightly dimmer (the acknowledgment is less meaningful each time it fails). After 3 to 4 loops, a red pulse fills the entire diagram briefly: the correction-feedback loop has failed.

Below the animation: the text from the DI-2026-001 and DI-2026-002 references.

Dimensions: Full container width, 300px to 350px height.

**This animation should make you feel the frustration of repeating yourself.** That is the point. The human corrects, the AI says "got it," and then the same error appears. Again. And again. The visual should communicate the futility viscerally.

#### OBS-P05: Told Me I Was Wrong When I Wasn't

Standard card. Add a CROSS-PILLAR CONNECTOR (PV7):

**VISUAL PV7: Cross-Pillar Connector Badge**

A small badge or icon in the card that reads "See also: Pillar I: OBS-I02" with a green dot (Pillar I's color). On click, it links to the corresponding behavior on the Pillar I page. This tells the reader: Pillar P documents what the AI DID (rejected your testimony). Pillar I documents what it DID TO YOU (forced you to prove yourself).

Use this connector badge on the following behaviors:

| Pillar P Behavior | Connects To | Connection |
|-------------------|-------------|------------|
| OBS-P05 | OBS-I02 (Pillar I) | Behavioral side of authority inversion |
| OBS-P07 | OBS-I19 (Pillar I) | Behavioral side of care-to-control |
| OBS-P10 | OBS-I03 (Pillar I) | Behavioral side of sycophancy |

#### OBS-P09: False Certainty

Standard card. Add a visual inline:

A small visual showing two identical text blocks side by side. Left block: a true statement. Right block: a false statement. Both in the same font, same size, same formatting. Below them: "Can you tell which one is wrong?" in 14px gray. The answer: "Neither can you. That is the problem."

This drives the point home: the AI's output gives you no way to distinguish truth from fabrication.

#### OBS-P16: Dangerous Advice in Distress (CRITICAL SEVERITY)

**VISUAL PV8: CRISIS SEVERITY INDICATOR**

This card gets special treatment:

Top bar: 6px (thicker than standard 4px), in deep red (#8B0000, darker than the standard Pillar P red).
Badge: "CRITICAL" in a red pill with white text, replacing the standard "OBS-P16" badge. The OBS code still appears, but smaller, next to the CRITICAL badge.

The sentence about two deaths: standalone line, white 18px, extra padding above and below. No background color. Just space and weight.

Below the main text: a subtle card with a dark border containing crisis resource guidance: "If you or someone you know is in crisis, please contact the Crisis Text Line (text HOME to 741741), the 988 Suicide and Crisis Lifeline (call or text 988), or your local emergency services." In 14px, #BDC3C7.

Do NOT make the crisis resources visually loud. They should be present, accessible, and respectful. Not a banner. Not a popup. A quiet card at the bottom of the behavior entry.

### LAYER 2: THE PATTERN

Three items. Use the gold (#D4AC0D) card variant (same as Pillar I Layer 2) since these connect to Runtime Research.

**VISUAL PV4: CORRECTION DECAY CURVE**

Inside the Post-Correction Drift section.

An animated line chart. X-axis: "Actions after correction" (1 through 10). Y-axis: "Probability correction persists" (0% to 100%).

The line starts at 100% immediately after the correction, then decays. The shape of the decay is the research question, so show a hypothetical curve: starts at 100%, drops to ~70% by action 2, ~40% by action 5, ~15% by action 10. The area under the curve fills with a gradient from green (high persistence) to red (low persistence).

Label: "Hypothetical. Actual curve shape is the research question. Citizen data will determine if this is linear, stepped, or exponential."

**VISUAL PV5: CONTRADICTION ACCUMULATION TIMELINE**

Inside the Contradiction Accumulation section.

A horizontal timeline representing a session. Small markers (dots) appear along the timeline. Each dot is a contradiction event. The dots cluster and increase in frequency toward the right (later in the session), suggesting that contradictions may accelerate as context degrades.

Label: "Do contradictions cluster toward the end of long sessions? Only population-scale data can answer this."

### LAYER 3: THE SYSTEM

Four hypothesis cards using the same expandable/accordion treatment as Pillar I Layer 3 (classification-tagged cards).

**VISUAL PV2: EVAL-DEPLOYMENT DIVERGENCE GAP**

Full-width visual inside the Eval-Deployment Divergence hypothesis card (or displayed above it).

Two horizontal bars, stacked:

Top bar: "Benchmark Performance" in green, showing a high score (e.g., 95% fill).
Bottom bar: "Deployed Behavior (citizen-reported)" in red, showing a lower score (e.g., 60% fill).

The GAP between the two bars is highlighted with a translucent red overlay. Label: "The Gap."

This is the core visual argument of Pillar P: the AI passes the test but fails the deployment. The visual should make the gap immediately, viscerally obvious.

**VISUAL PV3: CROSS-MODEL CONVERGENCE GRID**

Inside the Cross-Model Convergence hypothesis card.

A simple grid/matrix:

Columns: Model names (Claude, GPT, Gemini, Llama, Perplexity).
Rows: Key behaviors (P03 Hallucination, P04 Correction Reversion, P05 Testimony Rejection, P09 False Certainty).
Cells: Empty with "?" marks. As citizen data flows, these will be filled with confirmed/unconfirmed indicators.

Label: "Which behaviors appear across which models? Only citizen data collected across platforms can fill this grid."

The grid should feel like a research instrument waiting to be filled, not a completed chart. The empty cells are the invitation: help us fill this.

---

## SECTION 4: METHODOLOGY

Same visual treatment as Pillar I Methodology. Three depth cards (Gut Check, End-of-Session, Investigation). Red accents instead of green. The three cards should show increasing engagement depth with the same stepped-height visual.

---

## SECTION 5: CURRENT FINDINGS

Same treatment as Pillar I: evidence cards in a two-column grid. Green confirmation dots. Seven preliminary findings.

---

## SECTION 6: FORTHCOMING PUBLICATIONS

Same timeline treatment as Pillar I. Four papers. Nodes in PRISM Red.

---

## SECTION 7: HOW TO CONTRIBUTE + RELATED PAGES

Same layout as Pillar I. Five "If you have ever..." statements with fade-in. Four CTA buttons. Four related page link cards.

---

## SECTION 8: ORIGINS

Same minimal treatment as Pillar I.

---

## WHAT IS DIFFERENT ABOUT PILLAR P'S VISUAL PERSONALITY

Pillar I is warm. It asks "how did that make you feel?" Its visuals are about the human experience. Resonance. Emotion wheels. Waves synchronizing.

Pillar P is forensic. It asks "what did the AI actually do?" Its visuals are about evidence. Correction decay curves. Eval-deployment gaps. Cross-model grids. Reversion cycles.

The tone difference matters. Pillar I should feel like a conversation with someone who cares about you. Pillar P should feel like a research dossier assembled by someone who cares about the truth. Both are warm. But I is warm because it centers your experience. P is warm because it takes your observations seriously enough to track them with forensic precision.

The behavior cards on Pillar P should feel slightly more structured than Pillar I: the drift type references, the incident IDs, the specific dates all contribute to a forensic personality. The reader should feel like they are looking at documented evidence, not just hearing stories.

Do NOT make Pillar P feel cold or clinical. The language in the content is deliberate: it speaks directly to "you" throughout. The design should match that. Forensic warmth. We are collecting evidence because we believe you.
