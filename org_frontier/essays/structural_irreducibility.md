# Structural Irreducibility: When Individual Competence Cannot Secure Collective Outcomes

**Author:** Antonio Scala  
**Status:** Working outline; claims and examples require development and review.  
**Type:** Conceptual essay

## Central claim

Improving each participant's ability to understand and use algorithmic systems does not, by itself, guarantee better collective outcomes. Some failures arise from the structure of interactions among participants, platforms, and institutions. These failures persist even when each participant acts competently according to the information and incentives available locally.

The proposed contribution to algorithmacy is therefore a distinction between **individual competence** and **collective conditions of effective agency**. Algorithmacy should help people interact with one another through algorithmic systems, rather than merely help individuals optimise their position within those systems.

## 1. The problem: competent agents, adverse outcomes

- Define a setting in which individual choices are reasonable given local information.
- Identify a collective outcome that remains undesirable despite competent local choices.
- Separate a coordination failure from individual ignorance, manipulation, or poor interface design.
- **Example to develop:** recommendation-mediated interactions in which each user selects useful content while the aggregate selection process reduces shared visibility or mutual understanding.

## 2. What makes a failure structurally irreducible?

**Working definition:** A failure is structurally irreducible relative to a specified class of individual-level interventions when improving the competence or behaviour of participants within that class cannot reliably remove the failure without changing the interaction rules, information structure, incentives, or governance.

This is a conditional claim, not an assertion that collective behaviour is inherently unpredictable or that individual actions never matter.

Questions to resolve:

- What interventions count as individual-level improvements?
- Which system-level properties must remain fixed for the claim to hold?
- How should irreducibility be distinguished from a difficult but solvable training problem?
- What observable result would refute a particular claim of irreducibility?

## 3. A minimal formal framework (to be developed)

Let $G=(V,E)$ describe the interaction structure, $x_i$ the state or action of participant $i$, and $F(x_1,\ldots,x_N;G,M)$ a collective outcome under mediation rules $M$.

Define a class $\mathcal{I}$ of permissible individual-level interventions and a desired outcome set $\mathcal{D}$. The proposed test asks whether there exists an intervention $I\in\mathcal{I}$ such that the resulting collective outcome enters $\mathcal{D}$ while $G$ and $M$ remain fixed.

**Open task:** Specify the dynamics, admissible interventions, and decision criterion before making any theorem-like claim. The notation alone establishes no result.

## 4. Candidate mechanisms

### 4.1 Externalities and feedback

Locally beneficial actions may change the environment faced by others, producing feedback that individual competence cannot neutralise.

### 4.2 Selection and visibility

An intermediary may shape which people, claims, and opportunities become mutually visible. Better use of the interface does not necessarily change the distribution of visibility.

### 4.3 Coordination and incompatible local information

Participants may hold locally coherent views that do not support a consistent collective decision or shared account of the situation.

### 4.4 Asymmetric authority and contestability

Even capable participants may lack access to decision records, effective appeals, or the authority needed to change mediation rules.

## 5. Relation to algorithmacy

- **Individual layer:** understanding algorithmic mediation and acting competently within it.
- **Relational layer:** enabling people to coordinate, exchange reasons, and sustain meaningful interaction.
- **Institutional layer:** making the rules and consequences of mediation observable, contestable, and revisable.

The thesis to test is that the relational and institutional layers cannot always be replaced by more individual training.

## 6. Examples and possible tests

1. **Recommendation systems:** compare individual relevance gains with collective coverage and exposure distributions.
2. **Multi-agent decisions:** test whether locally reasonable policies produce globally harmful equilibria.
3. **Platform-mediated groups:** distinguish an increase in individual engagement from the survival and value of relationships among participants.

For each case, identify the model, baseline, individual intervention, structural intervention, outcome metric, and possible falsifier. Any reported numerical result must link to a reproducible script committed to this repository.

## 7. Objections and boundaries

- Some apparent structural failures may disappear after sufficiently effective individual learning.
- Collective objectives may be contested; an outcome cannot be labelled a failure without a declared criterion.
- Changing incentives may count as an individual intervention under some definitions.
- In-silico results on small models do not establish empirical claims about organisations or societies.

## 8. Implications for design and governance

Develop criteria for when algorithmacy programmes should move beyond literacy or interface skills to require shared evidence, coordination mechanisms, published decision boundaries, and procedures for contesting outcomes.

## 9. Research tasks

- [ ] Establish the relationship to existing algorithmacy claims in this repository.
- [ ] Review relevant literature on externalities, coordination, network effects, and collective agency.
- [ ] Select one precise model and state a falsifiable proposition.
- [ ] Identify a counterexample or limiting case.
- [ ] Decide whether the essay needs an accompanying reproducible experiment.
- [ ] Add verified references and distinguish conceptual claims from empirical findings.
- [ ] Revise into a complete essay following the repository's prose conventions.

---

*This file is a skeleton, not a completed paper. It reports no empirical results and makes no claim that structural irreducibility has been demonstrated.*
