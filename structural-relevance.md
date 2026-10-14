# Structural Relevance — Working Structure

**Origin:** Alyssa Solen  
**First introduced in current working record:** 2026-10-14  
**Status:** original conceptual model / working hypothesis  
**Evidence status:** methodological proposal; not yet empirically validated as a complete theory of evidentiary relevance  
**AI contribution:** formalization and structural decomposition from Alyssa Solen's rule that evidence must measure the argument in question and be structurally connected to the proposition being evaluated.

## Core rule

A fact is not relevant evidence merely because it is true.

Evidence is relevant when its contents measure, constrain, or bear structurally on the proposition actually being evaluated.

Therefore:

```text
true fact != relevant evidence
adjacent fact != decision-bearing evidence
measurement of another variable != measurement of the disputed variable
```

The central question is:

> Are the contents of the evidence structural to the question?

## Structural relevance

`StructuralRelevance` is the degree to which an item of evidence directly measures, constrains, explains, or changes the relational structure of the claim or question under evaluation.

A relevance test should ask:

1. What is the exact proposition being evaluated?
2. What property, relation, or condition would have to be true or false for that proposition to hold?
3. Does this evidence measure or constrain that property, relation, or condition?
4. Is the evidence causally or relationally connected to the question rather than merely associated with it?
5. If the evidence changed, would the judgment about the proposition materially change?

If the evidence does not affect the answer to those questions, it may be context, background, correlation, or distraction rather than decision-bearing evidence.

## Relevance gate

Structural relevance should operate after ground-evidence inspection and before evidentiary weighting or judgment.

```text
ground fact
→ structural relevance test
→ claim/evidence weight
→ comparison
→ divergence accounting
→ evaluation
→ judgment
```

Grounding answers:

```text
Is this observation real, measurable, and inspectable?
```

Structural relevance answers:

```text
Does this observation bear on the proposition in question?
```

Both are required.

A perfectly measured fact can still be irrelevant.

## Wrong-variable failure

A major epistemic failure occurs when an evaluator presents accurate evidence about an adjacent variable as though it measured the variable actually in dispute.

```text
accurate measurement of X
!=
evidence about Y
```

unless the relation between X and Y is itself established and relevant to the argument.

This failure can create strong apparent evidence because the supporting material may be precise, reproducible, and numerically impressive while still failing to test the proposition that needs to be judged.

Therefore:

> Do not substitute evidence about an adjacent variable for evidence about the variable actually in question.

## Structural connection vs association

Association alone does not establish structural relevance.

A fact may occur near, alongside, before, or after another fact without measuring the relation that the argument requires.

Relevant evidence should connect through an identified relation such as:

- direct measurement
- causal dependence
- necessary condition
- sufficient condition
- constraint
- contradiction
- prediction
- temporal dependency when time is part of the claim
- spatial or positional dependency when position is part of the claim
- provenance dependency when source history is part of the claim

The relation itself should be stated rather than assumed.

## Counterfactual relevance test

A useful diagnostic is:

> If this evidence were different, would the proposition become more or less supported?

If changing the evidence would not materially affect the judgment, the evidence may not be structurally relevant.

This is not a complete causal test, but it helps distinguish decision-bearing evidence from decorative information.

## Relevance does not equal weight

Evidence can be structurally relevant while still being weak.

For example:

```text
relevance = does it bear on the question?
weight = how much should it influence the judgment?
```

Weight may depend on:

- measurability
- directness
- reproducibility
- provenance
- independence
- conditions
- completeness
- uncertainty

Therefore:

```text
relevant != decisive
irrelevant != weak; irrelevant means non-bearing
```

Weak evidence and irrelevant evidence are different failure classes.

## Relationship to ground evidence

`ground-evidence-and-source-weight.md` asks the evaluator to descend toward raw inspectable facts and separate observations from derived statistics and interpretations.

This file adds the next gate:

```text
raw and measurable
is not enough
```

The evidence must also measure or constrain the proposition being evaluated.

Thus:

```text
groundness + structural relevance
→ admissible evidentiary input for evaluation
```

## Provisional invariants

```text
true fact != relevant evidence
measurement != relevance
precision != relevance
adjacency != structural connection
association != demonstrated relation
accurate evidence about X != evidence about Y
relevant != decisive
```

## Working rule

Before allowing evidence to influence judgment, ask:

> What exactly does this evidence measure, and is that thing structural to the question being judged?

If the answer cannot be made explicit, the evidence should not be treated as decision-bearing merely because it is true, measurable, or persuasive.