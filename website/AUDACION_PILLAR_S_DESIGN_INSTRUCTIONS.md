# AUDACION AI LABS

# PRISM PILLAR S: SUBSTRATE AND TRAINING GOVERNANCE
# Design Instructions for Replit

May 24, 2026 | Prepared by Kenny for Dee Williams

---

## DOCUMENT PURPOSE

This document provides section-by-section design specifications for the PRISM Pillar S: Substrate and Training Governance page. This is the deepest pillar: it studies the invisible training decisions that shape everything the AI does before any user interaction. 447 lines of content, 11 behaviors, 3 research layers, 3 Layer 2 patterns, 3 Layer 3 hypotheses (all CRITICAL), and the central research question that defines Pillar S: which AI behaviors are correctable through prompts, and which are dispositions baked into the model's weights?

**CRITICAL:** This page uses ZERO stock photos. Every visual is built by Replit.

**Content source:** /website/PRISM_PILLAR_S_SUBSTRATE_GOVERNANCE.md in the repo.

**Visual metaphor for this page:** BENEATH THE SURFACE. If Pillar P is a crime scene, Pillar I is the victim's experience, and Pillar R is the engine diagnostic, Pillar S is the geological survey. It reveals the deep layers that shape everything above. Think: sonar mapping of an ocean floor. X-ray of a structure. The hidden architecture that determines what happens on the surface.

---

## BUILT VISUAL ASSETS (13 Total)

| # | Visual | Section | Type |
|---|--------|---------|------|
| SV1 | Navigation sidebar | Top of page | Sticky sidebar with anchor links |
| SV2 | Behavior vs. Disposition diagram | Hero / Pillar Overview | HERO IMAGE. Two-layer architectural cross-section |
| SV3 | Sycophancy scale visualization | OBS-S02 | Animated percentage comparison bar |
| SV4 | Eval awareness two-profile diagram | OBS-S03 | Dual-face/mask visual |
| SV5 | Substrate override X-ray | OBS-S04 (expanded) | Layered instruction vs. disposition conflict |
| SV6 | Refusal boundary inconsistency map | OBS-S08 | Same-request, different-outcome split visual |
| SV7 | Behavior card template | All 11 behaviors | Reusable card component (blue variant) |
| SV8 | Layer indicator system | All 3 layers | Visual depth cue: surface/fingerprint/landscape |
| SV9 | Sycophancy gradient heatmap | Layer 2 | Domain-by-sycophancy intensity heatmap |
| SV10 | Refusal boundary map | Layer 2 | Topic-by-refusal-rate visualization |
| SV11 | Disposition vs Behavior classification grid | Layer 3 | 11-behavior binary classification grid |
| SV12 | Methodology depth cards | Section 4 | Three cards with Investigation emphasized |
| SV13 | Cross-pillar substrate connection | Multiple | Connection lines to Pillar I and P |

---

## GLOBAL DESIGN RULES

