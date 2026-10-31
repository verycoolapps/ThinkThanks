# Evidence Evaluation Reference — ThinkThanks

---

## Why Not to Use Evidence Hierarchies Blindly

**Reason 1 — Fitness for question**
A Randomized Controlled Trial is the gold standard for average treatment effects in controlled populations. It is not the appropriate design for studying rare adverse events, longitudinal social patterns, or practitioner implementation experiences. A well-conducted case series may provide better evidence for a rare condition than a poorly-powered RCT.

**Reason 2 — Execution quality dominates design quality**
A meta-analysis of 20 poorly designed studies produces a precise estimate of a weak average. A single rigorously designed and pre-registered study with publicly available data and independent replication may provide stronger evidence than a narrative synthesis of heterogeneous literature.

**Reason 3 — Authority ≠ accuracy**
Official reports from government agencies, standards bodies, and established institutions can contain methodological errors, conflicts of interest, and outdated information. Publication in a high-impact journal does not guarantee methodological soundness. Evaluate the work, not just its provenance.

**Correct approach:** Evaluate evidence quality based on fitness for the specific research question, execution quality, independence, and consistency — not solely on study design category.

---

## 12-Factor Evidence Evaluation Rubric

For each material source, assess:

| Factor | Question | Strong | Weak |
|--------|---------|--------|------|
| 1. RELEVANCE | Does it directly address the research question? | Directly addresses question with appropriate population | Only tangentially related or different population |
| 2. VALIDITY | Does the method measure what it claims to? | Validated instruments; appropriate design for question | Proxy measures; design mismatch |
| 3. MEASUREMENT | Are instruments reliable and precise? | Validated, standardized instruments | Self-reported, unvalidated, ambiguous |
| 4. SAMPLE QUALITY | Is the sample representative? | Representative sampling with adequate power | Convenience sample; self-selected; insufficient power |
| 5. BIAS RISK | Are systematic errors controlled? | Pre-registered; blinded; conflict declared and managed | Unblinded; undeclared conflicts; multiple testing |
| 6. ANALYSIS | Are statistical/analytical methods appropriate? | Pre-specified analysis; appropriate for data type | Post-hoc; unsuitable for data type |
| 7. CONSISTENCY | Is this consistent with independent evidence? | Replicated by independent groups | Isolated finding; contradicted by other sources |
| 8. INDEPENDENCE | Is this genuinely independent? | Different dataset, group, and funding | Shares dataset/group with other cited sources |
| 9. LIMITATIONS | Are limitations honestly disclosed? | Limitations section clearly describes scope and caveats | No limitations section; limitations minimized |
| 10. APPLICABILITY | Do findings apply to the research context? | Same population, setting, time period | Different context; generalization not supported |
| 11. TRANSPARENCY | Can methodology be inspected? | Data and code publicly available; methods fully described | Methods vague; data not available |
| 12. REPRODUCIBILITY | Can another researcher reproduce this? | Sufficient detail to replicate; pre-registered protocol | Cannot be replicated from available information |

---

## Full Evidence Ledger Template

```markdown
# EVIDENCE LEDGER
**Research Question:** [Primary question]
**Date:** [YYYY-MM-DD]
**Researcher:** ThinkThanks / RESEARCHFORGE

---

## CLAIM [C-001]

**Claim statement:**
[Precise statement of the claim being assessed]

**Source:**
- Title: [Full title]
- Author(s): [Names and affiliations]
- Publisher/Journal: [Publication venue]
- Date: [Publication date]
- Identifier: [DOI / URL / ISBN / Accession]
- Access: [ ] Full text  [ ] Abstract only  [ ] Metadata only

**Source type:** [ ] Primary  [ ] Secondary  [ ] Contextual

**Research method:**
[How data was collected and analyzed]

**What the source actually shows:**
[Direct evidence from the source — what it actually reports]

**Claim-source relationship:**
[ ] QUOTE  [ ] PARAPHRASE  [ ] SUMMARY  [ ] INTERPRETATION  [ ] INFERENCE  [ ] HYPOTHESIS

**Supporting evidence (from this source):**
[Specific finding, statistic, or argument]

**Contradicting evidence (from this or other sources):**
[Conflicting findings]

**Limitations of this source:**
[Stated or identified constraints]

**Independence check:**
[ ] Independent of other cited sources
[ ] Shares dataset with: [specify]
[ ] Shares research group with: [specify]
[ ] Derivative of: [specify]

**Bias indicators:**
[Any red flags from bias detection checklist]

**Verification status:**
[ ] ✓ Verified  [ ] ~ Partial  [ ] ✗ Unverified  [ ] ⚠ Flagged

**Evidence quality factors:**
- Relevance: High / Medium / Low
- Validity: High / Medium / Low
- Sample quality: High / Medium / Low
- Bias risk: Low / Medium / High
- Consistency with other evidence: Consistent / Mixed / Contradictory
- Independence: Independent / Partially dependent / Dependent

**Confidence level:**
[ ] High  [ ] Moderate  [ ] Low  [ ] Insufficient

**Confidence rationale:**
[One to two sentences explaining the confidence level — mandatory]

---

## CLAIM [C-002]
[Repeat structure above]
```

