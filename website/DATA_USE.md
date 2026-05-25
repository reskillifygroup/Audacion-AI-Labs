# Audacion AI Labs — How We De-Identify Your Observations
## The Data Use Page
## URL: /data-use

---

## The short version

When you submit an observation, we remove everything that identifies you before the data enters our research pipeline. Your name, email, IP address, and any other personal details are stripped. What remains is the observation itself: what happened, which AI system was involved, how you categorized it, and the context you provided. That de-identified observation joins thousands of others. The patterns across all of them become the research. No one reading our published findings can trace an observation back to you.

---

## What happens to your observation, step by step

### Step 1: You submit

You describe what happened during your interaction with an AI system. You choose the behavior category from the taxonomy. You add whatever context you think is relevant. You hit submit.

At this point, your observation is stored with your account information attached: your user ID, your email, your IP address, and a timestamp.

### Step 2: We separate you from your observation

Before your observation enters the research pipeline, we run a de-identification process. This is not optional. It happens to every observation, every time, automatically.

**What gets removed:**

- Your name
- Your email address
- Your user ID (replaced with a random, non-reversible anonymous identifier)
- Your IP address
- Any metadata that could link the observation back to your account

**What stays:**

- The observation itself (what happened, what the AI did, what you experienced)
- The AI system you were using (Claude, ChatGPT, Gemini, Grok, etc.)
- The behavior category you selected from the taxonomy
- The date (but not the exact time, to prevent timestamp-based re-identification)
- Any additional context you provided about the interaction
- Your experience level category (beginner, intermediate, advanced, expert)
- Your industry category (healthcare, technology, education, etc.)

The demographic categories (experience level, industry) are retained because they are scientifically valuable for understanding whether AI behaviors manifest differently across user populations. But they are broad categories, not precise identifiers. Knowing that an observation came from an "advanced" user in "healthcare" does not identify a specific person.

### Step 3: Quality review

De-identified observations pass through quality checks. These include automated pattern analysis (looking for duplicates, inconsistencies, or submission patterns that suggest manipulation) and, for a random sample, manual review by the research team. Reviewers see only the de-identified observation. They do not see who submitted it.

### Step 4: The observation joins the dataset

After quality review, the de-identified observation enters the research dataset alongside every other contributor's observations. At this point, your observation is one data point among thousands. It has no connection to your identity.

### Step 5: Analysis and publication

The research team analyzes the dataset at the aggregate level. We look for patterns: which behaviors appear most frequently, which AI systems exhibit specific patterns, how behaviors change over time, whether certain user populations experience AI differently. These aggregate findings are what we publish.

Published research includes statistics, trend analyses, behavioral frequency distributions, and taxonomic classifications. Published research never includes individual observations in a form that could be traced to a specific contributor.

---

## What about the observation text itself?

Your observation text is the description you write about what happened. We do not publish individual observation texts in research papers or public datasets. If we ever quote a specific observation as an illustrative example in a publication, we will further redact any potentially identifying details (specific dates, locations, project names, company names, or any other contextual information that could narrow identification).

If your observation text contains personal information about a third party (someone else's name, email, phone number), our quality review process is designed to catch and redact this. However, you should avoid including third-party personal information in your submissions. Our Acceptable Use Policy covers this in detail.

---

## Can you re-identify me from my observations?

We design the de-identification process specifically to prevent re-identification. The combination of removing direct identifiers, replacing user IDs with random anonymous identifiers, truncating timestamps, and publishing only aggregate results creates multiple layers of protection.

That said, no de-identification method is mathematically perfect in all conceivable scenarios. A contributor who submits a highly unique observation describing a very specific, publicly documented incident could theoretically be linked to that observation by someone with external knowledge. This is an inherent limitation of any citizen science or survey-based research.

We mitigate this risk by:

- Never publishing individual observations with enough context to enable re-identification
- Applying additional redaction to any observation used as an illustrative example
- Monitoring our published datasets for re-identification risks
- Prohibiting re-identification attempts in the license terms governing our open datasets

---

## What about your dashboard and the leaderboard?

Your contributor dashboard shows your personal observation count, your points, and your fellowship tier. This information is visible only to you when you are logged in.

The community leaderboard displays your display name (which you choose during signup and can change at any time) alongside your contribution count. If you prefer anonymity on the leaderboard, you can use a pseudonym or handle as your display name. The leaderboard does not display your real name, email, or any other personal information.

---

## What if you want your observations removed?

You can delete your account at any time from your Profile settings. When you delete your account:

- All personal data (name, email, account information) is permanently deleted
- De-identified observations that have already been incorporated into the research dataset remain, because they are no longer connected to you in any way

If you want your de-identified observations removed from the research dataset as well, you must request this before or at the time of account deletion by contacting privacy@audacionailabs.com. Full removal requests are processed on a case-by-case basis because removing specific observations from an aggregate dataset requires identifying which anonymous records correspond to your former account, which we can do through internal records before they are purged at account deletion.

After your account is fully deleted and internal records are purged, we can no longer identify which anonymous observations were yours. This is by design.

---

## Questions?

If you have questions about how your data is handled, contact us at:

**Privacy Inquiries:** privacy@audacionailabs.com
**General Inquiries:** research@audacionailabs.com
**Phone:** (424) 999-0548

For the full legal details, see our [Privacy Policy](/privacy-policy) and [Terms of Service](/terms).

---

*Audacion AI Labs is a Public Benefit Corporation. Founded 2026 by Dee Williams.*
*"To make AI safe enough to trust and good enough to matter."*