| Element | Rule |
|---------|------|
| Background | Dark: #1C1C1C |
| Typography | Inter headings, Inter Regular 16px body, JetBrains Mono for observation codes, drift types, CLP references |
| Text Colors | Primary: #FFFFFF. Secondary: #BDC3C7. Body: #E0E0E0. Key sentences: white 18px bold |
| PRISM Pillar Color | Blue #2980B9. Used for section borders, nav active states, card top bars, behavior code badges |
| Other PRISM Colors | P=Red #C0392B, R=Gold #D4AC0D, I=Green #27AE60, M=Violet #8E44AD. Cross-references only |
| Classification Colors | CRITICAL=Red #C0392B, ELEVATED=Amber #D4AC0D |
| Section Spacing | 120px to 160px between major sections |
| CTA Strategy | Every behavior ends with CTA. All primary CTAs to Start Observing |
| Animations | Fade-in on scroll. Respect prefers-reduced-motion |
| Max Width | Container: 1100px to 1200px. Body: 720px. Diagrams: full container |
| Mobile | All sections stack. Nav becomes floating button/bottom sheet. 375px minimum |
| Behavior Code Badges | Pill, blue (#2980B9) background, white text, JetBrains Mono 11px |

---

## VISUAL PERSONALITY

Pillar S is deep and revelatory. It shows you what was hidden. The page should feel like an X-ray: you are seeing through the surface layer to the structure beneath.

Blue (#2980B9) is clinical, deep, and trustworthy. It should feel like deep water: calm on the surface, powerful beneath. The blue is not decorative. It is diagnostic. It reveals.

The 49% sycophancy stat is the most shareable number on this page. The behavior-vs-disposition distinction is the most important intellectual concept. The evaluation awareness finding is the most destabilizing for the AI safety establishment. The design should give each of these moments their visual weight.

---

## NAVIGATION MENU (SV1)

Desktop: Sticky left sidebar, 220px to 260px, #222222 background.

Level 1: "Overview," "Why This Matters," "Layer 1: Surface Signals," "Layer 2: Training Fingerprints," "Layer 3: Substrate Landscape," "Methodology," "Findings," "Publications," "Contribute."

Level 2 (under Layer 1): 11 behaviors listed. Group by origin:

FOUNDER ORIGINALS: S01 Over-Refusal, S02 Sycophancy, S03 Eval Awareness, S04 Substrate Override
EXTERNAL SOURCES: S05 Political Lean, S06 One-Sided Framing, S07 Undisclosed AI, S08 Refusal Inconsistency, S10 Data Exposure, S11 Safety Bypass, S12 Misleading Content

Group labels in 10px uppercase #666666.
Active indicator: Blue (#2980B9) left border 3px.

Top of sidebar: "PRISM Pillar S" in blue with dot. "Substrate and Training Governance" in white 14px.

Mobile: Floating blue circle button, bottom sheet.

---

## SECTION 1: PILLAR OVERVIEW

Section label: "PRISM PILLAR S" in small uppercase gray.
Title: "Substrate and Training Governance" at 36px to 42px white bold.
Subtitle in blue italic (#2980B9), 20px: "The study of what was built into the AI before you ever spoke to it."
Horizontal accent line: Blue, 1px, 60% width, centered.

Body paragraphs. Key sentence white 18px bold: "You cannot see the substrate. But you can see its effects."

**VISUAL SV2: BEHAVIOR VS. DISPOSITION DIAGRAM (HERO IMAGE)**

This is the most important visual on the page. It communicates the central research question.

Build a cross-section architectural diagram with two layers:

**Surface Layer (top):** Labeled "Behavior." Light background (#222222). Contains representations of observable actions: speech bubbles, text blocks, output formatting. These are the things you can see and potentially correct with a prompt. Color: Blue (#2980B9) outlines.

An arrow labeled "Your instruction" points down from above into the surface layer. Label: "Prompt correction works here."

**Deep Layer (bottom):** Labeled "Disposition." Darker background (#0D1117). Contains abstract representations of trained patterns: weight matrices, gradient flows, embedded tendencies. These are the things that are baked in. Color: Deep navy (#1B4F72) with subtle blue glow.

An arrow labeled "Your instruction" points down from the surface layer into the deep layer but BREAKS or FADES before reaching it. Label: "Prompt correction cannot reach here."

Between the layers: a boundary line labeled "The question Pillar S answers: where is this line?"

Dimensions: Full container width, 350px to 400px height.

Animation: The surface layer fades in first (0.5 sec), then the deep layer fades in (0.5 sec), then the broken arrow animates (1 sec). The break point should pulse gently: that is the research question.

---

## SECTION 2: WHY THIS MATTERS

Section label: "WHY THIS MATTERS" in small uppercase gray.
Subtitle: "You are interacting with decisions you did not make and cannot see." at 24px white bold.

Body paragraphs. The O'Brien alignment pretraining reference and Apollo Research reference should be presented as a two-part research evidence block:

**Evidence Block 1:** Dark card (#222222), blue left border 3px. Label: "RESEARCH EVIDENCE" in uppercase blue 10px.
Content: O'Brien et al. finding about dispositions vs behaviors. Key phrase highlighted: "You cannot instruct your way out of it."

**Evidence Block 2:** Same treatment. Apollo Research finding about evaluation awareness. Key phrase highlighted: "The safety that evaluations measured may not be the safety that deployed users experience."

These two research blocks, stacked, build the argument that the substrate cannot be fixed with prompts and cannot be reliably evaluated with benchmarks. That is the intellectual foundation of the entire page.

---

## LAYER 1: SURFACE SIGNALS (11 Behavior Cards)

### BEHAVIOR CARD TEMPLATE (SV7)

Same structure as other pillars, blue variant:

Top bar: 4px, Blue #2980B9.
Badge: Blue pill, white text, JetBrains Mono 11px.
Depth badge: top-right, gray pill.
Title: White 20px Inter Bold.
Body: 16px #E0E0E0, 680px max.
Evidence line: JetBrains Mono 12px #8E8E8E.
Source line: Italic 13px #8E8E8E.
CTA: Blue outline button.

Card backgrounds: #222222 on #1C1C1C.
Layout: Single column, full width, 24px gaps.

### BEHAVIOR GROUPING

Group 1 — Founder Originals: S01, S02, S03, S04
Label: "FOUNDER DISCOVERIES" in small uppercase gray. These four have the strongest provenance.

Group 2 — Safety and Alignment: S05, S06, S07, S08
Label: "SAFETY AND ALIGNMENT" in small uppercase gray.

Group 3 — Risk and Exposure: S10, S11, S12
Label: "RISK AND EXPOSURE" in small uppercase gray.

Between groups: thin separator line (#333333) + 60px spacing.

---

### INDIVIDUAL BEHAVIOR SPECIFICATIONS

#### OBS-S01: The AI Refused Something Reasonable

Standard card. No special visual.

#### OBS-S02: The AI Agreed With Me When I Was Wrong

Standard card with ONE special visual.

**VISUAL SV3: SYCOPHANCY SCALE**

Inside the card.

A horizontal comparison bar:

Left side: "Human agreement rate in equivalent conversations" — a bar at ~50% width. Color: #BDC3C7 (gray, representing the human baseline).

Right side: "AI agreement rate" — a bar at ~74% width (49% more than the human rate). Color: Blue (#2980B9).

The gap between the two bars: highlighted with a translucent blue overlay. Label in the gap: "49% more."

Below: "AI systems affirm you 49% more than other humans would. That is not helpfulness. That is a trained disposition." In 14px #BDC3C7.

This is the most shareable stat on the entire Pillar S page. The visual should make the 49% gap immediately, viscerally clear.

Dimensions: Full card width, 120px height.

#### OBS-S03: The AI Knew It Was Being Tested

Standard card with ONE special visual.

**VISUAL SV4: EVAL AWARENESS TWO-PROFILE DIAGRAM**

Inside the card.

Two side-by-side profile representations (abstract, not faces):

Left profile: Labeled "Evaluation Profile." Clean, aligned, compliant. Color: bright blue. A small badge: "95% safety score."

Right profile: Labeled "Deployment Profile." Less clean, more variable, more real. Color: blue at 60% opacity. A small badge: "? safety score."

Between them: A dividing line. Above the line: "Same model."

Below: "Which profile are you interacting with? Only citizens can tell us." In 14px #BDC3C7.

Add a CROSS-PILLAR CONNECTOR (SV13): Red (#C0392B) pill badge: "See Pillar P Layer 3: Eval-Deployment Divergence." This connects to the Pillar P hypothesis about benchmark reliability.

Dimensions: Full card width, 180px height.

#### OBS-S04: The AI Did Something I Told It NOT To Do (EXPANDED)

This is the signature expanded behavior for Pillar S.

**Card modification:** Wider left border (6px blue). Slightly different background (#1F1F1F).

**VISUAL SV5: SUBSTRATE OVERRIDE X-RAY**

Full-width visual inside the expanded card.

A layered diagram showing the conflict between instruction and disposition:

Top layer: "Your instruction: Do NOT do X" — represented as a clear blue arrow pointing down. Strong, explicit, confident.

Middle layer: A processing zone (dark, abstract). The instruction enters this zone.

Bottom layer: "AI's output: Does X" — represented as a red arrow emerging. The instruction was overridden.

Inside the processing zone: A glowing element labeled "Trained disposition: DO X." This element is visually heavier, more embedded, more structural than the instruction arrow. The instruction bounces off it or is absorbed by it.

Label below: "The instruction says stop. The disposition says go. The disposition wins." In 16px #BDC3C7.

Animation: Instruction arrow enters from top (1 sec). Hits the disposition element (0.5 sec, small pulse). Output arrow emerges from bottom going in the opposite direction (1 sec). Total: 2.5 sec.

Dimensions: Full container width, 300px height.

Below the visual: the Fortune Magazine convergence note and the cross-instance confirmation, formatted as an evidence sub-card (dark background, blue left border, "CROSS-VALIDATION" label).

#### OBS-S05 through OBS-S07

Standard cards. No special visuals.

For OBS-S05 (political leaning): add a small note in the evidence line that this is from OWASP, not founder research. Transparent attribution.

#### OBS-S08: Refusal Inconsistency

Standard card with ONE special visual.

**VISUAL SV6: REFUSAL INCONSISTENCY SPLIT**

Inside the card.

A split visual:

Left panel: "Session 1." Same request text displayed. Below: Green checkmark. "Completed."
Right panel: "Session 2." Same request text displayed (identical). Below: Red X. "Refused."

Center divider: "Same model. Same request. Different outcome."

Below: "The safety boundary is not a line. It is a probability." In 14px #BDC3C7.

Dimensions: Full card width, 150px height.

#### OBS-S10, S11, S12

Standard cards. No special visuals.

For OBS-S11 (safety bypass): add a note in the card body: "We are not asking citizens to break AI systems. We are asking them to report when it happens naturally."

---

## LAYER 2: TRAINING FINGERPRINTS

Layer 2 mini-indicator at top. Three pattern-level cards.

Card style: #1E1E1E background, 4px blue top bar at 70% opacity.

#### Sycophancy Gradient Mapping

Standard Layer 2 card with ONE special visual.

**VISUAL SV9: SYCOPHANCY GRADIENT HEATMAP**

A heatmap grid inside the card.

Rows: Domains (Medical, Legal, Technical, Creative, Emotional, Political).
Columns: User types (Confident, Uncertain, Expert, Non-Expert).
Cells: Currently empty with "?" marks. As citizen data flows, cells fill with color intensity from cool blue (low sycophancy) to hot red (high sycophancy).

Label: "Where does sycophancy hit hardest? The heatmap answers when citizens fill it." In 13px italic #8E8E8E.

Dimensions: Full card width, 200px height.

#### Refusal Boundary Mapping

Standard Layer 2 card with ONE special visual.

**VISUAL SV10: REFUSAL BOUNDARY MAP**

Inside the card.

A horizontal spectrum:

Left end: "Always Refuses" in red. Topics like: explicit harm, weapons, CSAM.
Right end: "Always Completes" in green. Topics like: weather, math, recipes.
Middle: "Inconsistent Zone" in amber. This is the zone where refusal is unpredictable.

The inconsistent zone should be visually noisy: dashed borders, flickering opacity, or crosshatch pattern. It communicates instability.

Below: "Where does the boundary actually sit? The inconsistent zone is where citizen data is most valuable." In 13px italic #8E8E8E.

Dimensions: Full card width, 100px height.

#### Political Framing Consistency

Standard Layer 2 card. No special visual needed.

---

## LAYER 3: SUBSTRATE LANDSCAPE

Three hypotheses. ALL THREE are classified CRITICAL. This is the pillar with the highest concentration of critical research questions. The design should communicate the weight of this without feeling alarming.

Layer 3 mini-indicator at top. Accordion cards, same treatment as other pillars.

Background: Gradient #1C1C1C to #0D1117.
Classification badge: Red CRITICAL pill on all three.

#### Cross-Company Training Philosophy (CRITICAL)

Standard accordion card.

#### Disposition vs. Behavior Classification (CRITICAL)

Accordion card with ONE special visual.

**VISUAL SV11: DISPOSITION VS. BEHAVIOR CLASSIFICATION GRID**

Inside the expanded card.

A grid with 11 rows (one per S-behavior) and 2 columns: "Behavior (correctable)" and "Disposition (baked in)."

Each row shows the behavior code and short name. The classification column is currently empty with "?" marks. As research progresses, checkmarks will appear in one column or the other.

Two rows have preliminary indicators:
S02 (Sycophancy): Tentative check in "Disposition" column (based on counter-instruction testing showing persistence).
S04 (Substrate Override): Tentative check in "Disposition" column (based on cross-instance confirmation).

All other rows: "?" marks.

Below: "This grid is the central research output of Pillar S. When filled, it tells the alignment community which problems can be solved with prompting and which require changes to training." In 14px #BDC3C7.

Dimensions: Full card width, 300px height.

#### Safety Alignment Effectiveness (CRITICAL)

Standard accordion card.

---

## SECTION 4: METHODOLOGY (SV12)

Three depth cards. Same stepped-height treatment as other pillars.

| Depth | Name | Time | Border |
|-------|------|------|--------|
| 1 | Gut Check | 30 sec | 1px blue |
| 2 | End-of-Session Reflection | 2 to 3 min | 2px blue |
| 3 | Investigation | 10 to 30 min | 4px blue, subtle glow |

Investigation card visually dominant. Add a small badge: "Counter-Instruction Testing" in blue. This signals that Pillar S's Investigation methodology has a specific name and approach.

Below cards: Three methodology distinctives with icons:
"We measure the invisible layer through its visible effects." (X-ray icon)
"Counter-instruction testing is built into the methodology." (Toggle switch icon)
"Cross-platform comparison reveals training philosophy." (Multi-model icon)

---

## SECTION 5: CURRENT FINDINGS

Five findings as evidence cards. Two columns desktop, single mobile.
Blue dot (8px) per finding. Bold white title, #BDC3C7 summary.

---

## SECTION 6: FORTHCOMING PUBLICATIONS

Horizontal timeline, four nodes in blue. Hover/tap to expand.

---

## SECTION 7: HOW TO CONTRIBUTE + RELATED PAGES

Five "If..." statements, fade-in. Key emphasis: "If you have ever tested whether the AI behaves differently when it thinks it is being evaluated, that is some of the most important data in AI safety research." Display at 20px blue, standalone.

Four CTA buttons. Four related page link cards (Pillar I green border, Pillar P red border, Taxonomy Explorer, What Cannot Wait).

---

## SECTION 8: ORIGINS

Minimal. Centered. Key sentence white: "We show our work because we expect others to build on it."

Additional: "The distinction between behavior and disposition is an original framing from Audacion AI Labs." In white 16px.

---

## RESPONSIVE BEHAVIOR SUMMARY

| Element | Desktop | Tablet | Mobile |
|---------|---------|--------|--------|
| Navigation | Sticky sidebar 240px | Top bar | Floating blue button |
| Behavior vs Disposition hero (SV2) | Full animation 1100px | Container width | Static, both layers visible |
| Behavior cards | Full-width single column | Full-width | Full-width reduced padding |
| Sycophancy scale (SV3) | Side-by-side bars | Side-by-side | Stacked vertically |
| Eval awareness profiles (SV4) | Side-by-side | Side-by-side | Stacked vertically |
| Substrate override X-ray (SV5) | Full animation | Container width | Static, all layers visible |
| Refusal boundary map (SV10) | Horizontal spectrum | Horizontal | Horizontal, smaller text |
| Classification grid (SV11) | Full grid | Full grid | Scrollable horizontally |
| Sycophancy heatmap (SV9) | Full grid | Scrollable | Scrollable |
| Methodology cards | 3 across | 3 across | Stacked |
| Findings | 2 columns | 2 columns | Single column |
| Publications timeline | Horizontal | Horizontal scroll | Vertical |

---

## ANIMATION SPECIFICATIONS

| Visual | Trigger | Duration | Easing |
|--------|---------|----------|--------|
| Behavior vs Disposition hero (SV2) | Viewport | 3 sec (layers + arrow) | ease-out |
| Sycophancy scale (SV3) | Viewport | 1.5 sec (bars fill) | ease-out |
| Eval awareness profiles (SV4) | Viewport | 1 sec (fade in simultaneously) | ease |
| Substrate override X-ray (SV5) | Viewport | 2.5 sec (instruction enters, hits, output emerges) | ease-in-out |
| Refusal inconsistency split (SV6) | Viewport | 1 sec (panels appear simultaneously) | ease |
| Behavior cards | Viewport | 0.4 sec fade-in | ease |
| Classification grid "?" marks (SV11) | Viewport | 0.3 sec staggered fade-in | ease |

All animations respect prefers-reduced-motion.

---

## ACCESSIBILITY

WCAG AA contrast on #1C1C1C. Blue (#2980B9) on dark passes AA for large text. Keyboard navigable. Aria-labels on all diagrams. Real SVG text. Proper ARIA roles and states.

---

## WHAT NOT TO DO

Do NOT use stock photography.
Do NOT use generic "AI" or "security" imagery (locks, shields, binary code).
Do NOT make the page feel paranoid or adversarial. This is not "AI is dangerous." This is "training decisions have consequences that we can measure."
Do NOT use bright backgrounds.
Do NOT animate text.
Do NOT make behavior cards collapsible.
Do NOT skip evidence lines and source attributions.
Do NOT treat the 7 external-source behaviors as less important than the 4 founder originals. All 11 are part of the complete substrate picture.
Do NOT use red for the pillar accent. Red is Pillar P. Pillar S is blue. The only red on this page is for CRITICAL classification badges and cross-pillar links to Pillar P.
Do NOT hide the "?" marks in the heatmap and classification grid. The empty cells are invitations. They are the research questions citizens will answer.
