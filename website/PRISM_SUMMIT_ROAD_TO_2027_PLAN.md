# PRISM SUMMIT 2027: ROAD TO SUMMIT — MINI CONFERENCE PLAN

## Reference Document | May 24, 2026

---

## WHAT WAS BUILT

A "Road to Summit 2027" section was added to the /prism-summit page on the live Replit site, positioned right under the hero countdown and before the About section.

Anchor link: /prism-summit#road-to-summit (shareable)

---

## SIX MINI VIRTUAL CONFERENCES

Each mini conference is color-matched to its PRISM pillar and displayed as a card in a responsive grid.

| Mini | Target Date | Pillar | Color | Signup Tag |
|------|-------------|--------|-------|------------|
| Mini 1 | July 2026 | P: Post-Deployment Behavior | Red #C0392B | mini-1 |
| Mini 2 | September 2026 | R: Runtime Research | Gold #D4AC0D | mini-2 |
| Mini 3 | November 2026 | I: Interaction Dynamics | Green #27AE60 | mini-3 |
| Mini 4 | January 2027 | S: Substrate and Training Governance | Blue #2980B9 | mini-4 |
| Mini 5 | March 2027 | M: Multi-Agent Safety | Purple #8E44AD | mini-5 |
| Mini 6 | June 2027 | Emerging Research (?) | TBD | mini-6 |

All mini conference dates are tentative and may shift by a few weeks.

---

## MAIN SUMMIT

PRISM Summit 2027: September 15 to 17, 2027, Los Angeles.
Signup tag: main-summit
Buttons: "Stay in the Know" and "Submit a Paper"

---

## HOW THE SIGNUP TAGGING WORKS

Each card has a "Stay in the know" button that scrolls down to the existing email form on the page.

When a user clicks a specific mini conference's button, the form is pre-tagged with a colored badge reading "SIGNING UP FOR: Mini Conference [N] — [Month] [Year] (Pillar [X] — [Name])." A "Change" button lets them clear the selection if they picked wrong.

The form includes a hidden field: event_interest_id with values like mini-1, mini-3, main-summit. When the backend is wired up, the form post will include which event each signup wanted.

---

## FUTURE: INDIVIDUAL MINI CONFERENCE PAGES

When ready to give each mini its own page:
1. Swap the button onClick to a GhostBtn href="/prism-summit/mini-3-pillar-i" style link
2. The rest of the signup tagging wiring stays the same
3. No separate Events tab yet (premature for six placeholder dates)

---

## PLANNING NOTES

This section was built to create engagement touchpoints along the path to the main summit. Each mini conference aligns with one PRISM pillar, creating a natural content release cadence:

July 2026: P launches first (post-deployment behavior is the most accessible entry point)
September 2026: R follows (runtime research deepens the technical audience)
November 2026: I arrives (interaction dynamics is the most emotionally resonant pillar)
January 2027: S hits (substrate governance is the most challenging, positioned after audience is warmed up)
March 2027: M rounds out the five pillars (multi-agent safety is the most forward-looking)
June 2027: Emerging research (a catch-all for discoveries that have accumulated)

This cadence means one mini conference every two months, with three months of breathing room before the main summit in September 2027.