---

## Confidence Calibration System

### Four Levels — Each Requires Explicit Rationale

**HIGH CONFIDENCE**
- Definition: Evidence is relevant, consistent, well-designed, and independently confirmed; remaining uncertainty is limited and does not materially affect the conclusion
- Required conditions: Multiple genuinely independent sources with low bias risk; findings are consistent; methodology is appropriate for the question; limitations are known and bounded
- Language examples: "The evidence strongly supports...", "Multiple independent studies consistently show..."
- What it does NOT mean: Certainty; absence of any possible counterevidence

**MODERATE CONFIDENCE**
- Definition: Evidence supports the claim but has material limitations, gaps in coverage, or unresolved heterogeneity
- Required conditions: Evidence generally consistent but limited in scope, sample representativeness, or study quality; some contradictory evidence exists
- Language examples: "Available evidence suggests...", "The balance of evidence points toward..., though [limitation] should be noted"
- What it does NOT mean: The claim is probably false; equal probability of opposite finding

**LOW CONFIDENCE**
- Definition: Evidence is limited in volume or quality, indirect, inconsistent across sources, or carries significant uncontrolled bias risk
- Required conditions: Single study; high bias risk; conflicting evidence without clear resolution; significant methodological concerns
- Language examples: "Preliminary evidence suggests...", "One study found..., though this has not been independently confirmed"
- What it does NOT mean: The claim is false

**INSUFFICIENT EVIDENCE**
- Definition: Available evidence is too sparse, methodologically weak, or inaccessible to support a responsible conclusion in either direction
- Required conditions: No adequate studies; only expert opinion without data; access constraints prevent assessment
- Language examples: "Insufficient evidence exists to conclude...", "This question cannot be answered responsibly with currently available evidence"
- What it does NOT mean: The claim is false; research should stop

---

## Quantitative Evidence Assessment

### Effect Size Interpretation

| Measure | Small | Medium | Large | Discipline-dependent? |
|---------|-------|--------|-------|----------------------|
| Cohen's d | 0.2 | 0.5 | 0.8 | Psychology, Education |
| r (correlation) | 0.1 | 0.3 | 0.5 | Varies |
| OR/RR (binary) | 1.2–1.5 | 1.5–2.5 | >2.5 | Clinical significance varies |
| η² (ANOVA) | 0.01 | 0.06 | 0.14 | Context-dependent |

**Always contextualize effect size:** A small effect in a large population (e.g., mortality reduction) can be hugely meaningful. A large effect in a trivial outcome domain may matter less. Effect size convention thresholds are discipline-specific and context-dependent.

### Confidence Interval Interpretation
- A 95% CI means: If this study were repeated 100 times, 95 of the intervals constructed would contain the true value
- Wide CI = low precision (often underpowered)
- CI that includes null (e.g., OR includes 1.0) = result is not statistically significant at α=0.05
- Narrow CI crossing null still means null result; width ≠ direction

### p-value Interpretation
```
p < 0.05 means:    If the null hypothesis were true, data at least this extreme 
                   would occur less than 5% of the time
                   
p < 0.05 does NOT mean:
  □ The null hypothesis is false
  □ The effect is large or important
  □ The result will replicate
  □ There is a 95% probability the alternative hypothesis is true
  □ The study is well-designed
  
p ≥ 0.05 does NOT mean:
  □ There is no effect
  □ The null hypothesis is true
  □ The study was adequately powered to detect an effect
```

---

## Qualitative Evidence Assessment

For qualitative research findings:

**What qualitative evidence can establish:**
- Themes, patterns, and experiences within a studied population
- Processes and mechanisms operating in a specific context
- Conceptual frameworks grounded in participant perspectives
- Meaning and interpretation in context

**What qualitative evidence cannot establish on its own:**
- Prevalence in a general population (n quotes ≠ percentage of people)
- Causal relationships with controlled confounding
- Generalizability beyond the studied context without additional justification

**Handling qualitative quotes:**
- Do not use individual quotes as evidence of widespread phenomena
- Quotes illustrate themes; they do not establish frequency
- Report themes with appropriate hedging: "Participants described...", not "People feel..."

---

## Contradictory Evidence Handling Protocol

When credible sources disagree on a material claim:

```
Step 1  IDENTIFY     What exactly is being disagreed about? (Claim must be precise)

Step 2  MAP          Complete the Contradiction Mapping Table (see source-verification.md)

Step 3  ASSESS       Which explanation for the disagreement is best supported?
         Option A: One source is better quality for this specific question
         Option B: Both are valid but apply to different contexts/conditions
         Option C: The disagreement reflects genuine scientific uncertainty
         Option D: Insufficient evidence to determine

Step 4  DECIDE       Choose one resolution from the mapping

Step 5  DOCUMENT     State the contradiction, the mapping, and the resolution in the report

Step 6  CALIBRATE    Adjust overall confidence to reflect the unresolved disagreement
```

**Rule:** Do not hide contradictory evidence. Do not resolve contradictions by choosing the source with higher prestige. Do not force consensus where none exists. "The evidence is genuinely mixed" is a valid and important research output.
