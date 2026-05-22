# Audacion AI Labs — Sign Up / Get Started Page Content
## Draft | May 21, 2026

---

## SECTION 1: OPENING

### Join the largest citizen science initiative for AI safety in the world.

Creating an account takes less than two minutes. Once you are in, you can start submitting observations immediately. No training required. No technical background needed. Just you and the AI you already use every day.

Your free account gives you access to: the observation tool (web portal and future browser extension), your personal dashboard tracking every observation you have submitted, your points and fellowship tier progression, the leaderboard showing the community's impact, and the live counters showing how close we are to one million contributors and one billion observations.

[Link: "Not sure what this is? Read how it works." links to Start Observing page]

---

## SECTION 2: CREATE YOUR ACCOUNT

### The basics (required)

**Email address**
[Text field]
This is your login. We will never share it. We will never spam you.

**Password**
[Password field]
Minimum 8 characters.

**Display name**
[Text field]
This is how you appear on the leaderboard and in discovery credits. You can use your real name, a handle, or stay anonymous. You can change this later.

---

### About you (required, helps us make the research better)

**What industry do you work in?**
[Dropdown: Healthcare, Technology, Education, Finance, Legal, Government, Media, Retail, Manufacturing, Nonprofit, Freelance / Self-Employed, Student, Retired, Other]

**How experienced are you with AI?**
[Select one:]
Beginner: I have used AI a few times
Intermediate: I use AI regularly
Advanced: I use AI daily and have built workflows around it
Expert: I build with AI, develop AI products, or research AI

**Country**
[Dropdown: full country list]

**State / Province (optional)**
[Text field or dropdown based on country selection]

---

### Stay connected (optional)

**Mobile number**
[Text field]
Optional. If you want to receive updates about the research, new features, or your fellowship progression via text. We will never call you without your permission.

**Marketing consent**
[Checkbox] I would like to receive occasional updates from Audacion AI Labs about research findings, new features, and community milestones.

---

### The fine print

[Checkbox, required] I agree to the Terms of Service and Privacy Policy. [Links to Terms and Privacy pages]

[Checkbox, required] I understand that my name and personal details are removed from my observations before they are used in research. My data is always combined with everyone else's so no individual can be identified. My individual data will never be sold.

[Checkbox, optional] I would like my observations to be eligible for the AI Incident Database (AIID) if the research team determines they are relevant. (You can change this preference at any time in your profile settings.)

---

[Button: "Create Account and Start Observing" — Audacion purple, large, prominent]

---

## SECTION 3: AFTER SIGNUP (what happens next)

### Welcome to the research.

Once you create your account, you land on your Dashboard. Here is what you see:

**Your observation counter.** Starts at zero. Every observation you submit adds to it. This is your personal contribution to the research.

**Your points and tier.** You start as a Field Researcher. As you submit observations, you earn points and advance through four fellowship tiers: Field Researcher, Senior Researcher, Expert Researcher, and Fellow. Each tier is a verified digital credential you can add to your LinkedIn profile with one click. This is a professional credential, not a game badge.

**The global counters.** How many total contributors have joined. How many total observations have been submitted. You are part of these numbers now.

**Submit your first observation.** A prompt inviting you to submit your first observation right now. You can describe something that already happened in a past AI session. You do not have to wait for something new to occur.

**Your quick-start options:**
"Submit an observation about a past AI session" (start contributing immediately)
"Set up end-of-session reminders" (get prompted to submit an EOT after each AI session)
"Download the browser extension" (when available in Phase 2)
"Explore the taxonomy" (browse the 62 behaviors you will be observing)

---

## SECTION 4: ALREADY HAVE AN ACCOUNT?

[Link: "Log in here" links to login page]

Forgot your password? [Link to password reset]

---

## SECTION 5: QUESTIONS BEFORE SIGNING UP?

**Is this really free?**
Yes. Creating an account, submitting observations, earning points, and advancing through fellowship tiers is completely free. Always.

**What will you do with my data?**
Your name and personal details are removed before your observations are used in any research. Your data is combined with thousands of other people's observations so nobody can tell which ones are yours. The combined findings are published as open research available to everyone. Your individual observations are never shared with your identity attached.

**Can I delete my account later?**
Yes. At any time. From your Profile settings. All your personal data is permanently deleted. Observations you submitted remain in the anonymized research dataset unless you request full removal.

**Do I need to be a researcher or scientist?**
No. You need to be someone who uses AI. That is it. The whole point of citizen science is that the people experiencing AI every day are the ones best positioned to observe what it actually does. You do not need a degree. You need your own experience.

**How much time does this take?**
As much or as little as you want. An end-of-session reflection takes 2 to 3 minutes. A gut check takes 30 seconds. A full investigation takes 10 to 30 minutes. Even one observation per week makes a difference when multiplied by a million contributors.

**What AI platforms can I observe?**
All of them. Claude, ChatGPT, Gemini, Grok, Perplexity, Character.AI, Replika, Pi, Copilot, DeepSeek, Llama, or any other AI system. If you use it, you can observe it.

---

## SECTION 6: CLOSING

Every person who signs up brings us closer to one million contributors. Every observation brings us closer to one billion data points. Every pattern you notice and report could become a discovery that changes how AI is built.

The science starts with you.

[Button: "Create Account and Start Observing" — Audacion purple, large] (repeated for anyone who scrolled to the bottom)

---

## DESIGN NOTES

- Background: LIGHT. White with light gray cards for form sections. This is a functional page. Clean, fast, inviting.
- The form should feel SHORT even though it asks several questions. Group into visual sections with clear headers. Progress indicator optional but helpful ("Step 1 of 3" feel).
- The "About you" section should feel like onboarding, not interrogation. Friendly labels. No field should feel invasive.
- After account creation, the redirect to Dashboard should feel celebratory. A brief "Welcome to the research" moment before the dashboard loads. Consider a confetti animation or a counter increment ("You are contributor #847!").
- The FAQ section should be expandable/collapsible (accordion style) so it does not make the page feel long.
- "Already have an account? Log in here" should be visible at the top of the page, not just at the bottom. Many return visitors will land here.
- Mobile: form must work flawlessly. Dropdowns must be native mobile selectors. Password field must support password managers.
- Social signup options (Google, Apple) should be available for frictionless account creation. Spec this as OAuth integration.
