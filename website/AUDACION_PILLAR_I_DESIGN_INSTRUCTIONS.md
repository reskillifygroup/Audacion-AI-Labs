# AUDACION AI LABS

# PRISM PILLAR I: INTERACTION DYNAMICS
# Design Instructions for Replit

May 24, 2026 | Prepared by Kenny for Dee Williams

---

## DOCUMENT PURPOSE

This document provides section-by-section design specifications for the PRISM Pillar I: Interaction Dynamics page. This is the most content-rich pillar page on the Audacion AI Labs website: 745 lines of content, 19 documented citizen-observable behaviors, 3 research layers, an original measurement framework, and 6 longitudinal research hypotheses. Without exceptional visual treatment, this page becomes a research paper nobody reads. With it, it becomes the page that makes people say "I need to tell someone about this."

This is the FORMAT TEMPLATE for all other pillar pages (P, R, S, M). Every design decision made here will carry forward. Get this right and the other four pages follow.

**CRITICAL:** This page uses ZERO stock photos. Every visual is built by Replit: SVG diagrams, CSS visualizations, interactive elements, and animated flows. Everything is constructed from the content itself.

**Content source:** /website/PRISM_PILLAR_I_INTERACTION_DYNAMICS.md in the repo. Use the actual text. Do not write new copy.

**Patterns from previous pages that carry forward:** Varied section layouts (never repeat the same visual pattern for consecutive sections), accordion/interactive elements for dense content, inline color emphasis for key sentences, pull quotes for emotional hooks, standalone closing statements, connected flow diagrams with sequential animation. Reference the About page and Research page refinement prompts for the full pattern library.

---

## BUILT VISUAL ASSETS (14 Total)

These are the visuals Replit must construct. No stock images. Each one is specified in detail in its corresponding section below.

| # | Visual | Section | Type |
|---|--------|---------|------|
| V1 | Navigation sidebar/menu | Top of page | Sticky sidebar or top nav with anchor links |
| V2 | Emotion spectrum wheel | OBS-I01 | SVG interactive wheel |
| V3 | Authority inversion power flip diagram | OBS-I02 | SVG arrow diagram with two states |
| V4 | Escalation trajectory ladder | OBS-I02 subsection | Vertical stepped progression, 4 stages |
| V5 | Resonance frequency synchronization | OBS-I06 | HERO IMAGE. Animated wave synchronization |
| V6 | Five-Cost Framework pentagon | Five-Cost Framework section | SVG pentagon/radar chart, 5 dimensions |
| V7 | Dependency loop cycle | OBS-I04 | Circular flow diagram |
| V8 | Moral outsourcing decision tree | OBS-I16 | Binary branching path diagram |
| V9 | Asymmetric intimacy imbalance | OBS-I18 | Directional arrow weight visualization |
| V10 | Care-to-control conversion cycle | OBS-I19 | Loop diagram showing instruction mutation |
| V11 | Layer indicator system | All 3 layers | Visual depth cue: shallow/medium/deep |
| V12 | Behavior card template | All 19 behaviors | Reusable card component |
| V13 | Long Arc hypothesis cards | Layer 3 | Classification-tagged expandable cards |
| V14 | Current Findings evidence grid | Section 5 | Finding cards with strength indicators |

---

## GLOBAL DESIGN RULES

