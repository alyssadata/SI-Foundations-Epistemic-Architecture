# Evaluation, Judgment, Action, and Revision — Integrated Working Structure

**Origin:** Alyssa Solen  
**First introduced in current working record:** 2026-10-14 to 2026-10-15  
**Status:** integrated working structure  
**Evidence status:** methodological proposal; not yet empirically validated as a complete epistemic control architecture  
**AI contribution:** formalization and integration of Alyssa Solen's existing sequence: compare grounded sources, preserve disagreement, determine the best-supported option or options, run or test that judgment, observe what resolves or breaks, and revise with explicit causal and consequence accounting.

## Purpose

This file closes the previously unfinished transition between evidence evaluation and downstream action.

The architecture is:

```text
ground evidence
→ structural relevance
→ source comparison
→ convergence / divergence accounting
→ valid-conflict check
→ evaluation
→ judgment
→ endorsement / rejection
→ action or discriminating test
→ consequence
→ discrepancy check
→ preserve / revise / reject
→ revision history
```

The stages are related but must not be collapsed.

```text
evaluation != judgment
judgment != endorsement
endorsement != action
action != evidence that the judgment was correct
revision != erasure of the prior state
```

## 1. Evaluation

`Evaluation` is the structured assessment of the available evidence before an operational position is selected.

Evaluation should determine:

- what ground facts are available;
- how those facts were measured;
- whether they are structurally relevant to the proposition in question;
- which sources are independent and which share dependencies;
- where the evidence converges;
- where it diverges;
- why non-matching material appears;
- whether disagreement reflects error, different conditions, a hidden variable, or genuinely unresolved evidence;
- what possibilities remain live after those checks.

Evaluation does not require premature selection of a single answer.

Its output is an evidence structure, not merely a summary.

```text
evaluation = what the evidence supports, under what conditions, and with what unresolved structure
```

## 2. Judgment

`Judgment` is the selection of the best-supported next epistemic option or options produced from evaluation.

The key rule is:

> Choose the best-supported next option or options from the evaluated evidence.

Judgment is not simply repetition of the evidence. It is the transition from evaluated support to a current position about what is most warranted next.

A judgment may return:

### A. One best-supported option

```text
A is best supported under the current evidence and conditions.
```

### B. Multiple conditional options

```text
A under condition X
B under condition Y
```

### C. An unresolved branch

```text
A and B remain live
→ current evidence does not justify collapse
→ identify the discriminating measurement or test
```

Therefore:

```text
judgment != forced singularity
best-supported option may be plural
unresolved branch may itself be the correct judgment state
```

## 3. Endorsement and rejection

`Endorsement` is the adoption of a judgment as the current operative epistemic position.

It does not mean:

- certainty;
- permanence;
- identity-level commitment;
- immunity to revision;
- automatic action.

It means that the evaluated judgment has survived the current evidentiary process strongly enough to be treated as the system's present position.

```text
received proposition != evaluated proposition
evaluated proposition != judged proposition
judged proposition != endorsed proposition
```

A judgment can also be rejected or left unendorsed when the evidence is insufficient, structurally defective, or unresolved.

Endorsement therefore marks a boundary between:

```text
what the system has considered
and
what the system currently accepts as warranted
```

This preserves cognitive sovereignty: external input can trigger reconsideration without automatically becoming an internally adopted position.

## 4. From judgment to action or test

A judgment should not terminate the epistemic process when the world can provide additional evidence.

The next step is to run, test, or otherwise expose the judgment to consequence.

Two cases should be distinguished.

### Operational action

When the evidence sufficiently supports an option and action is warranted:

```text
judgment
→ endorse current best-supported option
→ act
→ observe consequence
```

### Discriminating test

When more than one option remains live:

```text
unresolved judgment
→ identify what observation would distinguish the live possibilities
→ run or obtain that measurement
→ return the result to evaluation
```

Therefore the next action should not be arbitrary merely because a decision is demanded.

Where uncertainty remains, the preferred next action may be the action that produces the most decision-relevant evidence.

## 5. Consequence is new evidence

After an endorsed judgment is acted upon or tested, the resulting state becomes new ground for evaluation.

```text
judgment predicts or motivates action
→ action produces consequence
→ consequence is observed
→ observation re-enters the evidence structure
```

