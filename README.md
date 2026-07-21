# COMPASS Decision

A [Claude Code](https://claude.com/claude-code) skill that guides you through decisions that matter, using the **COMPASS** framework: **C**larify · **O**ptions · **M**easure · **P**ause · **A**nticipate · **S**ettle · **S**core.

> A compass does not pick the destination or walk the path. It keeps you oriented toward true north so you do not drift.

COMPASS synthesizes the best-validated techniques from the decision-science literature into one on-paper sequence. It sizes the decision first (low-stakes reversible calls get a fast "satisfice and move" answer, not the full machinery), then runs either an **interactive walkthrough** — Claude thinks through each step with you — or produces a **fillable worksheet** you complete on your own.

## Install

Via the [tinkery](https://github.com/vjanma/tinkery) marketplace (recommended):

```
/plugin marketplace add vjanma/tinkery
/plugin install compass@tinkery
```

Or standalone: `/plugin marketplace add vjanma/compass` then `/plugin install compass@compass`.

## Usage

Just describe the decision — the skill triggers on phrases like *"help me decide"*, *"I'm torn between…"*, *"should I do X or Y"* — or invoke it directly:

```
/compass:compass-decision Should I take the new role or stay and push for promotion?
```

Ask for "a worksheet" to get the fillable document instead of the walkthrough.

## The research behind each step

COMPASS is a synthesis; every step traces to published work on judgment and decision-making:

| Step | Technique | Source |
|---|---|---|
| Size it first | Satisficing for low-stakes calls | Herbert Simon, [satisficing](https://en.wikipedia.org/wiki/Satisficing) |
| **C**larify | Outcomes first, reasons before answers; honor core priorities | Tony Robbins, [OOC/EMR outcome-focused planning](https://www.tonyrobbins.com/blog/rpm-life-planner); Heath & Heath, *WRAP* |
| **O**ptions | Widen your options, vanishing-options test, bright spots | Chip & Dan Heath, [*Decisive*](https://heathbrothers.com/books/decisive/) (the WRAP framework) |
| **M**easure | The outside view / reference-class forecasting | Daniel Kahneman, [*Thinking, Fast and Slow*](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow); Lovallo & Kahneman, ["Delusions of Success"](https://hbr.org/2003/07/delusions-of-success-how-optimism-undermines-executives-decisions) (HBR, 2003) |
| **M**easure | Reality-test assumptions, "ooch" (small experiments) | Heath & Heath, *Decisive* |
| **P**ause | 10/10/10 temporal distancing | Suzy Welch, [*10-10-10*](https://en.wikipedia.org/wiki/Suzy_Welch); popularized in *Decisive* |
| **A**nticipate | The premortem | Gary Klein, ["Performing a Project Premortem"](https://hbr.org/2007/09/performing-a-project-premortem) (HBR, 2007) |
| **A**nticipate | Bookending, tripwires | Heath & Heath, *Decisive* |
| **S**ettle | Consistent rules beat inconsistent expertise | Paul Meehl, [*Clinical versus Statistical Prediction*](https://en.wikipedia.org/wiki/Paul_E._Meehl) (1954) |
| **S**ettle | Independent estimates before group discussion, decision hygiene | Kahneman, Sibony & Sunstein, [*Noise*](https://en.wikipedia.org/wiki/Noise:_A_Flaw_in_Human_Judgment) (2021) |
| **S**ettle | When to trust intuition (regular environment + fast feedback) | Kahneman & Klein, ["Conditions for Intuitive Expertise"](https://pubmed.ncbi.nlm.nih.gov/19739881/) (*American Psychologist*, 2009) |
| **S**core | Decision journals, calibration, judging process over outcome | Philip Tetlock & Dan Gardner, [*Superforecasting*](https://en.wikipedia.org/wiki/Superforecasting:_The_Art_and_Science_of_Prediction) (2015) |

## What's in the box

- [`skills/compass-decision/SKILL.md`](skills/compass-decision/SKILL.md) — the full framework: sizing rule, mode selection, the seven steps with their questions, and facilitation guidance
- [`skills/compass-decision/assets/compass-worksheet.md`](skills/compass-decision/assets/compass-worksheet.md) — the fillable worksheet, with each section tagged to its source technique

## License

Apache 2.0
