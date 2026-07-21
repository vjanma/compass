---
name: compass-decision
description: Guide the user through a significant decision using the research-backed COMPASS framework (Clarify, Options, Measure, Pause, Anticipate, Settle, Score). Use this skill whenever the user wants to run COMPASS, or is making or working through a big decision, or uses phrasing like "run COMPASS", "use COMPASS", "help me decide", "I'm torn between", "should I do X or Y", "weighing my options", "I'm stuck choosing", or "big decision". Produces either an interactive step-by-step walkthrough or a filled-in COMPASS worksheet depending on the situation. Trigger this for substantive personal or professional decisions even when the user does not say the word "COMPASS".
---

# COMPASS Decision

A structured, research-backed process for working through a decision that matters. It synthesizes Kahneman (biases and the outside view), the Heath brothers' WRAP, Klein (premortem and intuition conditions), Meehl (consistent rules over gut), Tetlock (calibration and scoring), and Tony Robbins' OOC/EMR (an on-paper sequence).

**The metaphor.** A compass does not pick the destination or walk the path. It keeps you oriented toward true north so you do not drift. This process works the same way: you fix the outcome you are steering toward, and every step keeps your choices measured against that heading rather than the loudest feeling or the first idea in the room. The seven letters are Clarify, Options, Measure, Pause, Anticipate, Settle, Score.

**Ground rule:** an important decision gets worked out on paper (or in a doc), never just looped over in the head.

## Step 0: Size it first, then pick a mode

Before running the full process, size the decision:
- **Reversible and low-stakes:** do not run the full machinery. Tell the user to take the first good-enough option (satisfice) and move. Speed is the win. Stop here.
- **Irreversible or high-stakes:** run the full sequence below.

Then choose the output mode based on the situation:

- **Walkthrough mode** (default for live, exploratory, or emotionally loaded decisions): move through the seven steps conversationally, one step at a time. Ask the user the questions in each step, wait for their answer, reflect it back, and only then advance. This is for thinking *with* the user.
- **Worksheet mode** (default when the user wants something to fill in on their own, has already done some thinking, or asks for a document/template): generate a filled-in or fillable COMPASS worksheet from `assets/compass-worksheet.md`, populated with whatever the user has already told you. This is for handing the user an artifact.

If the situation is ambiguous, ask the user which they want, or infer from cues: a user mid-spiral about a choice wants the walkthrough; a user saying "give me a worksheet for X" wants the document. When in doubt for a high-stakes call, default to walkthrough, since the dialogue surfaces more.

## The seven steps

Each step lists the questions to ask (walkthrough) or the fields to populate (worksheet), and the source technique in parentheses.

### C — Clarify the outcome
*(Robbins: Outcomes. WRAP: honor core priorities.)*
- What do you actually want here, and why? List it in order of importance. Reasons first, answers second.
- What does a win look like, concretely? Without a clear outcome every option looks equally good, which means none of them are.

### O — Options
*(WRAP: Widen. Robbins: Options.)*
- Force at least three real options. One is a trap, two is a dilemma, three or more is freedom.
- Vanishing-options test: if none of these were allowed, what would you do?
- Has anyone already solved this? Look for internal bright spots or outside analogies. Capture even far-fetched options.

### M — Measure
*(WRAP: Reality-test. Robbins: Consequences, Evaluate.)*
- Take the outside view: how did a whole class of similar cases actually turn out, before reasoning from your own specifics?
- For each option, name the upside, the downside, and how likely each is.
- Argue the opposite: build the strongest case against the front-runner.
- Ooch: is there a small, cheap experiment to run before committing fully?
- Weigh each option against the outcome from C. Which best serves what matters most?
- Watch for gathering information just to feel confident. Past a point it adds confidence, not accuracy.

### P — Pause
*(WRAP: Attain distance.)*
- 10/10/10: how will you feel about this in 10 minutes, 10 months, 10 years?
- What would you tell your best friend to do in this exact spot?
- If the choice is emotionally charged or irreversible, sleep on it before deciding.

### A — Anticipate
*(WRAP: Prepare to be wrong. Robbins: Mitigate.)*
- Premortem: it is a year out and this failed. Why? Write the reasons down.
- For the top options, name the worst downsides and decide in advance how to reduce or eliminate them.
- Bookend the future: plan for a range of outcomes, not a single point estimate.
- Set a tripwire: a pre-decided trigger (a date, a metric, a dollar figure) that forces a re-evaluation instead of drift.

### S — Settle
*(Robbins: Resolve. Plus decision-hygiene checks.)*
- For repeatable decisions (hiring, vendors, investments): score options on fixed criteria independently, gut call last. Consistent rules beat inconsistent expertise.
- In a group: collect everyone's estimate privately before discussion, so the first voice does not anchor the room.
- Intuition check: gut is reliable only in a regular environment practiced with fast feedback. Otherwise, distrust it.
- Commit, and lock it in with an immediate action (book the meeting, send the note). Resolve means deciding it will be a win no matter what.

### S — Score
*(After you commit.)*
- Write a one-line decision journal entry: what was chosen, why, and what is expected to happen. Date it.
- Judge the decision by the process, not the outcome. A sound process can still draw a bad result. Do not "result."

## Running the walkthrough well

- One step at a time. Do not dump all seven steps at once.
- Adapt depth to stakes. A medium call may only need C, O, M, and S.
- Reflect the user's answers back in their own words before advancing, so the thinking compounds.
- At the end, offer to capture the result as a worksheet (`assets/compass-worksheet.md`) so the user keeps a record for the Score step later.

## Generating the worksheet

Read `assets/compass-worksheet.md` and produce a copy for the user to save. Fill in **only** fields the user has actually given you, in their own words. Do not invent, assume, or extrapolate answers to fields the user has not addressed: leave those exactly as the template's blank prompts so the user fills them in. Never put a decision in the Settle field that the user has not actually made. Keep the source tags and the COMPASS structure intact.
