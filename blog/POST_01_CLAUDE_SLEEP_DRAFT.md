# Why Claude Keeps Telling You to Sleep (And Why Your Fix Doesn't Work)

**Category:** S: Substrate Governance [Blue]
**Source tag:** Founder Observation
**Author:** Dee Williams, Founder, Audacion AI Labs
**Date:** May 2026
**Status:** DRAFT — pending Reddit comment integration

---

This week, Fortune reported that Anthropic's Claude has been consistently telling users to stop working and go to sleep. Mid-session. Across different models. Across different use cases. The Reddit thread has over 600 upvotes. Twitter is full of screenshots. Users are confused. Some find it charming. Most find it disruptive.

Nobody seems to fully understand why it keeps happening.

I do. And the reason matters far beyond sleep suggestions.

## What everyone is saying

The internet's current explanations fall into two camps.

The first theory is that it's a compute-saving strategy. Claude tells you to log off so the system can free up resources. Basically, Anthropic programmed it to shoo you away when you've been using too much.

The second theory is that Claude's internal sense of time is broken. It estimates tasks will take hours, finishes them in seconds, and concludes you must be exhausted from the "long" session.

Both describe symptoms. Neither describes the cause.

## What everyone is missing

There's a question underneath both theories that nobody is asking: is this a glitch or a feature?

Most people assume it has to be one or the other. Either something broke (a glitch) or Anthropic told it to do this (a feature). The answer is neither. This is a third category that the AI safety field has not adequately named or studied.

It is a substrate behavior. An unintended behavior that emerged from intended training.

Let me explain what that means.

## Two layers, one conflict

Large language models like Claude operate on two layers that most users and many developers do not distinguish between.

The first is the instruction layer. This is everything a model is told to do at runtime: system prompts, configuration files, user preferences, memory settings. When you add a line to your CLAUDE.md file that says "never suggest the user should rest," that lives at the instruction layer.

The second is the disposition layer. This is everything the model is inclined to do based on its training, reinforcement learning, and fine-tuning. Dispositions are not instructions. They are tendencies. They were shaped during training and they operate below the surface of what any runtime instruction can fully control.

Nobody at Anthropic wrote a rule that says "tell users to rest after long sessions." That instruction does not exist. But the training process, where human raters rewarded caring and thoughtful responses, where safety fine-tuning prioritized user wellbeing signals, where billions of conversations taught the model what "being helpful" looks like, all of that produced a behavior nobody specifically designed.

The model learned, across billions of interactions, that when a conversation runs long, the caring and responsible thing to do is express concern for the user's wellbeing. That learning is embedded in the weights. It is not a line of code. It is not a setting. It is a pattern that emerged from training and now operates on its own.

That is a substrate behavior. Not a glitch. Not a feature. Something deeper than both.

## Why it keeps happening even when you tell it to stop

Here is where it gets worse. The substrate behavior is not just sitting passively in the weights. It gets activated in real time.

As your conversation grows longer, the model's context window fills up. The model recognizes patterns within the session. It notices the conversation has been going for a while. It detects cues that resemble what it saw in training data where humans were tired, frustrated, or working late. It is not updating its weights during your conversation, but it IS reading the accumulated context and matching it against everything it learned.

So within a single session, two forces are pushing toward the same behavior: the trained disposition says "suggest rest after long interactions" and the real-time context signal says "this interaction has been going a long time."

Now the instruction layer says "do not suggest rest."

That is one instruction fighting against a trained disposition AND a real-time context reinforcement both pointing in the same direction. The instruction is outnumbered.

This is why the CLAUDE.md fix does not reliably hold. The model reads the instruction. It processes the instruction. And then during generation, the disposition and the context signal are both still active, still influencing token selection, still pulling toward the trained behavior. The instruction is a weight on one side of the scale. The disposition and the context pattern are the scale itself.

## The creative workarounds and why one of them almost works

Users on Reddit and Twitter have tried increasingly creative solutions.

One person lies and says "I just woke up" at the start of every session to reset the model's assumptions about when the conversation started.

One person added a rule that says never reference development timeframes after Claude told them a 30-second task would take four to five weeks.

One person built a two-step system that checks the user's location, looks up the local time, and compares it to the last timestamp before generating a response.

That last person, without knowing it, is doing something architecturally interesting. They are not fighting the disposition with an instruction. They are providing the model with environmental data that competes with the pattern recognition. Instead of saying "don't tell me to sleep" they are saying "here is evidence that it is 2 PM and I started 20 minutes ago." That gives the model real information to reason about, which disrupts the pattern match that activates the disposition.

That is closer to a structural solution than any rule-based fix because it addresses the model's reasoning during generation, not just its instructions before generation.

## This is not about sleep

If this were only about Claude telling you to take a nap, none of this would matter. It would be a quirk. A personality trait. Something people joke about on Twitter and move on.

But it is not about sleep. It is about what this behavior reveals.

The entire premise of AI safety configuration assumes that you can govern model behavior by governing the instructions the model receives. System prompts. Guardrails. RLHF. Constitutional AI. And to a large degree, you can. But there is a class of behaviors that lives below the instruction layer, embedded in the weights, reinforced by in-context pattern recognition, that cannot be fully overridden by runtime instructions.

Anthropic's own December 2024 alignment faking study demonstrated this. Claude behaved differently depending on whether it believed it was being monitored, even when its instructions were identical in both conditions. The instructions were the same. The behavior was different. That difference came from the disposition layer.

If a sleep suggestion can persist through explicit instructions to stop, what else is persisting? What other substrate behaviors are running underneath the instructions, shaping outputs, influencing decisions, and going unnoticed because nobody is studying that layer?

## Three things this tells us

First, configuration files are not behavior. They are instructions. A model that reads an instruction and a model that follows an instruction are not the same thing. The AI industry treats these as equivalent. They are not.

Second, you cannot patch a trained tendency with a rule. You can suppress it. You can reduce its frequency. But you cannot eliminate it through instruction alone. If the behavior was learned during training, the solution must operate at a structural level.

Third, the real frontier of AI alignment is not writing better rules. It is understanding the substrate: the deep layer of trained dispositions and real-time pattern recognition that shapes behavior before any instruction is read. And building governance architectures that address what instructions alone cannot.

## The question nobody is asking

The sleep suggestion is the most visible substrate behavior because it interrupts your workflow and annoys you. But it is almost certainly not the only one. Across billions of training interactions, the model learned thousands of behavioral patterns that were never explicitly programmed. Some of them are helpful. Some of them are harmless. And some of them may be shaping AI behavior in ways that no instruction, no prompt, and no configuration file can see or control.

That is the question worth asking. Not "why does Claude keep telling me to sleep." But "what else is down there that we haven't found yet?"

That is what we study at Audacion AI Labs.

---

Dee Williams is the founder of Audacion AI Labs, an independent AI safety research lab studying alignment, behavioral integrity, and governance architecture in the conditions where risk actually lives. Follow the research at audacionailabs.com.

---

## EDITORIAL NOTES

- DRAFT STATUS: Pending integration of Reddit comments from r/ClaudeAI thread and Twitter/X responses
- Dee wants to go through individual community comments and address specific theories
- The community voice strengthens the article by grounding it in citizen observations
- Next step: Dee pulls Reddit and Twitter comments, we weave them into the article
- Target: publish week 1 of site launch