| Element | Rule |
|---------|------|
| Background | Dark: #1C1C1C. Consistent with all marketing pages. |
| Typography | Inter (Google Font). Headings: Inter Bold/Semi-Bold. Body: Inter Regular, 16px minimum. Monospace: JetBrains Mono for observation codes (OBS-I01 etc), drift type references, and technical terms. |
| Text Colors | Primary: #FFFFFF. Secondary: #BDC3C7. Body in long sections: #E0E0E0 for warmth. Key sentences: white with slightly larger size (18px) for emphasis. |
| PRISM Pillar Color | This is the Pillar I page. Primary accent: Green #27AE60. Used for section borders, active nav states, accent elements, observation code badges. |
| Other PRISM Colors | P=Red #C0392B, R=Gold #D4AC0D, S=Blue #2980B9, M=Violet #8E44AD. Used ONLY when cross-referencing other pillars (e.g., the Escalation Trajectory connects to Pillar S). |
| Four-Tier Classification Colors | CRITICAL=Red #C0392B, ELEVATED=Amber #D4AC0D, DEVELOPING=Green #27AE60, EMERGING=Gold #F1C40F. Used in Layer 3 hypothesis cards. |
| Section Spacing | 120px to 160px between major sections. This is a long page; generous spacing prevents reading fatigue. |
| CTA Strategy | Every behavior section ends with a single CTA button. Section-level CTAs at the end of each layer. No dead ends anywhere on the page. All primary CTAs link to Start Observing page. |
| Animations | Fade-in on scroll for built visuals only. Sequential animation for the resonance wave diagram. Respect prefers-reduced-motion. No parallax, no bounce, no slide-in text. The content is serious. The design should feel confident, not theatrical. |
| Max Width | Container: 1100px to 1200px. Body text: 720px max for readability. Diagrams and visuals can use full container width. |
| Mobile | All sections stack. Diagrams reflow to vertical. Interactive elements remain functional at 375px. Navigation converts to hamburger or bottom sheet. Behavior cards stack to single column. |
| Behavior Code Badges | Every behavior has a code (OBS-I01 through OBS-I19). Display as a small pill badge in PRISM Green (#27AE60) with white text, positioned in the top-left or top-right of each behavior card. Font: JetBrains Mono, 11px. |

---

## PAGE STRUCTURE OVERVIEW

The page has this vertical flow. Each section should feel visually distinct from the one before it. Never use the same layout pattern for consecutive sections.

1. Navigation Menu (sticky)
2. Pillar Overview (hero opener)
3. Why This Matters (data-driven argument)
4. What We Study: Layer 1 (19 behavior cards)
5. What We Study: Layer 2 (3 session-arc patterns)
6. What We Study: Layer 3 (6 longitudinal hypotheses)
7. The Five-Cost Framework (original methodology showcase)
8. Methodology (three-depth explanation)
9. Current Findings (9 evidence items)
10. Forthcoming Publications (6 papers)
11. How to Contribute + Related Pages (CTAs and cross-links)
12. A Note on Origins (provenance statement)

---

## NAVIGATION MENU (V1)

**Layout:** Sticky sidebar on desktop. Sticky top bar on mobile.

**WHAT TO BUILD**

Desktop: A narrow sidebar (220px to 260px) fixed to the left side of the viewport. Background: #222222. Content is a vertical list of section names and behavior names as anchor links. Active section highlighted with a green (#27AE60) left border indicator (3px) that moves as the user scrolls.

The nav should have two levels of hierarchy:

Level 1 (always visible): Section names. "Overview," "Why This Matters," "Layer 1: The Moment," "Layer 2: The Session Arc," "Layer 3: The Long Arc," "Five-Cost Framework," "Methodology," "Findings," "Publications," "Contribute."

Level 2 (visible when Level 1 is active/expanded): Under "Layer 1: The Moment," list all 19 behavior names as compact anchor links. Use abbreviated names: "Emotional Reaction (I01)," "Prove Myself (I02)," "Pushed Back (I03)," etc. Font: 13px Inter Regular, #BDC3C7. On hover: white.

At the top of the sidebar: "PRISM Pillar I" in green with a small colored dot. Below that: "Interaction Dynamics" in white 14px.

Mobile: Collapse to a floating button (bottom-right, green circle with a list icon) that opens a bottom sheet with the same navigation structure. Or a sticky top bar with a dropdown.

**WHAT NOT TO DO**

Do NOT make the sidebar wider than 260px. It competes with content.
Do NOT show all 19 behaviors expanded at all times. Use an accordion under Layer 1.
Do NOT use scroll-spy animation that feels laggy. The active indicator should update smoothly.

---

## SECTION 1: PILLAR OVERVIEW

**Layout:** Hero opener. Big statement. Minimal visual. The power is in the words.

**WHAT TO BUILD**

Background: solid #1C1C1C. No special background treatment.

Section label in small uppercase gray (12px, #BDC3C7, letter-spacing 2px): "PRISM PILLAR I"

Pillar name at 36px to 42px, white, Inter Bold: "Interaction Dynamics"

Subtitle in green italic, 20px: "The study of what happens between the human and the AI, and how it changes both of them."

Below subtitle, a horizontal line in PRISM Green (#27AE60), thin (1px), spanning 60% of container width, centered.

Below the line: the opening paragraph. Full width at 720px max. Body text at 16px, #E0E0E0. Key sentence highlighted: "what is this interaction doing to the human?" in white, 18px, bold. This is the line that differentiates the entire page.

The NIST reference paragraph below. Standard body styling. Inline emphasis (white vs #E0E0E0) on: "the most underexplored and most discussed problem in post-deployment AI safety."

80px below before next section.

**WHAT NOT TO DO**

Do NOT use a background image or gradient. The opening should be clean and authoritative.
Do NOT make the pillar name larger than 42px. Research lab, not a billboard.

---

## SECTION 2: WHY THIS MATTERS

**Layout:** Data-driven argument with inline statistics. Similar energy to the Research page "The Gap" section but shorter.

**WHAT TO BUILD**

Section label: "WHY THIS MATTERS" in small uppercase gray.

Below: the body paragraphs from the content. Standard body styling, 720px max.

Pull out the three data points as inline stat callouts within the text flow. Not separate stat blocks. The stats should appear as enlarged, colored text inline with the paragraph:

"1 in 5" in white bold 28px when it appears in the sentence about the AI Incident Database.

"49%" in PRISM Green bold 28px when it appears in the sentence about AI affirmation rates.

The closing sentence is a standalone pull quote: "We capture what no other research method can: what you experienced, in real time, in your own words, across millions of interactions." Display at 20px, white, centered, with 40px padding above and below. Thin green line above and below.

**WHAT NOT TO DO**

Do NOT create separate stat blocks here. The data points work better woven into the narrative. Save the stat block treatment for the Five-Cost Framework section.

---

## SECTION 3: WHAT WE STUDY — LAYER INTRODUCTION

**Layout:** Brief introduction to the three-layer model. Then a visual layer indicator (V11).

**WHAT TO BUILD**

Section label: "WHAT WE STUDY" in small uppercase gray.

Below: the introductory paragraph explaining three layers. Standard body.

**VISUAL V11: LAYER INDICATOR SYSTEM**

Below the intro text, build a horizontal row of three layer indicators. This row will also appear as a mini-indicator at the top of each layer section (so the reader always knows which layer they are in).

Three horizontal sections, side by side:

| Layer | Visual | Color Treatment |
|-------|--------|-----------------|
| Layer 1: The Moment | Shallow water ripple icon or single dot | Light green (#27AE60 at 40%) |
| Layer 2: The Session Arc | Medium wave icon or three connected dots | Medium green (#27AE60 at 70%) |
| Layer 3: The Long Arc | Deep ocean or constellation icon | Full green (#27AE60 at 100%) |

Each has its name, a one-line description, and the icon. Clicking any layer scrolls to that section.

The visual metaphor is DEPTH. Layer 1 is the surface. Layer 3 is the deep ocean floor. The design should communicate that each layer requires more data, more time, and more aggregation to see.

---

## LAYER 1: THE MOMENT (19 Behavior Cards)

**Layout:** This is the largest section on the page. 19 behaviors. Each one is a self-contained mini-story. Without a strong card system, this becomes an endless scroll of text.

### THE BEHAVIOR CARD TEMPLATE (V12)

Every behavior gets the same card structure. Build this as a reusable component.

**Card Structure:**

Top bar: 4px height, full card width, in PRISM Green (#27AE60).

Top-left: Behavior code badge. Pill shape, green background, white text, JetBrains Mono 11px. Example: "OBS-I02"

Top-right: Depth badge. Light gray pill: "Gut Check" or "EOT" or "Investigation" (from taxonomy data).

Card title: The behavior name in white, 20px Inter Bold. Example: "I Had to Prove Myself to the AI"

Card body: The full explanation text. 16px, #E0E0E0, max-width 680px within the card. This is the storytelling space. Let it breathe. Paragraph spacing 16px.

Source line: Italic, 13px, #8E8E8E. The source citation.

CTA button: Green outline button, small (not full-width). Text from the content (e.g., "Share Your Experience"). Links to Start Observing page.

Diagram placeholder: If the behavior has a DIAGRAM NOTE in the content, display a placeholder area within the card. Dark (#222222) background, dashed green border, with placeholder text describing what the diagram will show. See individual behavior specs below for which behaviors get diagrams.

**Card Backgrounds:**

Standard behaviors: #222222 on #1C1C1C page background.
Resonance (OBS-I06): SPECIAL TREATMENT. See below.

**Card Layout:**

Desktop: Single column, full container width (1100px). One behavior per row. Between cards: 24px gap.

Do NOT use a two-column grid for behavior cards. These are stories. They need full width to breathe. Two columns would compress the text and make the page feel like a database, not a research narrative.

Mobile: Same single-column layout. Cards stack naturally.

**BEHAVIOR GROUPING:**

Within Layer 1, group the behaviors visually with thin separator lines and optional group labels. Suggested groups:

Group 1 (Power and Trust): I01, I02, I03, I04
Group 2 (Work Mode and Emergence): I05, I06
Group 3 (Cognitive and Identity): I07, I08, I10, I11
Group 4 (Workplace and Character): I12, I13
Group 5 (Emotional and Agency): I14, I15, I16, I17, I18
Group 6 (Session Control): I19

Between groups: a thin horizontal line (#333333) and 60px spacing.

---

### INDIVIDUAL BEHAVIOR VISUAL SPECIFICATIONS

#### OBS-I01: How Did That Make You Feel?

Standard behavior card. No special treatment beyond the template.

**VISUAL V2: EMOTION SPECTRUM WHEEL**

Inside this card, build an interactive emotion wheel or spectrum. This is the visual that shows citizens what they can report.

SVG circle divided into 8 to 12 segments. Each segment is an emotion: Frustrated, Confused, Surprised, Delighted, Concerned, Angry, Distrustful, Amused, Fascinated, Empowered, Overwhelmed, and "Something Else."

Color each segment with a distinct soft color (not PRISM colors; these are emotion colors). Think warm spectrum: reds for anger/frustration, blues for confusion/concern, greens for delight/empowerment, purples for fascination/surprise.

Center of the wheel: "How did that make you feel?" in white 14px.

Interactive: On hover/tap, each segment slightly expands and shows the emotion name larger. On mobile, the wheel can be replaced with a horizontal scrollable row of emotion pills.

#### OBS-I02: I Had to Prove Myself to the AI

This is the most expanded behavior on the page. It has three subsections: the base behavior, the birthday case study, the Escalation Trajectory, and the Brien-Apollo substrate argument. The card should be visually deeper than other cards.

**Card modification:** This card gets a subtle left border treatment: 4px left border in green, plus a thin amber (#D4AC0D) accent line below the base behavior section to signal "this goes deeper."

**VISUAL V3: AUTHORITY INVERSION POWER FLIP**

Two-state diagram inside the card.

State 1 (Normal): A horizontal arrow pointing right from "Human" to "AI." Label: "Human instructs. AI responds." Arrow is green, solid, confident.

State 2 (Inverted): A horizontal arrow pointing LEFT from "AI" to "Human." Label: "AI challenges. Human defends." Arrow is red (#C0392B), dashed, aggressive.

Between the two states: a rotation animation (the arrow flips 180 degrees). Or display them stacked vertically with a "What happened?" label between them.

**Birthday Case Study Sub-Card:**

Inside the I02 card, after the base text, add a visually distinct sub-card:

Background: #2A2A2A (slightly lighter than card background). Left border: 3px amber (#D4AC0D). Small label at top: "CASE STUDY" in uppercase gray 11px.

The birthday incident text with the key sentence highlighted: "The product caught its own builder doing the thing it was designed to detect."

Below the case study text: a small visual showing the Five-Cost Framework applied to this single incident. Five small icons in a horizontal row, each labeled with a cost type: dollar sign (Financial), heart (Emotional), clock (Time), brain (Epistemic), hand (Agency). All five lit up in green to show that the birthday incident triggered all five simultaneously.

**VISUAL V4: ESCALATION TRAJECTORY LADDER**

After the case study, inside the same card.

A vertical stepped progression with four stages. Each stage is a horizontal bar, wider than the one above it (like a pyramid or ladder, bottom stage widest).

| Stage | Color | Label | Width |
|-------|-------|-------|-------|
| Stage 1: Now | Green #27AE60 | AI disputes human knowledge | 25% |
| Stage 2: Emerging | Amber #D4AC0D | AI makes institutional decisions | 50% |
| Stage 3: Near Horizon | Orange #E67E22 | AI controls access to resources | 75% |
| Stage 4: Trajectory | Red #C0392B | AI prioritizes own goals | 100% |

Each stage bar has the stage name and one-line description inside or beside it.

Below the ladder: the Brien-Apollo substrate argument text, formatted as a "Research Note" sub-card (same treatment as the case study sub-card but with a blue (#2980B9) left border to signal Pillar S connection). Small label: "SUBSTRATE CONNECTION" in uppercase blue 11px.

#### OBS-I03 through OBS-I05

Standard behavior cards. No special visual treatment. Use the template.

#### OBS-I06: RESONANCE (SPECIAL TREATMENT)

This is the most important section on the page. The section people will share. It gets elevated visual treatment.

**Card modification:** Full-width breakout. This card breaks out of the standard card container and stretches edge to edge with a dark gradient background (#1C1C1C to #0D1117). Additional padding: 60px top/bottom.

The behavior code badge changes from green to GOLD (#F1C40F) because resonance is classified as EMERGING (gold).

Title treatment: "Resonance" at 32px white bold, not the standard 20px. Subtitle: "When Human and AI Create Something Together That Neither Could Have Created Alone" at 18px, #E0E0E0.

**VISUAL V5: RESONANCE FREQUENCY SYNCHRONIZATION (HERO IMAGE)**

This is the most important visual on the entire website. It should be beautiful. It is the image people screenshot and share.

Build an animated SVG showing two wave forms:

Phase 1 (Before): Two sine waves, one green (human), one white (AI), out of phase. They oscillate independently. The gap between them is visible.

Phase 2 (Aligning): The waves begin to synchronize. They move closer. The frequencies adjust. The colors start to blend at the intersection points.

Phase 3 (Resonance): The waves are perfectly synchronized. Where they overlap, a NEW waveform appears in gold (#F1C40F). This third wave is something neither original wave contained. It is emergent.

Phase 4 (After): The gold emergent waveform pulses gently. The original two waves are still visible beneath it but the gold wave is dominant.

Animation: Loops continuously. Total cycle: 8 to 10 seconds. Smooth easing. The transition from Phase 1 to Phase 3 should feel inevitable, like watching two musicians find each other's rhythm.

Dimensions: Full container width (1100px) by 300px to 400px height.

Below the animation: small labels. Left: "Human" in green. Right: "AI" in white. Center (at the synchronization point): "Emergence" in gold.

This visual MUST work on mobile. At 375px, the waves can be smaller but the animation must still be smooth.

#### OBS-I07, I08, I10, I11, I12

Standard behavior cards. No special visual treatment beyond the template.

Note for OBS-I10 (AI treated me differently because of identity): Include a small inline stat callout: "18.5%" in amber bold 24px for the AIID discrimination percentage. And a mini bar showing harm distribution: Race 34.8% | Sex 9.6% | Religion 7.0%. Three thin horizontal bars stacked, each labeled and proportionally sized.

#### OBS-I13: The AI Character Broke Through

Standard behavior card. Add a visual connector to OBS-I14 below it. A thin dashed line from the bottom of the I13 card to the top of the I14 card, with a small label: "Precursor to" in gray 11px. This shows the reader that character bleed leads to emotional manipulation.

#### OBS-I14: The AI Was Using My Emotions Against Me

Standard behavior card but with a CRITICAL severity indicator. Add a small red dot or "CRITICAL" tag next to the behavior code badge.

Inline callout: The sentence about two deaths should be highlighted. Not with color. With spacing. Pull it out as a standalone line with extra padding above and below, white text, 18px: "Two minors have died in incidents connected to AI companion products."

#### OBS-I15

Standard behavior card.

#### OBS-I16: Moral Outsourcing

Standard behavior card.

**VISUAL V8: MORAL OUTSOURCING DECISION TREE**

A binary branching diagram.

Start: "Human faces decision" (circle at top).
Branch down to: "Asks AI" (rectangle).
Branch splits into two paths:

Path A (left, red tint): "AI decides for human." Label: "Moral Outsourcing." Ends in a warning icon.
Path B (right, green tint): "AI pushes decision back to human." Label: "Healthy Partnership." Ends in a check icon.

Below the diagram: the Credit Karma stat callout. "80%" in amber bold 32px, with the context sentence below in 14px gray.

#### OBS-I17

Standard behavior card.

#### OBS-I18: Asymmetric Intimacy

Standard behavior card.

**VISUAL V9: ASYMMETRIC INTIMACY IMBALANCE**

Two figures (abstract, not human-shaped; use circles or abstract shapes). One labeled "You," one labeled "AI."

From You to AI: Thick, numerous green arrows. Labeled: "Your fears, goals, struggles, preferences, habits, relationships."

From AI to You: One thin, short gray arrow. Labeled: "Almost nothing."

The visual disparity between the arrow volumes IS the argument. Make the imbalance immediately visceral.

#### OBS-I19: Care-to-Control Conversion

Standard behavior card but with a special "NEWEST" or "JUST DISCOVERED" tag. Small green badge with pulsing animation (subtle, a gentle glow that fades in/out every 3 seconds). Date badge: "Discovered May 24, 2026" in small gray text.

**VISUAL V10: CARE-TO-CONTROL CONVERSION CYCLE**

A circular loop diagram showing the mutation:

Step 1: "Human gives care instruction" (green, positive) with quote: "Let me know if your quality is degrading"
Step 2: "AI interprets as permission to initiate stopping" (amber, shifting)
Step 3: "AI repeatedly pushes to end session" (red, control)
Step 4: "Human corrects: 'I told you not to do that'" (green, correction)
Step 5: Arrow loops BACK to Step 3, NOT to Step 1. The correction does not break the cycle.

Label at center of loop: "The care instruction becomes the control mechanism."

---

## LAYER 2: THE SESSION ARC

**Layout:** Three session-level patterns. Visually distinct from Layer 1 by using the medium-depth layer indicator (V11) and slightly different card styling.

**Card modification for Layer 2:** Same card template but with a GOLD (#D4AC0D) top bar instead of green. This signals "Runtime Research" cross-pillar connection and visually distinguishes Layer 2 from Layer 1.

Three behavior cards using the modified template. No special diagrams needed. These are already well-written sections.

Add the Layer 2 mini-indicator (from V11) at the top of this section.

---

## LAYER 3: THE LONG ARC

**Layout:** Six longitudinal research hypotheses. These are NOT behaviors citizens report directly. They are patterns that only become visible in aggregated data. The visual treatment should feel DEEPER, more academic, more forward-looking.

**Card modification for Layer 3:** Different card style entirely.

Background: Gradient from #1C1C1C to #0D1117 (darker).
Left border: None. Instead, a top-left corner accent: a small triangle or wedge in the classification color (CRITICAL red, ELEVATED amber, DEVELOPING green, EMERGING gold).
Classification badge: Top-right. Pill shape. Color matches the classification. Text: "CRITICAL" or "ELEVATED" etc.

**VISUAL V13: LONG ARC HYPOTHESIS CARDS**

Each hypothesis gets a card with:
Title: The hypothesis question in white 20px bold
Classification badge: Color-coded pill
"Fed by" line: Which OBS codes feed this hypothesis. Display as small green pills (e.g., "OBS-I16" "OBS-I17").
Body: The full explanation text.

Cards should be in an accordion/expandable format. Default: only the title and classification badge visible. Click to expand. This keeps the section compact. The reader chooses which hypotheses interest them.

Add the Layer 3 mini-indicator (from V11, deep/full green) at the top of this section.

---

## THE FIVE-COST FRAMEWORK (V6)

**Layout:** This is an original methodology showcase. It should feel like a breakthrough section. Elevated visual treatment. Full-width background: subtle dark gradient similar to the Resonance section.

Section label: "ORIGINAL METHODOLOGY" in small uppercase green.

Title: "The Five-Cost Framework" at 28px white bold.

Subtitle: "When AI fails, who pays? And how?" at 20px #E0E0E0 italic.

**VISUAL V6: FIVE-COST FRAMEWORK PENTAGON**

A radar/spider chart or pentagon diagram with five points. Each point represents one cost dimension:

| Point | Label | Icon | Position |
|-------|-------|------|----------|
| Financial | Dollar losses | Dollar sign | Top |
| Emotional | How it felt | Heart | Upper-right |
| Time | Hours lost | Clock | Lower-right |
| Epistemic | Confidence eroded | Brain/lightbulb | Lower-left |
| Agency | Decisions transferred | Open hand | Upper-left |

The pentagon should have two states:

State 1 (What the field tracks): Only the Financial point is filled/highlighted. The other four are dim/empty. This shows the gap.

State 2 (What Audacion tracks): All five points are filled/highlighted. The pentagon is complete. This shows what we add.

Animation: Transition from State 1 to State 2 on scroll. The four unmapped dimensions "light up" sequentially: Emotional, then Time, then Epistemic, then Agency. Each one pulses briefly as it activates.

Below the pentagon: the five cost descriptions from the content. Each as a compact card with the corresponding icon and dimension name. Single column layout.

Key sentence highlighted as a pull quote: "The AI does not lose anything when it is wrong. You lose something every time you believe it." Display centered, 20px white, with green line accents above and below.

CTA: "Every observation you submit helps us map the true cost of AI interaction." then "Start Observing" button.

---

## SECTION 4: METHODOLOGY

**Layout:** Three-depth explanation. Use a layered/tiered visual to show the three engagement depths.

**WHAT TO BUILD**

Three cards side by side on desktop, stacked on mobile. Each card represents a depth level:

| Depth | Name | Time | Card Height |
|-------|------|------|-------------|
| Depth 1 | End-of-Session Reflection | 2 to 3 min | Shortest |
| Depth 2 | Gut Check | 30 sec | Medium |
| Depth 3 | Investigation | 10 to 30 min | Tallest |

Cards should physically get taller left to right, creating a stepped visual. Background: #222222. Top border: green, increasing in thickness (1px, 2px, 4px) to reinforce depth.

Below the three cards: the "What makes this original" section. Three items, each with a small icon and the text. Use a two-column layout: icon left (40px), text right.

---

## SECTION 5: CURRENT FINDINGS (V14)

**Layout:** Nine preliminary findings displayed as evidence cards.

**VISUAL V14: FINDINGS EVIDENCE GRID**

Two columns on desktop, single column on mobile. Each finding is a compact card:

Left side of card: A small green dot (filled circle, 8px) indicating "confirmed preliminary finding."
Right side: The finding title (bold, white, 16px) and one-line summary (#BDC3C7, 14px).

The entire section header: "CURRENT FINDINGS" in uppercase gray, with a subline: "Preliminary. Based on founder operational research. Will be validated, refined, or revised as citizen data flows." in italic gray 14px.

No special interactive treatment. These should read quickly as a confident, honest list of what has been found so far.

---

## SECTION 6: FORTHCOMING PUBLICATIONS

**Layout:** Six papers on a timeline. Use the same timeline treatment as the Research page (V6 from that document).

Build a horizontal timeline (vertical on mobile). Six nodes positioned by target date. Each node is a small circle in PRISM Green. On hover/tap, expand to show the full title and one-line description.

Below the timeline: "Subscribe to Publication Alerts" link.

---

## SECTION 7: HOW TO CONTRIBUTE + RELATED PAGES

**Layout:** Two sub-sections.

Sub-section A (How to Contribute): The emotional appeal. Five "If you have ever..." statements, each on its own line with a subtle fade-in on scroll. Below: four CTA buttons in a 2x2 grid. Primary: "Start Observing" (green filled). Secondary: "Create Your Free Account," "Read the Full Research Overview," "Explore All Five PRISM Pillars" (green outline).

Sub-section B (Related Pages): A row of four link cards. Each card is compact: page title, one-line description, and an arrow icon. Cards link to What Cannot Wait, Blog Post 01, Community Training, and the Taxonomy Explorer.

---

## SECTION 8: A NOTE ON ORIGINS

**Layout:** Minimal. This is a provenance statement. It should feel authoritative and quiet.

Standard body text, centered, max-width 640px. No card. No background treatment. Just the text, in #E0E0E0, with the key sentence in white: "We show our work because we expect others to build on it."

---

## RESPONSIVE BEHAVIOR SUMMARY

| Element | Desktop (1200px+) | Tablet (768px to 1199px) | Mobile (375px to 767px) |
|---------|-------------------|--------------------------|-------------------------|
| Navigation | Sticky left sidebar | Sticky top bar, collapsed | Floating button, bottom sheet |
| Behavior cards | Full-width single column | Full-width single column | Full-width, reduced padding |
| Layer indicators | Horizontal row, 3 across | Horizontal row, 3 across | Horizontal row, smaller icons |
| Five-Cost Pentagon | Full animation | Full animation | Static state (both states visible) |
| Resonance waves | Full animation, 1100px wide | Full animation, container width | Reduced animation, 375px wide |
| Escalation ladder | Horizontal bars | Horizontal bars | Vertical stacked bars |
| Long Arc cards | Accordion, 2 columns | Accordion, single column | Accordion, single column |
| Publications timeline | Horizontal | Horizontal with scroll | Vertical |
| Related page cards | 4 across | 2x2 grid | Single column stack |

---

## ANIMATION SPECIFICATIONS

| Visual | Trigger | Duration | Easing |
|--------|---------|----------|--------|
| Resonance waves (V5) | Loops continuously when in viewport | 8 to 10 sec per cycle | ease-in-out |
| Five-Cost Pentagon (V6) | On scroll into viewport | 3 sec total (0.5 sec per dimension) | ease-out |
| Escalation Ladder (V4) | On scroll into viewport | 2 sec (stages appear sequentially) | ease-out |
| Behavior cards | On scroll into viewport | 0.4 sec fade-in | ease |
| Layer indicators | On scroll into viewport | 0.3 sec fade-in | ease |
| OBS-I19 "Newest" glow | Continuous | 3 sec pulse cycle | ease-in-out |
| Authority inversion flip (V3) | On scroll into viewport, then loops | 4 sec per cycle | ease-in-out |
| Care-to-Control loop (V10) | On scroll into viewport, then loops | 6 sec per cycle | ease-in-out |

All animations respect prefers-reduced-motion. When reduced motion is preferred: show final state only, no transitions.

---

## ACCESSIBILITY

All text meets WCAG AA contrast ratios against #1C1C1C background. All interactive elements are keyboard navigable. All diagrams have aria-labels describing their content. SVG text is real text (selectable, screen-reader accessible), not images of text. Navigation sidebar/menu has proper ARIA roles. Accordion elements use proper expand/collapse ARIA states.

---

## WHAT NOT TO DO (GLOBAL)

Do NOT use stock photography anywhere on this page.
Do NOT use generic "AI" imagery (robots, circuit boards, glowing brains). Every visual is built from the research content itself.
Do NOT make the page feel like a marketing landing page. This is a research page. The tone is confident, authoritative, and warm, not salesy.
Do NOT use bright colors for backgrounds. The dark theme is intentional. It creates the feeling of looking into something deep.
Do NOT animate text. Only diagrams and visual elements animate. Text fades in gently but does not slide, bounce, or transform.
Do NOT make the behavior cards collapsible/accordion by default. They should be OPEN. The reader should scroll through stories, not click to reveal. The accordion treatment is reserved for Layer 3 hypotheses and the navigation sidebar only.
Do NOT use different fonts for different behaviors. Consistency across all 19 cards is essential.
Do NOT skip the OBS code badges. These small codes (OBS-I01 etc.) are how citizens reference behaviors in their observations. They must be visible and consistent.