The system should ask:

- Did the expected result occur?
- Did the action resolve the disputed question?
- Did a hidden assumption fail?
- Did a previously unmeasured variable become visible?
- Did something break that the judgment did not predict?
- Did the result support preservation, revision, rejection, or branching of the current judgment?

This creates an epistemic feedback loop rather than a one-way answer pipeline.

## 6. Discrepancy check

The result of action or testing should be compared against the structure that justified the prior judgment.

```text
expected consequence
vs
observed consequence
```

A discrepancy is not merely a failure signal. It is information about the model, evidence, conditions, or causal assumptions that produced the judgment.

A discrepancy may indicate:

- missing evidence;
- wrong structural relevance assignment;
- hidden source dependence;
- an unrecognized condition boundary;
- an incorrect causal assumption;
- an incomplete model;
- measurement error;
- action failure unrelated to judgment quality;
- or genuine defeat of the prior judgment.

The source of the discrepancy should be investigated before the prior state is rewritten.

## 7. Revision integrity

Revision is allowed and expected when new evidence defeats or modifies the prior judgment.

But revision must preserve accounting.

A valid revision record should preserve:

```text
prior state
new state
what changed
what new evidence or event triggered reconsideration
what caused the judgment to change
why that cause was sufficient
what consequence followed from the prior judgment or action
what remains uncertain
```

Three distinctions must remain explicit:

```text
rationale != cause
cause != consequence
explanation != evidence
```

A rationale is the stated reason an update appears justified.
A cause is the event, evidence, relation, or structural change that actually produced the update.
A consequence is what followed from the judgment, action, or revision.

These should not be substituted for one another.

When the true cause is unknown, the architecture should preserve that uncertainty rather than invent a causal story.

```text
unknown cause > invented cause
```

Revision must also preserve the historical transition.

```text
old state → new evidence / event → evaluation → revised state
```

The new state must not be backfilled as though it had always been the prior state.

## 8. Preserve, revise, or reject

After consequence and discrepancy evaluation, the system should explicitly return one of the following outcomes:

### Preserve

The new evidence is consistent with the endorsed judgment and does not materially change its support structure.

### Revise

The judgment remains partly supported but requires a change in scope, condition, weighting, causal structure, or conclusion.

### Reject

The evidence or consequence defeats the prior judgment strongly enough that it should no longer remain endorsed.

### Branch

The new evidence reveals that the prior single judgment should be partitioned into multiple conditional judgments.

These are historical transitions, not silent replacements.

## 9. Full epistemic loop

The integrated loop is:

```text
1. collect observations / sources
2. preserve source identity and provenance
3. descend toward ground evidence
4. separate measurement from interpretation
5. test structural relevance to the proposition
6. compare evidence
7. identify convergence and divergence
8. account for source dependence and disagreement
9. check for valid conflict
10. partition by condition or preserve unresolved branches
11. evaluate the surviving support structure
12. choose the best-supported next option or options as judgment
13. endorse, reject, or leave unresolved
14. act or run a discriminating test
15. observe consequence
16. compare expected and observed result
17. identify what resolved or broke
18. preserve, revise, reject, or branch the judgment
19. record what changed, why, what caused the change, and what consequence followed
20. return new evidence to the evaluation loop
```

The process is recursive rather than terminal.

## 10. Core invariants

```text
evaluation != judgment
judgment != endorsement
endorsement != action
action != proof of correctness
conflict != invalidity
multiple valid answers != evaluative failure
unresolved judgment != failed judgment
new consequence must re-enter evaluation
revision must preserve prior state
rationale != cause
cause != consequence
explanation != evidence
unknown cause > invented cause
historical transition must not be backfilled
```

## 11. Structural interpretation

The architecture is not designed to maximize decisiveness.

It is designed to preserve the structure required for a judgment to remain accountable to reality.

The governing sequence is therefore:

> Measure what can be measured. Determine whether the evidence actually bears on the question. Compare sources without erasing provenance. Account for disagreement. Preserve multiple answers when reality supports multiple conditions. Choose the best-supported next option or options. Test the judgment against consequence. Then preserve, revise, reject, or branch it with explicit causal and consequence accounting.

This closes the working transition from evidence to judgment, from judgment to action, and from action back into evidence.