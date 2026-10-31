# Research Methodology Reference — ThinkThanks

---

## Literature Review Types

| Type | Purpose | Scope | Rigor | Use when |
|------|---------|-------|-------|----------|
| **Narrative Review** | Synthesize and discuss a topic | Selective, not exhaustive | Low-Medium | Broad introduction; expert-guided synthesis |
| **Scoping Review** | Map the extent of literature on a topic | Broad, exhaustive attempt | Medium | Understanding what research exists before systematic review |
| **Systematic Review** | Answer a specific question via exhaustive, reproducible search | Exhaustive, protocol-driven | High | Clinical/policy decisions requiring comprehensive evidence |
| **Meta-Analysis** | Statistically combine results across studies | Defined by inclusion criteria | High | Quantitative synthesis of effect sizes across studies |
| **Rapid Review** | Accelerated systematic review with defined shortcuts | Bounded; documented compromises | Medium | Time-constrained decisions; policy rapid response |

**Do not:** Call a review "systematic" unless it follows a documented protocol with explicit inclusion/exclusion criteria, reproducible search strategy, and transparent bias assessment.

---

## Systematic Review Protocol (PRISMA-aligned)

A systematic review is only systematic if these steps are documented and reproducible:

```
Step 01  REGISTRATION        Register protocol before search (PROSPERO or equivalent if applicable)
Step 02  QUESTION            Define using PICO or equivalent framework (Population, Intervention, Comparator, Outcome)
Step 03  ELIGIBILITY         Write explicit inclusion and exclusion criteria before searching
Step 04  DATABASES           List all databases to be searched (PubMed, Scopus, Web of Science, etc.)
Step 05  SEARCH DATE         Record exact search dates for each database
Step 06  FULL QUERY          Document complete search queries for each database, including syntax
Step 07  DEDUPLICATION       Remove duplicates before screening; document removal count
Step 08  TITLE/ABSTRACT      Screen all results against eligibility criteria; two reviewers if high-stakes
Step 09  FULL TEXT           Retrieve and screen full text of remaining articles
Step 10  EXCLUSION REASONS   Document reason for each full-text exclusion
Step 11  RISK OF BIAS        Assess each included study using validated tool (Cochrane RoB, ROBINS-I, etc.)
Step 12  DATA EXTRACTION     Extract data using pre-defined form; double-check key variables
Step 13  SYNTHESIS           Narrative or quantitative synthesis; address heterogeneity
Step 14  PUBLICATION BIAS    Assess if applicable (funnel plot, Egger's test, or narrative assessment)
Step 15  REPORT              Follow PRISMA reporting guidelines; include PRISMA flow diagram
```

**If steps are missing or access-limited:** Describe the actual process used and its deviation from full systematic review protocol. Do not claim systematic review if the protocol was not followed.

---

## Quantitative Research Checklist

Evaluate every quantitative study on these 15 dimensions:

```
01  Variable definitions     Are independent and dependent variables precisely defined?
02  Sample size              Is the sample large enough to detect the claimed effect?
03  Sampling technique       Is the sample drawn to represent the target population?
04  Randomization            Is treatment assignment random (for experiments)?
05  Missing data             How is missingness handled? Is missing-not-at-random ruled out?
06  Outlier handling         Are outliers documented and justified, not silently removed?
07  Confounding              Are confounders identified and controlled or adjusted for?
08  Effect size              What is the magnitude of the effect (not just p-value)?
09  Confidence interval      What is the precision of the estimate?
10  Statistical significance  p < 0.05 is a threshold, not proof of importance
11  Practical significance    Is the effect large enough to matter in practice?
12  Multiple comparisons      Are false discovery rate adjustments applied where needed?
13  Model assumptions         Are regression assumptions checked and reported?
14  Reproducibility           Is code, data, and analysis pipeline available?
15  Pre-registration          Was the analysis plan registered before data collection?
```

**Key distinction:** Statistical significance ≠ practical significance. An effect can be statistically significant (large sample, tiny effect) and practically irrelevant. Always report effect sizes and confidence intervals, not just p-values.

**Key distinction:** Non-significant result ≠ no effect. Absence of evidence is not evidence of absence, especially in underpowered studies.

---

## Qualitative Research Checklist

Evaluate qualitative studies on these 12 dimensions:

```
01  Research design       Is the design (grounded theory, phenomenology, ethnography, etc.) appropriate for the question?
02  Sampling strategy     Is purposive/theoretical sampling justified? Is saturation addressed?
03  Participant context   Who are participants? What is their relationship to the phenomenon?
04  Data collection       Are interviews, observations, or documents described in sufficient detail?
05  Coding process        Is the coding approach described? Inductive vs. deductive?
06  Reflexivity           Does the researcher acknowledge their positionality and potential influence?
07  Saturation            Is data saturation claimed? If so, how was it determined?
08  Negative cases        Were contradictory or disconfirming cases sought and addressed?
09  Triangulation         Are multiple data sources, methods, or investigators used?
10  Member checking       Were findings validated with participants where appropriate?
11  Audit trail           Is the research process documented so others could follow the logic?
12  Transferability       Are the limits of applying findings to other contexts stated?
```

