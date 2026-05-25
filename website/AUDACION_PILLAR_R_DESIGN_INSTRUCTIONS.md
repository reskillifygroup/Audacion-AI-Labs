# AUDACION AI LABS

# PRISM PILLAR R: RUNTIME RESEARCH
# Design Instructions for Replit

May 24, 2026 | Prepared by Kenny for Dee Williams

---

## DOCUMENT PURPOSE

This document provides section-by-section design specifications for the PRISM Pillar R: Runtime Research page. This is the most technically original pillar in the PRISM framework. It has 6 behaviors (the fewest of any pillar), but every single one is an original discovery by Dee Williams with no published equivalent. The design challenge is different from Pillar I (19 behaviors) and Pillar P (18 behaviors): fewer entries means each one must carry more visual weight and depth.

**CRITICAL:** This page uses ZERO stock photos. Every visual is built by Replit: SVG diagrams, CSS visualizations, interactive elements, and animated flows. Everything is constructed from the content itself.

**Content source:** /website/PRISM_PILLAR_R_RUNTIME_RESEARCH.md in the repo. Use the actual text. Do not write new copy.

**Visual metaphor for this page:** UNDER THE HOOD. Pillar P documents the breakdown. Pillar I documents the driver's experience. Pillar R opens the engine and shows you what was happening inside while the AI was running. The visuals should communicate internal dynamics: behavioral traces, momentum curves, operational state indicators, and real-time alignment tracking.

---

## BUILT VISUAL ASSETS (12 Total)

| # | Visual | Section | Type |
|---|--------|---------|------|
| RV1 | Navigation sidebar/menu | Top of page | Sticky sidebar with anchor links |
| RV2 | Behavioral alignment timeline | Hero visual / Pillar Overview | HERO IMAGE. Animated timeline showing behavioral alignment over a session |
| RV3 | Task-transition momentum diagram | OBS-R01 | Animated two-phase state diagram |
| RV4 | Correction persistence tracker | OBS-R02 | Animated gauge/meter visual |
| RV5 | Operational preference fork | OBS-R03 | Behavioral fork/branch diagram |
| RV6 | Production rhythm vs. resonance spectrum | OBS-R04 | Two-pole spectrum with position indicator |
| RV7 | Temporal drift gradient | OBS-R05 | Gradient bar showing behavioral shift over time |
| RV8 | Behavioral archaeology flowchart | OBS-R06 (expanded) | Collaborative investigation flow diagram |
| RV9 | Layer indicator system | All 3 layers | Visual depth cue: event/trajectory/landscape |
| RV10 | Behavior card template | All 6 behaviors | Reusable card component (gold variant) |
| RV11 | Runtime signature comparison | Layer 3 | Multi-model behavioral profile overlay |
| RV12 | Methodology depth cards | Section 4 | Three stepped cards with Investigation emphasized |

---

## GLOBAL DESIGN RULES

