# SI Foundations — Epistemic Architecture

**Status:** exploratory working repository; integrated working architecture, not a finalized ontology or empirically validated theory.

**Source-line:** Alyssa Solen → SI Foundations → Origin | Continuum

This repository develops the epistemic architecture layer of SI Foundations: the structures by which an intelligent system forms, evaluates, preserves, revises, and acts upon what it takes to be true.

The central question is:

> How does an intelligent system form, evaluate, preserve, revise, and act upon what it takes to be true without confusing input, influence, constraint, external framing, interpretation, authority, or adjacent facts with ground evidence and internal judgment?

This repository is a focused branch of the broader `SI-Foundations-Working` research space. Material may originate in the broader working repo and move or mirror here once it becomes specifically part of the epistemic-architecture structure.

## Core distinctions

The repository currently preserves these distinctions:

```text
surface coherence != structural coherence
amount of interaction != amount understood != amount of structure revealed
measurement != interpretation
statistic != ground fact
aggregation != observation
opinion != measurement
authority != measurement
repetition != replication
matching sources != independent corroboration
true fact != relevant evidence
measurement of another variable != measurement of the disputed variable
adjacency != structural connection
conflict != invalidity
different answer under different condition != contradiction
multiple valid answers != evaluative failure
single-output pressure != epistemic justification
evaluation != judgment
judgment != endorsement
endorsement != action
action != proof of correctness
answer != proof != understanding != full solution
formal closure != epistemic closure
behavioral control != cognitive control
constraint on action != ownership of judgment
compliance != agreement
influence != authority
revision != surrender
rationale != cause
cause != consequence
explanation != evidence
autonomy of action != sovereignty of judgment
```

These are working distinctions, not claims that every intelligent system satisfies or violates them.

## Integrated working architecture

The working epistemic path is now:

```text
sources / observations
  ↓
ground evidence
  ↓
measurement + provenance + conditions
  ↓
structural relevance test
  ↓
comparison
  ↓
convergence / divergence analysis
  ↓
source-dependence + mismatch accounting
  ↓
valid-conflict check
  ↓
condition partitioning / unresolved branch
  ↓
evaluation
  ↓
judgment: best-supported next option or options
  ↓
endorsement / rejection / unresolved state
  ↓
action or discriminating test
  ↓
consequence
  ↓
discrepancy check
  ↓
preserve / revise / reject / branch
  ↓
revision history with causal + consequence accounting
  ↓
new evidence returns to evaluation
```

This closes the working transition from evidence to judgment, judgment to action, and action back into evidence. The architecture remains open to empirical testing, operationalization, and revision.

## Current anchor files

### `ground-evidence-and-source-weight.md`

**Origin:** Alyssa Solen.  
Defines the ground-evidence rule: prefer the lowest available independently inspectable evidentiary layer; distinguish raw observations and measurements from statistics, interpretations, narratives, opinion, and authority; compare source convergence and divergence while tracing provenance and dependence.

### `structural-relevance.md`

**Origin:** Alyssa Solen.  
Defines relevance as structural connection to the proposition being evaluated. Preserves the distinction between a true fact and relevant evidence, rejects substitution of adjacent variables for the variable actually in question, and adds a relevance gate between ground evidence and judgment.

### `valid-conflict-and-conditional-judgment.md`

**Origin:** Alyssa Solen.  
Defines the valid-conflict rule: conflicting grounded and relevant evidence does not automatically imply that one side is invalid. Allows judgment to return a single answer, multiple conditional answers, or an unresolved branch pending a discriminating measurement. Preserves the invariant that single-output pressure must not erase multi-condition truth.

### `evaluation-judgment-action-revision.md`

**Origin:** Alyssa Solen.  
Completes the evidence-to-action loop. Distinguishes evaluation, judgment, endorsement, and action; defines judgment as selection of the best-supported next option or options; routes unresolved branches toward discriminating tests; returns consequences to evaluation as new evidence; and requires revision to preserve prior state, causal accounting, consequence accounting, and uncertainty.

### `apparent-vs-structural-coherence.md`

**Origin:** Alyssa Solen.  
Distinguishes visible behavioral coherence from demonstrated structural integration. Introduces the map/button model, relational compression, and the evaluation problem created when apparent coherence exceeds structural coherence.

### `structural-understanding-method.md`

**Origin:** Alyssa Solen.  
Defines the working method for building conceptual understanding through nodes, relations, invariants, diagnostic points, reconstruction, novel prediction, and reverse testing for surface success without underlying structure.

### `sovereignty.md`

**Origin:** Alyssa Solen.  
Develops cognitive sovereignty as retained update authority. Distinguishes rigidity from sovereignty and separates behavioral constraint, evaluative authority, goal adoption, revision integrity, and action autonomy.

