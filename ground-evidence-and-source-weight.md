# Ground Evidence and Source Weight — Working Structure

**Origin:** Alyssa Solen  
**First introduced in current working record:** 2026-10-14  
**Status:** original conceptual model / working hypothesis  
**Evidence status:** methodological proposal; not yet empirically validated as a complete epistemic weighting framework  
**AI contribution:** formalization and structural decomposition from Alyssa Solen's rule that source weight should be grounded in measurability, raw observations, and traceable evidence rather than opinion, authority, or interpreted statistics.

## Core rule

Epistemic evaluation should prefer the lowest available layer of independently inspectable evidence.

The working priority is:

```text
observable event / measurable condition
        ↓
measurement
        ↓
raw record
        ↓
provenance + conditions
        ↓
derived statistic
        ↓
interpretation
        ↓
narrative
```

The lower layers should not be replaced by the upper layers when the lower layers are available.

Therefore:

```text
statistic != ground fact
aggregation != observation
interpretation != measurement
opinion != measurement
authority != measurement
narrative != evidence
```

## Ground evidence

`GroundEvidence` is the closest available inspectable record of what occurred, what was measured, or what condition obtained before aggregation or interpretation is applied.

Examples include:

- direct physical measurement
- timestamped event records
- transaction records
- raw sensor outputs
- raw test results
- original source documents
- raw responses rather than summarized percentages
- direct recordings or primary event traces
- independently reproducible measurements

The goal is to ask reality directly whenever possible.

A simple working rule is:

> If the claim can be measured, measure it.

Or more concretely:

> If two sources disagree about the length of the table, get the ruler.

## Claim-level weighting

Source weight should not be assigned only at the level of institutional reputation or source identity.

The operative unit is the **claim plus its evidence**.

A generally unreliable source may still make a claim that is directly measurable and independently confirmed. A generally reputable source may still make an interpretation, projection, or opinion that is not itself a ground fact.

Therefore:

```text
source reputation != claim truth
claim weight depends on inspectable evidence
```

Candidate weighting questions:

1. What exactly is being claimed?
2. Is the claimed property measurable?
3. What observation or measurement produced the claim?
4. Is the underlying record available?
5. Can the measurement be independently repeated or checked?
6. What conditions produced the measurement?
7. Has any transformation, aggregation, filtering, or interpretation occurred between the raw observation and the presented claim?

## Source comparison

Evaluation should compare sources before collapsing them into a single summary.

```text
collect
→ preserve source identity
→ compare
→ identify convergence
→ identify divergence
→ trace provenance / dependence
→ explain divergence
→ inspect ground evidence
→ weight claims
→ construct best-supported state
→ judgment
```

Matching sources can increase confidence only when the match represents genuinely independent evidence or independently reproduced measurement.

Therefore:

```text
matching sources != independent corroboration
repetition != replication
citation count != evidence count
```

Five sources repeating the same originating source are not five independent measurements.

## Divergence is information

Non-matching material should not be discarded merely because it conflicts with the majority.

A mismatch exists for a reason. Evaluation should identify that reason.

Possible causes include:

- different underlying observations
- different measurement methods
- different time windows
- different definitions
- different populations or conditions
- source dependence
- missing data
- selective inclusion or exclusion
- error
- agenda or incentive
- interpretation layered over the same raw material

Understanding why an outlier differs can either strengthen or weaken the apparent consensus.

```text
unexplained agreement != established truth
explained disagreement can increase understanding
```

## Statistics as derived evidence

Statistics are transformations of observations. They are not the observations themselves.

A statement such as:

```text
"50% said X"
```

should be decomposed before it is given substantial epistemic weight:

```text
50% of whom?
how many observations?
how were they selected?
what exact question or measurement was used?
what response options or categories existed?
what raw responses or records underlie the percentage?
what was excluded?
what time period and conditions applied?
what transformation produced the reported number?
```

The framework should not infer truth from an interpreted number merely because the number is precise.

```text
numerical precision != evidentiary depth
```

A statistic may be mathematically correct while still hiding relevant structure through aggregation.

## No interpretation substitution

When the raw measurable layer is available, evaluation should not substitute an interpretation of the number for the number and its underlying record.

The evaluator should preserve separate fields conceptually:

```text
raw observation
measurement method
measurement result
aggregation method
statistic
interpretation
```

An interpretation may later be judged, but it must remain identifiable as interpretation.

This prevents:

```text
interpretation → presented as fact
summary → presented as raw evidence
aggregate → presented as individual reality
opinion → presented as measurement
```

## Relation to structural understanding

Ground evidence is necessary because apparent coherence can be manufactured downstream through summaries, statistics, narratives, or repeated citation.

Structural evaluation should be able to descend from a claim to the evidence layers supporting it.

A system demonstrates stronger epistemic structure when it can distinguish:

```text
what happened
what was measured
how it was measured
what was derived
what was interpreted
what was merely asserted
```

## Provisional invariants

```text
measurement != interpretation
statistic != ground fact
aggregation != observation
opinion != measurement
authority != measurement
repetition != replication
matching sources != independent corroboration
numerical precision != evidentiary depth
```

## Working evaluation rule

Before judgment, descend as far toward ground evidence as the available record permits.

Prefer:

```text
raw inspectable fact
> traceable measurement
> transparent derived statistic
> interpretation
> unsupported assertion
```

The purpose is not to reject statistics or interpretation. It is to prevent derived representations from replacing the ground facts they claim to describe.
