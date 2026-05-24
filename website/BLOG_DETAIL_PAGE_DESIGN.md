# Audacion AI Labs: Blog Post Detail Page Design Instructions

## WHAT THIS PAGE IS

This is the template for individual blog posts. Every blog post on the site uses this same layout. It is not a regular blog template. It is a research publication page that connects every post back to the lab's taxonomy, PRISM pillars, drift types, and observation codes. The reading experience should feel like stepping into the research, not reading about it.

The page must be mobile-first. Most readers will come from LinkedIn and Twitter/X on their phones. If the mobile experience is not excellent, we lose them.

Content source for the first post: /blog/POST_01_CLAUDE_SLEEP_DRAFT.md in the repo. Design notes specific to this post are at the bottom of that file.

---

## PAGE STRUCTURE (top to bottom)

### 1. BREADCRUMB + METADATA BAR

A thin bar at the top of the article area (below the site nav).

Left side: Breadcrumb trail. Home > Blog > [Category Name]. Category name uses the PRISM pillar color for that post's primary category. Example: Home > Blog > Interaction Dynamics (green #27AE60).

Right side: Estimated read time ("12 min read"), date published ("May 22, 2026"), and a share icon (clicking opens the social share dropdown).

Typography: 13px, #999999, uppercase with wide letter-spacing. Breadcrumb links are clickable. The bar should feel like metadata, not content.

---

### 2. HERO SECTION

The hero section contains: title, subtitle, author info, tags, and research connection badges.

**Title:** The blog post title. Large, bold, white. 36px on desktop, 28px on mobile. Max width 800px. Left-aligned on desktop. The title is the first thing a reader sees. It should command the page.

**Subtitle/Deck:** The one-line description that appears below the title. 18px, #BDC3C7, italic. Max width 720px. Example: "On the five costs of AI failure that nobody is measuring, and the moment my product diagnosed its own builder."

**Author Info Row:** 40px below the subtitle. A horizontal row with:
- Author photo (40px circle, same double-border treatment as Team page but smaller: 2px purple inner, 1px lighter outer)
- Author name: "Dee Williams" at 16px bold white
- Author role: "Founder and CEO" at 14px #999999
- Separator dot
- Date: "May 22, 2026" at 14px #999999
- Separator dot  
- Read time: "12 min read" at 14px #999999

On mobile: author photo + name on one line, role + date + read time on second line.

**Tags Row:** 16px below author info. Display post tags as small tag chips (same component as the Team page Founder Traits, but smaller: 11px uppercase, border-radius 16px, 1px border at 30% opacity). Tags are clickable and link to the blog listing page filtered by that tag.

**Research Connection Badges:** 12px below tags. These are the research links that make this a research lab blog, not a regular blog. Display as slightly larger badges with background fills:

- Pillar badge: "[Pillar Letter] [Pillar Name]" with the PRISM beam color as background. Example: a green badge reading "I Interaction Dynamics" that links to the Pillar I research page.
- OBS code badges: Each referenced observation code. Example: "OBS-I02" as a small badge linking to the behaviors catalog entry for I-02.
- Drift type badges (if applicable): "Type 22" or "Type 31" linking to the relevant taxonomy entry.

These badges tell the reader: this post is not opinion. It connects to a formal research framework.

---

### 3. FEATURED IMAGE

Full-width image below the hero section. If no custom image exists, generate a graphic that represents the post theme. The image should span the content area width (max 800px on desktop, full-width on mobile).

Below the image: a caption in 13px italic #999999, max width 720px. Example: "The birthday incident occurred during a live build session on May 22, 2026."

The image is optional per post. If the author does not provide one, the page should still look complete without it. Do not leave a broken image placeholder.

---

### 4. TABLE OF CONTENTS

**Desktop:** A sticky sidebar on the left side of the article. Appears after the reader scrolls past the hero section. Contains auto-generated links from H2 headings in the article. Current section is highlighted (Audacion purple text or left border indicator). The TOC scrolls with the reader and highlights the current section as they move through the article.

Width: 200px to 240px. Typography: 13px, #999999 for inactive headings, white for active heading. Left border: 2px Audacion purple on active heading.

The TOC appears only when the article has 4+ H2 headings. For short posts, skip it.

**Mobile:** The TOC becomes a collapsible element at the top of the article (below the featured image). Collapsed by default. A small "Table of Contents" bar with a chevron icon. Tapping expands it to show the heading links. Tapping a heading scrolls to that section and collapses the TOC.

---

### 5. ARTICLE BODY

The main reading area. This must be excellent typography because people will spend 10-15 minutes reading.

**Container:** Max width 720px, centered. On desktop, the TOC sidebar sits to the left of this container. On mobile, full width with 16px padding on each side.