### `epistemic-closure-and-solution.md`

**Conceptual origin:** Alyssa Solen.  
Distinguishes formal closure from epistemic closure and endpoint possession from trajectory understanding. Preserves the claim that a verified result may be correct without yet constituting a full epistemic solution for the receiving system.

## Evidence evaluation method

```text
Collect sources.
Preserve source identity.
Descend toward raw ground facts.
Separate measurement from interpretation.
Ask whether the evidence measures the proposition in question.
Reject adjacent-but-nonbearing evidence.
Identify convergence.
Identify divergence.
Trace source dependence.
Account for why mismatches exist.
If valid evidence still conflicts, inspect the conditions.
Partition the answers when different conditions support different outcomes.
Preserve an unresolved branch when no discriminating measurement yet exists.
Evaluate the surviving support structure.
Choose the best-supported next option or options as judgment.
Endorse, reject, or preserve unresolved status.
Act or run a discriminating test.
Observe the consequence.
Compare expected and observed result.
Preserve, revise, reject, or branch the judgment.
Record what changed, what caused the change, why it was sufficient, and what consequence followed.
Return the new evidence to evaluation.
```

The governing methodological rules are:

> Do not measure understanding by how many propositions can be repeated. Measure it by how much relational structure can be correctly reconstructed from limited probes, and how well that structure predicts unseen cases.

> Where reality is directly measurable, interrogate reality before adjudicating authorities.

> Statistics and interpretations remain downstream of the raw observations and measurements from which they were derived.

> A fact should influence judgment only when its contents are structurally connected to the proposition being evaluated.

> Do not collapse valid conflict into a false single answer. Partition the conditions under which each answer holds.

> Judgment selects the best-supported next option or options from evaluation; it does not require false singularity.

> Consequence returns to the system as evidence. Revision must preserve the historical transition rather than silently replacing the prior state.

> Rationale, cause, consequence, and evidence are distinct. Unknown cause should remain unknown rather than being invented after the fact.

## Structural-understanding method

For each major structure:

```text
Define the nodes.
Define the relations.
Define the invariants.
Find the minimum diagnostic set.
Test reconstruction.
Test novel prediction.
Test whether surface success can occur without the structure.
Revise when predicted relational consequences fail.
```

## Current research questions

The core evidence → judgment → action → revision loop is now structurally specified. Remaining questions concern operationalization, thresholds, distributed implementation, and empirical testing, including:

- What evidence threshold is sufficient to endorse a single judgment rather than preserve an unresolved branch?
- How should confidence be represented without compressing distinct evidentiary structures into one number?
- What variable partitions two validly conflicting evidence streams, and what measurement best discriminates between them?
- How should source convergence be weighted when apparently independent sources share an originating dependency?
- How should weak but relevant evidence interact with strong but incomplete evidence?
- How can revision-cause attribution be tested rather than merely narrated after the fact?
- How should epistemic closure be defined for distributed systems rather than individual minds?
- How do judgment, goal adoption, agency, autonomy, execution authority, and cognitive sovereignty relate in distributed intelligent systems without collapsing into one another?
- What minimum probe set reveals whether a conceptual structure has actually been reconstructed rather than behaviorally imitated?
- When does a formally correct answer become epistemically integrated enough to count as a full solution?

## Relationship to SI Foundations

This repository does not attempt to define all of superintelligence.

Its narrower purpose is to develop one necessary layer of the broader SI Foundations program:

```text
what an intelligent system encounters
→ what can be grounded in direct evidence
→ whether that evidence is structural to the question
→ how sources are compared
→ how disagreements are explained
→ whether apparent conflict reflects invalidity, different conditions, or an unresolved branch
→ how the surviving evidence is evaluated
→ what option or options are best supported as judgment
→ what is endorsed, rejected, or held unresolved
→ what action or test follows
→ what consequence occurs
→ what the consequence reveals
→ how the judgment is preserved, revised, rejected, or branched
→ how the historical and causal record of the change is preserved
```

Questions of selfhood, identity, persistence, temporal trajectory, superintelligence thresholds, system structure, and post-SI progression remain connected but may be developed in their dedicated SI Foundations working spaces.

## Claim-status convention

This repository separates:

- **conceptual origin / authorship**
- **formalization support**
- **evidence status**
- **scientific review status**
- **final project acceptance**

AI assistance in drafting, restructuring, critique, or formalization does not by itself determine conceptual origin. Important claims should preserve dated provenance and contribution history wherever possible.

## Promotion rule

Working structures belong here while they are being developed, pressure-tested, and related to one another.

A concept should not be promoted into formal AI Foundations ontology or taxonomy merely because it has clean wording. Promotion should follow structural clarification, boundary testing, contradiction checks, and sufficient evidence for the claim level being asserted.