**Do not:** Treat qualitative findings as universally generalizable. Individual experiences are not population statistics. Quote participants only to illustrate themes, not as evidence of prevalence.

---

## Experimental and Technical Research

For evaluations of technology, AI models, algorithms, software, or systems:

```
BASELINE            What is the comparison point? Is it a reasonable baseline?
EXPERIMENTAL SETUP  How was the experiment configured? What parameters were used?
DATASET             What data was used? Is it appropriate for the evaluation?
DATA SPLITS         How was train/validation/test split? Is contamination ruled out?
HARDWARE            What hardware was used? (Affects timing/performance claims)
SOFTWARE VERSIONS   What specific library and tool versions were used?
HYPERPARAMETERS     What hyperparameters were used? Were they tuned on test data?
EVALUATION METRICS  Are metrics appropriate for the claimed use case?
REPEATED TRIALS     Were experiments run multiple times? Variance reported?
FAILURE MODES       Were edge cases and failure conditions tested?
REPRODUCIBILITY     Is code and data sufficient to reproduce results?
LIMITATIONS         What conditions does this evaluation not cover?
```

**Do not:** Claim a system is best without specifying: best on what metric, on what dataset, under what conditions, compared to which baselines, as of what date.

**Do not:** Accept benchmark claims at face value without checking for data leakage, cherry-picked benchmarks, or benchmark saturation.

---

## OSINT & Investigative Research Rules

### Permitted
- Public records (court filings, company registrations, regulatory filings)
- Government databases and open data portals
- Published news articles and investigative reports
- Academic and think-tank publications
- Official organizational websites and publications
- Social media content published publicly by the subject
- Patent databases, trademark records
- Web archives (Wayback Machine) for historical public content
- Geospatial data from public satellite or mapping services

### Not Permitted
- Accessing accounts or systems requiring authentication without authorization
- Bypassing access controls (paywalls, login walls) through technical means
- Social engineering to obtain information
- Aggregating personal information beyond what is necessary for the research purpose
- Inferring private information from public information in ways the subject would not expect
- Doxxing: publishing private location, contact, or personal information
- Identifying individuals from anonymized datasets when re-identification was not the legitimate research purpose

### For individual subjects
- Apply strict data minimization: collect only what is necessary for the stated research purpose
- Do not include home addresses, personal phone numbers, or health information unless directly relevant and properly sourced
- Apply the test: "Is inclusion of this information necessary, proportionate, and appropriate?"
- Consider potential harm of publication, even of technically public information

---

## Hypothesis Decomposition Framework

Use for any question involving causality, effectiveness, or comparison:

```
HYPOTHESIS     : [Specific claim being tested]
DEFINITION     : [Precise meaning of each key term]
POPULATION     : [Who/what does this apply to?]
METRICS        : [How is the outcome measured?]
COMPARISON     : [Compared to what?]
CONDITIONS     : [Under what conditions?]
TIMEFRAME      : [When?]
PREDICTED SIGN : [Direction of expected effect?]
EFFECT SIZE    : [How large an effect would be meaningful?]
DISCRIMINATING : [What observation would confirm vs. refute?]
ALTERNATIVES   : [Other explanations for the same observations]
CONFOUNDERS    : [Factors that could produce a spurious relationship]
NULL           : [Statement of no effect]
```

---

## Alternative Hypothesis Formulation

For every causal or effectiveness claim, generate at minimum:

| Hypothesis | Description |
|-----------|-------------|
| H-primary | The main claim being investigated |
| H-alt-1 | Alternative explanation A (different cause, same effect) |
| H-alt-2 | Alternative explanation B (confounding variable) |
| H-null | No real effect; observations are noise or coincidence |
| H-boundary | Effect exists but only in limited conditions not meeting current context |

Document: "What evidence would distinguish H-primary from H-alt-1?" This discriminating evidence is the most important thing to search for.

---

## Stop Conditions Guide

Research is sufficiently complete when any of the following is true:

```
CONDITION 1  All key subquestions have evidence adequate for the decision risk level
             (High-stakes decision = higher evidence bar than exploratory inquiry)

CONDITION 2  Continued search returns only sources already reviewed or
             derivatives of already-reviewed sources

CONDITION 3  The evidence quality ceiling has been reached given available access
             (All accessible databases searched; paywalled sources documented)

CONDITION 4  The time or resource budget is exhausted
             → Document what remains open; report on what was completed

CONDITION 5  Available evidence is genuinely insufficient to conclude
             → Report this honestly; do not force a conclusion
             → This is a valid and important research outcome
```

**Do not:** Claim exhaustive search when access was limited. Do not claim "no evidence exists" when "no evidence was found in accessible sources" is the accurate statement.