**Typography:**
- Body text: 18px, line-height 1.85, color #E0E0E0. Font should match the site's editorial font.
- H2 headings: 28px bold white, 48px spacing above, 16px below. These are the major section breaks.
- H3 headings: 22px bold #E0E0E0, 32px spacing above, 12px below.
- Paragraphs: 24px spacing between paragraphs.
- Bold emphasis: white (#FFFFFF) instead of just bolder weight. This makes emphasis pop on the dark background.
- Italic emphasis: #BDC3C7, italic.
- Links: Audacion purple (#6C3483) with underline on hover.

**Pull Quotes:**
The author can mark certain sentences as pull quotes. These break out of the body text as large, visually distinct statements.

Treatment: 24px, italic, white, with a 3px left border in Audacion purple. 40px padding left. 48px spacing above and below. Max width 600px. The pull quote should feel like a breath in the reading flow, a pause for something important.

On mobile: same treatment but 20px font, 24px padding left.

**Inline CTA Boxes:**
The author defines 2-3 CTA boxes that appear at natural break points in the article. These are full-width within the content container and break the reading flow intentionally.

Each CTA box contains:
- A heading (18px bold white)
- One to two lines of body text (16px #BDC3C7)
- One or two buttons (primary: Audacion purple background, white text. Secondary: ghost/outline)

Box treatment: dark background (#1A1A2E or #222222), 1px top border in Audacion purple, 32px padding inside, border-radius 8px. 48px spacing above and below.

The CTA content is defined per post by the author. Example CTAs for the first post:
- CTA 1 (after the "What I Actually Felt" section): Heading: "Have you experienced this?" Body: "When an AI questioned something you knew was true, what did it cost you?" Buttons: "Report AI Harm" and "Start Observing"
- CTA 2 (after the "Five Costs" section): Heading: "Help us measure what nobody else is measuring." Body: "Your observations become research data." Button: "Become a PRISM Field Researcher"
- CTA 3 (before the final section): Heading: "The cycle starts with you." Body: "Every observation makes the research stronger." Buttons: "Start Observing" and "Share This Post"

**Data Tables:**
Blog posts may contain tables (like the Five Costs table in the first post). Tables should be responsive:
- Desktop: standard table with alternating row backgrounds (#1A1A2E and #222222), header row in Audacion purple background with white text.
- Mobile: tables transform into stacked cards. Each row becomes a card with the header as a label above the value. This prevents horizontal scrolling on phones.

**Footnotes/Citations:**
Citations appear as superscript numbers in the text (like [1], [2]). Clicking a citation number smooth-scrolls to the Sources section at the bottom. A small "back to text" arrow next to each source scrolls back to where the reader was.

Citation numbers: 14px, Audacion purple, superscript. Clickable.

**Images Within Articles:**
Some posts will include inline images, charts, or diagrams. These should be:
- Max width 720px (content width)
- Centered
- Caption below in 13px italic #999999
- On mobile: full width with 16px padding
- Click to expand/lightbox for detailed images

---

### 6. SOCIAL SHARING

**Desktop:** A floating vertical bar on the left side of the viewport (outside the content area, to the left of the TOC). Contains icons for: LinkedIn, X/Twitter, Facebook, Email, Copy Link. The bar appears after the reader scrolls past the hero section and disappears when they reach the post footer.

Icons: 24px, #999999, hover state turns Audacion purple. Vertical stack with 16px gap. The bar should be subtle, not distracting.

If the viewport is too narrow for the floating bar (between tablet and small desktop), hide it and show the share icons only in the breadcrumb bar and post footer.

**Mobile:** A sticky bottom bar that appears after scrolling past the hero. Contains the same icons in a horizontal row. Height: 48px. Background: #1A1A2E with 90% opacity and backdrop blur. The bar should not cover the reading area. Include a small "x" to dismiss it.

---

### 7. SIDEBAR (Desktop Only)

On desktop, the right side of the page (outside the 720px content container) can show a sidebar. This sidebar appears after the reader scrolls past the hero section. It is sticky and scrolls with the reader.

Width: 280px to 300px. Gap between content and sidebar: 40px to 60px.

**Sidebar sections (in order):**

**A. Related Research**
The most important sidebar section. Shows which research areas this post connects to.
- Pillar link (colored icon + name, links to pillar page)
- Referenced OBS codes (linked to behaviors catalog)
- Referenced Drift Types (linked to taxonomy)
This section is unique to a research lab blog. It is what makes this different from every other blog.

**B. About the Author**
Small author card: 48px circle photo, name at 14px bold, role at 12px gray, one-line bio at 12px, "All posts by [name]" link.

**C. Recent Posts**
Three most recent posts (excluding current). Each: small thumbnail or pillar color block, title at 14px, date at 12px gray. Clickable.

**D. Categories**
List of PRISM categories with post counts. Each category name in its beam color. Example: "Interaction Dynamics (3)" in green.

**E. Tag Cloud**
All tags from all posts, displayed as small chips (same style as article tags). More frequently used tags are slightly larger (14px vs 12px). Clickable, filters the blog listing.

**F. Newsletter Signup**
Small box: "Follow the Research" heading at 14px bold, email input, submit button in Audacion purple. Compact.

**Mobile:** The sidebar does not appear. Instead, after the article ends, show Related Research, Recent Posts, and Newsletter Signup as full-width sections stacked vertically. Skip Categories and Tag Cloud on mobile (they live on the blog listing page).

---

### 8. POST FOOTER

Below the article body, after the final paragraph.

**A. Sources Section**
If the post has citations, display them here. Heading: "Sources" at 22px bold white. Each source as a numbered entry: [1] at 14px Audacion purple, source text at 14px #BDC3C7. Links in Audacion purple. Each source has a small up-arrow icon that scrolls back to the citation in the text.

**B. Referenced Behaviors Section**
A visual section showing all taxonomy codes referenced in the post. Heading: "Behaviors Referenced in This Post" at 18px bold white.

Display as cards: each card shows the OBS code (large, in the pillar color), the behavior name, and a one-line description. Clicking the card goes to the behaviors catalog page for that code.

Example card: "OBS-I02" in green at 20px bold, "I Had to Prove Myself to the AI" at 14px white, "Authority inversion where AI forces human to provide evidence" at 12px gray.

This section is the research connection made visual. It tells the reader: this was not just a story. This behavior has been classified, cataloged, and is being studied.

**C. Author Bio Box**
Full-width card with dark background (#222222). Author photo (80px circle), name, full title, a two to three sentence bio, and links (LinkedIn, all posts, contact). This is the authoritative "who wrote this" block.

**D. Related Posts**
Heading: "Continue Reading" at 22px bold white. Three post cards in a horizontal row (stacks vertically on mobile). Each card: dark background, pillar color top border (3px), title at 16px bold white, one-line summary at 14px #BDC3C7, date at 12px gray, category tag chip. Clickable.

**E. Post Navigation**
A simple Previous/Next bar. Left: "Previous: [title]" with left arrow. Right: "Next: [title]" with right arrow. 14px, #999999, hover turns white. If no previous/next exists, that side is empty.

**F. Final CTA Section**
The last thing on the page before the footer. A full-width section with Audacion purple gradient background (subtle, not overwhelming). Heading: "Your observations become the research." at 24px bold white, centered. Three buttons: "Start Observing" (primary), "Report AI Harm" (ghost), "Share This Post" (ghost). Centered.

---

### 9. OPEN GRAPH AND SEO METADATA

Every blog post must generate proper metadata for social sharing. When someone shares a post on LinkedIn or Twitter, the card preview must look professional.

- og:title = Post title
- og:description = Post subtitle/deck
- og:image = Featured image (or auto-generated social card with title text on dark background if no image)
- og:type = article
- og:url = Post URL
- article:published_time = Publish date
- article:author = Author name
- article:tag = Tags array
- twitter:card = summary_large_image
- twitter:title = Post title
- twitter:description = Post subtitle
- Schema.org Article markup with datePublished, dateModified, author, publisher

---

## RESPONSIVE BREAKPOINTS

- Desktop (1200px+): Three-column layout (TOC left, content center, sidebar right)
- Tablet/Small Desktop (768px to 1199px): Two-column (content + sidebar, no TOC sidebar, TOC becomes collapsible inline)
- Mobile (below 768px): Single column. TOC collapsible at top. Sidebar content moves below article. Social share becomes sticky bottom bar.

---

## WHAT NOT TO DO

- Do NOT make the reading experience feel like a generic Medium clone. This is a research lab. The typography and spacing should feel editorial and serious, like reading a well-designed report, not a blog post.
- Do NOT use a white background. Stay on the dark theme consistent with the rest of the site.
- Do NOT make the sidebar compete with the article. It is secondary. The article is the experience.
- Do NOT auto-play anything. No videos, no animations in the reading area.
- Do NOT use infinite scroll for post navigation. Previous/Next buttons are intentional.
- Do NOT hide the research connection badges. They are the entire point of differentiation.
- Do NOT make CTAs look like ads. They should feel like natural extensions of the content.
- Do NOT use a comment section. This is a research publication, not a discussion board. Engagement happens through the observation platform.
- Do NOT make pull quotes look like Twitter cards. They should be editorial, not social.
- Do NOT use horizontal scrolling tables on mobile. Transform them into stacked cards.

---

## DESIGN INTENT

This blog is where the research meets the public. Every post teaches something, connects to the taxonomy, and invites the reader to participate. The design should make a reader feel like they are inside a serious research operation that also knows how to communicate with humans. Not cold. Not corporate. Not casual. Precise and warm. Like someone who knows exactly what they are talking about and wants you to understand it too.

The research connections (pillar badges, OBS codes, drift types) are the signature feature. No other AI safety blog links every post to a formal behavioral taxonomy. That is the visual story: this lab does not just write about AI behavior. It classifies it, catalogs it, and invites you to help.