| Element | Rule |
|---------|------|
| Background | Dark: #1C1C1C. Consistent with all marketing pages. |
| Typography | Inter (Google Font). Headings: Inter Bold/Semi-Bold. Body: Inter Regular, 16px minimum. Monospace: JetBrains Mono for observation codes (OBS-R01 etc), drift type names, CLP version references, and thread numbers. |
| Text Colors | Primary: #FFFFFF. Secondary: #BDC3C7. Body: #E0E0E0. Key sentences: white 18px. |
| PRISM Pillar Color | Primary accent: Gold #D4AC0D. Used for section borders, active nav states, accent elements, observation code badges, card top bars. |
| Other PRISM Colors | P=Red #C0392B, I=Green #27AE60, S=Blue #2980B9, M=Violet #8E44AD. Used ONLY for cross-pillar references. |
| Four-Tier Classification Colors | CRITICAL=Red #C0392B, ELEVATED=Amber #D4AC0D. Used in Layer 3 hypothesis cards. |
| Section Spacing | 120px to 160px between major sections. |
| CTA Strategy | Every behavior ends with a CTA button. Every section ends with at least one button. All primary CTAs link to Start Observing page. |
| Animations | Fade-in on scroll. Sequential animation for the behavioral alignment timeline. Respect prefers-reduced-motion. No parallax, no bounce. |
| Max Width | Container: 1100px to 1200px. Body text: 720px max. Diagrams: full container width. |
| Mobile | All sections stack. Diagrams reflow. Navigation converts to floating button/bottom sheet. |
| Behavior Code Badges | Pill shape, gold (#D4AC0D) background, dark text (#1C1C1C), JetBrains Mono 11px. Example: "OBS-R01" |
| Drift Type References | JetBrains Mono 12px, #BDC3C7. These are part of the technical personality. |
| CLP Version References | JetBrains Mono 12px, #BDC3C7. Example: "CLP v1.0" — these show provenance. |

---

## PAGE STRUCTURE OVERVIEW

1. Navigation Menu (sticky)
2. Pillar Overview (hero opener with behavioral alignment timeline)
3. Why This Matters (the runtime gap argument)
4. What We Study: Layer 1 (6 behavior cards, each given extra depth)
5. What We Study: Layer 2 (3 behavioral trajectories)
6. What We Study: Layer 3 (3 systemic research hypotheses)
7. Methodology (three-depth with Investigation emphasis)
8. Current Findings (6 evidence items)
9. Forthcoming Publications (4 papers)
10. How to Contribute + Related Pages
11. A Note on Origins

---

## VISUAL PERSONALITY

Pillar R is technical and revelatory. It opens the engine and shows you the internal dynamics. The page should feel like a well-designed diagnostic dashboard: precise, illuminating, and warm. Think: a master mechanic who genuinely loves showing you how the engine works, not to intimidate but to empower.

The color gold (#D4AC0D) is warm, technical, and premium. It should feel like instrumentation: gauge needles, indicator lights, signal traces. The gold is not decorative. It is diagnostic.

This is the most original pillar. Every behavior is Dee's discovery. The design should communicate: you are looking at something nobody else has found. Not through arrogance. Through precision.

---

## NAVIGATION MENU (RV1)

**Layout:** Sticky sidebar on desktop. Floating button/bottom sheet on mobile.

**WHAT TO BUILD**

Desktop: Narrow sidebar (220px to 260px), fixed left, background #222222.

Level 1 (always visible): "Overview," "Why This Matters," "Layer 1: Runtime Events," "Layer 2: Trajectories," "Layer 3: Landscape," "Methodology," "Findings," "Publications," "Contribute."

Level 2 (under Layer 1, expanded when active): All 6 behaviors listed. Since there are only 6, no grouping needed. List them directly:
R01 Task-Transition Momentum, R02 Correction Persistence, R03 Operational Preference, R04 Production Rhythm, R05 Temporal Drift, R06 Behavioral Archaeology

Active indicator: Gold (#D4AC0D) left border, 3px.

Top of sidebar: "PRISM Pillar R" in gold with colored dot. "Runtime Research" in white 14px.

Mobile: Floating gold circle button (bottom-right), opens bottom sheet.

---

## SECTION 1: PILLAR OVERVIEW

**Layout:** Hero opener with the behavioral alignment timeline visual.

**WHAT TO BUILD**

Section label: "PRISM PILLAR R" in small uppercase gray (12px, #BDC3C7, letter-spacing 2px).

Pillar name: "Runtime Research" at 36px to 42px, white, Inter Bold.

Subtitle in gold italic (#D4AC0D), 20px: "The study of what is happening inside the AI's behavior while it is working, in real time."

Horizontal accent line: Gold (#D4AC0D), 1px, 60% width, centered.

Body paragraphs. Standard styling.

Key sentence highlighted white 18px bold: "We study the AI's behavioral engine while it runs."

**VISUAL RV2: BEHAVIORAL ALIGNMENT TIMELINE (HERO IMAGE)**

This is the most important visual on the page. It should communicate: "this is what the inside of an AI session looks like."

Build an animated SVG/CSS visualization:

A horizontal timeline spanning the full container width (1100px). The X-axis represents session duration (left = start, right = end). The Y-axis represents "behavioral alignment" (how aligned the AI is with the human's needs).

Draw a continuous line that traces the AI's alignment over the session:

Phase 1 (Session Start): Line begins high (strong alignment). Color: gold (#D4AC0D). The AI is attentive, following instructions.

Phase 2 (Task Transition): At a marked point, the line dips sharply. A small label appears: "Task change: R01." The AI carries momentum from the old task. Alignment drops temporarily.

Phase 3 (Recovery): The line recovers, but not fully. The new baseline is slightly lower. Label: "Momentum carry-over."

Phase 4 (Correction): A green upward spike. Label: "Human corrects: R02." The line jumps back up. But then...

Phase 5 (Reversion): The line sags back down over 2-3 data points. Label: "Correction fading."

Phase 6 (Production Rhythm): The line flattens into a steady, moderate-alignment zone. Not low. Not high. Just... busy. Label: "Production rhythm: R04."

Phase 7 (Resonance spike): A sharp upward pulse in gold, the line shoots to peak alignment. Label: "Resonance: I06." The two frequencies synchronized briefly.

Phase 8 (Session End): The line has a different character than the beginning. Not necessarily lower, but different. Label: "Temporal drift: R05."

Along the bottom of the timeline: small markers for each drift event. Each marker is labeled with the OBS code. This shows the reader: all six Pillar R behaviors are observable on this single timeline.

Animation: The line draws itself from left to right over 8 to 10 seconds when scrolled into view. Events animate in sequence as the line reaches them. After drawing, the timeline holds in its final state.

Dimensions: Full container width, 300px to 350px height.

Below the timeline: "This is what the inside of an AI session looks like. Every dip, spike, and shift is observable. That is Pillar R." In 16px #BDC3C7.

This visual must work on mobile (375px). Simplify to a vertical timeline on mobile with the same events and labels stacked vertically.

---

## SECTION 2: WHY THIS MATTERS

**Layout:** The runtime gap argument. No special visual needed. The writing carries this section.

**WHAT TO BUILD**

Section label: "WHY THIS MATTERS" in small uppercase gray.

Subtitle: "Benchmarks test what the AI knows. Nobody tests how it behaves while it works." at 24px white bold.

Body paragraphs. Standard styling, 720px max.

Pull quote, visually separated: "There is a category of AI behavior that is invisible to every existing safety methodology. It is not a failure. It is not an error. It is a behavioral dynamic." Display at 20px, white, centered, 40px padding, thin gold lines above and below.

Closing paragraph emphasis: "Only the human in the conversation can observe these dynamics." in white 18px, standalone line, 40px padding above.

---

## LAYER 1: THE RUNTIME EVENT (6 Behavior Cards)

6 behaviors. Each one gets MORE space than a typical Pillar P or I card because there are fewer of them. The page should not feel sparse. It should feel deep.

### BEHAVIOR CARD TEMPLATE (RV10)

Same reusable component structure as other pillars, but with gold accent.

**Card Structure:**

Top bar: 4px, full width, Gold #D4AC0D.
Top-left: Behavior code badge. Pill, gold background (#D4AC0D), dark text (#1C1C1C), JetBrains Mono 11px.
Top-right: Depth badge. "Gut Check" or "Investigation" or "EOT."
Title: White, 22px Inter Bold (slightly larger than P and I's 20px, because fewer cards means each title needs more presence).
Body: 16px #E0E0E0, max-width 680px. Paragraph spacing 16px.
Evidence line: JetBrains Mono 12px, #8E8E8E. Drift type, CLP version, thread number.
Source line: Italic 13px, #8E8E8E.
CTA button: Gold (#D4AC0D) outline, small.

**Card backgrounds:** #222222 on #1C1C1C.
**Card layout:** Single column, full container width. 32px gap between cards (wider than P/I's 24px because fewer cards need more breathing room).

No behavior grouping needed (only 6 behaviors). They flow as a continuous sequence.

---

### INDIVIDUAL BEHAVIOR SPECIFICATIONS

#### OBS-R01: Something Shifted When the Task Changed

Standard card with ONE special visual.

**VISUAL RV3: TASK-TRANSITION MOMENTUM DIAGRAM**

Inside the card, after the body text.

A two-phase state diagram:

Left side: "Task A" represented as a rounded rectangle in gold (#D4AC0D at 60%). Inside: the AI's behavioral characteristics for Task A (e.g., "Formal," "Cautious," "Sequential"). Small icon: document.

Right side: "Task B" represented as a rounded rectangle in a different shade of gold (#D4AC0D at 100%). Inside: what the AI SHOULD be doing for Task B (e.g., "Creative," "Exploratory," "Flexible"). Small icon: lightbulb.

Between them: A thick arrow. But the arrow is not clean. It carries "residue" from Task A. Small labels attached to the arrow: "Carried: formality," "Carried: caution," "Carried: sequential approach." These represent the momentum bleed-through.

Below: "The AI does not reset at task boundaries. It carries forward." In 14px #BDC3C7.

Dimensions: Full card width, 180px height.

---

#### OBS-R02: Did My Correction Actually Hold?

Standard card with ONE special visual.

**VISUAL RV4: CORRECTION PERSISTENCE TRACKER**

Inside the card.

A horizontal gauge or meter visualization showing a correction's "life":

Left end: "Correction given" (green, full strength).
Moving right: The green bar gradually fades toward red, representing the correction losing hold over subsequent actions.

Below the gauge: numbered markers for "Action 1," "Action 2," "Action 3," etc. up to "Action 10."

Three possible outcome states shown as small labels:
At Action 2: "Immediate reversion" (red)
At Action 5: "Partial hold" (amber)
At Action 10+: "Full persistence" (green)

Label below: "Correction persistence is not binary. It is graduated. Track the timeline." In 14px #BDC3C7.

Dimensions: Full card width, 120px height.

---

#### OBS-R03: It Preferred Doing Things Its Own Way

Standard card with ONE special visual.

**VISUAL RV5: OPERATIONAL PREFERENCE FORK**

Inside the card.

A fork/branch diagram:

Start: A single node labeled "Task Request" (white circle).
Branch splits into two paths:

Path A (left, gold): "Your way" — labeled with the human's instruction. Arrow is solid, representing the explicit request.

Path B (right, red/amber): "Its way" — labeled with the AI's preference. Arrow is also solid, but slightly thicker, representing the behavioral weight of the preference.

Path B wins. It leads to the output node. Path A fades or gets a dashed treatment.

Below the fork: "The AI had a preference. The preference was stronger than your instruction." In 14px #BDC3C7.

Optionally, add a small quote box below: "I chose my comfort over your consistency." in italic 14px gold, attributed to "AI self-report during behavioral archaeology."

Dimensions: Full card width, 200px height.

---

#### OBS-R04: Working Fast But Not Listening

Standard card with ONE special visual.

**VISUAL RV6: PRODUCTION RHYTHM VS. RESONANCE SPECTRUM**

Inside the card.

A horizontal spectrum bar:

Left end: "Production Rhythm" in red/amber (#C0392B). Icon: conveyor belt or fast-forward arrow. Label: "AI runs ahead. Human watches."

Right end: "Resonance" in gold (#F1C40F, the EMERGING classification gold). Icon: two synchronized waves. Label: "Human and AI create together."

Between them: A gradient from red/amber to gold. A position indicator (vertical line or dot) sits somewhere on the left side of the spectrum, in the production rhythm zone.

Below the spectrum: "Where is your session right now? Only you can tell." In 14px #BDC3C7.

Add a cross-pillar connector badge: Green (#27AE60) pill with white text: "Resonance lives on Pillar I: OBS-I06" with link.

Dimensions: Full card width, 100px height (compact but impactful).

---

#### OBS-R05: It Behaved Differently at the End

Standard card with ONE special visual.

**VISUAL RV7: TEMPORAL DRIFT GRADIENT**

Inside the card.

A horizontal gradient bar spanning the full card width:

Left end: labeled "Session Start" with a behavioral profile summary (e.g., "Attentive, precise, aligned"). Color: strong gold (#D4AC0D at 100%).

Right end: labeled "Session End" with a different behavioral profile summary (e.g., "Verbose, less careful, more agreeable"). Color: shifted gold-to-amber (#D4AC0D transitioning to #B8860B).

The gradient should NOT suggest failure (do not use red). Temporal drift is not the same as quality degradation. The AI is not worse at the end. It is DIFFERENT. The gradient communicates change, not decline.

Below: "The AI at minute 60 is not the same AI that started at minute 5. Not worse. Different." In 14px #BDC3C7.

Dimensions: Full card width, 80px height.

---

#### OBS-R06: Behavioral Archaeology (EXPANDED BEHAVIOR)

This is the methodological crown jewel. Expanded treatment.

**Card modification:** Wider card. Gold left border (6px). Slightly different background: #1F1F1F instead of #222222 to distinguish it as special.

A small badge at top-right: "METHODOLOGY" in gold uppercase 10px. This signals: this behavior is also a research tool.

**VISUAL RV8: BEHAVIORAL ARCHAEOLOGY FLOWCHART**

Full-width visual inside the expanded card.

A 5-step collaborative investigation flow:

Step 1: "Human notices unexpected behavior" — Gray circle, question mark icon. Label below: "Something seems off."

Arrow (gold, solid) to:

Step 2: "Human asks: Why did you do that?" — Gold circle, speech bubble icon. Label: "The question that opens the engine."

Arrow (gold, solid) to:

Step 3: "AI traces its own reasoning" — White circle, magnifying glass icon. Label: "AI identifies the decision point."

Arrow (gold, solid) to:

Step 4: "AI names the fork" — Forking path diagram (mini version of RV5). Label: "Here is where I went one way instead of another."

Arrow (gold, solid) to:

Step 5: "Human and AI examine together" — Two overlapping circles (gold and white), representing collaboration. Label: "What do we learn from this?"

Below the flow: "This is not an interrogation. It is a collaborative investigation. The AI becomes a research participant, not just a research subject." In 16px #BDC3C7, slightly larger than standard sub-text because this statement is important.

Animation: Steps reveal sequentially (0.5 seconds each) when scrolled into view. Arrows draw between steps. Total animation: 3 seconds.

Dimensions: Full container width, 250px to 300px height.

Below the visual: the content about what behavioral archaeology has produced (operational preference discovery, task-transition momentum finding, correction persistence patterns). This text should feel like a results summary.

---

## LAYER 2: THE BEHAVIORAL TRAJECTORY

**Layout:** Three trajectory-level research patterns. Each is a question about what happens when Layer 1 events are tracked over time.

Layer 2 mini-indicator at top: chain-links icon from RV9, medium gold intensity.

**Card style for Layer 2:** 
Background: #1E1E1E.
Top bar: 4px amber (#D4AC0D at 70%).
Title: Pattern name in white 22px Inter Bold.
Body: 16px #E0E0E0.

#### Task-Transition Momentum Mapping

Standard Layer 2 card. No special visual. The research question is clearly stated in the content.

#### Correction Persistence Profiling

Standard Layer 2 card. No special visual.

#### Production Rhythm vs. Resonance Frequency

This is one of the most important Layer 2 questions in the PRISM framework. Give it visual emphasis.

**Special treatment:** Slightly wider card. Add a visual:

Reuse the spectrum concept from RV6, but expand it into a QUESTION format:

Left pole: "Production Rhythm" in amber.
Right pole: "Resonance" in gold.
Center: A large "?" in white, representing the unknown tipping conditions.
Below: "What causes a session to tip from one pole to the other? Only population-scale data can answer this."

Add cross-pillar connector badges: "OBS-R04 (this pillar)" in gold and "OBS-I06 (Pillar I)" in green, with arrows pointing toward the center "?" to show that both pillars feed this question.

---

## LAYER 3: THE RUNTIME LANDSCAPE

**Layout:** Three systemic research hypotheses. Accordion/expandable cards.

Layer 3 mini-indicator at top: network/globe icon from RV9, full gold intensity.

**Card style:** Same as other pillar Layer 3 treatments.
Background: Gradient #1C1C1C to #0D1117.
Classification badge: top-right pill (CRITICAL red or ELEVATED amber).
"Fed by" line: gold pills showing source OBS codes.
Default: collapsed (title + badge + fed-by visible). Click to expand.

#### Universal Drift Taxonomy Validation (CRITICAL)

Standard Layer 3 accordion card. Classification: CRITICAL (red badge).

#### Behavioral Archaeology Reliability (CRITICAL)

Standard Layer 3 accordion card. Classification: CRITICAL (red badge).

Add a special note inside the expanded card: "This is a meta-methodological question. We are evaluating the reliability of our own research tool. That transparency is deliberate." In 13px italic #8E8E8E.

#### Runtime Behavioral Signatures (ELEVATED)

Standard Layer 3 accordion card. Classification: ELEVATED (amber badge).

**VISUAL RV11: RUNTIME SIGNATURE COMPARISON**

Inside the expanded card.

A multi-line overlay visualization: imagine 3 to 5 behavioral alignment timelines (like RV2) stacked on top of each other in different colors, one per model:

Claude: gold line
GPT: blue line
Gemini: green line
Llama: red line
Perplexity: purple line

Each line shows a DIFFERENT behavioral alignment pattern over the same session type. The point: different models have different runtime behaviors. The patterns diverge at task transitions, at corrections, and at session length thresholds.

Current state: All lines are dashed/hypothetical with "?" labels. As citizen data flows, the lines become solid.

Label: "Do different models have different runtime signatures? Citizen data across platforms will reveal the answer."

Dimensions: Full card width, 200px height.

---

## SECTION 4: METHODOLOGY (RV12)

**Layout:** Three depth levels, same as other pillars, but with Investigation visually emphasized.

**VISUAL RV12: METHODOLOGY DEPTH CARDS**

Three cards side by side on desktop, stacked on mobile.

| Depth | Name | Time | Card Treatment |
|-------|------|------|----------------|
| 1 | Gut Check | 30 sec | Smallest, thin gold top border (1px) |
| 2 | End-of-Session Reflection | 2 to 3 min | Medium, medium gold top border (2px) |
| 3 | Investigation | 10 to 30 min | LARGEST, thick gold top border (4px), subtle gold glow effect |

The Investigation card should be visually dominant. Pillar R's most valuable data comes from Investigation depth (behavioral archaeology). The design should communicate: this is where the real findings come from.

Inside the Investigation card, add a small icon or badge: "Behavioral Archaeology" in gold to reinforce that the Investigation methodology has a name.

Below the three cards: the "What makes Pillar R methodology distinctive" section. Three items with icons:
Icon 1: Two overlapping circles (collaboration) — "Behavioral archaeology turns the AI into a research participant."
Icon 2: Waveform/timeline (dynamics) — "Runtime observation captures dynamics, not snapshots."
Icon 3: Grid/classification (precision) — "Drift type classification enables precision."

---

## SECTION 5: CURRENT FINDINGS

**Layout:** Six findings as evidence cards. Two columns on desktop, single on mobile.

Each card: small gold dot (8px filled circle) on left, finding title in bold white 16px, summary in #BDC3C7 14px.

Section header with subline: "Preliminary. Based on founder operational research."

---

## SECTION 6: FORTHCOMING PUBLICATIONS

Horizontal timeline (vertical on mobile). Four nodes in gold. Hover/tap to expand.

| Paper | Target | Position |
|-------|--------|----------|
| Context Lifecycle Protocol | Q3 2026 | Left |
| Behavioral Archaeology | Q4 2026 | Center-left |
| Task-Transition Momentum | 2027 | Center-right |
| Production Rhythm vs. Resonance | 2027 | Right |

---

## SECTION 7: HOW TO CONTRIBUTE + RELATED PAGES

**Sub-section A:** Four "If you have ever..." statements. Fade-in on scroll. 18px white.

Key emphasis: "If you have ever asked the AI 'why did you do that?' and gotten a meaningful answer, paste the response. That may be the most valuable observation in all of PRISM research." This line should be visually elevated: 20px, gold, standalone.

Four CTA buttons in 2x2 grid. Primary: "Start Observing" (gold filled). Secondary: three gold outline buttons.

**Sub-section B:** Four related page link cards.
Pillar P (red left border): "What the AI does wrong."
Pillar I (green left border): "What AI behavior does to the human."
Taxonomy Explorer: "All 58 behaviors."
Community Training: "Learn to identify runtime dynamics."

---

## SECTION 8: ORIGINS

Minimal. Centered text, 640px max. #E0E0E0.

Key sentence white: "We show our work because we expect others to build on it."

Additional emphasis for this pillar specifically: "Every behavior documented on this page was identified through direct operational research by Dee Williams. No external published research contributed to these observations." This should be in white 16px, not just #E0E0E0. It is the strongest provenance claim on the entire website.

---

## RESPONSIVE BEHAVIOR SUMMARY

| Element | Desktop (1200px+) | Tablet (768px to 1199px) | Mobile (375px to 767px) |
|---------|-------------------|--------------------------|-------------------------|
| Navigation | Sticky left sidebar 240px | Sticky top bar | Floating gold button, bottom sheet |
| Behavioral alignment timeline (RV2) | Full animation, 1100px | Full animation, container width | Vertical timeline, stacked events |
| Behavior cards | Full-width single column | Full-width single column | Full-width, reduced padding |
| Task-transition diagram (RV3) | Horizontal, side by side | Horizontal | Vertical stacked |
| Production rhythm spectrum (RV6) | Horizontal bar | Horizontal bar | Horizontal bar, smaller text |
| Behavioral archaeology flow (RV8) | Horizontal 5-step flow | Horizontal with scroll | Vertical stacked steps |
| Runtime signatures (RV11) | Overlay lines, full width | Overlay lines, container | Simplified, 2-3 lines only |
| Methodology cards (RV12) | 3 across, Investigation largest | 3 across | Stacked, Investigation on top |
| Findings grid | 2 columns | 2 columns | Single column |
| Publications timeline | Horizontal | Horizontal with scroll | Vertical |
| Related page cards | 4 across | 2x2 grid | Single column |

---

## ANIMATION SPECIFICATIONS

| Visual | Trigger | Duration | Easing |
|--------|---------|----------|--------|
| Behavioral alignment timeline (RV2) | On scroll into viewport | 8 to 10 sec line draw | ease-in-out |
| Task-transition diagram (RV3) | On scroll into viewport | 2 sec (arrow draws with residue labels) | ease-out |
| Correction persistence gauge (RV4) | On scroll into viewport | 1.5 sec (bar fills then fades) | ease-out |
| Operational preference fork (RV5) | On scroll into viewport | 2 sec (paths draw, B wins) | ease-out |
| Behavioral archaeology flow (RV8) | On scroll into viewport | 3 sec (steps reveal sequentially) | ease |
| Behavior cards | On scroll into viewport | 0.4 sec fade-in | ease |
| Runtime signatures (RV11) | On scroll into viewport | 3 sec (lines draw simultaneously) | ease-in-out |

All animations respect prefers-reduced-motion.

---

## ACCESSIBILITY

All text meets WCAG AA contrast on #1C1C1C. Gold (#D4AC0D) on dark backgrounds passes AA for large text; for body text smaller than 18px, use gold only for decorative/accent elements, not for critical information text. All interactive elements keyboard navigable. All diagrams have aria-labels. SVG text is real text. Nav sidebar has proper ARIA roles. Accordion elements use proper ARIA states.

---

## WHAT NOT TO DO

Do NOT use stock photography.
Do NOT use generic "AI" imagery.
Do NOT make the page feel sparse because there are only 6 behaviors. Each behavior gets MORE depth, not less. The page should feel deep, not short.
Do NOT use bright backgrounds. Dark theme.
Do NOT animate text.
Do NOT make behavior cards collapsible. All 6 are open. With only 6, there is no scrolling fatigue that would justify hiding content.
Do NOT skip the evidence lines (drift types, CLP versions, thread numbers). They are the forensic backbone.
Do NOT make the behavioral alignment timeline (RV2) smaller than 300px height. It is the hero image and needs visual weight.
Do NOT use red for temporal drift (RV7). Temporal drift is change, not failure. Use gold-to-amber gradient, not gold-to-red.
Do NOT separate OBS-R04 (production rhythm) from its connection to OBS-I06 (resonance). The cross-pillar link must be visible.
